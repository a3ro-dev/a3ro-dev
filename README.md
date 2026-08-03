<div align="center">

<h1>Akshat Singh Kushwaha</h1>
<p><strong>CTO @ bits&bytes</strong> · <strong>Systems & AI Engineer</strong> · <strong>Retrieval & Infra</strong></p>

<a href="https://a3ro.dev"><img src="https://img.shields.io/badge/Portfolio-a3ro.dev-0b5fff?style=flat" alt="Portfolio" /></a>
<a href="https://github.com/a3ro-dev"><img src="https://img.shields.io/badge/GitHub-a3ro--dev-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://www.linkedin.com/in/akshat-singh-kushwaha/"><img src="https://img.shields.io/badge/LinkedIn-akshat--singh--kushwaha-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://x.com/a3rodev"><img src="https://img.shields.io/badge/X-@a3rodev-000000?style=flat&logo=x&logoColor=white" alt="X" /></a>
<a href="mailto:akshatsingh14372@outlook.com"><img src="https://img.shields.io/badge/Email-akshatsingh14372@outlook.com-444?style=flat&logo=microsoft-outlook&logoColor=white" alt="Email" /></a>

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&height=2" alt="divider" />
</div>

## <svg viewBox="0 0 24 24" width="16" height="16" role="img" aria-label="overview" style="vertical-align: -2px; margin-right: 6px;"><circle cx="12" cy="12" r="8" fill="none" stroke="#0b5fff" stroke-width="2" stroke-dasharray="50 6"><animateTransform attributeName="transform" type="rotate" from="0 12 12" to="360 12 12" dur="3s" repeatCount="indefinite"/></circle><circle cx="12" cy="12" r="2" fill="#8e4162"><animate attributeName="r" values="2;2.8;2" dur="1.8s" repeatCount="indefinite"/></circle></svg>At a glance

i build retrieval engines, backend infrastructure, and AI tools under tight hardware and latency constraints.

most of my work is about making models and systems useful when memory, money, or compute run out. i care more about TTFT, context window management, zero-downtime persistence, and clean abstractions than benchmark scores.

i default to lower-case, first-principles code, and software that doesn't break when real users touch it.

## <svg viewBox="0 0 24 24" width="16" height="16" role="img" aria-label="quote" style="vertical-align: -2px; margin-right: 6px;"><path d="M7.2 6C4.9 6 3 7.9 3 10.2s1.9 4.2 4.2 4.2c.5 0 .9-.1 1.3-.2-.3 2.1-1.5 3.8-3.5 4.9-.3.1-.4.5-.2.7.1.2.3.3.5.3.1 0 .2 0 .3-.1 2.6-1.4 4.2-3.8 4.4-6.6 0-.1 0-.2 0-.4V6.8c0-.5-.4-.8-.8-.8H7.2zM16.9 6c-2.3 0-4.2 1.9-4.2 4.2s1.9 4.2 4.2 4.2c.5 0 .9-.1 1.3-.2-.3 2.1-1.5 3.8-3.5 4.9-.3.1-.4.5-.2.7.1.2.3.3.5.3.1 0 .2 0 .3-.1 2.6-1.4 4.2-3.8 4.4-6.6 0-.1 0-.2 0-.4V6.8c0-.5-.4-.8-.8-.8h-2z" fill="#6e84d6"><animate attributeName="opacity" values=".85;1;.85" dur="2.5s" repeatCount="indefinite"/></path></svg>Dynamic quote

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&border=true" />
    <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&border=true" alt="Dynamic quote" />
  </picture>
</div>

