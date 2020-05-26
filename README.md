# DELIVERY EUREKA CLIENTE SERVER
> Simple project of delivery


## Instalation

Download Maven dependencies

```sh
mvn clean package
```

## Configure ambient

You need to install docker and run it.

After docker is running, run the file docker-compose to run MySql service.

```sh
docker-compose up
```

## Using the project

To start the application, first need to run the docker-compose file.
After use your favotire IDE (InteliJ) and run the services in order:
 - delivery-config-server
 - delivery-eureka-server
 - delivery-auth-server
 - delivery-order-service


## Project

Is a simple project to describe how to use some tecnologies:
  - Eureka Client and Server
  - Spring config server
  - OAuth2
  
  
