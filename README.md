# docker-config

To be able to start the project clone all of the necessary services to one folder to create following structure:

  ![img.png](img.png)

1) api-gateway: https://github.com/Jgier47/api-gateway
2) config-server: https://github.com/Jgier47/config-server
3) department-service: https://github.com/Jgier47/department-service
4) docker-config: current repo -> https://github.com/Jgier47/docker-config
5) employee-service: https://github.com/Jgier47/employee-service 
6) organization-service: https://github.com/Jgier47/organization-service
7) react-frontend: https://github.com/Jgier47/employee-frontend
8) service-registry: https://github.com/Jgier47/service-registry


Docker compose requires pre-build docker images of almost all services - except react-frontend.
To build service image it is necessary that <b> service-registry and config-server</b> will work.


The easiest option is to comment part of the docker-compose file leaving only 
<b>  mysql,service-registry and config-server</b> uncommented. 
Then go to  docker-config folder and type:
docker compose up

After that build images with the following names:

service-registry
organization-service
employee-service
config-server
department-service
api-gateway

After that stop the containers, uncomment docker compose file and go to docker-config folder and use
docker compose build

after the frontend image will be created run

docker compose up
