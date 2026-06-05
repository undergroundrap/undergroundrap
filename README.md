# Ocean Bennett
### Systems Engineer - Architecture, Local Automation & Mobile AI Products

I design and build deterministic software architectures optimized for local-first execution environments. My engineering focus centers on zero-cloud automation, air-gapped systems orchestration, localized retrieval models, developer toolchains, and mobile products designed to run safely on native hardware.

As a Computer Science student at Southern New Hampshire University, my core development philosophy is rooted in low-level resource control, strict compile-time safety, and product systems that can survive real user constraints. I have historical grounding building native applications in C++, program primarily in Rust for systems work, and use TypeScript / React Native when the product needs to reach users on mobile.

---

## Flagship Systems & Architectures

### [hematite-cli](https://github.com/undergroundrap/hematite-cli)
*A high-precision local AI agent harness, data science runtime, and terminal intelligence platform running 100% on native silicon.*

* **Lead Computational Researcher Mandate:** Engineered a verifiable computation layer that rejects language model hallucinations for mathematical and physics vectors. Integrates high-precision symbolic solvers, unit-aware dimensional analysis, and an empirical Big-O complexity auditor that runs performance regressions against varying input sizes to mathematically verify algorithmic throughput.
* **Analytical SQL & Dataset Ingestion:** Built a native streaming SQL data engine for local files (CSV, JSON, SQLite) supporting automatic schema inference and transactional batching. Pairs with a secure Python sandbox execution environment to run statistical discovery, trend calculations, and generate inline data visualizations directly from production datasets.
* **High-Performance Data & Search Indexing:** Developed a hybrid codebase index pairing an SQLite FTS5 BM25 search engine with a local vector embedding layer. Implements automated background data backfills, path-segment room taxonomy routing, and an active-room memory bias engine to optimize retrieval scores based on hot-subsystem editing velocity.
* **Algorithmic Repository Mapping:** Utilizes tree-sitter AST parsing to extract definitions and references across entire workspaces, running a localized PageRank algorithm via petgraph to weight and map core execution modules directly into prompt contexts with zero runtime network dependency.
* **Proactive Security & Privacy Filtering:** Enforces an aggressive, two-tier identity-stripping privacy gateway before any diagnostic data interfaces with external layers. Combines a fast compiled regular expression pass (`--edge-redact`) with a dedicated local summarizer model (`--semantic-redact`) to programmatically sanitize usernames, hostnames, MAC addresses, and credentials.
* **Full-Stack Telemetry Matrix:** Monitors a monolithic 128+ read-only headless topic catalog mapping low-level Windows kernel metrics, process I/O read/write thrashing counters, network socket allocations, memory pressure, and real-time hardware trends directly to an interactive, mouse-enabled TUI.

### [UEFN-TOOLBELT](https://github.com/undergroundrap/UEFN-TOOLBELT)
*An industrial Python automation framework and actor orchestration engine running inside the sandboxed Unreal Editor for Fortnite process.*

* **Slate-Tick Dispatch Architecture:** Resolved Unreal Engine's primary thread-lock constraint by engineering a two-layer asynchronous bridge. External Model Context Protocol (MCP) HTTP commands are safely ingested via a background FastMCP server, queued, and deterministically dispatched on UEFN's main execution thread using native Slate pre-tick callbacks (`register_slate_pre_tick_callback`) to eliminate engine deadlocks.
* **Algorithmic Asset Mapping:** Orchestrated the first programmatic traversal and taxonomy mapping of the sandboxed Fortnite Creative device palette, systematically cataloging 4,698 device Blueprints across 35 structural categories from 24,000+ total assets.
* **Four-Stage Security Plugin Gate:** Implements a strict, zero-trust security perimeter for community plugin ingestion. Before runtime execution, unverified `.py` files are pushed through four blocking constraints: a 50 KB payload cap, an abstract syntax tree (AST) token scanner that blocks rogue socket, subprocess, and ctypes injections, API version mapping, and SHA-256 integrity hashing logged to an unalterable audit trail.
* **Asynchronous Event-Loop UI:** Drives a 26-tab dark-themed desktop dashboard with PySide6. The UI hooks cleanly into native Slate tick signals to facilitate synchronous interface state modifications and cross-tab search filtering over all 358 modules without micro-stuttering the main viewport's render thread.
* **Dual-Layer World Schema Generator:** Exposes a static 1.6 MB baseline schema mapping all core engine/Fortnite classes alongside a dynamically generated project-level schema. This gives external tools a reliable object-property dictionary wrapper, dropping loose log-parsing overhead.
* **Rigorous Test Automation:** Backed by an automated, invasive 163-test regression suite running natively in-editor. It programmatically spawns actors, tests cross-module configurations, asserts state updates, and flushes environment state clean inside isolated undo windows using scoped editor transactions (`unreal.ScopedEditorTransaction`).

