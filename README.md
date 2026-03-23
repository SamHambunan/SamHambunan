[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Hi+I'm+Sam+Hambunan+:D)](https://git.io/typing-svg)


<p align="center"> <img src="https://komarev.com/ghpvc/?username=samhambunan&label=Profile%20views&color=0e75b6&style=flat" alt="samhambunan" /> </p>

  ![snake gif](https://github.com/samhambunan/samhambunan/blob/output/github-snake-dark.svg)

# 👨‍💻 My Portfolio

> *Information Technology Student · Full-Stack Web Developer · AI/ML Integrator · Aspiring Software Architect*

---

## 🧑‍🎓 About Me

I'm a **Information Technology student at Cebu Technological University (CTU)** in Cebu, Philippines, driven by a strong passion for building robust, scalable, and well-architected web applications. My development journey spans across backend engineering with Laravel, modern frontend development with React and Tailwind CSS, authentication systems, performance optimization with Redis and caching, AI/ML integration via FastAPI, and an ever-growing interest in **system design and software architecture**.

I approach every project with a mindset of clean code, thoughtful design, and continuous learning — always pushing toward deeper understanding rather than surface-level familiarity.

---

## 🎓 Education

| Field | Details |
|-------|---------|
| **Institution** | Cebu Technological University (CTU) |
| **Program** | Bachelor of Science in Information Technology |
| **Status** | Ongoing / Currently Enrolled |
| **Location** | Cebu City, Cebu, Philippines |

---

## 🛠️ Full Tech Stack Breakdown

### 🔥 Currently Mastering

#### Laravel *(PHP Backend Framework)*
Laravel is my primary backend framework and the core of my development practice. I'm actively advancing across its ecosystem — not just building CRUD apps, but working toward production-grade architecture.

**Areas of Active Development:**
- Routing, middleware, and request lifecycle
- Eloquent ORM — relationships, scopes, eager loading, query optimization
- RESTful API development with resource controllers and API resources
- Job queues, background processing, and event broadcasting
- Service container and dependency injection
- Form requests, validation pipelines, and custom rules
- Blade templating engine
- Laravel Artisan CLI — custom commands, scheduling
- Database migrations, seeders, and factories
- Policy & Gate-based authorization

---

### 🔐 Authentication *(Adept)*

I have solid, hands-on proficiency in Laravel's authentication ecosystem — both for traditional web apps and API-based systems.

#### Laravel Breeze
- Lightweight scaffolding for session-based authentication
- Handles login, registration, password reset, and email verification out of the box
- Used in full-stack apps paired with Blade or React (Inertia.js / API)
- Comfortable customizing flows, views, and guards
- Understands the underlying auth mechanics Breeze abstracts

#### Laravel Sanctum
- Token-based authentication for SPAs and mobile clients
- Issuing, revoking, and managing personal access tokens
- Cookie-based SPA authentication for React frontends
- Protecting API routes with `auth:sanctum` middleware
- Token abilities and scoped permissions
- Understands the difference between Sanctum and Passport and when to use each

> **Authentication Confidence Level:** Adept — capable of implementing secure, production-ready auth flows independently for both web and API contexts.

---

### 🌐 Frontend Development

#### React *(Web Only — Not React Native)*
- Functional components and React Hooks (`useState`, `useEffect`, `useContext`, `useReducer`, `useMemo`, `useCallback`)
- Component composition and reusability patterns
- Client-side routing with React Router
- State management with Context API
- Fetching and integrating with Laravel REST APIs
- Building SPAs that consume Sanctum-protected endpoints
- **Note:** React Native (mobile) is **not** part of my current stack

#### Vite
- Primary build tool for frontend development
- Fast HMR (Hot Module Replacement) for development efficiency
- Configuring Vite for Laravel + React projects
- Optimized production builds with code splitting
- Plugin ecosystem familiarity

#### Tailwind CSS
- Utility-first CSS for rapid, consistent UI development
- Responsive design with Tailwind's breakpoint system
- Custom theme configuration (`tailwind.config.js`)
- Component-level styling patterns without CSS bloat
- Dark mode support
- Paired seamlessly with React and Vite projects

---

### 🔧 Backend Infrastructure *(Actively Practicing)*

#### Redis
- In-memory key-value store for high-speed data access
- Exploring use cases: session storage, rate limiting, leaderboards, real-time counters
- Understanding Redis data structures: strings, hashes, lists, sets, sorted sets
- Integrating Redis with Laravel via the Redis facade and Predis/PhpRedis drivers
- Pub/Sub patterns for real-time messaging
- Persistence strategies: RDB snapshots vs AOF logging

#### Caching Strategies
- Laravel's Cache facade with multiple drivers (file, database, Redis, Memcached)
- Cache-aside pattern: manual fetch, store, and invalidation
- HTTP response caching
- Query result caching for expensive database operations
- Cache tagging and grouped invalidation
- Understanding TTL (Time-to-Live) and cache stampede prevention
- Exploring full-page and fragment caching strategies

> **Goal:** Build applications that scale efficiently by reducing redundant computation and database load through intelligent caching layers.

---

### 🤖 AI / ML Integration *(Actively Practicing)*

#### FastAPI *(Python)*
- Async Python web framework designed for high-performance APIs
- Building microservices that expose ML models as REST endpoints
- Request/response schemas using Pydantic
- Integrating trained models (scikit-learn, etc.) into FastAPI routes
- Connecting FastAPI services to Laravel backends via HTTP clients (Guzzle)
- Exploring background tasks for async inference jobs
- API documentation with auto-generated Swagger UI

**Integration Architecture Pattern I'm Exploring:**
```
React Frontend
      │
      ▼
Laravel API (main backend, auth, business logic)
      │
      ▼
FastAPI Microservice (ML inference, AI processing)
      │
      ▼
ML Model (scikit-learn / etc.)
```

> **Goal:** Build a clean separation between web application logic (Laravel) and AI/ML computation (FastAPI) through well-defined microservice contracts.

---

### 📐 System Architecture & System Design *(Actively Learning)*

This is a key area of intellectual investment. I'm moving beyond "how to build features" toward "how to design systems that scale, survive failure, and evolve over time."

**Topics Currently Studying:**

#### Architectural Patterns
- Monolithic vs. Microservices vs. Modular Monolith
- MVC and its variants in the context of Laravel
- Service-Oriented Architecture (SOA) basics
- API Gateway patterns
- Event-driven architecture concepts

#### System Design Fundamentals
- Scalability: horizontal vs. vertical scaling
- Load balancing concepts
- Database design: normalization, indexing strategies, read replicas
- CAP Theorem (Consistency, Availability, Partition Tolerance)
- SQL vs. NoSQL trade-offs
- Eventual consistency

#### Reliability & Performance
- Caching layers (L1/L2 cache, CDN, application-level cache)
- Queue-based decoupling for async workloads
- Rate limiting and throttling
- Fault tolerance: retries, circuit breakers, fallback strategies

#### Design Principles Being Applied
- SOLID principles in Laravel service/repository patterns
- DRY (Don't Repeat Yourself), KISS (Keep It Simple, Stupid)
- Separation of concerns in full-stack architecture
- RESTful API design best practices

> **Learning Path:** Studying through system design literature, real-world architecture teardowns, and applying concepts in personal projects. Goal is to architect systems thoughtfully — not just make them work, but make them *right*.

---

## 📊 Skill Level Overview

| Technology | Category | Proficiency |
|------------|----------|-------------|
| **Laravel** | Backend Framework | 🟡 Mastering |
| **Laravel Breeze** | Authentication | 🔵 Adept |
| **Laravel Sanctum** | API Authentication | 🔵 Adept |
| **React** *(Web only)* | Frontend | 🟢 Capable |
| **Vite** | Build Tooling | 🟢 Capable |
| **Tailwind CSS** | Styling | 🟢 Capable |
| **Redis** | Infrastructure / Caching | 🟠 Practicing |
| **Application Caching** | Performance | 🟠 Practicing |
| **FastAPI** | AI/ML Microservices | 🟠 Practicing |
| **System Architecture** | Design & Planning | 🟠 Learning |
| **System Design** | Scalability & Patterns | 🟠 Learning |
| **React Native** | Mobile | ❌ Not in Stack |

### Legend

| Badge | Meaning |
|-------|---------|
| 🔵 Adept | Strong, independent proficiency — can implement in production confidently |
| 🟡 Mastering | Deep, active learning — going beyond basics into advanced internals |
| 🟢 Capable | Comfortable and productive — can build real features without assistance |
| 🟠 Practicing / Learning | Actively studying and building — growing rapidly |
| ❌ Not in Stack | Not currently available or pursued |

---

## 🎯 Focus Areas & Goals

### 1. 🏗️ Full-Stack Web Development
Building end-to-end web applications using **Laravel** as the API backend and **React + Tailwind CSS** as the frontend. Emphasis on clean separation of concerns, RESTful design, and secure authentication using **Breeze** and **Sanctum**.

### 2. 🔐 Secure Authentication Systems
Designing and implementing authentication flows — from traditional session-based auth (Breeze) to token-based SPA/API authentication (Sanctum) — with attention to security best practices like token scoping, guard configuration, and CSRF protection.

### 3. ⚡ Performance Engineering
Applying **Redis** and strategic **caching** to reduce server load, improve response times, and build applications that perform well under pressure. Goal: think about performance *during* design, not as an afterthought.

### 4. 🤖 AI / ML-Powered Applications
Using **FastAPI** to bridge the gap between machine learning models and production web apps. Interested in building intelligent features — recommendations, predictions, NLP — powered by Python ML pipelines exposed as clean microservice APIs.

### 5. 📐 Software Architecture & System Design
Developing the ability to **design systems before writing code** — thinking in terms of components, data flow, failure modes, and scalability. Studying how real-world systems are architected and applying those principles to personal and academic projects.

---

## 🗺️ Learning Roadmap

```
Current Focus
├── Laravel (deepening — queues, events, service patterns)
├── Breeze & Sanctum (solidifying adept-level knowledge)
├── Redis (expanding use cases beyond caching)
├── FastAPI (building real AI/ML integration pipelines)
├── System Design (daily study — patterns, scalability, trade-offs)
│
Next Up
├── Docker & Containerization (for dev/prod parity)
├── PostgreSQL advanced features (indexing, full-text search)
├── CI/CD pipelines (GitHub Actions)
└── Message queues (deeper dive — Laravel Horizon, Redis Queues)
```
    
