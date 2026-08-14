# Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development

[![LaTeX](https://img.shields.io/badge/LaTeX-008080.svg?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=for-the-badge)](LICENSE)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=for-the-badge)]()
[![GitHub Repo](https://img.shields.io/badge/GitHub-TarunyaProgrammer-blue?style=for-the-badge&logo=github)](https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World)

---

## 📌 Executive Summary

This repository hosts the primary research workspace, data collection telemetry, BibTeX bibliography, and manuscript source for the empirical software engineering study:

> **"Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development"**

* **Author**: Tarunya Kesharwani
* **Affiliation**: 2nd Year B.Tech, Newton School of Technology
* **GitHub**: [@tarunyaprogrammer](https://github.com/tarunyaprogrammer)
* **Email**: `tarunyak.10@gmail.com`
* **Manuscript Format**: Traditional 2-Column Academic Research Article

---

## 🔬 Empirical Research Framework & Methodological Principles

This study investigates how classical software engineering principles—specifically **orthogonality**, **duplication avoidance (DRY)**, **modularity**, and **test-driven guardrails**—manifest when software implementation is partially or fully delegated to autonomous AI coding agents.

### Scientific Principles Guiding This Study
* **RQ-Driven Investigation**: All metrics, repository mining procedures, and statistical tests map directly to explicit Research Questions.
* **Evidence vs. Interpretation**: Clear operational distinction between observed commit diffs, statistical correlations, analytical interpretations, and hypotheses.
* **No Unsupported Causal Claims**: Strict usage of correlational terminology (*associated with*, *correlated with*) to prevent unwarranted causal assertions.
* **Reproducible Data Lineage**: Every quantitative table value and plot is traceable through a transparent analysis pipeline:

$$\text{data/raw/} \longrightarrow \text{data/processed/} \longrightarrow \text{analysis/} \longrightarrow \text{Paper/main.pdf}$$

---

## 🎯 Research Questions (RQs)

* **RQ1 (Principle Manifestation)**: How do traditional pragmatic software-engineering principles (e.g., orthogonality, DRY, modularity) manifest in AI-assisted software development?
* **RQ2 (Engineering Practice Impact)**: How does AI-assisted code generation affect core practices such as refactoring, test co-evolution, and change propagation?
* **RQ3 (Critical Guardrails)**: Which traditional engineering practices become most critical to system stability when implementation is delegated to AI agents?
* **RQ4 (Emergent Defect Taxonomy)**: What specific categories of architectural friction and integration defects emerge in AI-generated code bases?

---

## 🗺️ Research Workspace Architecture (`research/`)

- [x] **[`01-research-question.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/01-research-question.md)**: Formalized RQ specifications.
- [x] **[`02-literature-review.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/02-literature-review.md)**: Primary literature matrix & research gap identification.
- [x] **[`03-pragmatic-principles.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/03-pragmatic-principles.md)**: Operationalized principles into observable software engineering metrics.
- [x] **[`04-methodology.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/04-methodology.md)**: Empirical repository mining methodology & commit classification.
- [x] **[`05-research-log.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/05-research-log.md)**: Chronological research decision log.

---

## 📂 Public Repository Layout

```text
ResearchPaper-Pragmatic_Programming_in_AI_World/
├── research/
│   ├── 01-research-question.md    # Formalized Research Questions (RQs)
│   ├── 02-literature-review.md    # Verified literature matrix & research gap
│   ├── 03-pragmatic-principles.md # Pragmatic principles mapped to SE metrics
│   ├── 04-methodology.md          # Empirical dataset & study methodology
│   └── 05-research-log.md         # Chronological research decision log
├── data/
│   ├── raw/                       # Raw git commit metadata & telemetry logs
│   └── processed/                 # Cleaned classified commit datasets (AI vs Human)
├── analysis/
│   └── extract_metrics.py         # Automated Python metric extraction script
├── Paper/
│   ├── main.tex                  # 2-column LaTeX manuscript source
│   ├── references.bib            # BibTeX bibliography database
│   ├── main.pdf                 # Compiled 2-column PDF manuscript
│   └── .gitignore               # LaTeX build exclusions
├── README.md                     # Project documentation (this file)
└── LICENSE                       # All Rights Reserved strict license
```

---

## 🛠️ Building & Previewing the Paper

### Command Line Build
```bash
export PATH="/Library/TeX/texbin:$PATH"
cd Paper
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

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

Copyright (c) 2026 Tarunya Kesharwani. All rights reserved. See the [LICENSE](LICENSE) file for strict usage permissions.
