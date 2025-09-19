# Information Retrieval & Recommendation in E-Commerce 🚀
*A practical, code-driven companion to mastering search & recommendation in the age of AI.*

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)

---

## TL;DR

If you build, study, or just geek-out over digital storefronts, this repo gives you:

| What? | Why it matters |
|-------|----------------|
| **Production-ready code** for *search* & *recommendation* pipelines | Clone → run → benchmark or deploy |
| **A book-in-progress** (open-source!) | Learn the maths *and* the PyTorch behind modern IR/rec-sys—chapter by chapter |
| **An autonomous research agent** | Let the bot scour the web, cluster findings, and hand you a cited report |

---

## Why another repo? 🤔

E-commerce IR has exploded—from BM25 to bi-encoders, from naïve top-N to neural bandits—yet solid, narrative-driven code examples are scattered across blogs and papers.  
This project stitches them together in one place, backed by real notebooks, tested pipelines, and readable prose.

---

## Repo layout
```
information-retrieval-e-commerce/
├─ search/                # Vector & hybrid search pipelines (BM25 → RAG)
├─ recommendations/       # Baseline → bandits → neural CTR models
├─ deep-research-hybrid/  # Submodule – autonomous research agent
│   └─ documentation/     # LaTeX chapters for the agent paper
├─ ecom-ir-book/          # Submodule – book chapters + Jupyter notebooks
│   └─ docs/              # Compiled book manuscript (coming soon)
├─ bandits/               # Submodule – book chapters on bandits optimization for search + Jupyter notebooks
│   └─ Bandits_Book/      # Draft manuscript plus notebooks
```
### Sub-modules at a glance

| Sub-repo | Elevator pitch |
|----------|----------------|
| [`DeepResearchHybrid`](https://github.com/VladPrytula/DeepResearchHybrid) | AI agent that loops through *Plan → Search → Analyze → Synthesize* to produce fully-cited research reports—complete with **embedding-based topic discovery** (semantic clustering + auto-labeling) and HyDE query expansion. |
| [`ecom-ir-book`]([https://github.com/VladPrytula/notes2blog](https://github.com/VladPrytula/ecom-ir-book.git)) | Notebook-first “book” that starts with an embedding-MLP baseline, marches through contextual bandits, and lands in neural UCB—each chapter equal parts intuition, maths, and PyTorch code. |


---

## Quick start ⚡

```bash
# 1. Clone with sub-modules
git clone --recursive https://github.com/VladPrytula/information-retrieval-e-commerce.git
cd information-retrieval-e-commerce

read :)
```


## Contributing 

Issues and PRs are welcome—especially examples, benchmarks, or corrections to the book chapters.
Please read CONTRIBUTING.md before opening your first pull request.
