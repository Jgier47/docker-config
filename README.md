# Project Documentation

## Docker Configuration

Welcome to the Docker configuration repository for the project. All necessary images are posted on [Docker Hub](https://hub.docker.com/repositories/jgier47).

## Running the Application

To start the application, follow these steps:

1. Navigate to the `docker-config` directory in your terminal.
2. Run the following command:
   ```sh
   docker compose up


## Overview

This project involves various services and configurations as detailed in the diagrams below.

## Services and Ports Diagram

This diagram provides a visual representation of the services and their ports used in the system.

![Services and Ports Diagram](https://github.com/user-attachments/assets/056968a6-a7e6-482f-961e-e8a481edb30d)

## Configuration Flow Diagram

This diagram illustrates the configuration setup of the services and their interactions.

![Configuration Flow Diagram](https://github.com/user-attachments/assets/8de4842a-2f27-449d-b823-b634d7fd456b)




**Configuration Details:**

- **Service Registry**: Manages service registration and discovery.
- **Config Server**: Provides configuration data to other services.
- **RabbitMQ**: Interact with the Config Server asynchronously to refresh the configuration file from the config server.
- **Services**: Interact with the services as Server and Service Registry as needed.

## Data Flow

This diagram shows the flow of data within the system.

![Data Flow Diagram](https://github.com/user-attachments/assets/deb7bc68-90c4-4c5f-8b8c-73de73cbf833)

**Data Flow Details:**

- **Service to Database**: Data read and write operations.

## Distributed Tracing

This diagram provides insights into distributed tracing within the system.

![Distributed Tracing Diagram](https://github.com/user-attachments/assets/3355e721-51fd-4edd-8db0-26d613b50071)


**Tracing Details:**
- **Zipkin**: Aggregates and visualizes tracing data.

## Repositories
1. [api-gateway](https://github.com/Jgier47/api-gateway)
2. [config-server](https://github.com/Jgier47/config-server)
3. [department-service](https://github.com/Jgier47/department-service)
4. [docker-config](https://github.com/Jgier47/docker-config) (current repo)
5. [employee-service](https://github.com/Jgier47/employee-service)
6. [organization-service](https://github.com/Jgier47/organization-service)
7. [react-frontend](https://github.com/Jgier47/employee-frontend)
8. [service-registry](https://github.com/Jgier47/service-registry) 
## Additional Information

For more details, contact me directly at [slardevos@gmail.com](mailto:slardevos@example.com).
