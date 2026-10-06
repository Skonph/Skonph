# Hi, I'm Skon 👨‍💻
### Senior AI Automation & Systems Engineer | Autonomous Multi-Agent Systems Architect

I design and deploy resilient, high-availability **Autonomous Multi-Agent AI Systems**, **Deterministic LLM Safety Guardrails**, and **Production Cloud Infrastructure**.

---

### 🧠 Core Competencies & Specializations

* **Agentic AI Architecture:** Multi-agent supervisor-worker coordination, context engineering, tool-calling interfaces, and structured Pydantic schema validation.
* **Deterministic Guardrails on Non-Deterministic AI:** Multi-stage pre-flight combination locks and invariant validation protecting against LLM hallucinations.
* **Autonomous Self-Healing:** Event-driven reconciliation loops, automated drift detection, orphaned process termination, and SQLite WAL IPC buses.
* **Production Reliability & Verification:** Automated 16-tier pre-flight smoke testing suites, end-to-end telemetry, and real-time alerting.
* **Cloud & DevSecOps:** Linux daemon orchestration (systemd/cron), Docker, Kubernetes, Terraform IaC, and CI/CD pipelines.

---

### 🏗️ Featured Architecture: Autonomous Closed-Loop Execution Framework

```mermaid
graph TD
    A[Telemetry / Data Streams] --> B[Supervisor Agent]
    B --> C{Deterministic Pre-Flight Gate}
    C -->|Pass| D[Autonomous Worker Engine]
    C -->|Fail| E[Circuit Breaker / Alert]
    D --> F[Atomic Execution Layer]
    F --> G[Self-Healing Audit Daemon]
    G -->|State Drift Detected| D
    G -->|Healthy| H[WAL State Store & Telemetry]
