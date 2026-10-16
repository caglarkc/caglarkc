<div align="center">

# Ali Çağlar Koçer

**Computer Engineer · Backend & AI Systems · Founder of [ACK Techs](https://ack-techs.com)**

Istanbul, Turkey · Open to new opportunities

[![Website](https://img.shields.io/badge/Website-alicaglarkocer.com-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://alicaglarkocer.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ali--caglar--kocer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-caglar-kocer/)
[![ACK Techs](https://img.shields.io/badge/ACK%20Techs-ack--techs.com-111827?style=for-the-badge&logo=rocket&logoColor=white)](https://ack-techs.com)
[![Email](https://img.shields.io/badge/Email-alicaglarkocer%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alicaglarkocer@gmail.com)

</div>

---

## About

I'm a computer engineer who started in software testing, optimization and observability, and now builds production backend systems and **AI-powered products**. Over the last two years I've shipped software in **Node.js, Go and Python**, and my focus has moved from classic backend work toward **LLM-based, agentic systems**: tool use, MCP, RAG and multi-agent orchestration.

I like systems that are measurable, explainable and safe by default: deterministic decisions where it matters, LLMs where they add real value.

I'm the founder of **[ACK Techs](https://www.linkedin.com/company/ack-techs/)**, an independent product and technology team building software, AI and design products ("Engineering Ideas Into Reality").

## What I'm Working On

| Project | What it is | Status |
|---|---|---|
| **[WatchTower](https://github.com/caglarkc/watchtower-demo)** | CLI-first UEBA platform for closed corporate networks. Learns user/entity baselines, scores anomalies with deterministic engines, and produces explainable alerts. LLMs are used only for explanation, never for final decisions. (Python, LangGraph) | Active development |
| **[Sentinel](https://github.com/ACK-Techs/sentinel)** | Agentic observability CLI plus a read-only gateway over Prometheus, Loki and Tempo, so metrics, logs and traces are inspected from one terminal workflow. (Python, FastAPI, Kubernetes, OpenTelemetry) | Prototype |
| **[Immense](https://github.com/caglarkc/immense)** | Fitness platform connecting athletes and coaches: plans, progress tracking and communication in one place. 17 microservices plus a mobile app. | Live |
| **[Argus](https://github.com/caglarkc/argus)** | Extensible Python runtime for LLM coding agents: provider adapters (OpenAI-compatible, Anthropic), tool registry, permission modes, hooks, skills, trajectory recording and BFCL / SWE-bench style evaluation. | Open source |
| **[NookSpace](https://github.com/caglarkc/nookspace)** | Desktop AI agent workspace (Electron, React, TypeScript) with scoped file/command tools, MCP connectors, skills and session traces. | Open source |
| **[EstatePilot](https://github.com/caglarkc/estate-agent)** | Human-in-the-loop AI assistant for estate agents: intent routing, tool chain, reply drafting with approval gate and CRM follow-ups. (React, TypeScript, multi-provider LLM client) | Prototype |

### Featured technical work

**[Agent Browser](https://github.com/caglarkc/agent-browser)** — an experimental browser execution layer for AI agents. The page is observed through DOM controls, [JEV](https://typesafe.ai/) chooses the next typed action, [Lightpanda](https://github.com/lightpanda-io/browser) executes it, and the real outcome is verified independently. Chromium DOM and screenshot/OCR paths serve as baselines.

In the published live benchmark (matched subset: the 9 tasks all three paths completed, cold browser starts), the Lightpanda DOM path was **73% faster** and used **84% less local memory** than the Chromium screenshot/OCR path. Raw results, measurement protocol and caveats are in the repo. This is measured prototype data, not a general claim about all browsers.

| Path (matched live tasks) | Median task time | Median local peak memory |
| :--- | ---: | ---: |
| Chromium + screenshot/OCR + JEV | 11.07 s | 538.69 MiB |
| Chromium DOM + JEV | 6.97 s | 483.09 MiB |
| **Lightpanda DOM + JEV** | **2.96 s** | **83.79 MiB** |

**[Architecture Catalog](https://github.com/caglarkc/architecture-catalog-distribution)** — a versioned catalog and CLI (`archcat`) for scaffolding architecture starters: FastAPI, NestJS, LangGraph agent API, Typer CLI, React + FastAPI full-stack and FastAPI microservices (Compose). Templates are distributed as independent ZIPs, fetched on demand and verified by SHA-256. v0.1.0 is an untested initial release (build, types, schemas, manifests and packaging checked); npm publication is pending.

More from ACK Techs: **DemandRift** (market-research agent), **Steward**, **Robotutor / OLMS**, **Archon** and **FIRST**, a program that helps students move from first open-source contributions to real projects. See [ack-techs.com](https://ack-techs.com).

## Tech Stack

**Backend & Architecture**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/.NET%20/%20C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC%20/%20Protobuf-244C5A?style=flat-square&logo=grpc&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**AI & Agentic Systems**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Tool%20Use-6E56CF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Vector%20Search-0EA5E9?style=flat-square)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Cloud, DevOps & Observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-466BB0?style=flat-square&logo=istio&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS%20Serverless-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

## Focus Areas

- **Backend & distributed systems**: microservices, REST/gRPC, event-driven design with RabbitMQ and Redis Streams, JWT-based auth.
- **Agentic AI**: LLM integration, tool use and MCP, LangGraph/LangChain workflows, RAG, human-in-the-loop approval gates.
- **Observability & reliability**: metrics, logs and traces with Prometheus, Grafana, Loki, Tempo and OpenTelemetry; load and chaos testing.
- **Cloud-native delivery**: Docker, Kubernetes, Istio, Terraform and AWS serverless.

## Selected Repositories

- [`agent-browser`](https://github.com/caglarkc/agent-browser): browser layer for AI agents with measured live benchmarks
- [`architecture-catalog-distribution`](https://github.com/caglarkc/architecture-catalog-distribution): versioned architecture starter catalog and `archcat` CLI
- [`watchtower-demo`](https://github.com/caglarkc/watchtower-demo): explainable UEBA for closed networks
- [`sentinel`](https://github.com/ACK-Techs/sentinel): agentic observability CLI and read-only gateway
- [`argus`](https://github.com/caglarkc/argus): agent runtime and evaluation framework
- [`nookspace`](https://github.com/caglarkc/nookspace): desktop AI agent workspace
- [`estate-agent`](https://github.com/caglarkc/estate-agent): AI assistant for estate agents
- [`CoffyPlatformBackendProject`](https://github.com/caglarkc/CoffyPlatformBackendProject): multi-branch coffee chain order platform with microservices, Redis Pub/Sub, RabbitMQ, Stripe/İyzico and Traefik

## Let's Connect

I'm open to backend, AI/agentic systems and platform engineering roles, and to collaborations on interesting products.

- Website: [alicaglarkocer.com](https://alicaglarkocer.com)
- LinkedIn: [ali-caglar-kocer](https://www.linkedin.com/in/ali-caglar-kocer/)
- Company: [ACK Techs](https://ack-techs.com) · [LinkedIn page](https://www.linkedin.com/company/ack-techs/)
- Email: [alicaglarkocer@gmail.com](mailto:alicaglarkocer@gmail.com)

<div align="center">

<sub>Engineering ideas into reality.</sub>

</div>
