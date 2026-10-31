
<div align="center">

# Mahmoud Amin
### Backend .NET Engineer &nbsp;|&nbsp; Distributed Systems & Microservices

**Giza, Egypt** &nbsp;&bull;&nbsp; **B.Sc. in Computer Science & AI — Fayoum University (GPA: 3.2 / 4.0)**

<br/>

<a href="https://www.linkedin.com/in/mahmoud-amin-466948257/" target="_blank">
  <img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-Mahmoud%20Amin-0A66C2?style=for-the-badge&logo=linkedin-white&logoColor=white&labelColor=084d92" height="34" alt="LinkedIn" />
</a>&nbsp;&nbsp;
<a href="mailto:mahmoud886.amin@gmail.com">
  <img src="https://custom-icon-badges.demolab.com/badge/Email-mahmoud886.amin%40gmail.com-D14836?style=for-the-badge&logo=mail&logoColor=white&labelColor=a33325" height="34" alt="Email" />
</a>&nbsp;&nbsp;
<a href="https://github.com/MahmoudAmin5" target="_blank">
  <img src="https://custom-icon-badges.demolab.com/badge/GitHub-MahmoudAmin5-24292F?style=for-the-badge&logo=github&logoColor=white&labelColor=161B22" height="34" alt="GitHub" />
</a>

</div>

---

## Executive Summary

Backend Software Engineer specializing in architecting distributed, high-concurrency systems on **.NET 9** and **ASP.NET Core**. Proven track record of designing **Clean** and **Vertical Slice** architectures, event-driven microservices with **RabbitMQ (MassTransit)** and the **Transactional Outbox** pattern, low-latency **gRPC** and **SignalR** communication layers, and **SQL Server execution plan & index tuning** alongside **Redis** distributed caching.

---

## Technical Stack

<p align="left">
  <img height="58" src="https://go-skill-icons.vercel.app/api/icons?i=cs,cpp,dotnet,sqlserver,redis,rabbitmq,docker,githubactions,git,linux,postman" alt="Tech Stack" />
</p>

| Domain | Technologies & Engineering Practices |
| :--- | :--- |
| **Languages & Frameworks** | C# &bull; C++ &bull; ASP.NET Core (.NET 9) &bull; Entity Framework Core &bull; LINQ &bull; SQL |
| **Architecture & Patterns** | Clean Architecture &bull; Vertical Slice Architecture &bull; Microservices &bull; CQRS (MediatR) &bull; Event-Driven Architecture &bull; Transactional Outbox &bull; Repository & Savepoint Unit of Work |
| **Gateways, RPC & Real-Time** | YARP API Gateway &bull; Ocelot API Gateway &bull; gRPC &bull; RabbitMQ (MassTransit) &bull; SignalR &bull; Pusher / WebSockets &bull; Polly Resilience |
| **Databases, Caching & Jobs** | SQL Server (Execution Plan Analysis, Covering & Filtered Indexes, RowVersion Concurrency) &bull; Redis (Distributed Cache-Aside) &bull; Hangfire |
| **DevOps, Logging & Testing** | Docker & Docker Compose &bull; GitHub Actions (CI/CD) &bull; Serilog & Seq &bull; xUnit &bull; FluentAssertions &bull; OpenAPI / Scalar |

---

## Professional Experience

### Backend .NET Developer Trainee — Elevate Tech *(Feb 2026 – Aug 2026)*
- Engineered distributed, cloud-ready backend microservices using **.NET**, **Vertical Slice Architecture**, and **CQRS (MediatR)** with strict separation of concerns.
- Built asynchronous event-driven workflows utilizing **RabbitMQ (MassTransit)**, multi-level **Redis** caching strategies, and multi-container orchestration with **Docker Compose**.

### Backend Developer Intern — Duaya *(July 2025 – Sept 2025 | Hybrid)*
- Built a real-time customer-support chat module on a **Pusher / WebSocket** architecture with per-conversation channels, presence tracking, and durable **SQL Server** persistence, significantly reducing median first-response time compared to HTTP polling.
- Architected scalable backend services with **Clean Architecture** and **CQRS**; enforced transactional data consistency using **Repository** and **Unit of Work** patterns, and integrated **MediatR Pipeline Behaviors** for centralized request validation and automated error handling.

---

## Featured Systems & Projects

