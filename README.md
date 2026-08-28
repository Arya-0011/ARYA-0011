# 👋 Hi, I'm Arya Aniket

### Backend Engineer · DevOps · Cloud · Distributed Systems · AI-assisted Engineering

I build **backend systems, developer infrastructure, automation workflows, and cloud-native applications**.

My primary focus is the intersection of:

```text
Backend Engineering
        +
Distributed Systems
        +
DevOps & Cloud
        +
Developer Automation
        +
AI-assisted Software Engineering
```

I enjoy understanding how systems work underneath the abstractions — from APIs and databases to containers, Kubernetes, service meshes, CI/CD pipelines, observability, messaging systems, and increasingly **AI agents and developer tooling**.

---

## 🧭 What I Do

```text
┌──────────────────────────────────────────────────────────────┐
│                       ENGINEERING                            │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│  ⚙️ Backend          Build APIs, services & microservices    │
│                                                              │
│  📨 Distributed      Kafka, Redis, queues & event systems    │
│     Systems                                                  │
│                                                              │
│  ☁️ Cloud & DevOps   Docker, Kubernetes, AWS & IaC          │
│                                                              │
│  🔄 Automation       CI/CD, GitHub automation & tooling     │
│                                                              │
│  📊 Observability    Metrics, logs, tracing & monitoring     │
│                                                              │
│  🔐 DevSecOps        Security integrated into delivery      │
│                                                              │
│  🤖 AI Engineering   Agents, MCP & AI coding workflows       │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

# 🚀 Currently Building & Exploring

### 🤖 AI-assisted Software Engineering

I'm increasingly interested in **how AI can change the software development process itself**, not just generate code.

Current areas of exploration include:

- AI coding agents
- Claude Code
- Kiro
- MCP
- Agent workflows
- Context engineering
- Codebase knowledge graphs
- AI-assisted code navigation
- AI-assisted code review
- Token/context optimization
- Developer productivity tooling
- Agent-specific instructions and skills
- Automated development workflows

I'm particularly interested in the architecture behind systems such as **Graphify**, **Ponytail**, MCP-based tooling, and agent-specific workflows — and how these ideas can be combined into practical engineering environments.

```text
                     Developer
                         │
                         ▼
                ┌─────────────────┐
                │   AI Coding     │
                │     Agent       │
                └────────┬────────┘
                         │
            ┌────────────┼────────────┐
            │            │            │
            ▼            ▼            ▼
        Codebase       Tools        Context
        Knowledge       MCP        / Memory
            │            │            │
            └────────────┼────────────┘
                         │
                         ▼
                 Development Loop
                         │
              ┌──────────┴──────────┐
              ▼                     ▼
          Generate                Verify
              │                     │
              └──────────┬──────────┘
                         ▼
                    Ship Faster
```

---

# 🧠 My Engineering Interests

I tend to gravitate toward systems where multiple pieces have to work together.

### Backend

- REST APIs
- Microservices
- Modular architecture
- Authentication & authorization
- Event-driven systems
- API design
- Background workers
- Distributed services
- Performance optimization

### Distributed Systems

- Apache Kafka
- Redis
- Event-driven architecture
- Message queues
- Service-to-service communication
- Distributed caching
- Data consistency
- Failure handling

### Cloud & Infrastructure

- AWS
- Docker
- Kubernetes
- Terraform
- Ansible
- Vagrant
- Nginx
- Apache
- Cloudflare
- DigitalOcean
- Vultr
- Linode

### DevOps

- CI/CD
- GitHub Actions
- GitLab CI
- Jenkins
- TeamCity
- ArgoCD
- GitOps
- Infrastructure as Code
- Automated deployments
- Environment management

### Observability

- Prometheus
- Grafana
- Elasticsearch
- Logging
- Metrics
- Monitoring
- Application diagnostics
- Production troubleshooting

### Platform & Networking

- Kubernetes networking
- Istio
- Service Mesh
- WireGuard
- Reverse proxies
- Container networking

### DevSecOps

- SonarQube
- SonarLint
- Security-aware CI/CD
- Static analysis
- Secure deployment pipelines

---

# ⚙️ Backend Engineering

My backend work primarily revolves around **TypeScript/Node.js and NestJS**, while I also experiment with other ecosystems.

```text
Client
  │
  ▼
API Gateway / Reverse Proxy
  │
  ▼
┌────────────────────────────────────┐
│           Backend Services          │
│                                    │
│  NestJS      Node.js      Express  │
│                                    │
└───────────────┬────────────────────┘
                │
       ┌────────┼─────────┐
       ▼        ▼         ▼
    PostgreSQL Redis     Kafka
       │        │         │
       └────────┼─────────┘
                ▼
        Supporting Services
                │
                ▼
       Docker / Kubernetes
                │
                ▼
       Monitoring & Logging
