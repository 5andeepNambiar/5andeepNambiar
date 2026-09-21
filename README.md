# Hi, I'm Sandeep Prem Nambiar 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/sandeep-nambiar)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:sandeepnambiar02@gmail.com)

**Full Stack Software Engineer** specializing in **distributed billing, transaction switches, and event-driven architectures**[cite: 7]. Currently engineering high-concurrency payment-adjacent systems at **Copart India Technology Centre** across Java, Spring Boot, MariaDB, Redis, Apache Kafka, and Angular[cite: 7].

---

### ⚡ Technical Snapshot

- **Languages:** Java (Multithreading, Concurrency), TypeScript, JavaScript, SQL, Python[cite: 7]
- **Backend & Frameworks:** Spring Boot, Spring Data JPA, Hibernate, REST APIs, Microservices, FastAPI, Node.js[cite: 7]
- **Distributed Systems & Storage:** Apache Kafka, Redis (Distributed Locking, Rate Limiting, Cache-Aside), MariaDB, MySQL, MongoDB[cite: 7]
- **Architecture & Reliability:** Low-Latency Systems, Idempotent Operations, Transactional Outbox Pattern, Circuit Breakers, ACID Ledgers[cite: 7]
- **Frontend:** Angular (v14+), RxJS, TypeScript, State Management, HTML5, SCSS[cite: 7]
- **Engineering Practices:** Docker, CI/CD, JUnit, Mockito, Agile/Scrum, Git, Linux, OWASP Secure Coding[cite: 7]

---

### 🚀 Featured Systems Engineering Projects

#### ⚡ [AgenticUPI — Delegated UPI-Style Micro-Payment Engine](https://github.com/5andeepNambiar/AgenticUPI)
> **Stack:** Java, Spring Boot, MariaDB, Redis, Kafka, FastAPI, Angular[cite: 7]  
> *Production-inspired delegated execution switch modeling autonomous micro-transactions under user-defined revocable mandates, per-transaction caps, and rolling 24-hour velocity limits[cite: 7].*

- **Deterministic Safety Controls:** Built a policy gateway enforcing HMAC-signed agent intents, Redis Lua-based velocity reservations, and cache-level mandate revocation[cite: 7].
- **ACID Persistence & Outbox Engine:** Designed the persistence layer with MariaDB ACID ledgering, durable idempotency keys, transaction state machines, and transactional outbox events for zero-loss Kafka publishing[cite: 7].
- **Reconciliation & Recovery:** Modeled UPI-style reconciliation flows for downstream timeouts, ambiguous payment states, compensating ledger entries, and audit-grade event replay[cite: 7].

---

#### 🛡️ [AI-Powered Threat Detection & Security Analysis Engine](https://github.com/5andeepNambiar/AI-Threat-Detection-Platform)
> **Stack:** Python, FastAPI, AngularJS, MariaDB, Vector DB[cite: 7]  
> *Asynchronous security log analysis platform identifying anomalous access patterns and vulnerability summaries across distributed services[cite: 7].*

- **Asynchronous Log Analysis Pipeline:** Built high-throughput ingestion services using FastAPI and vector similarity search to identify suspicious access anomalies across distributed service logs in real time[cite: 7].
- **Telemetry & Visualization Console:** Developed an administrative dashboard in AngularJS to render real-time threat telemetry, vulnerability summaries, and audit logs[cite: 7].

---

#### 🔗 [LinkForge — Distributed Low-Latency Redirection & Analytics Platform](https://github.com/5andeepNambiar/LinkForge)
> **Stack:** Java, Spring Boot, Redis, Apache Kafka, MariaDB, Angular, Docker[cite: 1]  
> *Horizontally scalable distributed redirection engine built for high-throughput read paths with sub-15ms resolution latency[cite: 1].*

- **Cache-Aside Architecture:** Designed a multi-tier cache hierarchy with Redis to serve high-traffic redirection paths with low latency while reducing relational database load[cite: 1].
- **Distributed Rate Limiting:** Enforced token-bucket throttling using Redis primitives to protect downstream persistence layers during traffic surges[cite: 1].
- **Decoupled Telemetry Pipeline:** Streamed clickstream events asynchronously through Apache Kafka consumer groups, isolating redirection latency from real-time analytics aggregation[cite: 1].

---

### 💼 Engineering Impact at a Glance (Copart India)

- **35% P95 Latency Reduction:** Reduced p95 response times from **410ms to 265ms** by refactoring REST microservices, introducing Redis cache-aside layers, and optimizing MariaDB index lookups[cite: 7].
- **Rebate Payout Engine:** Designed and built an automated payout execution platform leveraging Kafka-published batch events, per-seller distributed locking, and idempotent execution semantics[cite: 7].
- **Zero-Downtime Migration:** Owned lot billing management migration from the legacy platform to a modernized Spring Boot microservices architecture with continuous operational continuity[cite: 7].
- **Automated Cache Refresh:** Built Redis Pub/Sub cache invalidation and automated pod-level cache refresh flows, eliminating manual multi-service restarts during seller onboarding[cite: 7].

---

### 📄 Research & Publications

- **Large Language Model Security:** Published research paper on Large Language Model Security at **IEEE ICEEICT (2024)**[cite: 7].

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=5andeepNambiar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=5andeepNambiar&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>