### 1. [Fitness App — Distributed Microservices Platform](https://github.com/Elevate-Fitness-Project-Teams/FitnessApp-team2)
`C#` &bull; `.NET 9` &bull; `6 Microservices` &bull; `Ocelot API Gateway` &bull; `RabbitMQ (MassTransit)` &bull; `Transactional Outbox` &bull; `gRPC` &bull; `Redis` &bull; `RS256 JWT` &bull; `Docker Compose` &bull; `GitHub Actions`
- Co-architected a distributed **.NET 9** backend across **6 domain microservices** orchestrated with **Docker Compose**; unified client ingress via an **Ocelot API Gateway** configured with rate-limiting, CORS, and **Polly** circuit-breaker resilience policies.
- Engineered event-driven cross-service workflows using **RabbitMQ (MassTransit)** with the **Transactional Outbox** pattern to guarantee at-least-once message delivery, backed by **gRPC** for low-latency synchronous RPCs.
- Implemented calculation and tracking engines following **CQRS + MediatR**; integrated a **Redis distributed cache-aside** layer with event-driven invalidation, cutting database round-trips and achieving **sub-10ms** query latencies.
- Hardened platform security with asymmetric **JWT (RS256)** authentication and RBAC; automated testing and deployment via a **GitHub Actions CI/CD** pipeline executing **xUnit** test suites and building verified multi-service Docker images.

### 2. [Travio — AI Travel Booking & Planner Platform](https://github.com/MahmoudAmin5/Travio)
`C#` &bull; `ASP.NET Core 9` &bull; `Clean Architecture` &bull; `SQL Server` &bull; `Stripe` &bull; `Duffel API` &bull; `Hotelbeds APITUDE` &bull; `SignalR` &bull; `Hangfire` &bull; `Redis` &bull; `xUnit`
- Delivered core backend architecture integrating third-party providers (**Stripe Payments**, **Duffel Flights**, **Hotelbeds APITUDE**, **Google Maps**) and a **SignalR** real-time messaging layer for the conversational AI travel assistant; authored **OpenAPI** specifications to unblock parallel mobile development.
- Eliminated double-charge race conditions during concurrent payment requests by combining **Stripe deterministic idempotency keys**, **Optimistic Concurrency (`RowVersion`)**, and **atomic set-based webhook locking**; inspected **SQL Execution Plans** to eliminate table/index scans and reduce lock contention on high-concurrency booking tables.
- Built high-performance endpoints using **Clean Architecture** on **ASP.NET Core**; reduced read latency with a **Redis** cache-aside layer and offloaded asynchronous ticket/voucher dispatch to **Hangfire** background workers.

### 3. [Flowery — E-Commerce Microservices Platform](https://github.com/elevate-flower-ecommerce-projects/Flower_ECommerce_Microservices-team3)
> **`.NET`** · **`6 Microservices`** · **`Vertical Slice Architecture`** · **`CQRS (MediatR)`** · **`YARP API Gateway`** · **`RabbitMQ (MassTransit)`** · **`Paymob`** · **`Serilog & Seq`** · **`Docker Hub CI/CD`**
- Co-architected an e-commerce backend across **6 domain microservices** (*Identity, Catalog, Cart, Order & Fulfillment, Payment [Paymob], Address Coverage*) unified through a high-performance **YARP API Gateway** with centralized JWT Bearer authentication, CORS policies, and aggregated OpenAPI documentation.
- Engineered asynchronous, event-driven workflows using **RabbitMQ (MassTransit)** for order processing, driver fulfillment dispatch, and payment notifications, decoupling inter-service communication and enforcing eventual consistency.
- Implemented core domain services using **Vertical Slice Architecture** with **CQRS (MediatR)**, isolating checkout pipelines, driver assignments, and order state machines into self-contained slices backed by shared enterprise **BuildingBlocks**.
- Designed an automated **GitHub Actions CI/CD matrix pipeline** to compile and publish **7 Docker images** in parallel to Docker Hub; orchestrated the multi-container ecosystem with **Docker Compose** and integrated **Seq** structured logging via **Serilog**.

---

## GitHub Activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MahmoudAmin5&show_icons=true&theme=transparent&hide_border=true&title_color=0A66C2&icon_color=0A66C2" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=MahmoudAmin5&theme=transparent&hide_border=true&ring=0A66C2&fire=0A66C2&currStreakLabel=0A66C2" alt="GitHub Streak" />
</div>
````