### [Ouxa](https://oceanbennett.com/ouxa/)
*A local-first mobile learning app for programming, systems, and AI-native product engineering. Built with Expo + React Native and released on the Apple App Store.*

* **Mobile Product Architecture:** Built the launch app on Expo SDK 55, React Native 0.83, React 19, Expo Router, and TypeScript, with native-development-build support for modules that cannot run in plain Expo Go.
* **Local-First Learning Runtime:** Implemented XP, hearts, streaks, completed lessons, lesson progress, and selected curriculum state through Zustand and AsyncStorage so the core product works without accounts, a custom backend, or a required database.
* **AI Tutor Pipeline:** Designed the tutor flow around a local-first execution order: on-device GGUF inference through `llama.rn` when available, optional remote tutor only behind explicit dev/admin flags, and deterministic offline hints as the zero-cost fallback for normal users.
* **Curriculum & Access Control:** Built the free/mastery learning gate around useful Foundations content, paid Difficulty 5-6 mastery depth, static catalog delivery, runtime curriculum validation, and doctor/check scripts that prevent launch-critical rule drift.
* **Store & Monetization Systems:** Integrated RevenueCat for optional one-time non-consumable purchases, including pro/no-wait benefits, mastery-pack unlocks, restore flows, safe missing-key behavior, and no subscription dependency for the MVP.
* **Release-Ready Mobile Surface:** Prepared App Store support surfaces, privacy/terms pages, EAS/dev-build workflows, haptics, native module expectations, app metadata, screenshots, and review notes for a real mobile launch.

---

## Applied Experience

* **Local AI Systems:** Rust CLI architecture, LM Studio / Ollama workflows, MCP tool surfaces, local retrieval, host inspection, vector/BM25 hybrid search, privacy redaction, and deterministic fallback design.
* **Mobile Product Engineering:** Expo, React Native, React 19, TypeScript, Expo Router, Zustand, AsyncStorage, RevenueCat, EAS, App Store review preparation, native module constraints, and offline-first UX.
* **Python Automation Platforms:** PySide6 dashboards, FastMCP servers, UEFN Python API automation, Unreal Slate event loops, editor transaction safety, AST inspection, and plugin sandboxing.
* **Curriculum & Developer Education:** Structured programming lessons, quiz/explanation authoring, schema validation, lesson quality automation, local-first AI tutoring, and paid/free content gating.
* **Data & Retrieval Engineering:** SQLite FTS5, local file ingestion, JSON/CSV/SQLite querying, schema inference, hybrid search, PageRank-style repository maps, and relational schema design.

---

## Technical Grounding & Ecosystems

* **Languages:** Rust, TypeScript, Python, C++, Node.js, Verse Lang
* **Mobile & Frontend:** Expo SDK 55, React Native 0.83, React 19, Expo Router, Zustand, AsyncStorage, EAS, Jest, React Native Testing Library
* **Local AI & Inference:** `llama.rn`, GGUF models, LM Studio, Ollama, ONNX Runtime, Model Context Protocol (MCP), FastMCP JSON-RPC, deterministic offline fallback systems
* **Databases & Caching:** SQLite FTS5, PostgreSQL, MySQL, MongoDB, Redis, CosmosDB, relational schema design, high-velocity index tuning
* **Systems Subsystems:** PySide6 / Qt Framework, Win32 Core APIs, Slate event loops, WMI telemetry probes, native process and network diagnostics
* **Product & Commerce:** RevenueCat, Apple App Store release workflows, one-time purchase architecture, entitlement gating, privacy-first product architecture
* **Safety & Code Integrity:** AST syntax trees, scoped editor transactions, SHA-256 verification, static code scanning, feature flags, local-first privacy boundaries

---

## Connection Matrix

* **Platform Hub:** [oceanbennett.com](https://oceanbennett.com/)
* **Ouxa:** [oceanbennett.com/ouxa](https://oceanbennett.com/ouxa/)
* **Ouxa on App Store:** [apps.apple.com/us/app/ouxa/id6767904241](https://apps.apple.com/us/app/ouxa/id6767904241)
* **LinkedIn:** [linkedin.com/in/oceanbennett](https://linkedin.com/in/oceanbennett)
* **X / Twitter:** [x.com/oceanbennett](https://x.com/oceanbennett)