```

I'm especially interested in:

- Clean service boundaries
- Microservice architecture
- Database design
- Caching strategies
- Event-driven communication
- API performance
- Background processing
- Observability
- Production debugging
- Deployment architecture

---

# 📨 Event-Driven Architecture

Apache Kafka and event-driven systems are an area I'm actively exploring.

The architecture I'm interested in looks roughly like:

```text
                 ┌───────────────┐
                 │   Service A   │
                 └───────┬───────┘
                         │
                         ▼
                  ┌─────────────┐
                  │    Kafka    │
                  │   Topics    │
                  └──────┬──────┘
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
        Service B   Service C   Service D
             │           │           │
             ▼           ▼           ▼
          Redis       Database     Search
```

Areas I'm interested in:

- Producers & consumers
- Topics & partitions
- Consumer groups
- Event-driven microservices
- Retry strategies
- Idempotency
- Dead-letter queues
- Ordering
- Event processing
- Distributed failure handling

---

# ☸️ Kubernetes & Cloud Native

I'm interested in moving beyond simply running containers and understanding the **platform layer underneath production applications**.

Current areas:

- Kubernetes
- Deployments
- Services
- Ingress
- ConfigMaps
- Secrets
- Persistent storage
- Horizontal scaling
- Service discovery
- Helm
- GitOps
- ArgoCD
- Kubernetes networking
- Istio
- Service Mesh

My mental model:

```text
                    Kubernetes
                        │
        ┌───────────────┼────────────────┐
        │               │                │
      Compute         Network          Storage
        │               │                │
     Pods/Nodes      Services        Volumes
        │               │
        └───────┬───────┘
                │
             Istio
                │
        ┌───────┴────────┐
        │                │
   Traffic Control   Observability
        │                │
        ▼                ▼
    Resilience      Prometheus
    Security        Grafana
    Routing         Logs
```

---

# 🔄 DevOps & Automation

I enjoy automating repetitive engineering tasks.

Areas I've worked with:

- GitHub automation
- CI/CD pipelines
- Deployment automation
- Infrastructure provisioning
- Linux automation
- Shell scripting
- Git workflows
- Environment setup
- Developer tooling
- Infrastructure as Code

### Tooling

`GitHub Actions` · `GitLab CI` · `Jenkins` · `TeamCity` · `Terraform` · `Ansible` · `Docker` · `Kubernetes`

---

# 📊 Observability

A system isn't really production-ready if you can't understand what it is doing.

I'm interested in the full observability pipeline:

```text
Application
    │
    ├──────────────► Logs
    │                  │
    │                  ▼
    │            Elasticsearch
    │
    ├──────────────► Metrics
    │                  │
    │                  ▼
    │              Prometheus
    │                  │
    │                  ▼
    │               Grafana
    │
    └──────────────► Traces
                       │
                       ▼
                  Distributed
                   Debugging
```

Areas I'm exploring:

- Application logging
- Structured logs
- Metrics
- Dashboards
- Alerting
- Performance monitoring
- Distributed systems debugging
- Production diagnostics

---

# 🔐 DevSecOps

I don't see security as a separate step at the end of the pipeline.

The goal is:

```text
Code
 │
 ▼
Lint
 │
 ▼
Test
 │
 ▼
Static Analysis
 │
 ▼
Security Checks
 │
 ▼
Build
 │
 ▼
Container
 │
 ▼
Deploy
 │
 ▼
Monitor
```

Tools I've worked with / explored include:

`SonarQube` · `SonarLint` · `GitHub Actions` · `GitLab CI` · `Docker` · `Kubernetes`

---

# 🧰 Technology Stack

## Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-121011?style=flat-square&logo=gnu-bash&logoColor=white)

## Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)

## Databases & Data

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

## Messaging & Distributed Systems

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

## Cloud & Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

## CI/CD & GitOps

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![TeamCity](https://img.shields.io/badge/TeamCity-000000?style=flat-square&logo=teamcity&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

## Observability

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

## Networking & Platform

![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)

## Developer Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

# 🧪 Selected Projects

## 🐧 Linux Tools & Installation Scripts

A collection of scripts for installing and configuring commonly used Linux and DevOps tooling.

**Focus:** Linux · Shell · DevOps · Automation

🔗 [View repository](https://github.com/Arya-0011/Linux-Tools-Installation-Scripts)

---

## ⚙️ GitHub Automation

Automation experiments around GitHub workflows and repository maintenance.

**Focus:** GitHub APIs · Automation · Developer Productivity

🔗 [View repository](https://github.com/Arya-0011/github-automation)

---

## 🔐 DevSecOps

A collection of DevSecOps learning material, tooling and practices around integrating security into the software delivery lifecycle.

**Focus:** DevOps · Security · CI/CD · Automation

🔗 [View repository](https://github.com/Arya-0011/DevSecOps)

---

# 🤖 AI Developer Tooling

I'm also building a personal ecosystem around **AI-assisted development**.

The goal isn't simply:

> "Ask an AI to write code."

The interesting problem is:

> **How do we give an AI agent the right context, tools, constraints and feedback so that it behaves more like an effective software engineer?**

This leads me toward:

```text
             AI Coding Agent
                    │
          ┌─────────┼─────────┐
          │         │         │
       Context     Tools    Rules
          │         │         │
          ▼         ▼         ▼
       Graphify    MCP     Agent Skills
          │         │         │
          └─────────┼─────────┘
                    │
                    ▼
             Code Generation
                    │
                    ▼
              Verification
                    │
                    ▼
                 Commit
                    │
                    ▼
                 CI/CD
