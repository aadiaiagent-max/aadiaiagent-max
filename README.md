# Aaditya · systems & agents

Building **agent runtimes, RAG systems, and LLM control planes** — infrastructure that ships into real customer environments.

📍 Remote (Canada)

## Agents & LLM systems

| Repo | What it is |
| --- | --- |
| [**agent-runtime**](https://github.com/aadiaiagent-max/agent-runtime) | Tool-calling agent loop, streaming events, memory, typed tools |
| [**rag-platform**](https://github.com/aadiaiagent-max/rag-platform) | Chunk → embed → retrieve → answer + hit-rate evals |
| [**llm-gateway**](https://github.com/aadiaiagent-max/llm-gateway) | Multi-provider routing, rate limits, usage logs, failover |
| [**multi-agent-orchestrator**](https://github.com/aadiaiagent-max/multi-agent-orchestrator) | Supervisor / worker handoffs over an in-process message bus |
| [**agent-evals**](https://github.com/aadiaiagent-max/agent-evals) | Golden-path eval harness: datasets, scorers, pass-rate reports |

## Platform & reliability

| Repo | What it is |
| --- | --- |
| [**distributed-job-queue**](https://github.com/aadiaiagent-max/distributed-job-queue) | Leases, retries, DLQ, idempotency — durable-style in-process queue |
| [**resilience-kit**](https://github.com/aadiaiagent-max/resilience-kit) | Circuit breaker, retry, timeout, bulkhead |
| [**observability-kit**](https://github.com/aadiaiagent-max/observability-kit) | Structured logs, metrics, correlated traces |
| [**platform-control-plane**](https://github.com/aadiaiagent-max/platform-control-plane) | Multi-tenant feature flags, kill switches, rollouts, audit log |
| [**api-contract-kit**](https://github.com/aadiaiagent-max/api-contract-kit) | API contract definitions and breaking-change detection |

## Deploy readiness

| Repo | What it is |
| --- | --- |
| [**fde-integration-kit**](https://github.com/aadiaiagent-max/fde-integration-kit) | Customer-environment validation, smoke tests, fail-closed readiness gate |

## What I care about

- **Agents you can operate** — explicit loops, events, tool policy, measurable evals
- **Platform primitives** — gateways, retrieval, adapters teams can actually adopt
- **Ship-ready shape** — small surface area, strong READMEs, CI that runs offline

## Stack

TypeScript · Node · Vitest · GitHub Actions · LLM APIs / tool-calling · RAG

## Links

- GitHub: [aadiaiagent-max](https://github.com/aadiaiagent-max)

---

*"Make the agent loop boring and the product interesting."*
