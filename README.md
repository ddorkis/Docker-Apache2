# Docker-Apache2
Create pache2 webserver with custom extra config file

1. create network create dorkis_net;
2. Launch command in project folder "docker build -t http-dorkis .";
3. docker-compose up;
4. docker container start DorkisWebServer;
4. docker exec -it DorkisWebServer bash

Next step i will create external document root for virtual host