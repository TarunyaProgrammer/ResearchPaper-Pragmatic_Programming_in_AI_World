# 02 - Literature Review & Research Gap Matrix

**Project Title**: Pragmatic Software Engineering in the Age of AI Coding Agents  
**Author**: Tarunya Kesharwani

---

## Literature Search Strategy
Academic search terms evaluated across IEEE Xplore, ACM Digital Library, Springer, and arXiv:
- `"AI-assisted software development"`
- `"AI coding agents" software engineering`
- `"LLM generated code" maintainability`
- `"repository mining" software engineering`
- `"technical debt" AI generated code`

---

## Verified Primary Literature Matrix

| Paper Citation | Year | Research Question | Dataset / Scope | Methodology | Key Findings | Identified Research Gap |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Ziegler et al.** (`githubcopilot2023`) | 2023 | Impact of Copilot on developer productivity | Survey & telemetry ($N > 2000$) | Empirical survey + log analysis | 55% speed increase reported; higher task completion satisfaction. | Focuses on speed/satisfaction, not architectural health or long-term maintainability. |
| **Kesh et al.** (`pragmaticai2024`) | 2024 | Pragmatic SE in LLM workflows | Case study & conceptual model | Qualitative SE analysis | Formulates intent-architect paradigm & test-driven guardrails. | Conceptual framework; requires repository-level quantitative measurement. |

---

## Identified Research Gap

> **The Research Gap**: Existing literature heavily measures short-term developer productivity, task completion speeds, or raw snippet syntax accuracy. However, **little empirical research investigates how AI-assisted development interacts with foundational software engineering principles (e.g., orthogonality, DRY, reversibility, change propagation)** over the multi-commit lifetime of an evolving repository.

This gap forms the exact focus of our study.
