# 🚀 Hi, I'm Alireza

**Backend & Distributed Systems Engineer**  
*Production-grade Systems • Go • Bun • Zig • DevOps*

> Building scalable, high-performance backend systems with a focus on clean architecture and operational excellence.

---

## 📊 GitHub Analytics

<p align="center">
  <img width="100%" src="./assets/overview.svg" alt="GitHub Overview" />
</p>

<p align="center">
  <img width="49%" src="./assets/languages.svg" alt="Languages" />
  <img width="49%" src="./assets/achievements.svg" alt="Achievements" />
</p>

<p align="center">
  <img width="49%" src="./assets/habits.svg" alt="Habits" />
  <img width="49%" src="./assets/calendar.svg" alt="Calendar" />
</p>

<p align="center">
  <img width="100%" src="./assets/repositories.svg" alt="Repositories" />
</p>

<p align="center">
  <img width="49%" src="./assets/topics.svg" alt="Topics" />
  <img width="49%" src="./assets/activity.svg" alt="Activity" />
</p>

---

## ⭐ Featured Projects

### 🚀 Graph Database Platform
**Embedded, Cross-Platform Graph Database with WebAssembly Query Engine**

A modular, production-grade graph database platform with a custom binary storage engine, WASM-powered query processor, and full-stack management interface.

