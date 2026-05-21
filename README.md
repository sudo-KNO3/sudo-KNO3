# sudo-KNO3

Engineer building **Rust tooling, AI infrastructure, and data systems**.

Most of what I ship sits at the intersection of statistical computing,
knowledge engineering, and making information legible to LLM agents.

---

## Active project

### [rust-html-brain](https://github.com/sudo-KNO3/rust-html-brain)

A static HTML "second brain" generator written in Rust. Turns
Obsidian-style markdown into a portable, **AI-readable** site with a
live D3 force-graph view and **semantic code search**. `kb init` drops
it into any codebase — no Python file lands in the target repo (the
embed sidecar is bundled into the binary).

- Single binary, no runtime dependencies after build
- Schema.org `SoftwareSourceCode` JSON-LD + semantic HTML5 + microdata
  + `llms.txt` on every page — three layers of structured signal for
  LLM crawlers
- Docker images: `ghcr.io/sudo-kno3/rust-html-brain:slim` (~2.8 GB,
  model downloaded on first use) and `:full` (~3.5 GB, model pre-baked,
  fully offline)
- D3 force simulation rendered on canvas with continuous gentle motion;
  semantic search via a local HTTP service

```bash
cd any-repo
kb init && kb && kb index-code && kb serve
```

---

## Interests

- **Statistical computing** — descriptive + inferential stats,
  distribution fitting, regression, Monte-Carlo, geostatistics
- **AI context engineering** — structured output (JSON-LD, llms.txt,
  semantic HTML5) for LLM agents; embedding-based code retrieval
- **Knowledge graphs & second-brain architectures** — wikilinks,
  force-directed visualisations, backlink propagation
- **Low-friction CLI / TUI tooling** — single-binary, drop-in,
  zero-config-default

## Stack

`Rust` · `Python` · `TypeScript` · `Docker` · `GitHub Actions`
