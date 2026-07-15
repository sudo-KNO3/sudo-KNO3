# sudo-KNO3

Engineer building **Rust tooling, AI infrastructure, and data systems** — mostly
at the intersection of statistical computing, knowledge engineering, and making
information legible to LLM agents.

I like single-binary tools, structured data, and applying that tooling to hard
real-world domains (environmental / air-quality modelling, geoscience,
process engineering).

```text
Rust · Python · TypeScript · WASM · Docker · GitHub Actions · SQLite/FTS5
```

---

## Featured work

### 🧠 [rust-html-brain](https://github.com/sudo-KNO3/rust-html-brain)
A single-binary Rust SSG that turns Obsidian-style markdown into a portable,
**AI-readable** HTML site — live D3 force-graph, semantic code search, and three
layers of structured signal for LLM crawlers (JSON-LD + semantic HTML5 +
`llms.txt`). `kb init && kb serve` drops it into any repo.

### 🗃️ [contextkernel](https://github.com/sudo-KNO3/contextkernel)
Local-first **abstract-knowledge plugin for AI memory & context management**.
Rust core, SQLite + FTS5, HTTP API and a Python SDK — persistent, retrievable
context for agents without a cloud dependency.

### 📊 [statistics-and-reasoning](https://github.com/sudo-KNO3/statistics-and-reasoning)
Modular Rust statistical engine for **mining analytics** — a domain-agnostic
stats core (distributions, GoF, regression, geostatistics), a mining crate
(assay QA/QC, compositing, kriging, block models), and a `ratatui` terminal
workbench. Cargo workspace.

### 🌫️ [aermod-pipeline](https://github.com/sudo-KNO3/aermod-pipeline)
"ChatGPT for air modelling" — an AI agent that turns a plain-English scenario
into a full EPA **AERMOD** run: it builds the input files, fetches met/terrain
data, drives the Fortran toolchain, interprets the output, and self-corrects.

---

## More projects

**AI / agent tooling**
| Repo | What |
|---|---|
| [universal-architecture](https://github.com/sudo-KNO3/universal-architecture) | Source-aware agent framework — parses code into a call-graph + semantic model so an LLM can modify it safely |
| [Writing-agent](https://github.com/sudo-KNO3/Writing-agent) | Retrieval-augmented report writer with self-critique and tracked-changes output |
| [Lab-Data-Input-Pipeline](https://github.com/sudo-KNO3/Lab-Data-Input-Pipeline) | Self-training chemical-name normalizer (Ontario Reg 153/04) — matures via vocabulary growth, not perpetual retraining |

**Modelling & engineering**
| Repo | What |
|---|---|
| [Continuous-quality-guard](https://github.com/sudo-KNO3/Continuous-quality-guard) | Real-time flow-regime monitoring & supervisory control — ML regime detection, TimescaleDB, K8s-ready |
| [BIochar_Sim](https://github.com/sudo-KNO3/BIochar_Sim) | Techno-economic simulation of a septage-to-biochar hub — physics + financial sensitivity |
| [aermod-modernization](https://github.com/sudo-KNO3/aermod-modernization) | Modernizing legacy EPA air-modelling Fortran (AERMAP, MPRM, CALMET→netCDF) |

**For fun** 🦀
| Repo | What |
|---|---|
| [python-playground](https://github.com/sudo-KNO3/python-playground) | Rust→WASM nearest-Taco-Bell finder, sub-50 ms, zero network calls · [live](https://yesimthisgoofy.surge.sh) |
| [happy-birthday-ryleigh](https://github.com/sudo-KNO3/happy-birthday-ryleigh) | A from-scratch Rust→WASM oil-painting engine that repaints Alberta landscapes in the browser |

---

## What I care about

- **AI context engineering** — structured output (JSON-LD, `llms.txt`, semantic
  HTML5) and embedding-based retrieval that make code and knowledge legible to agents
- **Statistical computing** — distribution fitting, regression, Monte-Carlo, geostatistics
- **Knowledge graphs & second-brain systems** — wikilinks, force-directed views, backlinks
- **Low-friction CLI / TUI tooling** — single-binary, drop-in, zero-config-by-default
