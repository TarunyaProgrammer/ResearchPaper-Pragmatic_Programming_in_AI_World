# Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows

[![LaTeX](https://img.shields.io/badge/LaTeX-008080.svg?style=for-the-badge&logo=LaTeX&logoColor=white)](https://www.latex-project.org/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg?style=for-the-badge)](LICENSE)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg?style=for-the-badge)]()
[![GitHub Repo](https://img.shields.io/badge/GitHub-TarunyaProgrammer-blue?style=for-the-badge&logo=github)](https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World)

---

## 📌 Executive Summary

This repository contains the source code, BibTeX citations, and manuscript assets for the research paper titled **"Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows"** authored by **Tarunya Kesh**.

As Large Language Models (LLMs) and autonomous AI coding agents reshape the software engineering landscape, developer responsibilities are pivoting from low-level syntax construction to high-level intent architecture, prompt engineering, context window management, and automated verification. This paper establishes an empirical and pragmatic framework for navigating human-AI pair programming without accumulating hidden architectural debt.

---

## 📄 Abstract

> The rapid proliferation of Large Language Models (LLMs) and autonomous AI coding agents has initiated a paradigm shift in software engineering. Traditional programming workflows heavily prioritized manual syntax construction, boilerplates, and manual implementation details. In an AI-augmented landscape, pragmatic software engineering shifts developer focus toward high-level intent specification, architectural governance, and rigorous automated verification. This paper explores the core methodologies, operational trade-offs, and emerging design patterns of programming alongside AI agents. We analyze prompt engineering as informal specification, the dynamics of cognitive load, context-window management, and the crucial role of automated testing to bound non-deterministic model outputs. Finally, we formulate a pragmatic framework for evaluating when AI acceleration enhances system quality versus when it risks accumulating hidden architectural debt.

---

## 📂 Repository Structure

```text
ResearchPaper-Pragmatic_Programming_in_AI_World/
├── Paper/
│   ├── main.tex           # Primary LaTeX manuscript source file
│   ├── references.bib     # BibTeX citations and references database
│   ├── main.pdf          # Compiled publication-ready PDF document
│   └── .gitignore        # LaTeX build artifact exclusions
├── README.md              # Project overview and documentation (this file)
└── .gitignore             # Repository root ignore rules
```

---

## 🛠️ Building & Previewing the Paper

### Prerequisites
Make sure you have a TeX distribution installed on your Mac (such as `basictex` or `mactex`):

```bash
brew install --cask basictex
eval "$(/usr/libexec/path_helper)"
```

### Option 1: Command Line Compilation

Navigate into the `Paper/` directory and run:

```bash
cd Paper
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

### Option 2: Live Preview in VS Code / Cursor / Antigravity

1. Install the **LaTeX Workshop** extension in VS Code.
2. Open `Paper/main.tex`.
3. Press `⌘ + Option + V` to launch the live side-by-side PDF preview window.

---

## 📖 Citation Format

If you reference or build upon this work, please cite it using the following BibTeX entry:

```bibtex
@article{kesh2026pragmatic,
  title     = {Pragmatic Software Engineering in the Age of AI: Patterns, Trade-offs, and Verification Workflows},
  author    = {Kesh, Tarunya},
  journal   = {Research Paper Series in AI-Assisted Software Engineering},
  year      = {2026},
  url       = {https://github.com/TarunyaProgrammer/ResearchPaper-Pragmatic_Programming_in_AI_World}
}
```

---

## 📜 License

Copyright (c) 2026 Tarunya Kesh. All rights reserved. See the [LICENSE](LICENSE) file for strict usage permissions.
