# Class Schedule Optimization

Solo project solving a **class-schedule assignment problem** in Python by combining three optimization paradigms on the same problem — comparing tradeoffs in solution quality, runtime, and stakeholder-weighted preference handling.

> Final project for **DS1324 — Prescriptive Analytics**, BS Data Science, University of Asia and the Pacific. Solo.

## Methods compared

1. **Linear Programming (LP)** — exact optimization with deterministic constraints.
2. **Genetic Algorithm (GA)** — heuristic search via DEAP / PyGAD; useful when the search space is too large or non-convex for pure LP.
3. **Analytic Hierarchy Process (AHP)** — multi-criteria decision making to weight competing stakeholder preferences (faculty preferences, room utilization, student conflicts) before feeding into the optimizer.

## Repository layout

```
notebook/      Main project notebooks (final + earlier dated version)
documents/     Full documentation, project outline
```

## Stack

`Python` · `PuLP` (LP) · `DEAP` / `PyGAD` (Genetic Algorithm) · `numpy` · `pandas`

## Status

Course final project, completed Feb–May 2026. Solo.

---

**David Nathaniel P. Riego** · BS Data Science, UA&P (Aug 2023 – Aug 2027 expected) · [LinkedIn](https://linkedin.com/in/david-riego/)
