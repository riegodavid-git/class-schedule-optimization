# Class Schedule Optimization

Solo project solving a **class-schedule assignment problem** in Python by combining three optimization paradigms on the same problem and comparing tradeoffs in solution quality, runtime, and stakeholder-weighted preference handling.

> Final project for **DS1324 — Prescriptive Analytics**, BS Data Science, University of Asia and the Pacific. Solo project.

## Methods compared

1. **Linear Programming (LP)** — Exact optimization with deterministic constraints.
2. **Genetic Algorithm (GA)** — Heuristic search via DEAP / PyGAD; useful when the search space is too large or non-convex for pure LP.
3. **Analytic Hierarchy Process (AHP)** — Multi-criteria decision making to weight competing stakeholder preferences (faculty preferences, room utilization, student conflicts) before feeding into the optimizer.

The combination lets a stakeholder express *priorities* (via AHP), get an exact small-instance solution (via LP), and scale to larger / messier instances (via GA).

## What's in this repo

- `RIEGO_Class_Schedule_Optimization.ipynb` — main notebook with all three methods.
- `RIEGO_Class_Schedule_Optimization_Documentation.docx` — full written documentation.
- `Project_Outline.docx` — original project outline.

## Stack

`Python` · `PuLP` (LP) · `DEAP` / `PyGAD` (Genetic Algorithm) · `numpy` · `pandas`

## Status

Course final project, completed Feb–May 2026. Solo.

---

**David Nathaniel P. Riego** · BS Data Science, UA&P (Aug 2023 – Aug 2027 expected) · [LinkedIn](https://linkedin.com/in/david-riego/)
