# Watchlist

Repos and projects I want to check out.

## Considering


### Agent infrastructure and orchestration

- [paperclip](https://github.com/paperclipai/paperclip) — Multi-agent company orchestration layer with budgets, governance, and persistent tasking; interesting operating system thesis for autonomous teams. 🟩 [OSS] 🟦 [Popular]
- [Google Workspace CLI](https://github.com/googleworkspace/cli) — Dynamic CLI generated from Google Discovery docs with strong agent ergonomics and skills packaging. 🟩 [OSS] 🟦 [Popular]
- [pinchtab](https://github.com/pinchtab/pinchtab) — Lightweight browser-control server for agents with local-first defaults and multi-instance orchestration. 🟩 [OSS] 🟦 [Popular]
- [hermes-agent](https://github.com/NousResearch/hermes-agent) — Self-improving agent runtime with persistent memory, skill creation loop, messaging gateway, and multi-backend execution (local, Docker, SSH, Modal/Daytona); serious operator surface, though breadth and autonomy claims likely need disciplined safety policy and config hygiene in production. 🟩 [OSS] 🟦 [Popular]
- [molmoweb](https://github.com/allenai/molmoweb) — Open multimodal web agent stack from Ai2 with browser control, inference client, and reproducible benchmark path across local/cloud environments; strong research-to-ops bridge, though real-world reliability and eval depth still look early in the public roadmap. 🟩 [OSS]
- [copilot-sdk](https://github.com/github/copilot-sdk) — Multi-language SDK layer over Copilot CLI’s agent runtime with JSON-RPC transport, BYOK options, and hooks/skills integration; fast way to embed agent workflows, though dependency on Copilot CLI server mode adds operational coupling. 🟩 [OSS] 🟦 [Popular]
- [expect](https://github.com/millionco/expect) — Diff-aware browser testing CLI that generates AI test plans and executes them in live browser sessions with replay support; strong fast-feedback loop for web changes, but the FSL-1.1-MIT licence and agent/runtime coupling are real constraints. 🟦 [Popular]

### Memory, retrieval, and research

- [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) — End-to-end research pipeline from idea to paper with staged experiments and citation checks; useful benchmark for autonomous research claims. 🟩 [OSS] 🟦 [Popular]
- [autoresearch](https://github.com/karpathy/autoresearch) — Tight single-GPU loop where agents iterate on one training file under fixed time budgets; great for controlled auto-optimisation experiments. 🟥 [No licence] 🟦 [Popular]
- [feynman](https://github.com/getcompanion-ai/feynman) — Open-source AI research CLI with deep-research, lit review, audit, and replication workflows plus citation verification and optional local/cloud GPU execution; strong operator surface, though quality still rides on source coverage and toolchain setup discipline. 🟩 [OSS] 🟦 [Popular]
- [Prismer](https://github.com/Prismer-AI/Prismer) — End-to-end open research workspace combining paper reading, citation checks, LaTeX authoring, notebooks, and multi-agent orchestration with self-hosted Docker paths; ambitious scope, though the monorepo split and mixed per-directory licences add integration complexity. 🟩 [OSS] 🟦 [Popular]
- [youtu-rag](https://github.com/TencentCloudADP/youtu-rag) — Agentic RAG system centred on local deployment, adaptive retrieval, and dual-layer memory with file/SQL/Excel workflows in one stack; broad capability surface is attractive, though setup complexity and many optional model services can raise operational overhead quickly. 🟩 [OSS]
- [Memoria](https://github.com/matrixorigin/Memoria) — Persistent memory layer for agents with semantic retrieval plus snapshot, branch, merge, and rollback semantics on MatrixOne; strong auditability angle, though production hardening claims still need field validation. 🟩 [OSS]

### Skills, prompts, and workflow packs

- [CLI-Anything](https://github.com/HKUDS/CLI-Anything) — Generates agent-facing CLIs for existing software with broad demo coverage; ambitious scope, but licence is not currently declared in repo metadata. 🟥 [No licence] 🟦 [Popular]
- [financial-services-plugins](https://github.com/anthropics/financial-services-plugins) — Domain plugins for IB/ER/PE/WM workflows with MCP integrations and command packs for Claude. 🟩 [OSS] 🟦 [Popular]
- [gstack](https://github.com/garrytan/gstack) — Opinionated skill stack for Claude/Codex workflows with explicit plan-review-QA-ship gates; strong process packaging, but very tied to one operator style. 🟩 [OSS] 🟦 [Popular]
- [skills](https://github.com/slavingia/skills) — Claude Code skill pack based on The Minimalist Entrepreneur, mapping idea validation through first customers, pricing, and sustainable growth into explicit slash-command workflows; crisp operator framing, but no clear licence metadata in the repo. 🟥 [No licence] 🟦 [Popular]
- [everything-claude-code](https://github.com/affaan-m/everything-claude-code) — Large agent-harness toolkit spanning plugins, hooks, skills, and cross-host adapters; impressive operational depth, though breadth likely carries non-trivial config and maintenance overhead. 🟩 [OSS] 🟦 [Popular]
- [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) — Curated index of OpenClaw community skills with quality/security filtering and category views; useful discovery layer, but trust still depends on per-skill review before install. 🟩 [OSS] 🟦 [Popular]
- [antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) — Massive installable `SKILL.md` library with CLI-based distribution, curated bundles, and cross-tool compatibility docs; excellent discovery surface, though quality variance and security posture still require per-skill judgement. 🟩 [OSS] 🟦 [Popular]
- [advertising-skills](https://github.com/realkimbarrett/advertising-skills) — Direct-response advertising skill library for AI agents covering paid media, offer positioning, funnel design, and copy QA with orchestrated multi-skill campaign flows; practical operator framing, but licence metadata is unclear despite MIT claims in the README. 🟥 [No licence]
- [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) — Large community catalogue of real OpenClaw workflows across productivity, research, content, and operations, with concrete setup docs per scenario; excellent adoption playbook, though security quality still varies with linked third-party skills and integrations. 🟩 [OSS] 🟦 [Popular]
- [database-skills](https://github.com/planetscale/database-skills) — Focused skill pack for MySQL, Postgres, Vitess, and PlanetScale’s Neki to guide schema design, query tuning, and ops troubleshooting in agent workflows; useful domain grounding, though practical quality depends on keeping references current with fast-moving database features. 🟩 [OSS]
- [emil-design-eng](https://github.com/emilkowalski/skill/tree/main/skills/emil-design-eng) — Detailed UI craft playbook for interaction design and frontend implementation with concrete motion and component heuristics; high-signal guidance, but no clear repo licence metadata yet. 🟥 [No licence]
- [leaked-system-prompts](https://github.com/jujumilk3/leaked-system-prompts) — Large collection of leaked and reproducible system prompts for major LLM services with source links; useful for prompt-security and eval baselines, but provenance quality varies and DMCA/legal risk is explicit. 🟥 [No licence] 🟦 [Popular]
- [claude-token-efficient](https://github.com/drona23/claude-token-efficient) — Minimal `CLAUDE.md` rule pack to suppress verbosity and trim token burn in output-heavy agent workflows, with benchmark-style comparisons and profile variants; pragmatic for cost control, but gains are workload-dependent and extra prompt overhead can backfire on short sessions. 🟩 [OSS] 🟦 [Popular]

### Safety, sandboxing, and evals

- [sentrux](https://github.com/sentrux/sentrux) — Architectural quality sensor for agent-driven coding with live structure scoring, CI gates, and MCP hooks to enforce regression boundaries across sessions; strong governance angle, though its composite quality metric still needs careful calibration against each team’s architecture standards. 🟩 [OSS]
- [skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) — Multi-engine scanner for agent skills combining signature rules, behavioural dataflow, LLM judging, and CI/SARIF outputs; solid defence-in-depth baseline, but maintainers rightly position it as best-effort detection rather than certification. 🟩 [OSS] 🟦 [Popular]
- [gondolin](https://github.com/earendil-works/gondolin) — Local micro-VM sandbox for agent-executed code with programmable network/filesystem policy, secret injection controls, and snapshotting; strong safety primitive for autonomous tooling, though operational ergonomics and backend complexity are still early-stage. 🟩 [OSS]
- [crust](https://github.com/BakeLens/crust) — Local gateway that intercepts agent tool calls across HTTP, MCP, and ACP with rule-based blocking, DLP scanning, and plugin hooks before execution; compelling safety layer, though Elastic License 2.0 terms make commercial redistribution constraints worth checking early.
- [evmbench](https://github.com/paradigmxyz/evmbench) — Smart contract vulnerability benchmark and agent harness with queued worker execution, structured findings output, and optional proxy-token key handling; useful infra for repeatable evals, though running untrusted audits still demands careful runtime isolation. 🟩 [OSS]
- [zeroboot](https://github.com/zerobootdev/zeroboot) — Sub-millisecond KVM sandbox runtime for agent code execution using copy-on-write VM forks; compelling latency and density claims, though the maintainers still frame it as prototype-stage infra. 🟩 [OSS] 🟦 [Popular]

### Voice, OCR, and document intelligence

- [DeepSeek-OCR-2](https://github.com/deepseek-ai/DeepSeek-OCR-2) — OCR model stack with vLLM/Transformers inference paths and markdown-oriented document parsing; promising throughput claims, but setup is CUDA-pinned and rough around reproducibility. 🟩 [OSS] 🟦 [Popular]
- [ocrbase](https://github.com/majcheradam/ocrbase) — Bun-based PDF OCR API and SDK around PaddleOCR-VL with async parse/extract jobs and self-host paths; practical stack, though likely sensitive to model-serving and queue tuning in production. 🟩 [OSS]
- [personaplex](https://github.com/NVIDIA/personaplex) — Full-duplex speech model stack for persona/voice-conditioned conversations built on Moshi, with role prompts and low-latency interaction targets; strong demo surface, but deployment still depends on substantial GPU and model-serving ergonomics. 🟩 [OSS] 🟦 [Popular]
- [Qwen3-ASR](https://github.com/QwenLM/Qwen3-ASR) — Multilingual ASR and forced-alignment stack (52 languages/dialects) with both transformers and vLLM serving paths, plus streaming support; strong benchmark positioning, but practical performance hinges on substantial GPU memory and inference tuning. 🟩 [OSS] 🟦 [Popular]
- [kreuzberg](https://github.com/kreuzberg-dev/kreuzberg) — Rust-core document intelligence framework with broad format coverage and polyglot bindings across major runtimes; compelling infrastructure layer for ingestion pipelines, though operational footprint can get heavy once OCR and extra runtimes are enabled. 🟩 [OSS] 🟦 [Popular]
- [GLM-OCR](https://github.com/zai-org/GLM-OCR) — Compact OCR stack (0.9B) for complex document parsing with layout-aware pipelines and deployment support across vLLM/SGLang/Ollama; strong benchmark claims and practical SDK ergonomics, though end-to-end output quality still hinges on layout model tuning. 🟩 [OSS] 🟦 [Popular]
- [qwen-asr](https://github.com/antirez/qwen-asr) — Minimal-dependency C inference runtime for Qwen3-ASR (0.6B/1.7B) with streaming and stdin-first pipelines, tuned for strong CPU-only throughput; practical edge/server option, though no MPS path and long-file mode trade-offs still need careful tuning. 🟩 [OSS]
- [pdfcraft](https://github.com/PDFCraftTool/pdfcraft) — Browser-first PDF toolkit with 90+ local-processing tools and a visual workflow editor; strong privacy posture, though AGPL and heavy WASM/browser constraints will narrow some commercial use cases. 🟩 [OSS] 🟦 [Popular]

### GTM, branding, and operator tooling

- [sales](https://github.com/chaitanyya/sales) — Claude Code-powered lead research and qualification app with automated company profiling, scorecards, and contact discovery inside a Tauri desktop workflow; useful GTM operator tooling, though data quality and repeatability will depend on prompt discipline and source coverage. 🟩 [OSS]
- [claude-seo](https://github.com/AgriciDaniel/claude-seo) — Comprehensive Claude Code SEO skillset spanning technical audits, E-E-A-T checks, schema generation, GEO workflows, and strategic planning with subagent delegation; broad operator coverage, though outcomes will still depend on data-source quality and disciplined review of generated recommendations. 🟩 [OSS] 🟦 [Popular]
- [claude-ads](https://github.com/AgriciDaniel/claude-ads) — Paid media audit skill for Claude Code covering major ad platforms with weighted scoring, parallel specialist agents, and industry templates; practical for rapid account triage, though recommendation quality still depends on the completeness and freshness of exported account data. 🟩 [OSS] 🟦 [Popular]
- [brand-toolkit](https://github.com/jgerton/brand-toolkit) — Methodology-grounded branding toolkit for Claude Code spanning positioning, messaging, voice, and visual direction with shared state across skills; useful operator scaffold, though still early on real-world adoption signals. 🟩 [OSS]

### Productivity, email, and personal knowledge

- [OfficeCLI](https://github.com/iOfficeAI/OfficeCLI) — Agent-oriented CLI for deterministic Word/Excel/PowerPoint creation and editing with JSON output, batch/resident modes, and MCP integration; strong automation surface for document pipelines, though feature breadth and fast release pace likely require careful version pinning in production flows. 🟩 [OSS] 🟦 [Popular]
- [msgvault](https://github.com/wesm/msgvault) — Offline-first email/archive system with Gmail and IMAP sync, DuckDB-backed search/analytics, and MCP access over local history; strong data-sovereignty angle, though still alpha with storage/API churn risk. 🟩 [OSS] 🟦 [Popular]
- [velo](https://github.com/avihaymenahem/velo) — Keyboard-first, local-first desktop email client on Tauri/Rust with Gmail plus IMAP support and optional multi-provider AI assist; strong product polish for power users, though setup still depends on user-managed OAuth/API credentials. 🟩 [OSS]
- [mails](https://github.com/chekusu/mails) — Email infrastructure for agents with CLI/SDK send-receive flows, hosted mailboxes, and self-hosted Cloudflare Worker paths; practical integration surface, but licence metadata is currently unclear. 🟥 [No licence]
- [My-Brain-Is-Full-Crew](https://github.com/gnekt/My-Brain-Is-Full-Crew) — Eight-agent Obsidian workflow for capture, triage, search, and comms orchestration aimed at overloaded knowledge workers; compelling usability framing, though licence metadata is non-standard and needs care. 🟥 [No licence]

### UI, frontend, and creative tooling

- [ChartGPU](https://github.com/ChartGPU/ChartGPU) — WebGPU charting library pushing very high point counts with streaming dashboards and shared GPU device primitives; compelling for telemetry-heavy UIs if browser/WebGPU constraints are acceptable. 🟩 [OSS] 🟦 [Popular]
- [json-render](https://github.com/vercel-labs/json-render) — Guardrailed generative UI framework that constrains model output to a typed component catalog across web, mobile, and docs surfaces; useful reliability pattern, but schema/catalog discipline is the hard part. 🟩 [OSS] 🟦 [Popular]
- [ace-step-ui](https://github.com/fspecii/ace-step-ui) — Polished local-first UI layer for ACE-Step music generation with queueing, prompt/lyrics tooling, and built-in audio utilities; compelling “open Suno” UX, though licence status is unclear in repo metadata and operational setup still leans on heavyweight local dependencies. 🟥 [No licence]
- [map-to-poster](https://github.com/dimartarmizi/map-to-poster) — Client-side map poster generator with hybrid Leaflet/MapLibre rendering, rich theming, and very high-resolution export paths; polished creator tool, though extreme export sizes can hit browser memory/performance limits on modest machines. 🟩 [OSS]
- [galaxy-profile](https://github.com/vinimlo/galaxy-profile) — GitHub profile generator that produces animated galaxy-themed SVG stat cards from config plus GitHub API data, with scheduled auto-regeneration via Actions; distinctive branding angle, though custom visual templates can become maintenance-heavy as profile data and APIs evolve. 🟩 [OSS]

### Models and systems experiments

- [models.dev](https://github.com/anomalyco/models.dev) — Open-source model catalogue with structured provider/model metadata, pricing, limits, and capabilities exposed as API/JSON; practical backbone for eval tooling and model routing, though freshness still depends on steady community updates. 🟩 [OSS] 🟦 [Popular]
- [Kimi-K2.5](https://github.com/MoonshotAI/Kimi-K2.5) — Native multimodal MoE model release with long context and explicit agent/tooling modes, plus deployment guides for vLLM/SGLang; ambitious capability envelope, though the modified MIT terms add a hyperscale UI attribution condition to watch. 🟦 [Popular]
- [claudes-c-compiler](https://github.com/anthropics/claudes-c-compiler) — End-to-end C compiler written in Rust with in-house frontend, SSA pipeline, assembler, linker, and multi-arch backends, positioned as an autonomy stress test rather than production tooling; impressive systems scope, but maintainer explicitly flags correctness and portability risk. 🟩 [OSS] 🟦 [Popular]

### Games

- [zsweep](https://github.com/oug-t/zsweep) — Keyboard-first Minesweeper remake with competitive metrics (3BV/s, heatmaps, time mode) and a clean Svelte/Tailwind stack; sharp game feel, though current OSS traction is still early. 🟩 [OSS]
