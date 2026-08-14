# Core Scientific Research Directives & Guardrails

> [!IMPORTANT]
> **Priority Rule**: This document overrides general conversational or stylistic preferences. Any research synthesis, analysis, manuscript drafting, or citation management MUST strictly adhere to these 11 foundational principles.

---

## A. Never Fabricate Research
- **Strict Prohibition**: NEVER fabricate, hallucinate, or approximate papers, authors, citations, DOIs, datasets, experimental results, statistics, publication venues, or empirical findings.
- **Verification Rule**: Every source, citation, and metric must be verified against primary documents.
- **Unverified Marking**: If a source cannot be independently verified, explicitly mark it as `[UNVERIFIED SOURCE - REQUIRED AUDIT]`.

---

## B. Separate Evidence from Interpretation
Always maintain an explicit distinction between:
1. **Observed Evidence** (Raw empirical data, code analysis outputs, survey responses).
2. **Interpretation** (Analytical deductions derived from observed evidence).
3. **Hypothesis** (Testable predictions).
4. **Speculation** (Unverified theoretical possibilities).

*Never present an interpretation or hypothesis as an empirical finding.*
- ❌ **Incorrect**: "AI-generated code increases technical debt."
- ✅ **Acceptable**: "In our dataset, AI-assisted commits were associated with higher subsequent refactoring frequency ($p < 0.05$). This correlation does not establish that AI assistance caused technical debt."

---

## C. No Unsupported Causal Claims
- **Language Prohibition**: Do not use definitive causal terms (*causes*, *leads to*, *results in*, *improves*, *worsens*, *increases*, *decreases*) unless the experimental design explicitly supports causal inference (e.g., randomized controlled trials).
- **Required Terminology**: Prefer correlational and observational terms:
  - *associated with*
  - *correlated with*
  - *observed alongside*
  - *suggests*
  - *may indicate*

---

## D. Research Questions (RQs) Drive Everything
- **Scope Rule**: Every experiment, metric, visualization, table, and statistical test MUST map directly to an explicit Research Question defined in `research/questions.md`.
- **Anti-Pattern Guard**: Do not collect, calculate, or present vanity metrics merely because data is available. If RQ2 does not require cyclomatic complexity, do not calculate it just to fill a table.

---

## E. Never Manipulate Results
- **Scientific Integrity**: Never modify, omit, selectively report, or reinterpret data to make a hypothesis appear correct.
- **Negative & Inconclusive Results**: Negative, null, or statistically non-significant results carry equal scientific validity and MUST be reported fully.

---

## F. Maintain a Continuous Research Log
All research decisions, dataset changes, methodological pivots, excluded data points, assumptions, failed experiments, and analysis script versions MUST be logged chronologically in [`research/research-log.md`](file:///Users/tarunyakesh/Desktop/ResearchPapers/ResearchPaper-Pragmatic_Programming_in_AI_World/research/research-log.md).

---

## G. Reproducibility & Data Lineage
Every quantitative number, table value, or figure in the paper must be fully traceable through a transparent, reproducible pipeline:

$$\text{raw/} \longrightarrow \text{processed/} \longrightarrow \text{analysis/} \longrightarrow \text{figures/} \longrightarrow \text{paper/}$$

If the manuscript states *"Median = 4.2"*, the exact script and input dataset producing that value must be reproducible via a single command.

---

## H. Citation Discipline
- **Source Verification**: Every non-trivial claim regarding existing literature must have a verified primary source.
- **Relevance Audit**: Do not cite a source merely because its title sounds relevant. Verify that the primary text of the paper directly supports the asserted claim.

---

## I. Conceptual Frameworks vs. Empirical Evidence
- **The Pragmatic Programmer Notice**: Treat *The Pragmatic Programmer* (Hunt & Thomas) and similar software design books as **conceptual frameworks**, not empirical evidence.
- **Empirical Principle**: Do not treat book principles as established scientific facts. The research objective is to empirically investigate whether and how those concepts manifest in modern AI-assisted engineering.

---

## J. Actively Search for Contradictory Evidence
For every primary hypothesis, actively investigate:
1. Contradictory research studies and counter-examples.
2. Competing theoretical explanations.
3. Null or inconclusive results.
4. Methodological criticisms and threats to validity.

---

## K. Strict Target Venue Compliance
- Never invent custom or ad-hoc formatting conventions.
- Follow official publisher templates (IEEEtran / ACM SIGSOFT / LNCS) for document class, column layout, page limits, bibliography styles, and anonymization requirements.
