Here is your upgraded **GitHub Profile `README.md`** tailored directly from your CV. You can copy and paste this directly into your `MahmoudAmin5/MahmoudAmin5` repository's `README.md`:

````markdown
<h1 align="center">Hello World! 👋 I'm Mahmoud Amin</h1>

<h3 align="center">Backend .NET Software Engineer · Distributed Systems & Microservices · ICPC Mentor</h3>

<p align="center">
  📍 Giza, Egypt &nbsp;|&nbsp; 🎓 B.Sc. in Computer Science & AI — Fayoum University (GPA: 3.2 / 4.0 · Very Good)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mahmoud-amin-466948257/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Mahmoud%20Amin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mahmoud886.amin@gmail.com">
    <img src="https://img.shields.io/badge/Email-mahmoud886.amin%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/MahmoudAmin5" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-MahmoudAmin5-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

### ⚡ About Me

- 🏗️ **Backend .NET Engineer** specializing in **Clean Architecture**, **Vertical Slice Architecture**, and **Distributed Microservices** on **.NET 9 & ASP.NET Core**.
- 🔄 Experienced in designing **event-driven systems** with **RabbitMQ (MassTransit)**, **Transactional Outbox**, **CQRS (MediatR)**, **gRPC**, and **YARP / Ocelot API Gateways**.
- 🚀 Passionate about **database performance engineering** — inspecting **SQL Server Execution Plans**, tuning **Covering & Filtered Indexes**, enforcing **Optimistic Concurrency (`RowVersion`)**, and building **Redis distributed cache-aside** layers for sub-10ms query latencies.
- 🧠 **ICPC Competitive Programming Mentor** — mentored **25+ university students** in advanced data structures, graph algorithms, and dynamic programming.

---

### 🛠️ Languages, Frameworks & Tools

<p align="left">
  <img height="65" src="https://go-skill-icons.vercel.app/api/icons?i=cs,cpp,dotnet,sqlserver,redis,rabbitmq,docker,githubactions,git,linux,postman,stackoverflow" />
</p>

| Category | Technologies & Patterns |
| :--- | :--- |
| **Languages & Core** | `C#` · `C++` · `ASP.NET Core (.NET 9)` · `Entity Framework Core` · `LINQ` · `SQL` |
| **Architecture & Design** | `Clean Architecture` · `Vertical Slice Architecture` · `Microservices` · `CQRS` · `MediatR` · `Event-Driven Architecture` · `Transactional Outbox` · `Repository & Savepoint Unit of Work` |
| **Messaging, RPC & Real-Time** | `RabbitMQ (MassTransit)` · `gRPC` · `SignalR` · `Pusher / WebSockets` · `YARP` · `Ocelot API Gateway` · `Polly Resilience` |
| **Data, Caching & Background** | `SQL Server (Execution Plans & Index Tuning)` · `Redis (Distributed Cache-Aside)` · `Hangfire` |
| **DevOps, Observability & Testing** | `Docker & Docker Compose` · `GitHub Actions (CI/CD)` · `Serilog & Seq` · `xUnit` · `FluentAssertions` · `OpenAPI / Scalar` |

---

### 💼 Professional Experience & Mentorship

- **Backend .NET Developer Trainee — Elevate Tech** *(Feb 2026 – Aug 2026)*
  - Engineered distributed, cloud-ready backend microservices using **.NET**, **Vertical Slice Architecture**, and **CQRS (MediatR)** with strict separation of concerns.
  - Built event-driven workflows with **RabbitMQ (MassTransit)**, multi-level **Redis** caching strategies, and multi-container orchestration via **Docker Compose**.

- **Backend Developer Intern — Duaya** *(July 2025 – Sept 2025 · Hybrid)*
  - Built a **real-time customer-support chat module** on a **Pusher / WebSocket** architecture with per-conversation channels, presence tracking, and durable **SQL Server** persistence, significantly reducing median first-response time vs. HTTP polling.
  - Architected scalable backend services with **Clean Architecture & CQRS**, enforcing transactional consistency via **Repository & Unit of Work** patterns and **MediatR Pipeline Behaviors** for centralized validation and error handling.

