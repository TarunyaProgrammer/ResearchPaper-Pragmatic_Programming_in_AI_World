# 01 - Research Questions (RQs)

**Project Title**: Pragmatic Programming in the Age of AI Coding Agents: An Empirical Case Study of Software Engineering Practices in AI-Assisted Development  
**Author**: Tarunya Kesharwani (Newton School of Technology)

---

## Overview
This document formalizes the explicit research questions guiding this empirical case study. Every metric, dataset extraction, visualization, and statistical analysis in `data/` and `analysis/` must map directly to one or more of these questions.

---

## RQ1: Principle Manifestation in AI Development
> **How do traditional pragmatic software-engineering principles (e.g., orthogonality, DRY, modularity, reversibility) manifest in software projects developed alongside AI coding agents?**

* **Focus**: Operationalizing conceptual principles into observable software properties.
* **Measurable Proxies**: Cross-module change propagation, duplicate code block frequency, architectural coupling.
* **Target Data**: Repository commit histories, static analysis metrics.

---

## RQ2: Impact on Core Engineering Practices
> **How does AI-assisted code generation affect software engineering practices such as refactoring, test-driven development, modularity, and code review iteration?**

* **Focus**: Comparative metric analysis between AI-assisted commits versus human-authored commits.
* **Measurable Proxies**: Code churn per commit, files touched per change, test coverage additions, refactoring commit frequency.
* **Target Data**: Classified commit datasets ($N_{\text{AI}}$ vs. $N_{\text{Human}}$).

---

## RQ3: Essential Practices Under AI Delegation
> **Which traditional pragmatic programming practices become more critical to system stability when code implementation is partially or fully delegated to AI coding agents?**

* **Focus**: Identifying key defensive engineering practices (e.g., test-driven guardrails, interface specification, strict contract typing).
* **Measurable Proxies**: Post-commit bug fix frequency, regression test failure rates.
* **Target Data**: Issue tracker logs, CI build failure logs.

---

## RQ4: Emergent Engineering Defect Taxonomy
> **What specific categories of software engineering defects and architectural friction emerge when AI-generated code is integrated into an evolving software system?**

* **Focus**: Qualitative classification of recurring AI integration defects.
* **Qualitative Categories**:
  1. API & Contract Misuse
  2. Unnecessary/Over-engineered Abstractions
  3. Logic Duplication
  4. Inadequate Edge-Case Testing
  5. Architectural Inconsistency / Boundary Violations
