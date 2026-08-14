# Research Questions (RQs)

This document formalizes the explicit research questions guiding the manuscript. All metrics, datasets, and analysis pipelines must map directly to these questions.

---

## RQ1: Architectural Drift & Technical Debt
> **To what extent is AI-assisted code generation associated with shifts in technical debt metrics (e.g., refactoring frequency, code duplication, cyclomatic complexity) compared to traditional manual implementation?**

* **Target Metrics**: Refactoring commit frequency, duplicate code blocks, modularity coupling indices.
* **Data Sources**: Public git commit histories, automated static analysis tools.

---

## RQ2: Developer Intent vs. Code Verification Workflows
> **How do pragmatic software developers divide cognitive effort between intent specification (prompting/specifications) and automated code verification (unit/integration testing, static analysis) during AI pair programming?**

* **Target Metrics**: Time distribution between prompt crafting vs test creation, test coverage ratios in AI-assisted commits.
* **Data Sources**: Developer workflow logs, task execution telemetry.

---

## RQ3: Context-Window Optimization & Code Integrity
> **What context-window structuring patterns (e.g., interface-only context, modular prompt scoping) minimize non-deterministic API hallucinations and syntax failures in autonomous AI agents?**

* **Target Metrics**: Code compilation success rate on first attempt, hallucinated API endpoint frequency.
* **Data Sources**: Controlled agent execution benchmarks.
