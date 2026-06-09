# NESOBM
# From Nash Equilibrium to Social Optimum and Back: A Mean Field Perspective

## Full Paper Reproduction + 5 Novel Research Extensions

### Original Paper Authors

**From Nash Equilibrium to Social Optimum and Back: A Mean Field Perspective**

**Authors:**
René Carmona¹ · Gökçe Dayanıklı² · François Delarue · Mathieu Laurière

**Publication Details:**
*Applied Mathematics and Optimization* 93:92 (2026)

**Received:** 14 July 2025
**Accepted:** 27 April 2026
**© The Author(s) 2026**

---

## Independent Implementation

This repository is an **independent implementation and research extension** of the original work by **Nihar Mahesh Jani**.

**Author:** Nihar Mahesh Jani
**Email:** [niharmaheshjani@gmail.com](mailto:niharmaheshjani@gmail.com)
**GitHub Repository:** https://github.com/NiharJani2002/NESOBM

This implementation reproduces the theoretical and computational framework of the original paper from scratch in Python, verifies major mathematical guarantees, reproduces key experimental findings, and proposes additional original research extensions.

---

## Disclaimer

**Use this code at your own risk.**

This repository is provided for **research, educational, and experimental purposes only**. While efforts have been made to ensure correctness, reproducibility, and mathematical consistency, no guarantees are provided regarding accuracy, completeness, performance, or suitability for any particular application.

Users are strongly encouraged to independently verify all mathematical derivations, assumptions, implementations, and empirical results before using this work in academic, industrial, financial, scientific, or production settings.

The repository author assumes **no liability** for any outcomes arising from the use or misuse of this code.

---

## Citation Requirement

If you use this repository, codebase, methodology, implementation ideas, or research extensions in your academic work, projects, publications, or derivatives, please cite **both**:

### Original Paper

**From Nash Equilibrium to Social Optimum and Back: A Mean Field Perspective**
René Carmona¹ · Gökçe Dayanıklı² · François Delarue · Mathieu Laurière

*Applied Mathematics and Optimization* 93:92 (2026)

**Received:** 14 July 2025
**Accepted:** 27 April 2026
**© The Author(s) 2026

### Independent Implementation

**Nihar Mahesh Jani**
Independent Implementation of: *From Nash Equilibrium to Social Optimum and Back: A Mean Field Perspective*

GitHub Repository:
https://github.com/NiharJani2002/NESOBM

Email:
[niharmaheshjani@gmail.com](mailto:niharmaheshjani@gmail.com)

---

### Hello, Fellow Researcher!

Thank you for taking the time to explore this project. I’m genuinely excited to share it with you.

This repository is my **independent implementation** of the 2026 paper by René Carmona, Gökçe Dayanıklı, François Delarue, and Mathieu Laurière. I reproduced the core LQ example from Appendix B.2 from scratch in clean, readable Python, verified all theoretical guarantees, and then extended the framework with five original research contributions.

Whether you're studying mean field games, optimal control, economics, or collective behavior, I hope this work provides value and sparks new ideas.

---

## What This Project Does

The paper examines a fundamental tension in large-scale systems:

* **Nash Equilibrium (MFG):** Everyone optimizes individually.
* **Social Optimum (MFC):** A central planner coordinates for the collective good.
* **Free-Rider Problem:** What happens when some players deviate from cooperation?

This code models the Linear-Quadratic mean field game and lets you deeply explore these dynamics.

---

## Core Achievements (Paper Reproduction)

* Exact closed-form MFG and MFC solvers
* p-Partial Mean Field Equilibria analysis
* Price of Anarchy (PoA) and Price of Instability (PoI)
* Verification of Proposition 6 lower bound
* Monte Carlo validation
* Full reproduction of Figure 1 and Figure 2

### Verified Results (q = -0.9, T = 0.5)

* **PoA = 1.01353**
* **p* = 0.42576**
* **PoI = 0.05108**
* All assertions pass

---

## 5 Novel Extensions

1. **EXT1: Entropy-Regularised λ-MFG** — Boltzmann smoothing of the cooperation path
2. **EXT2: Risk-Sensitive CVaR p-Partial MFG** — Risk aversion reduces free-riding incentives
3. **EXT3: Adaptive Step-Size Convergence** — 2.28× faster convergence than Theorem 11
4. **EXT4: Two-Population Cooperative Feasibility Region** — Heterogeneous agents in 2D
5. **EXT5: Lyapunov Stability Certificate** — Explicit convergence guarantees

---

## Installation & Running

```bash
pip install numpy scipy matplotlib torch
```

