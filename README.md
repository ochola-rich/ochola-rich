# Richard Ochola

**Backend Engineer | Go, Distributed Systems & Payment Architectures (M-Pesa, Lightning)**  
Nairobi, Kenya • [LinkedIn](https://www.linkedin.com/in/richard-ochola) • [Dev.to](https://dev.to/ochola) • [Email](mailto:richardochola3@gmail.com)

---

### Engineering Focus

I build reliable backend systems, microservices, and payment integrations. My core experience centers on low-latency APIs in **Go**, financial integrations (Safaricom Daraja / M-Pesa, Flutterwave, and Bitcoin Lightning / LND), and resilient data processing pipelines.

- **Payment Systems & Fintech**: STK Push workflows, B2C disbursals, webhook validation, idempotency, and automated retries across mobile money and Lightning channels.
- **Microservices & Concurrency**: High-performance HTTP/gRPC services in Go, background worker orchestration, and containerized architectures.
- **Data & Vector Pipelines**: Clean service boundaries combining Go ingestion layers with Python ML/vector search services and PostgreSQL (pgvector).

---

### Featured Projects

#### [Loot](https://github.com/ochola-rich/Loot)
*Multi-Gateway Payment Engine (M-Pesa, Flutterwave, AES-256 Encryption)*
- Multi-gateway payment orchestrator routing transactions dynamically across **Safaricom Daraja (M-Pesa)** and **Flutterwave**.
- Implemented secure webhook ingestion with CIDR-based IP whitelisting and payload signature verification.
- Stored sensitive phone numbers using AES-256-GCM encryption at rest.
- Backed by automated CI workflows and containerized deployments.

#### [SkillSats](https://github.com/ochola-rich/SkillSats)
*P2P Marketplace with Bitcoin Lightning Payments*
- Built end-to-end Bitcoin Lightning settlement workflows using the **LND REST API** for instant micro-transactions and creator withdrawals.
- Scripted headless local Bitcoin Core regtest network automation: generates dual LND nodes, mines blocks, and balances channel liquidity for local testing.
- Integrated PostgreSQL and Prisma with transaction verification suites.

#### [Intelligent Document Analyzer](https://github.com/ochola-rich/Intelligent-Document-Analyzer)
*Polyglot Microservices Pipeline (Go, Python, pgvector, Docker)*
- Architected a distributed document processing system with a **Go API Gateway** managing asynchronous job state and upload staging.
- Python ML worker service handling text extraction, chunking, and semantic vector embeddings stored in PostgreSQL with **pgvector**.
- Orchestrated with Docker Compose for seamless local and production reproducibility.

---

### Open Source Contributions

- **[paykit-go](https://github.com/Flying-Tea-Squad/paykit-go)**: Core contributor to an open-source Go SDK for African payment gateways.
  - Implemented OAuth2 token management and caching for Safaricom Daraja M-Pesa.
  - Built request/response models and test suites for B2C disbursals, C2B simulations, account balance queries, and STK push callbacks.

---

### Core Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | Go, Python, Java, SQL, TypeScript |
| **Backend & Systems** | Microservices, REST APIs, Webhooks, Concurrency & Workers, OAuth2 |
| **Databases & Stores** | PostgreSQL, pgvector, Redis, Prisma |
| **Fintech & Protocols** | Safaricom Daraja (M-Pesa STK & B2C), Bitcoin Lightning (LND), Flutterwave |
| **DevOps & Cloud** | Docker, Docker Compose, Git, Linux, GitHub Actions CI/CD |

---

### Connect

- **LinkedIn**: [linkedin.com/in/richard-ochola](https://www.linkedin.com/in/richard-ochola)
- **Dev.to**: [dev.to/ochola](https://dev.to/ochola)
- **GitHub**: [github.com/ochola-rich](https://github.com/ochola-rich)
