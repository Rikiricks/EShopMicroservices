# EShopMicroservices
- .Net Core 8 and Minimal API
# HLD:
![image](https://github.com/user-attachments/assets/4499cbe5-7912-4d35-9956-c23d245f0d3e)

# Catalog Microservice:
- **Vertical Slice Architecture**
- **CQRS** **implementation** and **Validation Pipeline Behaviors** using **MediatR** and **FluentValidation**
- **Marten-library** for .NET Transactional Document DB on PostgreSQL
- **Carter** for Minimal API endpoint definition
- Cross-cutting concerns **Logging**, **Global Exception Handling** and **Health Checks**
  
# Basket Microservice:
- **Vertical Slice Architecture** with **MediatR CQRS**
- **Redis** as a Distributed Caching
- **Scrutor:** implements **Proxy**, **Decorator** and **Cache-aside** patterns
- Consume **Grpc** Service
- **RabbitMQ** along with **MassTransit**

# Discount Microservice:
- **Grpc Server** with exposing **Protobuf messages**
- **Entity Frameowrk Core** ORM using **SqlLite** DB

# Ordering Microservice
- **Domain Driven Design**, **Clean Architecture** along with **Event Driven Architecture**
- **CQRS** with using **MediatR**, **FluentValidation** and **Mapster** packages
- **RabbitMQ** along with **MassTransit**
- **Entity Frameowrk Core** ORM using **SQL** DB

# Yarp API Gateway Microservice
- **Yarp Reverse Proxy Configuration**; Route, Cluster, Path, Transform, Destinations
- **Rate Limiting** with FixedWindowLimiter on Yarp Reverse Proxy Configuration

# WebUI ShoppingApp Microservice
- ASP.NET Core Web Application with **Bootstrap 4** and **Razor** template
- Call Yarp APIs with **Refit HttpClientFactory**

# Docker Compose
- Containerization of **microservices**
- Containerization of **databases**
- **Override** **Environment** **variables**