```

Areas I'm experimenting with include:

- Kiro
- Claude Code
- MCP
- Graph-based code context
- Agent skills
- Agent instructions
- Codebase navigation
- AI-powered development workflows
- Token-efficient context
- Automated verification
- Developer productivity systems

---

# 🧠 Graph-Based Code Understanding

One of the areas I'm particularly interested in is using **graphs to understand codebases**.

Instead of asking an agent to repeatedly search through an entire repository:

```text
Repository
    │
    ▼
AST / Source Analysis
    │
    ▼
Knowledge Graph
    │
    ├── Files
    ├── Classes
    ├── Functions
    ├── Imports
    ├── Calls
    ├── Dependencies
    └── Relationships
            │
            ▼
       Agent Query
            │
            ▼
      Relevant Context
```

This can potentially reduce unnecessary context while making architectural relationships easier for an agent to understand.

I'm exploring this space through tools and workflows involving **Graphify, MCP and AI coding agents**.

---

# 🧩 AI Coding Workflow

My current approach is evolving toward a multi-layer development workflow:

```text
                    ┌───────────────┐
                    │   Developer   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ AI Agent / IDE│
                    └───────┬───────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
          Context          Tools          Rules
             │              │              │
          Graphify          MCP        Agent Skills
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                    Implementation
                            │
                            ▼
                    Tests / Linting
                            │
                            ▼
                       Verification
                            │
                            ▼
                          Git
                            │
                            ▼
                         CI/CD
```

I'm interested in making this workflow **repeatable, observable and maintainable**, rather than relying entirely on ad-hoc prompting.

---

# 📚 Currently Learning

### Deepening

- Kubernetes
- Apache Kafka
- NestJS architecture
- Microservices
- Distributed systems
- AWS
- CI/CD
- Observability
- Infrastructure as Code

### Exploring

- Istio
- Service Mesh
- ArgoCD
- GitOps
- MLOps
- AI agents
- MCP
- AI developer tooling
- Local model inference
- LLM application architecture

---

# 🗺️ My Learning Path

```text
Backend
   │
   ▼
APIs & Databases
   │
   ▼
Microservices
   │
   ▼
Messaging & Distributed Systems
   │
   ▼
Docker
   │
   ▼
Kubernetes
   │
   ├──────────────► Observability
   │
   ├──────────────► Service Mesh
   │
   └──────────────► GitOps
                         │
                         ▼
                       Cloud
                         │
                         ▼
                       MLOps
                         │
                         ▼
                  AI Engineering
                         │
                         ▼
                AI-assisted Development
```

---

# 🏗️ Engineering Philosophy

### 01 — Understand the system

I like knowing what happens underneath the abstraction.

### 02 — Automate repetitive work

If something has to be repeated often, it probably deserves automation.

### 03 — Observe everything important

A production system should make it possible to understand what went wrong.

### 04 — Keep systems simple

Complexity should have a reason.

### 05 — Learn by building

I prefer experimenting with real systems instead of only reading about them.

### 06 — Use AI as an engineering tool

AI should improve the engineering process — not replace engineering thinking.

---

# 📈 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Arya-0011&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Arya-0011&layout=compact&hide_border=true&theme=transparent" height="165">
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Arya-0011&hide_border=true&theme=transparent" />
</p>

---

# 🏆 GitHub

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Arya-0011&theme=flat&no-frame=true&no-bg=true&margin-w=10" />
</p>

---

# 📊 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Arya-0011&hide_border=true&theme=github-compact" />
</p>

---

# 🌐 Connect With Me

<p align="center">

<a href="mailto:aryaaniket2001@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://linkedin.com/in/arya-aniket2001/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://x.com/aryaaniket2001">
<img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/>
</a>

<a href="https://github.com/Arya-0011">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

---

# 💬 A Few Things About Me

```text
⚙️ Backend > Frontend

☁️ DevOps isn't just deployment —
   it's understanding the entire system.

🧠 I enjoy understanding how systems work
   underneath the abstraction.

🤖 Currently fascinated by AI coding agents
   and developer tooling.

🐧 Linux + automation + containers
   is a combination I genuinely enjoy.

📚 Most of my learning happens by building,
   breaking, debugging and rebuilding.
```

---

<p align="center">

### "Build it. Break it. Understand it. Automate it."

<br>

<img src="https://komarev.com/ghpvc/?username=Arya-0011&style=flat-square&color=blue" alt="Profile views"/>

</p>
