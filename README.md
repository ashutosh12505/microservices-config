# Microservices Config Repository

This repository contains the centralized configuration files used by the **Spring Cloud Config Server** in the Car Rental Microservices System.

The configuration stored here is fetched dynamically by microservices at runtime.

---

## Architecture Overview

This repository is part of a microservices architecture built using:

- Spring Boot
- Spring Cloud Config Server
- Netflix Eureka (Service Discovery)
- Spring Cloud Gateway (API Gateway)

Configuration flow:

GitHub Config Repo  
      ↓  
Config Server  
      ↓  
Microservices (Passenger Service, Car Rental Service)