| Property | Details |
|----------|---------|
| **Repository** | [Graph Database Platform](https://github.com/Skryl23/graph-db-platform) |
| **Status** | 🟢 Production-Ready |
| **Tech Stack** | Go • Rust • Zig • Python • TypeScript • React • Tauri |

---

#### 🗄️ Storage Engine (Go)
- Custom binary graph storage with **Memory-Mapped I/O**
- **Write-Ahead Logging (WAL)** for durability
- **Segmented Storage** architecture
- **ARC Cache** + **Bloom Filter** for performance
- **Hash Indexing** & **Memory Pool** optimization
- **gRPC** interface with **Structured Logging**

---

#### ⚡ Query Engine (Rust + WebAssembly)
- Independent query engine compiled to **WebAssembly**
- Layered architecture:
  - **Lexer** → **Parser** → **AST** → **Semantic Analysis** → **Query Planner**
- SQL-like query language support
- Optimized execution planning

---

#### 🖥️ Backend Management (Python + FastAPI)
- **Snapshot & Backup Manager** for data recovery
- **Nuitka** compilation to standalone executable
- **Free-Dependency** deployment (no Python runtime required)
- Exposed as **Tauri Sidecar** for seamless integration

---

#### 🎨 Frontend (TypeScript + React)
- **Analytics Dashboards** for real-time insights
- **Graph Studio** for query writing and execution
- **Community Detection** algorithms
- **React Flow** interactive graph visualization
- **Viewport-Based Fetching** (Google Maps-style progressive loading)
- Interactive documentation for graph algorithms and data structures

---

#### 🔬 Benchmark Engine (Rust + Zig)
- **Rust-based** performance benchmarking framework
- **Zig** implementations for algorithm optimization
- Native library with **C Extension** + **C ABI**
- Python bindings for seamless integration
- Cross-algorithm performance comparison

---

#### 🚀 Deployment & CI/CD
- **Docker Compose** for local development
- **Kubernetes** for production orchestration
- Full CI/CD pipeline with automated testing and deployment

---

#### 🏗️ Final Build Architecture
```
┌─────────────────────────────────────────────────────┐
│           Tauri Desktop Application                 │
│  ┌──────────────────────────────────────────────┐   │
│  │  Frontend (React + TypeScript)              │   │
│  └──────────────────────────────────────────────┘   │
│  ┌──────────────────────────────────────────────┐   │
│  │  Tauri Sidecar                              │   │
│  │  ┌───────────────────────────────────────┐  │   │
│  │  │  Python Backend (Nuitka Built)        │  │   │
│  │  │  - Snapshot & Backup Manager           │  │   │
│  │  └───────────────────────────────────────┘  │   │
│  │  ┌───────────────────────────────────────┐  │   │
│  │  │  Go Storage Engine                    │  │   │
│  │  │  - MMap • WAL • Segmented Storage     │  │   │
│  │  │  - ARC Cache • Bloom Filter           │  │   │
│  │  └───────────────────────────────────────┘  │   │
│  │  ┌───────────────────────────────────────┐  │   │
│  │  │  Rust WASM Query Engine               │  │   │
│  │  │  - Lexer • Parser • AST • Planner     │  │   │
│  │  └───────────────────────────────────────┘  │   │
│  │  ┌───────────────────────────────────────┐  │   │
│  │  │  Zig Library (Native + C ABI)         │  │   │
│  │  │  - Algorithm Optimizations            │  │   │
│  │  └───────────────────────────────────────┘  │   │
│  │  ┌───────────────────────────────────────┐  │   │
│  │  │  Rust Benchmark Engine                │  │   │
│  │  └───────────────────────────────────────┘  │   │
│  └──────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

---

#### 🔑 Key Features
- ✅ **Cross-Platform** (Windows & Linux)
- ✅ **Embedded** - No external dependencies
- ✅ **High Performance** with memory-mapped I/O
- ✅ **SQL-like Query Language** via WASM
- ✅ **Interactive Graph Visualization** with React Flow
- ✅ **Production-Ready** with full CI/CD

---

## 🏗 Architecture Interests

• **Distributed Systems** – Building resilient, scalable microservices
• **High-Performance Computing** – Optimizing for throughput and latency
• **Graph Databases** – Efficient storage and querying of connected data
• **Microservices** – Domain-driven design and service orchestration
• **Clean Architecture** – Separation of concerns and maintainability
• **DevOps & Platform Engineering** – CI/CD, observability, and infrastructure as code

---

## 💻 Engineering Philosophy

- **Clean Architecture & Code Quality** – Separation of concerns, modular design, and maintainable codebases
- **Scalability & Reliability** – Fault-tolerant systems designed for horizontal growth
- **Performance Optimization** – Query optimization, latency reduction, and bottleneck elimination
- **DevOps Ownership** – End-to-end responsibility from design to production monitoring
- **Continuous Learning** – Applying cutting-edge tools and patterns to real-world problems

---

## 📚 Currently Learning

• **Kubernetes** – Advanced orchestration and operator patterns  
• **SRE Practices** – Service Level Objectives, error budgets, and incident management  
• **System Design** – Large-scale distributed architectures  
• **Linux Internals** – Kernel, processes, memory management, and I/O  
• **WebAssembly** – High-performance browser and edge computing  
• **Distributed Databases** – Consistency models, sharding, and replication strategies

---

## 💻 Tech Stack

### 🚀 Languages
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Zig](https://img.shields.io/badge/Zig-F7A41D?style=for-the-badge&logo=zig&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

### ⚙️ Backend
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Chi](https://img.shields.io/badge/Chi-000000?style=for-the-badge&logo=go&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-%23000000.svg?style=for-the-badge&logo=bun&logoColor=white)
![Elysia](https://img.shields.io/badge/Elysia-000000?style=for-the-badge&logo=elysia&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

---

### 🗄️ Databases
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)

---

### 📨 Messaging
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![NATS](https://img.shields.io/badge/NATS-1999CC?style=for-the-badge&logo=nats&logoColor=white)

---

### ☁️ DevOps & Observability
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-6929C4?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

### 🎨 Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Ant Design](https://img.shields.io/badge/-AntDesign-%230170FE?style=for-the-badge&logo=ant-design&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radix-ui&logoColor=white)

---

### 🖥️ Desktop
![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF)
![Wails](https://img.shields.io/badge/Wails-DF0000?style=for-the-badge&logo=wails&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=electron&logoColor=white)
![Nuitka](https://img.shields.io/badge/Nuitka-1F4B99?style=for-the-badge&logo=nuitka&logoColor=white)

---

### 🛠️ Tools
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

---

## 🌐 Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Skryl23)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Skryl1622@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Skryl23)

---

> 💡 *"Building systems that are not just functional, but elegant, scalable, and resilient."*
