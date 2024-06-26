# ServiceDiscovery

## Steps to Install this Project Locally

1. Clone the project to your local machine.
2. Run `mvn clean install`.
3. You should now be able to run this project successfully.

## What is this Project?

Service Discovery is one of the microservices used in building an e-commerce web application. This service plays a crucial role in communication between microservices. Each microservice registers with the Service Discovery as a client. During communication between services, clients will reach out to the Service Discovery(Eureka server) to get the static IPs of client microservices to facilitate the communication. This way, we can avoid putting a burden on the API Gateway for internal communications.

