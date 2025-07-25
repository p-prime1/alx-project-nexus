# 🚀 ProDev Backend Engineering: My Progress and Learnings

A documentation of my Journey in the ProDev Engineering program. This repository contains the concepts, tools, technologies, best practices, and challenges I’ve explored and overcome as I deepen my expertise in building scalable and maintainable backend systems.

---

## 🛠️ Technologies & Tools

Here are the core technologies and tools I’ve worked with:

- **Django** – Web framework for building RESTful APIs
- **Celery** – Distributed task queue for asynchronous jobs
- **GraphQL** – API query language for flexible data fetching
- **Django REST Framework (DRF)** – Toolkit for building robust APIs
- **Docker** – Containerization for app deployment
- **Kubernetes** – Orchestration for managing Docker containers
- **Git & Git Flow** – Branching strategy and version control
- **Jenkins** – CI/CD automation
- **PostgreSQL & MongoDB** – SQL and NoSQL database systems
- **Redis** – In-memory store for caching and background tasks
- **Shell (SSH, Bash)** – Secure server access, configuration, and scripting

---

## 🧠 Core Backend Concepts

### 1. **Database Design & Query Optimization**
- Normalization and denormalization techniques
- Indexing and foreign keys
- Complex SQL joins and query optimization
- Modeling many-to-many and one-to-many relationships in Django ORM

### 2. **Asynchronous Programming**
- Background processing with Celery and Redis
- Using Django signals and Celery for decoupling heavy logic
- Handling long-running tasks like email sending, file uploads, and external API calls

### 3. **Caching Strategies**
- Redis for caching database queries and view logic
- Implementing cache invalidation and TTL (Time to Live)


### 4. **API Development**
- RESTful architecture using Django REST Framework
- GraphQL schema and resolver design for complex queries
- Token-based authentication with JWT
- Versioning, pagination, filtering, and rate limiting

### 5. **Containerization & Deployment**
- Dockerizing Django, Celery, and PostgreSQL
- Writing Docker Compose files
- Understanding Kubernetes Pods, Services, and Deployments
- Building CI/CD pipelines with Jenkins

### 6. **Security & SSH**
- Generating and configuring SSH RSA key pairs
- Managing SSH config for multiple remote hosts
- Disabling password authentication for improved security

---

## 🔧 System Design & Architecture

- Monolithic vs Microservices architectures
- Designing scalable APIs and background job processing flows
- Load balancing and horizontal scaling
- Logging, monitoring, and observability basics

---

## ⚠️ Challenges Faced

Here are some of the challenges I encountered and how I approached them:

- **SSH Configuration Confusion**:  
  Difficulty managing multiple SSH keys and remote hosts. Solved by customizing `.ssh/config` and understanding identity file settings.

- **Celery & Redis Setup Issues**:  
  Ensuring the Celery worker connects properly to Redis and Django settings.

- **Docker Networking**:  
  Encountered confusion with container-to-container communication and volumes. Solved through documentation and trial with Docker Compose.

- **Database Performance**:  
  Faced performance bottlenecks in complex queries. Improved with indexing and query profiling.

- **Raycasting & Game Logic (for side project)**:  
  Struggled with implementing raycasting for a 2D maze game. Learned to break down the algorithm and visualize rays and collisions step-by-step.

- **Debugging Fatigue**:  
  Found debugging to be draining initially. Learned to treat it as detective work and pace myself with structured breaks.

---

## 💡 Personal Takeaways & Best Practices

- **Think in Systems**:  
  Backend engineering is more than code; it’s about orchestrating reliable systems.

- **Document Everything**:  
  Keeping good internal documentation prevents repeated confusion.

- **Security First**:  
  Be proactive with secrets, authentication, and server configurations.

- **Start Simple, Scale Later**:  
  Focus on clarity and simplicity before trying to optimize prematurely.

- **Learn by Doing**:  
  The best way to internalize concepts like CI/CD, caching, and async tasks is by building and debugging real use cases.

- **Version Control Discipline**:  
  Using Git flow helped structure my development process and reduce merge conflicts.

---


---

## 📅 Ongoing Goals

- Learn and implement testing strategies: unit, integration, and mock testing.
- Build an api for movie suggestions
- Write more system design case studies.

---

> This documentation is a living project and will continue to grow as I progress.


