# ECommerce-AI-Microservices-Platform

**Enterprise-grade E-Commerce platform** built with Spring Boot microservices, Docker, Kubernetes, and AI microservices for product recommendation and fraud detection.

## Tech Stack
- Java 17, Spring Boot
- PostgreSQL, Redis
- Docker, Kubernetes (Minikube)
- Python (Flask) + scikit-learn for AI
- GitHub Actions (CI) — optional

## Repo Structure
- `product-service/` — Spring Boot microservice for Products
- `order-service/` — Spring Boot microservice for Orders
- `cart-service/` — Spring Boot microservice for Cart
- `auth-service/` — Spring Boot microservice for Authentication (JWT)
- `ai-recommendation/` — Python Flask service for recommendations
- `k8s/` — Kubernetes manifests
- `docker-compose/` — compose configuration for local dev

## Setup (local dev)
1. Install Java 17, Maven, Docker (optional)
2. Start database (Postgres)
3. Import `product-service` into IntelliJ and run

//(Expand with exact commands once you add files)//

## License
MIT
