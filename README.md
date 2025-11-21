# Project Overview

This project is a **personal study project** aimed at learning and exploring various technologies, including **Spring Boot 4.0.x**, **Kotlin 2.3.x**, and a wide range of modern tools and frameworks. Additionally, it includes the development of a blog application as a practical implementation.

See the full staged learning and engineering roadmap in `docs/ROADMAP.md`.

## Learning Goals

### Backend Technologies
- **Spring Boot 4.0.x**
- **Kotlin 2.3.x**
- **RabbitMQ**
- **Kafka**
- **JDBC**
- **JPA**
- **PostgreSQL**
- **Redis Cluster**
- **Valkey**
- **Elasticsearch**
- **Indexing**
- **HDFS**
- **Hadoop**
- **OAuth2**
- **MongoDB**
- **Neo4j**
- **Cassandra**

### DevOps and Cloud
- **Docker**
- **Kubernetes (K8s)**
- **CI/CD Pipelines**
- **Observability**
- **Configuration Center**

### Testing and Observability
- Comprehensive testing strategies.
- Observability tools for monitoring and debugging.

### Blog Development
- A blog application to apply and demonstrate the above technologies.

---

## Backend

### Features
- Built with **Kotlin** and **Spring Boot 4.0.x**.
- Includes modules for:
  - Web MVC
  - Data JPA
  - Validation
  - Actuator for monitoring
- Uses **H2 Database** for development.
- Supports **Gradle** for build automation.

### Requirements
- **JDK 25** or higher.
- **Gradle** (wrapper included).

### Startup
1. Navigate to the `backend` directory.
2. Run the following command to start the backend service:
   ```bash
   ./gradlew bootRun
   ```

### Build
To build the backend:
```bash
./gradlew build
```
The build artifacts will be located in `backend/build/libs`.

---

## Frontend

### Features
- Built with **React** and **TypeScript**.
- Uses **Vite** for fast development and build.
- Includes **ESLint** for code linting.

### Requirements
- **Node.js** (LTS version recommended).
- **pnpm** (preferred package manager).

### Startup
1. Navigate to the `frontend` directory.
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Start the development server:
   ```bash
   pnpm dev
   ```

### Build
To build the frontend:
```bash
pnpm build
```
The build output will be located in `frontend/dist`.

---

## Deployment

1. Build both the backend and frontend.
2. Deploy the backend JAR file from `backend/build/libs` to the server.
3. Deploy the frontend static files from `frontend/dist` to a web server.

---

## Technology Stack

### Backend
- **Kotlin 2.3.x**
- **Spring Boot 4.0.x**
- **RabbitMQ**, **Kafka**, **JDBC**, **JPA**
- **PostgreSQL**, **Redis Cluster**, **MongoDB**, **Neo4j**, **Cassandra**
- **Elasticsearch**, **Indexing**, **HDFS**, **Hadoop**
- **OAuth2**

### Frontend
- **React**
- **TypeScript**
- **Vite**
- **pnpm**

### DevOps and Cloud
- **Docker**, **Kubernetes (K8s)**
- **CI/CD Pipelines**
- **Observability**
- **Configuration Center**



