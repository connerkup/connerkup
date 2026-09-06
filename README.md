# Conner Kupferberg

**Systems Decision Architect** · Applied AI Runtimes · Catastrophe Risk & Spatial Systems · Database Internals

I design and build the infrastructure through which complex decisions get made under high uncertainty. My work focuses on deterministic agent runtimes, sandbox isolation, spatial loss accumulation engines, and high-throughput data kernels.

---

### Upstream Contributions & Systems Engineering

* **[DuckDB Spatial](https://github.com/duckdb/duckdb-spatial)**: Fixed WAL replay vector flattening in RTREE spatial index appends to eliminate crash loops during database checkpointing ([PR #864](https://github.com/duckdb/duckdb-spatial/pull/864)).
* **[Anthropic Sandbox Runtime](https://github.com/anthropics/sandbox-runtime)**: Hardened container write sandboxing by auto-denying critical hooks and traversal paths ([PR #518](https://github.com/anthropics/sandbox-runtime/pull/518)); designed low-overhead eBPF/seccomp supervisor monitor for read-only violation auditing ([Issue #511](https://github.com/anthropics/sandbox-runtime/issues/511)).
* **[OasisLMF](https://github.com/OasisLMF/OasisLMF)**: Implemented automatic CRS reprojection for multi-peril catastrophe loss accumulation in RTREE spatial joins ([PR #2138](https://github.com/OasisLMF/OasisLMF/pull/2138)).
* **[Model Context Protocol](https://github.com/modelcontextprotocol/python-sdk)**: Designed POSIX `preexec_fn` and `process_group` process isolation hooks for host agent supervision, resource budgeting, and orphan process mitigation ([#3457](https://github.com/modelcontextprotocol/python-sdk/issues/3457) / [PR #3461](https://github.com/modelcontextprotocol/python-sdk/pull/3461)).

---

### Core Focus Areas

* **Agent Runtimes & Execution Security:** seccomp-bpf system call filtering, POSIX process boundaries, memory/FD quotas, MCP tool orchestration, deterministic execution containers.
* **Spatial & Actuarial Modeling:** Sub-kilometer wildfire/flood accumulation grids, $25M+ PML exposure modeling, high-speed spatial indexing, catastrophe underwriting infrastructure.
* **Decision Infrastructure & Data Internals:** Reusable decision engines under uncertainty, event-driven state evaluation, zero-leakage enterprise boundaries, high-performance C++/Python data kernels.

---

### Links

* **Portfolio:** [connerkupferberg.com](https://connerkupferberg.com)
* **GitHub:** [@connerkup](https://github.com/connerkup)
* **LinkedIn:** [linkedin.com/in/connerkupferberg](https://www.linkedin.com/in/connerkupferberg/)
