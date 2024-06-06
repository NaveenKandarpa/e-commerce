# eCommerce website - Microservices architecture

## Overview

This project is an eCommerce website designed using a microservices architecture. The system is built with Java and Spring Boot, following the Model-View-Controller (MVC) pattern to ensure clean separation of concerns and maintainability. Each microservice is responsible for a specific domain of the application, allowing for scalability and independent development.

## Microservices

- **Product Service**: (https://github.com/NaveenKandarpa/productservice)
  - Description: Handles product data.
  - Key Features: CRUD operations, secured API calls.

- **User Service**: (https://github.com/NaveenKandarpa/userservice)
  - Description: Manages user profiles, user authentication and authorization.
  - Key Features: OAuth2, JWT tokens.

- **Payment Service**: (https://github.com/NaveenKandarpa/paymentservice)
  - Description: Processes payment transactions.
  - Key Features: Payment gateway integration, transaction history, refunds.

- **Notification Service**: (https://github.com/NaveenKandarpa/NotificationService)
  - Description: Sends an email notification to the user after signing up.
  - Key Features: Kafka, Pub-Sub model
  
- **Service Discovery**: (https://github.com/NaveenKandarpa/servicediscovery)
  - Description: Maintains the list of all servers running a particular microservice.
  - Key Features: Eureka server, Spring cloud.

- **API Gateway and Load Balancer**: (https://github.com/NaveenKandarpa/apigateway)
  - Description: Routes the request to corresponding microservice in a load balanced way.
  - Key Features: Load balancing, Rate limiting, extra layer of authentication.

<!-- 
## Project Architecture

![Architecture Diagram](link-to-your-architecture-diagram.png)

## Setup Instructions

To get started with the project, follow these steps:

1. Clone the repositories:
    ```bash
    git clone https://github.com/your-username/service1.git
    git clone https://github.com/your-username/service2.git
    git clone https://github.com/your-username/service3.git
    git clone https://github.com/your-username/service4.git
    ```
2. Set up environment variables and configurations as per each service's README.
3. Start each service:
    ```bash
    cd service1 && npm start
    cd service2 && npm start
    cd service3 && npm start
    cd service4 && npm start
    ```
    -->
For any questions or collaboration, feel free to reach out to me at kandarpanaveen7@gmail.com.
