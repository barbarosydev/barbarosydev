# Hi, I'm Barbaros Yildiz (`@barbarosydev`)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-barbaros--yildiz-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/barbaros-yildiz/)

**Senior Data & Platform Engineer** based in Berlin, Germany — with 12+ years building **cloud-scale data platforms**, **Infrastructure-as-Code on Kubernetes**, **security-by-design systems**, and **durable AI agent architectures**.

Currently **Senior Data Engineer (ADAS Data Ingestion, Validation & Storage)** at **CARIAD (Volkswagen Group)**, making **Azure, AKS, Databricks, Airflow, and Terraform** easy and reliable to build on for automated-driving engineering teams.

---

### Background & Core Competencies

- **Data Platforms & Cloud Architecture (Azure, GCP, AWS)**: Designed and operated self-service ingestion, validation, and analytics platforms across **Azure (AKS, Databricks, Airflow)**, **GCP (BigQuery, Apache Beam / Dataflow, Cloud Composer)**, and **AWS (Kafka, Hadoop, Elasticsearch)**.
- **Infrastructure-as-Code & Platform Engineering**: Delivered production **Kubernetes / AKS** platforms end-to-end as IaC (including CARIAD + Bosch's **Mender OTA** platform and CARIAD's **Big Loop** on-the-road data-collection backend) with **Terraform** and **Helm**.
- **Security & Compliance by Design**: Taken enterprise data and OTA platforms through **IT-Sec approval** and **NIST 800-53** controls from the ground up — zero-trust networking, least-privilege IAM/RBAC, secret hygiene, and policy-as-code.
- **From Zero to Scale**: Built **Ultimate's** GCP data platform from scratch as its first data engineer (growing the team from 1 to 4 prior to acquisition by Zendesk, including the data backend for an AI agent performance dashboard), following earlier cloud SIEM (`Comodo NxSIEM`) and high-throughput log pipelines (`LabirentLab`).
- **Current Exploration — Production-Patterned AI Systems**: Applying data-platform rigor (durability, observability, evaluation harnesses, sandboxing, and IaC) to multi-agent software engineering in Go, Temporal, and Python.

---

### Featured Project: Local-First AI Software Factory

A production-patterned 3-repository multi-agent platform running end-to-end on Apple Silicon with zero external LLM API keys:

| Repository | Role | Key Technologies |
| --- | --- | --- |
| **[`ai-factory`](https://github.com/barbarosydev/ai-factory)** | Durable control plane, PydanticAI agent worker, container `SandboxRunner`, Promptfoo evals, and GitHub App orchestrator | Go 1.26, Temporal 1.32, PydanticAI, OpenTelemetry, Promptfoo, Docker |
| **[`ai-factory-infra`](https://github.com/barbarosydev/ai-factory-infra)** | 100% Terraform & Helm Kubernetes platform with write-only secrets, 9 zero-trust `NetworkPolicy` rules, and 77 automated `task doctor` checks | Terraform, Helm, k3d, CloudNativePG PostgreSQL 18, LiteLLM, Arize Phoenix, Ollama, Conftest |
| **[`ai-factory-websites`](https://github.com/barbarosydev/ai-factory-websites)** | Target static website monorepo autonomously built, verified across 9 Playwright + WCAG 2.1 AA gates, and shipped via PRs | HTML5, CSS, Playwright, `@axe-core/playwright`, GitHub Actions |

#### Live Observability & Durable Execution

| End-to-End Trace Waterfall (`Arize Phoenix + OpenInference`) | Activity Timeline (`Temporal Web UI`) |
| --- | --- |
| ![Arize Phoenix trace waterfall](https://raw.githubusercontent.com/barbarosydev/ai-factory/main/docs/images/phoenix-trace-waterfall.png) | ![Temporal workflow Gantt timeline](https://raw.githubusercontent.com/barbarosydev/ai-factory/main/docs/images/temporal-workflow-timeline.png) |

---

- **Core Stack**: `Terraform` · `Kubernetes (AKS / k3d)` · `Azure` · `GCP` · `Databricks` · `Apache Airflow` · `Apache Beam` · `Kafka` · `PostgreSQL` · `Go` · `Python` · `Temporal` · `OpenTelemetry` · `Arize Phoenix` · `LiteLLM` · `Promptfoo` · `Playwright`
- **How to reach me**: [LinkedIn](https://www.linkedin.com/in/barbaros-yildiz/) or via GitHub.
