# Hi, I'm Dennis!

I'm a software development Student with a focus on Java, Spring Boot & a bit of fullstack web development.

Currently: Studying att IT-Högskolan and looking for a 6-month full-time internship (Nov – May).

## School projects

### [BrainDead – Web-based Satire Zombie Survival Quiz Game](https://github.com/TatjanaTrajkovic/BrainDead)
Group project: A choice-driven zombie survival game set in a zombie-infested Gothenburg.
Game loop of scenario → question → answer → feedback where every choice affects your brain capacity (health multiplier),
with resumable game sessions (create/resume/pause), anonymous guest players via hashed cookie tokens and a simple login system.
Backend: Node.js, Express and MySQL (mysql2) in a layered architecture (routes → controllers → services),
transactions with row locking for answer submission, CI (lint, prettier, unit tests) on GitHub Actions.
Frontend: Vue 3, Vite, vue-router, composables.
Art assets: AI-generated, then hands-on cleanup and adjusting to get the right feel – letting us focus on code and game logic.

### [School Portal – Case Management System](https://github.com/ithsjava25/project-backend-team-my-codebase-brings-all-the-boys)
Group project: A security-focused case management system for school environments.\
Handles assignment workflows (create → turn in → grade), enrollment-based role access control (admin/mentor/teacher/student),\
secure file uploads to AWS S3 and activity logging.\
Backend: Java 21 and Spring Boot with PostgreSQL, GitHub OAuth2 and CI via GitHub Actions\
Frontend: React, Vite, Tailwind.

### [AI-lab](https://github.com/DennSel/ai-lab)
A Spring Boot middleware chat service with per-session conversation memory that sits between a frontend and LLM providers via OpenRouter.\
Exposes a REST API, automatic retry with exponential backoff, and interactive Swagger documentation.\
Java 21+, Maven.

### [Game Library](https://github.com/DennSel/gamelibrarylab)
School project: A (deliberately simple) web app for managing game collections.\
Full CRUD, search by title and developer, pagination, form validation.\
Stack: Java 25, Spring Boot (MVC), Spring Data JPA, Thymeleaf, and an H2 database.

### [Library system](https://github.com/ithsjava25/project-jpa-grupp-6-d)
Group project: JPA and Hibernate with a GitHub workflow.\
A Java application backed by a relational database, built with feature branches,\ 
pull requests with code review and CI. Also uses Docker.

### [Labb2TDD](https://github.com/DennSel/Labb2TDD)
An exercise in test-driven development (TDD) and mocking with JUnit and Mockito.

### [Laboration-1-Git](https://github.com/DennSel/Laboration-1-Git)
First assignment — the basics of Git: repositories, commits, and workflow.

### [KandSys – Multi-Tenant Mini-ATS (Technical AI assignment)](https://github.com/DennSel/mini-ats)
:A multi-tenant Applicant Tracking System (ATS) for managing recruitment pipelines and candidate pools. 
Built entirely through agentic AI pair programming as a test to evaluate autonomous AI development, architectural discipline, and strict security invariants.

- **Features:** Drag-and-drop Kanban board, candidate bank, job management, interview scheduling, and secure CV uploads via private buckets and signed URLs.
- **In-Memory Demo Mode:** Fully isolated sandbox toggleable by admins, letting visitors test the entire ATS without touching the database.
- **Backend & Security:** Supabase (PostgreSQL) with strict Row-Level Security (RLS) enforcing tenant isolation on all tables and storage.
Verified with 17 pgTAP database regression tests.
- **Frontend & Stack:** React 19, TanStack Start, TanStack Router, TanStack Query, and Tailwind CSS.
- **Quality & CI:** 52 Vitest unit tests, ESLint, Prettier, and automated GitHub Actions CI.

## Tech stack dabbled in so far
| Category | Technologies |
|---|---|
| **Backend** | Java, Spring Boot, REST APIs, Node.js (express) |
| **Databases** | PostgreSQL, MySQL, SQL, H2 |
| **Persistence** | Spring Data JPA, JDBC, Hibernate |
| **Testing & QA** | JUnit, Mockito, Vitest, TDD |
| **Desktop** | JavaFX |
| **Security & Auth** | Spring Security, JWT, OAuth2, RBAC |
| **Frontend** | React, Vue.js, JavaScript, HTML, CSS, Tailwind, Thymeleaf |
| **DevOps & Tools** | Git, GitHub, GitHub Actions (CI/CD), Docker, Maven, Vite |
| **Other** | Microservices, AWS S3, JSON, XML, Figma |
