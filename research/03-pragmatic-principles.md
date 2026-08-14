# 03 - Operationalizing Pragmatic Principles into Measurable Metrics

**Project Title**: Pragmatic Programming in the Age of AI Coding Agents  
**Author**: Tarunya Kesharwani

---

## Conceptual Framework Transformation

We transform qualitative principles from *The Pragmatic Programmer* (Hunt & Thomas) into **observable, quantitative software engineering properties**.

| Pragmatic Principle | Research Interpretation | Measurable SE Proxy Metric | Data Collection Tool |
| :--- | :--- | :--- | :--- |
| **Orthogonality** | Changes to one module should have zero/minimal side-effects on unrelated modules. | **Change Propagation Rate**: Number of files & distinct directory modules modified per commit. | Git commit diff parsing |
| **DRY (Don't Repeat Yourself)** | Every piece of knowledge must have a single, unambiguous representation. | **Duplication Ratio**: Percentage of duplicate code blocks introduced in AI vs Human commits. | Static analysis AST duplicator (PMD / SonarQube / jscpd) |
| **Modularity & Complexity** | Code structures should maintain low coupling and high cohesion. | **Cyclomatic Complexity & Churn**: Lines added/deleted per commit and weighted complexity change. | `lizard` / `radon` static complexity tools |
| **Refactoring** | Continuous improvement of structural code quality without changing external behavior. | **Refactoring Commit Frequency**: Ratio of structural refactor commits to feature commits. | Commit message NLP & diff pattern analysis |
| **Testing Guardrails** | Verification boundaries that catch regressions automatically. | **Test Co-evolution Ratio**: Ratio of test line modifications to production line modifications per commit. | Git diff test folder matching |
| **Reversibility** | Preserving architectural flexibility so choices can be undone cleanly. | **Architectural Reversal Frequency**: Frequency of reverted or overwritten commits/PRs. | Git log revert & refactor analysis |

---

## Observational Rule

> **Critical Distinction**: *The Pragmatic Programmer* is a conceptual framework, NOT empirical evidence. We do not treat book principles as established scientific facts. Instead, we investigate whether and how these principles manifest in modern AI-assisted engineering.
