# Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development

[![LaTeX](https://img.shields.io/badge/LaTeX-008080.svg?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=for-the-badge)](LICENSE)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=for-the-badge)]()
[![GitHub Repo](https://img.shields.io/badge/GitHub-TarunyaProgrammer-blue?style=for-the-badge&logo=github)](https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World)

---

## 📌 Executive Summary

This repository contains the empirical research workspace, data collection pipeline, BibTeX citations, and 2-column manuscript for the paper:

**"Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development"**

* **Author**: Tarunya Kesharwani
* **Affiliation**: 2nd Year B.Tech, Newton School of Technology
* **GitHub**: [@tarunyaprogrammer](https://github.com/tarunyaprogrammer)
* **Email**: `tarunyak.10@gmail.com`
* **Manuscript Style**: Traditional 2-Column Academic Research Article

---

## 📜 Scientific Research Directives (`RESEARCH_RULES.md`)

This repository enforces strict scientific research principles governing AI-assisted research and manuscript generation:
* **Rule A (Never Fabricate)**: Zero tolerance for fake papers, DOIs, authors, or statistics.
* **Rule B (Evidence vs. Interpretation)**: Explicit separation between empirical data, analytical interpretation, hypotheses, and speculation.
* **Rule C (No Unsupported Causal Claims)**: Uses correlational language (*associated with*, *correlated with*).
* **Rule D (RQ-Driven Inquiry)**: Every metric and table maps to an explicit Research Question.
* **Rule E (No Result Manipulation)**: Full reporting of negative, null, or inconclusive results.
* **Rule G (Reproducibility)**: Traceable pipeline: $\text{raw/} \to \text{processed/} \to \text{analysis/} \to \text{figures/} \to \text{paper/}$.

---

## 🗺️ Research Milestone Progress (`research/`)

- [x] **[`01-research-question.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/01-research-question.md)**: Formalized RQ1, RQ2, RQ3, and RQ4.
- [x] **[`02-literature-review.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/02-literature-review.md)**: Primary literature matrix & research gap definition.
- [x] **[`03-pragmatic-principles.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/03-pragmatic-principles.md)**: Operationalized DRY, Orthogonality, Modularity, and Testing into observable metrics.
- [x] **[`04-methodology.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/04-methodology.md)**: Mixed-methods empirical study design & dataset pipeline.
- [x] **[`05-research-log.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/05-research-log.md)**: Chronological decision log.

---

## 📂 Repository Layout

```text
ResearchPaper-Pragmatic_Programming_in_AI_World/
├── RESEARCH_RULES.md          # Primary scientific research directives & AI agent guardrails
├── research/
│   ├── 01-research-question.md    # Formalized Research Questions (RQs)
│   ├── 02-literature-review.md    # Verified literature matrix & research gap
│   ├── 03-pragmatic-principles.md # Pragmatic principles mapped to SE metrics
│   ├── 04-methodology.md          # Empirical dataset & study methodology
│   └── 05-research-log.md         # Chronological research decision log
├── data/
│   ├── raw/                       # Raw git log & commit metadata
│   └── processed/                 # Cleaned classified dataset (AI vs Human)
├── analysis/
│   └── extract_metrics.py         # Python metric extraction pipeline
├── Paper/
│   ├── main.tex                  # 2-column LaTeX manuscript source
│   ├── references.bib            # BibTeX citations database
│   ├── main.pdf                 # Compiled 2-column PDF manuscript
│   └── .gitignore               # LaTeX build exclusions
├── .vscode/
│   └── settings.json             # VS Code LaTeX Workshop configuration
├── README.md                     # Project overview and milestone roadmap
└── LICENSE                       # All Rights Reserved strict license
```

---

## 🛠️ Building & Previewing the Paper

### Command Line
```bash
export PATH="/Library/TeX/texbin:$PATH"
cd Paper
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

### VS Code / Cursor / Antigravity
1. Open `Paper/main.tex`.
2. Press `⌘ + Option + V` (or click the green Play icon).
3. Live split-screen PDF preview opens automatically next to your code.

---

## 📖 Citation Format

```bibtex
@article{kesharwani2026pragmatic,
  title     = {Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development},
  author    = {Kesharwani, Tarunya},
  journal   = {Research Paper Series in AI-Assisted Software Engineering},
  year      = {2026},
  url       = {https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World}
}
```

---

## 📜 License

Copyright (c) 2026 Tarunya Kesharwani. All rights reserved. See the [LICENSE](LICENSE) file for usage terms.