## <svg viewBox="0 0 24 24" width="16" height="16" aria-label="projects" style="vertical-align: -2px; margin-right: 6px;" fill="none" stroke="#6e84d6" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="7" height="6" rx="1"/><rect x="14" y="4" width="7" height="6" rx="1"/><rect x="3" y="14" width="7" height="6" rx="1"/><rect x="14" y="14" width="7" height="6" rx="1"/><animate attributeName="opacity" values="1;.6;1" dur="2s" repeatCount="indefinite"/></svg>Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/a3ro-dev/hybridmind">HybridMind</a></h3>
      <p>Local-native vector + graph retrieval engine combining FAISS HNSW dense search, NetworkX graph proximity, and bm25s lexical search.</p>
      <ul>
        <li>Reciprocal Rank Fusion (RRF k=60) with <code>mxbai-rerank-large-v2</code> cross-encoder reranking</li>
        <li>TEI 4096-dim embeddings + RunPod vLLM multi-hop query decomposition</li>
        <li>Atomic <code>.mind</code> persistence with SQLite WAL mode & SHA-256 verified manifests</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/a3ro-dev/luna">Luna</a></h3>
      <p>AI-native health & cycle prediction engine with persistent long-term memory and structured UI rendering.</p>
      <ul>
        <li>Adaptive exponential smoothing with ACOG population priors & 2.5σ soft outlier clamp</li>
        <li>Next.js 15 App Router, Neon Postgres + Drizzle ORM, Vercel AI SDK v6</li>
        <li>Supermemory v4 API per-user fact recall + OpenUI DSL dynamic cards</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/gobitsnbytes/motherboard">bits&bytes Motherboard</a></h3>
      <p>Core production platform & monorepo for GOBITSNBYTES FOUNDATION (Section 8 non-profit builder network).</p>
      <ul>
        <li>FastAPI backend + Next.js web monorepo</li>
        <li>Custom IAM engine with async SQLAlchemy policy evaluator & audit logs</li>
        <li>RazorpayX ledger & institutional banking pipeline</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://a3ro.dev">Lexana & Legal AI</a></h3>
      <p>Multi-agent legal intelligence platform built during legal tech research & production sprints.</p>
      <ul>
        <li>Semantic caching cutting LLM API costs by 60%</li>
        <li>Real-time WebSocket document editing & RAG pipeline</li>
        <li>WhatsApp IVRS case onboarding & Gemini voice transcription</li>
      </ul>
    </td>
  </tr>
</table>

## <svg viewBox="0 0 24 24" width="16" height="16" aria-label="current" style="vertical-align: -2px; margin-right: 6px;" fill="none" stroke="#0b5fff" stroke-width="1.6"><path d="M12 2v4M12 18v4M4.93 4.93l2.83 2.83M16.24 16.24l2.83 2.83M2 12h4M18 12h4M4.93 19.07l2.83-2.83M16.24 7.76l2.83-2.83"/><circle cx="12" cy="12" r="3"/></svg>Currently

**bits&bytes™ (GOBITSNBYTES FOUNDATION)** — Chief Technology Officer & Tech Lead. Built the technical stack from scratch; running hackathons, dev squads, and product launches for student builders nationwide.


Previously **Research Engineer** at **jhana** (Nov 2025 – Jan 2026): context-window manager for long legal dictations, multimodal consultation analysis, and real-time WhatsApp case intake handling 1.6M+ quarterly requests.

## <svg viewBox="0 0 24 24" width="16" height="16" aria-label="stack" style="vertical-align: -2px; margin-right: 6px;" fill="none" stroke="#8e4162" stroke-width="1.6"><ellipse cx="12" cy="6" rx="7" ry="3"/><path d="M5 6v8c0 1.7 3.1 3 7 3s7-1.3 7-3V6"/><ellipse cx="12" cy="10" rx="7" ry="3" opacity=".35"/><ellipse cx="12" cy="14" rx="7" ry="3" opacity=".2"><animate attributeName="opacity" values=".2;.5;.2" dur="2s" repeatCount="indefinite"/></ellipse></svg>Tech stack

**Languages**: Python, TypeScript, SQL, Bash, Dart  
**Backend & APIs**: FastAPI, Next.js (App Router), Node.js, Express, REST & WebSockets, Pydantic v2  
**Retrieval & LLMOps**: FAISS, NetworkX, BM25, TEI, vLLM, Cross-Encoders, Vercel AI SDK, Docker  
**Databases & Storage**: PostgreSQL (Neon), SQLite (WAL), Redis, Drizzle ORM, Prisma  
**Cloud & Operations**: AWS (EC2/S3), RunPod, Vercel, pnpm, CI/CD, Linux, Git  
**Hardware & Edge**: Raspberry Pi, ESP32, Pygame/NumPy audio pipelines

## <svg viewBox="0 0 24 24" width="16" height="16" aria-label="interests" style="vertical-align: -2px; margin-right: 6px;" fill="none" stroke="#6e84d6" stroke-width="1.6"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 1 3-3h7z"/></svg>Current interests

- tri-signal retrieval fusion (combining vector HNSW, graph topologies, and BM25 lexical scores)
- adaptive time-series prediction engines on noisy user data with cold-start priors
- self-hosted LLMOps, reducing TTFT and inference costs without accuracy loss
- zero-downtime, local-first database persistence (`.mind` bundles & SQLite WAL)
- student builder networks & un-gatekept tech education

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=a3ro-dev&show_icons=true&theme=tokyonight&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=a3ro-dev&show_icons=true&theme=default&hide_border=true" />
    <img height="160" src="https://github-readme-stats.vercel.app/api?username=a3ro-dev&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats" />
  </picture>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=a3ro-dev&layout=compact&theme=tokyonight&hide_border=true" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=a3ro-dev&layout=compact&theme=default&hide_border=true" />
    <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=a3ro-dev&layout=compact&theme=default&hide_border=true" alt="Top Languages" />
  </picture>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer" alt="footer" />
</div>
