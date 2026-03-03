# CaDiCaL SAT Solver – Formal Methods Presentation

A 10-slide interactive web presentation about the **CaDiCaL SAT Solver**, created as a group assignment for the **Formal Methods (CS-320)** course.

## Live Presentation

**[View the presentation here](https://faisaliqbalkhattak.github.io/fm-presentation/)**

## What's Inside

The presentation covers:

1. **Title** – Project info and group members
2. **Introduction to CaDiCaL** – What it is, who built it, and why it matters
3. **What is SAT?** – Boolean Satisfiability explained simply with an example
4. **DPLL vs CDCL** – How SAT solvers evolved from basic backtracking to conflict-driven clause learning
5. **CaDiCaL's Core Loop** – The Decide → Propagate → Conflict → Learn cycle
6. **Smart Search Strategies** – Activity scoring, phase saving, restarts, and inprocessing
7. **Interactive CDCL Demo** – A step-by-step animated walkthrough of CDCL solving a small formula (click Step/Auto to watch it run)
8. **Solver Comparison** – CaDiCaL vs MiniSat vs Kissat feature table
9. **Summary & Reflections** – Key takeaways from studying the solver
10. **Conclusion & Q&A** – Final thoughts and references

## Why We Made This

This presentation was built as part of our Formal Methods (CS-320) course assignment. We chose CaDiCaL because it is one of the most successful modern SAT solvers — it has won multiple gold medals at the international SAT Competition — and its codebase is designed to be readable and well-documented, making it an excellent subject for study. The goal was to understand how formal methods theory (propositional logic, resolution, clause learning) translates into real, high-performance software.

## Group Members

| Name |
|-------------------|
| Faisal Iqbal Khattak          |
| Hassan Shahid                 |
| Farooq Shafi                  |
| Syed Muneeb ur Rehman Bukhari |

## Tech

Single-file HTML/CSS/JS presentation with scroll-snap navigation, fade-in animations, and an interactive CDCL solver demo. No frameworks or dependencies — just open `index.html` in a browser.
