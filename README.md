<p align="center">
  <img src="profile-assets/selected-works.png" width="100%" alt="Akshat Singh Kushwaha, selected works: qenlo, hybridmind, luna, and bits&bytes™" />
</p>

<br />

### 01 · [qenlo](https://github.com/a3ro-dev/qenlo)

<sub>RUST · EMBEDDED VECTOR STORAGE · CPU / WGPU / HNSW</sub>

the vector database i wanted for local agents: embedded, filter-aware, snapshot-safe, and honest about what happened during search.

`canonical rows → compiled filter plan → exact CPU / exact WGPU / USearch HNSW`

every query is pinned to one committed generation. its report names the backend, algorithm, filter path, preparation cost, allocation, and any fallback. the Rust core has Python, TypeScript, Go, Kotlin, and Swift bindings; Python also gets a snapshot-bound Torch index for CPU, CUDA, or MPS.

[source](https://github.com/a3ro-dev/qenlo) · [paper](https://github.com/a3ro-dev/qenlo/blob/main/QENLO-RESEARCH-PAPER.pdf) · [crates.io](https://crates.io/crates/qenlo) · [PyPI](https://pypi.org/project/qenlo/)

---

### 02 · [hybridmind](https://github.com/a3ro-dev/hybridmind)

<sub>PYTHON · DENSE + SPARSE + GRAPH RETRIEVAL</sub>

retrieval where the ranking is inspectable, not magic. dense, sparse, and graph paths can run together or alone, then meet in weighted reciprocal rank fusion.

`query → routed search modes → weighted RRF → optional rerank → trace`

the trace says which stages ran, what they produced, which controls resolved, and which config shaped the answer. bitemporal SQLite/WAL stays authoritative; portable `.mind.zip` snapshots carry checksummed projections and rebuild runtime indexes without executable pickle payloads.

[source](https://github.com/a3ro-dev/hybridmind)

---

### 03 · [luna](https://github.com/a3ro-dev/luna)

<sub>TYPESCRIPT · ADAPTIVE CYCLE PREDICTION · TEN BOUNDED TOOLS</sub>

a cycle companion with its prediction engine in code, not vibes from the model.

`conversation → typed tools → condition-aware forecast → OpenUI result`

the engine blends condition-specific priors with personal history, adapts smoothing from recent residuals, rejects implausible intervals, and reports jackknife uncertainty when the data can support it. cycle records stay in Postgres; Supermemory only holds personal context outside those records.

[source](https://github.com/a3ro-dev/luna)

---

### 04 · [bits&bytes™](https://github.com/gobitsnbytes/bitsnbytes)

<sub>TYPESCRIPT · BUILDER NETWORK · GROUNDED SITE ASSISTANT</sub>

the software behind our student builder network: events, applications, local forks, live services, and team scheduling.

`current page + Upstash corpus → grounded answer → navigation / form / booking`

the assistant has to retrieve before it states facts. from there it can search the site, highlight text on the page, match team expertise, submit enquiries, and schedule or manage calls through the separate Motherboard API.

[source](https://github.com/gobitsnbytes/bitsnbytes)

<br />

<p align="center"><sub>four repositories. no résumé.</sub></p>
