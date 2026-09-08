<p align="center">
  <img src="profile-assets/selected-works.svg" width="100%" alt="Akshat Singh Kushwaha, selected systems and software projects" />
</p>

<br />

<h2>01 / <a href="https://github.com/a3ro-dev/qenlo">qenlo</a></h2>

<sub>EMBEDDED VECTOR STORAGE · RUST</sub>

observable, embedded vector search over durable local collections. every query runs against one committed generation, so concurrent writes appear whole or not at all.

`canonical rows → compiled filter plan → exact CPU / exact WGPU / USearch HNSW`

the search report names the backend, algorithm, filter execution, preparation cost, allocation, and any fallback. the Rust core also feeds Python, TypeScript, Go, Kotlin, and Swift bindings; Python has a separate snapshot-bound Torch index for CPU, CUDA, or MPS.

[source](https://github.com/a3ro-dev/qenlo) · [research paper](https://github.com/a3ro-dev/qenlo/blob/main/QENLO-RESEARCH-PAPER.pdf) · [crates.io](https://crates.io/crates/qenlo) · [PyPI](https://pypi.org/project/qenlo/)

<p align="center">· &nbsp; · &nbsp; ·</p>

<h2>02 / <a href="https://github.com/a3ro-dev/hybridmind">hybridmind</a></h2>

<sub>HYBRID RETRIEVAL · PYTHON</sub>

an auditable retrieval service for agent memory. dense, sparse, and graph paths can run together or in isolation, with query-type routing and explicit temporal validity.

`query → routed search modes → weighted RRF → optional rerank → trace`

each response can expose which stages ran, how many candidates they produced, the resolved controls, and a hash of that configuration. bitemporal SQLite/WAL remains authoritative; `.mind.zip` snapshots carry checksummed JSON/JSONL projections and rebuild runtime indexes without loading executable pickle payloads.

[source](https://github.com/a3ro-dev/hybridmind)

<p align="center">· &nbsp; · &nbsp; ·</p>

<h2>03 / <a href="https://github.com/a3ro-dev/luna">luna</a></h2>

<sub>ADAPTIVE CYCLE PREDICTION · TYPESCRIPT</sub>

a cycle companion whose chat is wired directly into the prediction and persistence layer through ten bounded tools.

`conversation → typed tools → condition-aware forecast → OpenUI result`

the engine blends condition-specific priors with personal history, adapts its smoothing factor from recent residuals, gates implausible intervals, derives phase lengths under a physiological constraint, and reports jackknife uncertainty when there is enough data. cycle records stay in Postgres; Supermemory is limited to personal context outside those records.

[source](https://github.com/a3ro-dev/luna)

<p align="center">· &nbsp; · &nbsp; ·</p>

<h2>04 / <a href="https://github.com/gobitsnbytes/bitsnbytes">bits&amp;bytes</a></h2>

<sub>STUDENT BUILDER NETWORK · TYPESCRIPT</sub>

the public and operational web surface for a student-run builder network: events, applications, local forks, live services, and team scheduling.

`current page + Upstash corpus → grounded answer → navigation / form / booking`

the assistant is scoped to the organisation and required to retrieve before stating facts. its tools can search the site corpus, highlight live page text, match team expertise, submit enquiries, and schedule or manage calls through the separate Motherboard API.

[source](https://github.com/gobitsnbytes/bitsnbytes)

<br />

<p align="center"><sub>SELECTED WORKS · 04 REPOSITORIES</sub></p>
