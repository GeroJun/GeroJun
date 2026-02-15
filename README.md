# Victor (Gero) Jun

**Backend Engineer | CS @ APU (May 2026) | Rust, Node.js, Kubernetes**

Building distributed systems and infrastructure. Focused on performance optimization, fault tolerance, and scalable architectures.

---

## 💻 What I'm Working On

- **Kubernetes Authentication Infrastructure** – Building Gateway API v1.4 external auth service. Migrated from Node.js to Rust, achieving 3x throughput improvement through systematic benchmarking.
- **Production Microservices @ APU** – Maintaining systems serving 6,000+ users. Eliminated 20+ hours/week of manual work through automation.
---

## 📌 Featured Projects

### [Real-Time Settlement Engine](https://github.com/GeroJun/Real-Time-Transaction-Settlement-System)
FastAPI-based financial gateway with Kafka event streaming. Implements sub-millisecond idempotency using Redis and enforces strict settlement windows (T+0, T+1) for transaction processing.

**Stack:** Python, FastAPI, Apache Kafka, Redis, Docker  
**Patterns:** Event Sourcing, Idempotency, Async Processing

**Key Features:**
- Kafka-based event streaming for decoupled transaction processing
- Redis-backed idempotency to prevent double-spending
- Pydantic schema validation for financial data integrity
- OpenAPI/Swagger documentation

[View Code →](https://github.com/GeroJun/Real-Time-Transaction-Settlement-System)

---

### [Payment Reconciliation Engine](https://github.com/GeroJun/payment-reconciliation-engine)
Node.js payment processing system implementing double-entry accounting with async processing via AWS SQS FIFO. Built to understand production payment patterns.

**Stack:** Node.js, Express, PostgreSQL, Redis, AWS SQS, Docker  
**Patterns:** Double-Entry Ledger, Idempotency, Async Workers

**Key Features:**
- Double-entry ledger for financial accuracy
- Redis-based idempotency for safe retries
- AWS SQS FIFO integration for async processing
- Background workers for transaction processing
- Full audit trail with ledger history

[View Code →](https://github.com/GeroJun/payment-reconciliation-engine)

---

### Production Work @ APU

**Device Onboarding Portal** ([byod.apu.edu](https://byod.apu.edu))  
Self-service network authentication portal serving 6,000+ users. Reduced IT support tickets by 30%.  
*Stack: TypeScript, Node.js, Bootstrap, Docker*

**Photo Compliance Automation**  
Eliminated 20+ hours/week of manual ID photo validation by building automated reconciliation system processing 43,000+ records. Zero maintenance required since deployment.  
*Stack: Node.js, PeopleSoft API, Google Sheets API, Docker*

---

## 🛠️ Tech Stack

**Languages:** Rust, Python, TypeScript, JavaScript, SQL  
**Backend:** Node.js, FastAPI, Express  
**Infrastructure:** Kubernetes, Docker, Apache Kafka, Redis, PostgreSQL  
**Cloud:** AWS (SQS, Lambda, S3)  
**Patterns:** Event Sourcing, CQRS, Idempotency, Double-Entry Accounting

---

## 📫 Connect

- **Email:** gjun21@apu.edu
- **LinkedIn:** [(www.linkedin.com/in/gerojun)](https://www.linkedin.com/in/gerojun/)
- **Location:** Los Angeles, CA
- **Status:** Graduating May 2026, seeking New Grad SWE roles

**Work Authorization:** 3 years (STEM OPT)

---

*Currently seeking backend/infrastructure engineering roles for June 2026 start. Interested in distributed systems, payments, or Kubernetes ecosystem.*
