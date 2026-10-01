### Kirk Diamond — Principal Software Engineer · Go

I build high-throughput Go systems that sit in the hot path: reverse proxies, edge compute, distributed backends, and, increasingly, AI agent tooling.
Principal engineer and former CTO, with 15+ years designing and scaling distributed systems.

---

#### ⚡ Day job

Principal Software Engineer. I architect and lead a Go reverse-proxy platform that:

- handles **billions of HTTP requests per day**
- performs **real-time HTML transformation at sub-30ms latency**
- runs on a network-edge execution layer tuned for concurrency, memory efficiency and streaming
- is supported by resilient Go microservices over gRPC, with failover and graceful degradation
- extends into edge compute on **Cloudflare and Fastly** workers, including some unconventional Go compilation targets

I also lead AI-assisted engineering adoption: structured agent context (AGENTS.md), and LLM integrations with OpenAI and Anthropic in production.

#### 🛰️ Building in the open

- **[TLS Chain Checker](https://kirkdiamond.com/tools/chain)** diagnoses broken certificate chains (missing intermediates, wrong order, expired cross-signs) and tells you exactly how to fix them.
- **[tls-failure-fixtures](https://github.com/KirkDiamond/tls-failure-fixtures)** *(in progress)* provides deliberately broken TLS endpoints plus a CI matrix that captures the verbatim errors from curl, OpenSSL, Java, Python, Node and Go. It is reproducible ground truth for "works in my browser, fails in Java".
- **LCARS** is a self-hosted Go AI agent platform with tool-using agents, a persistent shell and browser, scheduled tasks, and RAG over SQLite with local embeddings.


#### 🧰 Toolbox

**Go** · gRPC/Protobuf · PostgreSQL · Redis · RabbitMQ · Pub/Sub · AWS · GCP · Cloudflare/Fastly workers · Docker · Linux · PHP · Python · LLM APIs

#### 📦 Open source

| Project | What it does |
|---|---|
| [Go-Postgresql-Query-Builder](https://github.com/KirkDiamond/Go-Postgresql-Query-Builder) | Lightweight, composable Postgres query builder for Go |
| [SystemicDB-Core](https://github.com/KirkDiamond/SystemicDB-Core) | Core engine of SystemicDB, embeddable in any Go project |
| [Go-Environment](https://github.com/KirkDiamond/Go-Environment) | Zero-dependency `.env` loader where values stay private to the process; a drop-in for `os.Getenv` |

#### 📡 Find me

[kirkdiamond.com](https://kirkdiamond.com) · [LinkedIn](https://www.linkedin.com/in/[your-handle]) · contact @ kirkdiamond.com

<sub>Mostly Go. Occasionally opinions about certificate chains.</sub>
