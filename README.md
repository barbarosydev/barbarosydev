# Hi, I'm @barbarosydev

Platform, Cloud & AI Systems Engineer focused on **Infrastructure-as-Code**, **Durable Multi-Agent Orchestration**, **LLMOps & Observability**, and **Defense-in-Depth Security**.

---

### Current Focus & Interests

- **Cloud & Infrastructure-as-Code**: Declarative platforms with **Terraform**, **Helm**, **Kubernetes** (`k3d`, AKS, GCP), **CloudNativePG**, and **Conftest (OPA/Rego)** policy-as-code.
- **Durable AI Agent Systems**: Asynchronous, fault-tolerant multi-agent workflows using **Go**, **Temporal**, **Python**, and **PydanticAI** with typed contracts, human-in-the-loop signals, and bounded self-correction.
- **LLMOps, Observability & Evals**: Cross-language **OpenTelemetry** + **Arize Phoenix (OpenInference)** trace waterfalls, **LiteLLM** virtual-key routing & cost telemetry, **Promptfoo** golden/red-team evaluations, and local **Ollama** GPU inference.
- **Security & Automated Quality Gates**: Zero-trust Kubernetes `NetworkPolicy` isolation, `--network=none` ephemeral OCI sandboxing, path-jailed agent tools, **`@axe-core/playwright`** WCAG 2.1 AA verification, and `gitleaks` secret hygiene.

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

- **Collaborating on**: Infrastructure-as-Code, Kubernetes platform engineering, durable AI agent architectures, and automated LLM evaluation harnesses.
- **How to reach me**: via GitHub or email.
