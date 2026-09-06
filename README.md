# Conner Kupferberg

**Systems Decision Architect** · Applied AI Runtimes · Catastrophe Risk & Spatial Systems · Database Internals

I design and build the infrastructure through which complex decisions get made under high uncertainty. My work focuses on deterministic agent runtimes, sandbox isolation, spatial loss accumulation engines, and high-throughput data kernels.

---

### Core Focus Areas

* **Agent Runtimes & Execution Security:** seccomp-bpf system call filtering, POSIX process boundaries, resource budgeting, MCP orchestration, deterministic execution containers.
* **Spatial & Actuarial Modeling:** Sub-kilometer wildfire/flood accumulation grids, $25M+ PML exposure modeling, high-speed spatial indexing, catastrophe underwriting infrastructure.
* **Decision Infrastructure & Data Internals:** Reusable decision engines under uncertainty, event-driven state evaluation, zero-leakage enterprise boundaries, high-performance C++/Python data kernels.

---

### Active Upstream Work & In-Flight Patches

Working on low-level correctness, isolation boundaries, and spatial kernels in the broader ecosystem:

* **[DuckDB Spatial](https://github.com/duckdb/duckdb-spatial)**: Resolving WAL replay non-flat vector appends in RTREE index checkpointing ([#864](https://github.com/duckdb/duckdb-spatial/pull/864) — verified 20/20 cross-platform CI).
* **[Anthropic Sandbox Runtime](https://github.com/anthropics/sandbox-runtime)**: Hardening container write boundaries ([#518](https://github.com/anthropics/sandbox-runtime/pull/518)) and designing eBPF supervisor monitors for read violation auditing ([#511](https://github.com/anthropics/sandbox-runtime/issues/511)).
* **[OasisLMF](https://github.com/OasisLMF/OasisLMF)**: Automatic CRS reprojection for multi-peril risk accumulation in RTREE spatial joins ([#2138](https://github.com/OasisLMF/OasisLMF/pull/2138)).
* **[Model Context Protocol](https://github.com/modelcontextprotocol/python-sdk)**: POSIX process isolation and resource limits for host-supervised stdio servers ([#3457](https://github.com/modelcontextprotocol/python-sdk/issues/3457)).

---

### Links

* **Live Systems Project Board:** [github.com/users/connerkup/projects/1](https://github.com/users/connerkup/projects/1)
* **Portfolio:** [connerkupferberg.com](https://connerkupferberg.com)
* **GitHub:** [@connerkup](https://github.com/connerkup)
* **LinkedIn:** [linkedin.com/in/connerkupferberg](https://www.linkedin.com/in/connerkupferberg/)
