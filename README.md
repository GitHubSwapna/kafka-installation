1.update the docker-compose.yml file with required configuration
2.Install and up the docker desktop
3.run the command inside kafka-installation as
     docker compose up -d
     docker container list
4.It will take few minute to up the server inside docker desktop.
5.Now up the docker explorer
using  bootstrap-servers: "broker:9292"  producer able to connect the kafka server.
 here broker is the container name of the kafka server.