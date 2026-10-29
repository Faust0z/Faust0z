### Hi, I'm Fausto 👋
**Backend Engineer (Java / Spring Boot)** · Argentina

For the past two years I worked as a B2B contractor at a software factory, building the backend of a multi-tenant SaaS from scratch in a team of up to four. I'm looking to join a larger engineering team and work on systems of greater scale.

**What I've built**
- **Multi-tenant SaaS backend** (Java 21, Spring Boot 3.5, Spring Modulith): identity, billing and core modules that communicate through events, with tenant isolation via Hibernate `@TenantId`.
- **Performance:** moved read projections into native PostgreSQL views, removing N+1 queries and avoiding loading full entities into memory. Result: 45% lower read latency and about 150 MB less JVM heap. Local caching with Caffeine (migrated from Redis).
- **Quality:** 564 tests (JUnit 5, Testcontainers on real PostgreSQL) plus ArchUnit rules that fail the build if any entity or native query skips the tenant filter.
- **Delivery:** GitHub Actions CI/CD that cut pipeline time from 15 to 5 minutes, with Flyway versioned migrations.
- **Security:** stateless OAuth2/JWT with role-based access control.
- **Teamwork:** peer code review with a senior lead, and legacy migrations (Python to Spring Boot, older Spring to current).
- **Applied project:** led a team of 8 students building a Flask API for a real client (Aeroclub Lincoln), gathering requirements directly from its board.
- **AI-assisted development with guardrails:** documented invariants (`AGENTS.md`) and architecture tests that keep generated code inside the rules.

**Currently working on**
- Observability: Micrometer, Prometheus, Grafana
- AWS deployment with Terraform
- RAG over text documents with pgvector

**Education:** Licenciatura en Informática, UNSAdA (2026)

**_Let's connect: [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fausto-mansilla-sanz-289038367/)_**

---

## 💻 Tech Stack
![Java 21](https://img.shields.io/badge/java_21-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring_boot-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-%232088FF.svg?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
