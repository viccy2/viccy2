# Victor Aremu David 👋

I’m a backend engineer specializing in distributed systems, transactional state machines, and cloud infrastructure. Most of my work involves writing Go, Python, and TypeScript, optimizing database performance, and building resilient async architecture.

Over the past few years, I’ve engineered backend infrastructure for platforms supporting 10k+ daily users, deployed CV inference pipelines handling 10,000+ daily evaluations at 99.9% uptime, and managed zero-downtime infrastructure scaled with Kubernetes and Terraform.

---

### 🛠 Tech Stack

* **Languages:** Go, Python, TypeScript, SQL
* **Data & Storage:** PostgreSQL, Redis, MySQL, MongoDB
* **Messaging & Queues:** Kafka, RabbitMQ, BullMQ
* **Infrastructure:** Kubernetes, Docker, Terraform, AWS, GCP, Nginx, GitHub Actions
* **Observability:** Prometheus, Grafana

---

### Selected Technical Work

#### [Utidia](https://utidia.com/) — Talent Recruitment & Matching Platform
* **Architecture:** Led the backend migration from a monolithic Node.js codebase to a microservice architecture to decouple application processing from user management.
* **Database & Cache:** Cut API response times by ~30% by restructuring slow PostgreSQL queries with composite indexes and implementing a Redis caching layer for read-heavy endpoints.
* **Payments:** Designed idempotent payment webhooks (Paystack/Stripe) using Redis locks to eliminate duplicate transactions caused by network retries.

<a href="https://utidia.com/">
  <img src="https://img.shields.io/badge/View_Platform-000000?style=for-the-badge&logo=googlechrome&logoColor=white" />
</a>

---

#### [FinTrack](https://fin-track-tau-one.vercel.app/) — Concurrent Financial Analytics Engine
* **Concurrency:** Built transaction-processing pipelines in TypeScript/Node.js, isolating async background processing from the primary REST API thread using message queues.
* **Reliability:** Implemented transactional outbox patterns and idempotency keys across financial workflows to ensure state consistency during partial network failures.

<a href="https://fin-track-tau-one.vercel.app/">
  <img src="https://img.shields.io/badge/View_Platform-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

---

#### [Event Reconciler](https://github.com/viccy2/lightwork-reconciler-task-victor-david) — Distributed Event Reconciliation Engine
* **Eventual Consistency:** Designed a lightweight reconciliation service in TypeScript to detect and resolve out-of-order state mutations across concurrent event streams.
* **Conflict Resolution:** Implemented deterministic conflict-resolution rules using vector clocks/timestamps to reconcile mismatched entity states.

<a href="https://github.com/viccy2/lightwork-reconciler-task-victor-david">
  <img src="https://img.shields.io/badge/View_Repository-000000?style=for-the-badge&logo=github&logoColor=white" />
</a>

---

#### [Go Task CLI](https://github.com/viccy2/go-task-cli) — Task Management Engine in Go
* **Data Integrity:** Built a zero-dependency CLI tool in Go using atomic file write-and-rename operations (`os.Rename`) to prevent JSON state corruption during process termination.

<a href="https://github.com/viccy2/go-task-cli">
  <img src="https://img.shields.io/badge/View_Repository-000000?style=for-the-badge&logo=github&logoColor=white" />
</a>

---

### 📫 Contact

<a href="https://linkedin.com/in/vaad">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:aremuvictor2016@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
