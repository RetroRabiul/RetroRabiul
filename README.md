<!-- MODULE: BANNER_START -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
    <img alt="Rabiul Hasan — Distributed Systems & Full-Stack Software Engineer" src="./assets/banner-dark.svg" width="100%" />
  </picture>
</div>

<br />

<p align="center">
  Architecting resilient edge runtimes, low-latency developer tooling, and accessible web interfaces.
</p>

<p align="center">
  [caffebd.org](https://caffebd.org) &nbsp;·&nbsp; [rabiul@caffebd.org](mailto:rabiul@caffebd.org) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/rabiul-hasan) &nbsp;·&nbsp; [X / @rabiul_codes](https://x.com/rabiul_codes)
</p>
<!-- MODULE: BANNER_END -->

---

<!-- MODULE: WORKING_STATUS_START -->
### Current Focus & Recent Activity

- **Active Build:** Building EdgeMesh KV — Geo-replicated state synchronization over WebAssembly — Designing deterministic conflict-free replicated data types (CRDTs) with sub-15ms regional read latency.
- **Researching:** Exploring eBPF kernel observability and zero-copy Rust serialization pipelines
- **Collaboration:** Open to reviewing RFCs in cloud-native telemetry, TypeScript compilers, and developer UX _(Available for select advisory & open-source collaboration)_

| Ref | Repository & Contribution Summary | Timeline |
| :--- | :--- | ---: |
| `#142` | **[rabiul-dev/edgemesh-kv](https://github.com/rabiul-dev/edgemesh-kv)** — Implement Raft snapshot compaction with streaming LZ4 frames | 2 days ago |
| `v2.4.0` | **[rabiul-dev/prism-ast](https://github.com/rabiul-dev/prism-ast)** — Release v2.4.0 — Incremental TypeScript diagnostic worker pool | 5 days ago |
| `8f3c91a` | **[open-telemetry/opentelemetry-rust](https://github.com/open-telemetry/opentelemetry-rust)** — Reduce heap allocations in batch span processor export loop | 1 week ago |
| `#89` | **[rabiul-dev/pulse-sql-studio](https://github.com/rabiul-dev/pulse-sql-studio)** — Add keyboard-first query plan flamegraph inspector for PostgreSQL 17 | 2 weeks ago |
<!-- MODULE: WORKING_STATUS_END -->

---

<!-- MODULE: SKILLS_START -->
### Technical Stack

**Core Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-5.7-161B22?style=flat-square&logo=typescript&logoColor=3178C6&labelColor=0D1117) ![Rust](https://img.shields.io/badge/Rust-2024-161B22?style=flat-square&logo=rust&logoColor=DEA584&labelColor=0D1117) ![Go](https://img.shields.io/badge/Go-1.23-161B22?style=flat-square&logo=go&logoColor=00ADD8&labelColor=0D1117) ![Python](https://img.shields.io/badge/Python-3.12-161B22?style=flat-square&logo=python&logoColor=3776AB&labelColor=0D1117) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-161B22?style=flat-square&logo=postgresql&logoColor=4169E1&labelColor=0D1117)

**Frontend & Interface Engineering**

![React](https://img.shields.io/badge/React-19-161B22?style=flat-square&logo=react&logoColor=61DAFB&labelColor=0D1117) ![Next.js](https://img.shields.io/badge/Next.js-15-161B22?style=flat-square&logo=nextdotjs&logoColor=F0F6FC&labelColor=0D1117) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-v4-161B22?style=flat-square&logo=tailwindcss&logoColor=06B6D4&labelColor=0D1117) ![WebAssembly](https://img.shields.io/badge/WebAssembly-WASI-161B22?style=flat-square&logo=webassembly&logoColor=654FF0&labelColor=0D1117)

**Systems, Cloud & Observability**

![Docker](https://img.shields.io/badge/Docker-OCI-161B22?style=flat-square&logo=docker&logoColor=2496ED&labelColor=0D1117) ![Kubernetes](https://img.shields.io/badge/Kubernetes-EKS-161B22?style=flat-square&logo=kubernetes&logoColor=326CE5&labelColor=0D1117) ![Redis](https://img.shields.io/badge/Redis-Cluster-161B22?style=flat-square&logo=redis&logoColor=FF4438&labelColor=0D1117) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-Traces-161B22?style=flat-square&logo=opentelemetry&logoColor=F5A800&labelColor=0D1117) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-161B22?style=flat-square&logo=githubactions&logoColor=2088FF&labelColor=0D1117)
<!-- MODULE: SKILLS_END -->

---

<!-- MODULE: PROJECTS_START -->
### Selected Projects

#### [EdgeMesh KV](https://github.com/rabiul-dev/edgemesh-kv)
> **Distributed embedded key-value store with Raft consensus & CRDT replication**

Zero-dependency Rust storage engine compiled to native Linux binaries and WASI modules. Sustains 185k ops/sec with automated snapshot compaction and Prometheus metrics.

`Rust` &nbsp;·&nbsp; ★ **1,240** &nbsp;·&nbsp; ⑂ **118** &nbsp;·&nbsp; Updated Oct 2026 · [Live Demo](https://edgemesh.caffebd.org)

---

#### [Prism AST Diagnostics](https://github.com/rabiul-dev/prism-ast)
> **Incremental static analysis & architectural boundary linter for TypeScript monorepos**

Validates module dependency graphs across 500k+ LOC workspaces in under 420ms using shared-memory worker pools and cached syntax trees.

`TypeScript` &nbsp;·&nbsp; ★ **876** &nbsp;·&nbsp; ⑂ **64** &nbsp;·&nbsp; Updated Oct 2026 · [Live Demo](https://prism-ast.caffebd.org)

---

#### [Pulse SQL Studio](https://github.com/rabiul-dev/pulse-sql-studio)
> **Minimalist browser-based EXPLAIN ANALYZE profiler and schema diff inspector**

Turns raw PostgreSQL execution plans into interactive timing breakdowns, index bottleneck warnings, and deterministic migration scripts.

`TypeScript` &nbsp;·&nbsp; ★ **615** &nbsp;·&nbsp; ⑂ **49** &nbsp;·&nbsp; Updated Sep 2026

---

#### [ Conduit HTTP Proxy](https://github.com/rabiul-dev/conduit-proxy)
> **Lightweight Go reverse proxy with adaptive circuit breaking and OTLP tracing**

Config-driven ingress router supporting hot-reloaded TLS certificates, token-bucket rate limiting, and structured JSON audit streams.

`Go` &nbsp;·&nbsp; ★ **432** &nbsp;·&nbsp; ⑂ **37** &nbsp;·&nbsp; Updated Aug 2026
<!-- MODULE: PROJECTS_END -->

---

<!-- MODULE: STATS_START -->
### Coding Activity & Top Languages

<div align="center">
  <a href="https://github.com/rabiul-dev">
    <img
      height="165"
      alt="rabiul-dev GitHub Stats"
      src="https://github-readme-stats.vercel.app/api?username=rabiul-dev&show_icons=true&hide_border=true&bg_color=0D1117&title_color=F0F6FC&text_color=9198A1&icon_color=3B82F6"
    />
  </a>
  <a href="https://github.com/rabiul-dev">
    <img
      height="165"
      alt="rabiul-dev Top Languages"
      src="https://github-readme-stats.vercel.app/api/top-langs/?username=rabiul-dev&layout=compact&langs_count=6&hide_border=true&bg_color=0D1117&title_color=F0F6FC&text_color=9198A1"
    />
  </a>
</div>

<br />

| Language | Proportional Share | Allocation | Footprint |
| :--- | :--- | ---: | ---: |
| **TypeScript** | `█████████░░░░░░░░░░░` | `42.6%` | 21 repos · 640k LOC |
| **Rust** | `█████░░░░░░░░░░░░░░░` | `27.4%` | 11 repos · 290k LOC |
| **Go** | `████░░░░░░░░░░░░░░░░` | `18.2%` | 9 repos · 185k LOC |
| **Python** | `██░░░░░░░░░░░░░░░░░░` | `7.8%` | 5 repos · 74k LOC |
| **SQL & Shell** | `█░░░░░░░░░░░░░░░░░░░` | `4.0%` | 2 repos · 32k LOC |

<sub>Annual Snapshot: <strong>1,482</strong> commits · <strong>3,163</strong> stars earned · <strong>214</strong> PRs merged · <strong>48</strong> public repositories</sub>
<!-- MODULE: STATS_END -->
