# Natthaphong Thammabut (Champ) 

Backend Developer with 4+ years of experience building production systems in Node.js/TypeScript,
from real-time EV charging (OCPP/WebSocket) and payment integrations (Omise, PromptPay, LINE Pay, Alipay)
to document approval platforms with RBAC. Strong in API design, caching, authentication, and clean architecture.
Currently building an open-source NestJSboilerplate with Kafka, JWT, and health checks.


Bangkok, Thailand · ichamp.natthaphong@gmail.com · +66 64 239 3284 · [github.com/champ-natthaphong](https://github.com/champ-natthaphong)

### Skills

<p align="left">
    <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=typescript" width="50" height=50" alt="typescript" /></a>
    <a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nodejs" width="50" height="50" alt="nodejs" /></a>
    <a href="https://nestjs.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=nestjs" width="50" height="50" alt="nestjs" /></a>
    <a href="https://bun.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=bun" width="50" height=50" alt="bun" /></a>
    <a href="https://elysiajs.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=elysia" width="50" height=50" alt="elysia" /></a>
    <a href="https://www.docker.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=docker" width="50" height=50" alt="docker" /></a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=mongodb" width="50" height=50" alt="mongodb" /></a>
    <a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=postgres" width="50" height=50" alt="postgres" /></a>
    <a href="https://redis.io/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=redis" width="50" height=50" alt="redis" /></a>
    <a href="https://www.prisma.io/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=prisma" width="50" height=50" alt="prisma" /></a>
    <a href="https://sequelize.org/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=sequelize" width="50" height=50" alt="sequelize" /></a>
    <a href="https://www.jest.io/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=jest" width="50" height=50" alt="jest" /></a>
    <a href="https://graphql.org/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=graphql" width="50" height=50" alt="graphql" /></a>
    <a href="https://git-scm.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=git" width="50" height=50" alt="git" /></a>
    <a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=figma" width="50" height=50" alt="figma" /></a>
    <a href="https://www.postman.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=postman" width="50" height=50" alt="postman" /></a>
    <a href="https://www.github.com/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=githubactions" width="50" height=50" alt="githubactions" /></a>
    <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer"><img src="https://skillicons.dev/icons?i=kafka" width="50" height=50" alt="kafka" /></a>
</p>

---


## WORK EXPERIENCE

### Backend Developer, FUJIFILM (Thailand) Ltd.
*Nov 2023 – Apr 2026*

**Photo Booth Backend System**
- Built the Koa.js backend for a photo booth platform with a modular API: file upload, QR code generation, image processing, and printer integration
- Implemented real-time live view and device interaction over WebSocket
- Added production features: rate limiting, validation, logging, error handling, and PM2 clustering, with MongoDB and Redis caching and scheduled background jobs

**Elysia Backend API System**
- Developed a high-performance API with Elysia: modular routes, Swagger docs, CORS, Redis caching, and cron jobs
- Designed APIs for user, admin, transaction, warehouse, and file management

**Document Management System**
- Built configurable multi-level approval workflows covering submission, file attachment, and status tracking
- Implemented RBAC with dynamic approver groups, and locked documents after final approval unless re-initiated

**Integrations:** Omise, LINE Pay, Alipay, PromptPay, Fujifilm Camera SDK, ASK400 Printer

### Backend Developer, Minerta Technology
*Sep 2021 – Oct 2023*

**EV Charging Backend (OCPP Platform)**
- Built an IoT backend with Node.js (Koa) and OCPP (RPC) for real-time communication and control of charging stations
- Designed a scalable system with MongoDB, Redis, and a secured API (authentication, rate limiting, validation)

**Drone Real-time Video Streaming**
- Developed multi-camera, multi-threaded streaming with Python, OpenCV, and TCP sockets, with optimized frame transmission and data serialization for stable low-latency video

---

## PERSONAL PROJECTS

### NestJS Microservice Starter · 2026
`NestJS` `TypeScript` `PostgreSQL` `TypeORM` `Kafka` `JWT` `Docker Compose` `Jest`

- Built a production-ready boilerplate with a 4-layer architecture (Controller → Manager → Service → Repository) and modular features (auth, users, notification)
- Designed a hybrid app serving REST (URI versioning, Swagger) and a Kafka microservice (custom KafkaJS/Confluent transport, automatic topic provisioning) from one codebase
- Implemented JWT/Passport authentication, bcrypt hashing, and a shared library: validation pipe, exception filter, structured logger, interceptors, and a health-check server for database and Kafka dependencies
- Managed schema with TypeORM migrations and seed scripts; set up Jest, ESLint, Prettier, Husky, and Docker Compose (PostgreSQL, Kafka, Kafka UI)

---

## SKILLS

- **Languages/Runtime:** TypeScript, JavaScript, SQL, Node.js, Bun
- **Frameworks:** NestJS, Koa.js, Elysia.js
- **Data/Messaging:** PostgreSQL, MongoDB, Redis, Kafka, MSSQL, Snowflake
- **Security:** JWT/Passport, RBAC, rate limiting
- **DevOps/Tools:** Docker, GitHub Actions, PM2, Git, Swagger
- **Integrations:** OCPP, Omise, LINE Pay, Alipay, PromptPay

---

## EDUCATION

**B.S.Tech.Ed. (Computer Engineering)**
Rajamangala University of Technology Isan, Surin Campus
