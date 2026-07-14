# 🚀 Mohammad Zeinhom | Backend Software Engineer

Backend Developer specializing in building **scalable, distributed, and AI-integrated backend systems** using **Spring Boot (Java)** and **ASP.NET Core (C#)**. Focused on clean architecture, robust concurrency, and high-performance design.

---

## 🧠 About Me
I am a passionate Backend Engineer dedicated to crafting clean, maintainable, and well-architected systems. I thrive on solving complex backend challenges—whether it's decoupling intensive AI inference from web requests, optimizing database queries with vector search, or modeling intricate multi-threaded simulations.

*   **Architectural Philosophy:** Adherent of **Clean Architecture**, **SOLID principles**, and separation of concerns.
*   **Decoupled & Asynchronous Design:** Experienced in event-driven systems using message brokers (RabbitMQ) to scale background workflows.
*   **Vector Search & AI RAG:** Practical expertise integrating LLMs (Spring AI) and vector extensions (`pgvector`) to build contextual recommendations and intelligent dining assistants.

---

## 🛠️ Tech Stack & Ecosystem

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) |
| **Backend Frameworks** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![.NET / ASP.NET Core](https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) |
| **Data & Caching** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **Messaging & Broker** | ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) |
| **DevOps & Tools** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black) |
| **Testing & Mocking** | `JUnit` • `Mockito` • `xUnit` • `Moq` • `Fluent Assertions` |

---

## ⚡ Featured Projects & Architectures

### 🍽️ InDine — Smart Table Reservation & AI Recommendation System
An enterprise-grade, asynchronous backend powering dining reservations and a RAG-based AI dining assistant.
*   **Asynchronous Ingredient Pipeline:** Implemented an event-driven workflow using **RabbitMQ** to offload heavy LLM ingredient extraction and allergen tagging to a decoupled Python worker, freeing up web-transaction threads.
*   **Semantic Recommendation Engine:** Utilized **Spring AI** and **PostgreSQL (`pgvector`)** to offer sub-millisecond semantic food recommendations based on dining histories, tastes, and safety profiles.
*   **Distributed Caching & Rates:** Structured multi-level caching using **Redis** (distributed session management) and **Caffeine** (high-speed local cache) to reduce database load.
*   **Secure Payment Integration:** Integrated **Paymob** checkout gateways, securely coordinating payment intents, webhook notifications, and cryptographic signature validations.
*   *Stack: Spring Boot 3.5, Java 21, pgvector, Redis, RabbitMQ, Python 3.10, Paymob, Cloudinary*

### 🚗 Multi-Threaded Parking Simulation
A concurrent simulation modeling real-world synchronization and resource allocation constraints.
*   **Thread Safety & Concurrency:** Designed using semaphore-based synchronization patterns to safely coordinate incoming/outgoing traffic.
*   **Liveness & Deadlock Prevention:** Fine-tuned critical sections to guarantee zero deadlocks under high simulated load.
*   *Stack: Java Core, Multithreading, Semaphores*

### 🔒 Enterprise ASP.NET Core Practice Ecosystems
A suite of REST APIs and MVC applications highlighting modern .NET architecture.
*   **Clean Architecture:** Implemented strong separation of concerns separating Domain, Application, Infrastructure, and API layers.
*   **Security & Identity:** Utilized ASP.NET Identity with custom policy-based JWT authorization rules.
*   **Robust Testing:** Maintained high coverage using **xUnit** and **Moq** for unit and integration testing.
*   *Stack: ASP.NET Core, EF Core, C#, JWT, SQL Server, xUnit*

---

## 🎯 Current Technical Focus
*   **Advanced System Design:** Mastering high-throughput microservices, API Gateway patterns, and event-sourcing.
*   **AI-Native Backends:** Deepening experience with vector index tuning, embedding optimizations, and agentic workflows.
*   **System Performance:** Tuning JVM & .NET garbage collection, asynchronous IO, and query performance.