- **Competitive Programming Mentor — ICPC Fayoum Community** *(Oct 2024 – Feb 2025)*
  - Mentored **25+ university students** in advanced data structures, graph algorithms, dynamic programming, and competitive problem-solving strategies for ICPC qualifications.

---

### 🚀 Featured Engineering Projects

#### 1. ✈️ [Travio — AI Travel Booking & Planner Platform (Graduation Project)](https://github.com/MahmoudAmin5/Travio)
> **`ASP.NET Core 9`** · **`Clean Architecture`** · **`SQL Server`** · **`Stripe`** · **`Duffel API`** · **`Hotelbeds APITUDE`** · **`SignalR`** · **`Hangfire`** · **`Redis`** · **`xUnit`**
- Integrated global third-party travel & payment providers (**Stripe**, **Duffel Flights**, **Hotelbeds APITUDE**, **Google Maps**) and architected a **SignalR** real-time streaming hub for the conversational **AI Travel Assistant**.
- Eliminated double-charge and double-booking race conditions during concurrent payment requests by combining **Stripe deterministic idempotency keys**, **Optimistic Concurrency (`RowVersion`)**, and **atomic set-based webhook locking (`ExecuteUpdateAsync`)** with stale-lease recovery.
- Inspected **SQL Execution Plans** and designed **Covering & Filtered Unique Indexes** to eliminate table/index scans and lock contention on high-concurrency booking tables; offloaded e-ticket generation to **Hangfire** workers.

#### 2. 🏋️ Fitness App — Distributed Microservices Platform
> **`.NET 9`** · **`6 Microservices`** · **`Ocelot API Gateway`** · **`RabbitMQ (MassTransit)`** · **`Transactional Outbox`** · **`gRPC`** · **`Redis`** · **`RS256 JWT`** · **`Docker Compose`** · **`GitHub Actions`**
- Co-architected a distributed **.NET 9** backend across **6 domain microservices** unified via an **Ocelot API Gateway** with rate-limiting, CORS, and **Polly** circuit-breaker policies.
- Engineered event-driven cross-service workflows using **RabbitMQ (MassTransit)** with the **Transactional Outbox** pattern for at-least-once delivery and **gRPC** for low-latency synchronous RPCs.
- Integrated a **Redis distributed cache-aside** layer with event-driven invalidation (achieving **sub-10ms** query latencies) and hardened security with asymmetric **JWT (RS256)** and RBAC.

#### 3. 🌸 Flowery — E-Commerce Microservices Platform
> **`.NET`** · **`6 Microservices`** · **`Vertical Slice Architecture`** · **`CQRS (MediatR)`** · **`YARP API Gateway`** · **`RabbitMQ (MassTransit)`** · **`Paymob`** · **`Serilog & Seq`** · **`Docker Hub CI/CD`**
- Co-architected an e-commerce platform across **6 domain microservices** (*Identity, Catalog, Cart, Order & Fulfillment, Payment [Paymob], Address Coverage*) behind a **YARP API Gateway** with centralized JWT authentication and aggregated OpenAPI docs.
- Implemented core domain services using **Vertical Slice Architecture + CQRS (MediatR)** backed by shared enterprise `BuildingBlocks` and asynchronous **RabbitMQ (MassTransit)** workflows for order processing and driver dispatch.
- Designed a parallel **GitHub Actions CI/CD matrix pipeline** to build and publish **7 Docker images** to Docker Hub with **Seq** structured logging via **Serilog**.

---

### 📊 GitHub Analytics

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=MahmoudAmin5&show_icons=true&theme=tokyonight&hide_border=true" alt="Mahmoud's GitHub Stats" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=MahmoudAmin5&theme=tokyonight&hide_border=true" alt="Mahmoud's GitHub Streak" />
</p>
````
