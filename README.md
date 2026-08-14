# Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows

[![LaTeX](https://img.shields.io/badge/LaTeX-008080.svg?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=for-the-badge)](LICENSE)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=for-the-badge)]()
[![GitHub Repo](https://img.shields.io/badge/GitHub-TarunyaProgrammer-blue?style=for-the-badge&logo=github)](https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World)

---

## 📌 Executive Summary

This repository contains the research workspace, empirical research rules, BibTeX citations, and 2-column manuscript source for the paper:

**"Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows"**

* **Author**: Tarunya Kesharwani
* **Affiliation**: 2nd Year B.Tech, Newton School of Technology
* **GitHub**: [@tarunyaprogrammer](https://github.com/tarunyaprogrammer)
* **Email**: `tarunyak.10@gmail.com`
* **Manuscript Style**: Traditional 2-Column Academic Research Article

---

## 📜 Scientific Research Directives (`RESEARCH_RULES.md`)

This repository enforces strict scientific research principles governing human-AI pair research and manuscript generation:
* **Rule A (No Fabrication)**: Zero tolerance for fake papers, DOIs, authors, or statistics. Unverified sources are explicitly flagged.
* **Rule B (Evidence vs. Interpretation)**: Clear separation between observed data, analytical interpretation, hypotheses, and speculation.
* **Rule C (No Unsupported Causal Claims)**: Uses correlational language (*associated with*, *correlated with*) unless experimental designs explicitly prove causation.
* **Rule D (RQ-Driven Inquiry)**: Every analysis maps to an explicit Research Question in `research/questions.md`.
* **Rule E (No Result Manipulation)**: Full reporting of negative, null, or inconclusive results.
* **Rule G (Reproducibility)**: Every quantitative metric is traceable: $\text{raw} \to \text{processed} \to \text{analysis} \to \text{figure} \to \text{paper}$.

---

## 📂 Repository Layout

```text
ResearchPaper-Pragmatic_Programming_in_AI_World/
├── RESEARCH_RULES.md       # Primary scientific research directives & AI agent guardrails
├── research/
│   ├── questions.md        # Explicit Research Questions (RQs)
│   ├── literature.md       # Literature matrix & verified source tracking
│   ├── methodology.md      # Detailed experimental methodology
│   └── research-log.md     # Chronological research decision log
├── Paper/
│   ├── main.tex           # 2-column LaTeX manuscript source
│   ├── references.bib     # BibTeX citations database
│   ├── main.pdf          # Compiled 2-column PDF paper
│   └── .gitignore        # LaTeX build exclusions
├── .vscode/
│   └── settings.json      # VS Code / Antigravity LaTeX Workshop configuration
├── README.md              # Project documentation (this file)
└── LICENSE                # All Rights Reserved strict license
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
  title     = {Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows},
  author    = {Kesharwani, Tarunya},
  journal   = {Research Paper Series in AI-Assisted Software Engineering},
  year      = {2026},
  url       = {https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World}
}
```

---

## 📜 License

Copyright (c) 2026 Tarunya Kesharwani. All rights reserved. See the [LICENSE](LICENSE) file for strict usage terms.
