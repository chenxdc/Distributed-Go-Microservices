# Distributed-Go-Microservices

This project is a collection of small, self-contained, and loosely coupled microservices. These microservices were designed to work together as a distributed application. The project involved implementing communication between services using JSON, Remote Procedure Calls (RPC), and gRPC. I also integrated event-driven communication using the Advanced Message Queuing Protocol (AMQP) with RabbitMQ. The deployment of the application was done using Docker Swarm and Kubernetes, allowing for efficient scaling and updates with minimal downtime. The microservices included a Front End service, an Authentication service with a Postgres database, a Logging service with a MongoDB database, a Listener service for message handling, a Broker service as an optional entry point, and a Mail service for email generation and delivery. All of these services were written in Go (Golang), a language well-suited for building distributed web applications
![image](https://github.com/chenxdc/Distributed-Go-Microservices/assets/94099798/1a56c714-6574-41b4-8a0d-e3117af526ee)
