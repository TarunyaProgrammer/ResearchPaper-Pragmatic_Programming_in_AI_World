# 04 - Methodology & Empirical Pipeline Specification

**Project Title**: Pragmatic Programming in the Age of AI Coding Agents  
**Author**: Tarunya Kesharwani

---

## 1. Study Design: Mixed-Methods Case Study
This study combines **quantitative repository mining** with **qualitative defect taxonomy analysis**.

```text
                  Git Repositories (N commits)
                               │
               ┌───────────────┴───────────────┐
               ↓                               ↓
      AI-Assisted Commits             Human-Only Commits
        (Group A: N_AI)                (Group B: N_Human)
               │                               │
               └───────────────┬───────────────┘
                               ↓
                   Quantitative Metric Extraction
         (Files touched, Churn, Complexity, Test ratio)
                               │
                               ↓
                    Statistical Comparison
              (Mann-Whitney U / Effect Size)
                               │
                               ↓
                    Qualitative Defect Taxonomy
```

---

## 2. Dataset Specification
- **Repositories Examined**: Target active Git repositories containing mixed AI-assisted and human commit histories.
- **Commit Classification Criteria**:
  - **AI-Assisted**: Identified via commit co-author trailers (`Co-authored-by: GitHub Copilot`, `Agent-ID`), PR metadata, or explicit developer session logging.
  - **Human-Only**: Traditional commits with no AI assistant involvement.

---

## 3. Quantitative Analysis Metrics
For each commit $c \in C$, we compute:
1. $\text{Churn}(c) = \text{LinesAdded}(c) + \text{LinesDeleted}(c)$
2. $\text{FilesTouched}(c) = |\text{UniqueFiles}(c)|$
3. $\text{ModulesTouched}(c) = |\text{UniqueDirectories}(c)|$
4. $\text{TestRatio}(c) = \frac{\text{TestLinesModified}(c)}{\text{TotalLinesModified}(c)}$

---

## 4. Threats to Validity
- **Internal Validity**: Disambiguating AI influence from developer experience.
- **External Validity**: Generalizability across single-developer vs multi-developer repositories.
- **Construct Validity**: Ensuring proxy metrics accurately reflect qualitative architectural health.
