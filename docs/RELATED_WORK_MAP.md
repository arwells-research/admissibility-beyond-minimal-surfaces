# RELATED_WORK_MAP.md

**Project:** admissibility-beyond-minimal-surfaces  
**Purpose:** Situate this paper precisely within existing literature, clarifying continuity, dependence, and non-overlap. This document is for authorial discipline and reviewer navigation.

---

## 1) Primary anchor work

### Surface minimization in physical networks (2024–2026)

**Representative work**
- Meng et al., *Surface optimization governs the local design of physical networks*, Nature (2026)

**What this work establishes**
- Physical networks are better modeled as smooth manifolds than as 1D graphs.
- Local branching motifs are governed by surface (area) minimization with a thickness constraint.
- Classical minimal surfaces predict:
  - stable trifurcations,
  - angle asymmetry regimes,
  - orthogonal sprouting behavior.
- The formulation is explicitly connected to string-theoretic minimal worldsheet geometry.

**What it does not attempt**
- Global topology selection.
- Cross-scale consistency of capacity constraints.
- Functional or multi-objective optimization.
- Competition between multiple admissible configurations.

**Relationship to this paper**
- This paper *accepts these results in full*.
- We reinterpret them as **classical saddle-point solutions** and identify the precise boundary of their explanatory power.

---

## 2) Historical precursors: wiring economy and volume optimization

### Steiner trees and wiring minimization
- Hwang, Richards, Winter — *The Steiner Tree Problem*
- Chklovskii et al. — wiring optimization in neural systems

**Status**
- Correct in the vanishing-thickness (1D) limit.
- Known to fail empirically for real physical networks.

**Role here**
- Treated as Σ₁ / zero-capacity approximations.
- Their failure motivates—but does not resolve—the need for higher-order constraints.

---

### Volume-based optimization (cylindrical models)
- Murray (1926)
- Zamir (1976)
- Cherniak (1992)

**Status**
- Improves upon pure length minimization.
- Still assumes simplified local geometry and fails to predict several observed motifs.

**Role here**
- Recognized as intermediate approximations.
- Still classical, still optimization-only, still incomplete in the same structural sense.

---

## 3) String-theoretic and geometric foundations

### Minimal surfaces and Nambu–Goto action
- Nambu–Goto formulation of string worldsheets
- Classical minimal surface theory

**Status**
- Provides a rigorous mathematical framework for surface minimization.
- Well-understood limitations at the classical saddle level.

**Role here**
- Supplies the correct language to classify surface-minimization network models.
- Enables a precise statement of what is included (single saddle) and excluded (fluctuations, topology competition).

---

### Pants decomposition and worldsheet topology
- Strebel differentials
- Closed string field theory (Witten, Zwiebach)

**Status**
- Natural framework for local branching (pair-of-pants vertices).
- Requires extension to address loops, handles, and global topology.

**Role here**
- Used to explain why local branching is captured correctly.
- Also explains why global topology is not decided.

---

## 4) Network science beyond optimization

### Physicality and constraints
- Dehmamy et al. (2018)
- Pósfai et al. (2024)

**Status**
- Recognize that physical embedding changes network structure.
- Often remain descriptive or phenomenological.

**Role here**
- Provide empirical motivation for constraint-based thinking.
- Do not offer a general admissibility principle.

---

### Loops, bundling, and nonlocal effects
- Work on knotting, entanglement, bundling in physical networks

**Status**
- Identifies phenomena incompatible with simple optimization.
- Typically addressed case-by-case.

**Role here**
- Treated as evidence that local optimization is insufficient.
- Point toward the necessity of global admissibility rules.

---

## 5) What this paper is deliberately *not* building on

To avoid confusion, this paper does not directly engage with:

- Developmental biology models of network growth.
- Agent-based growth simulations.
- Evolutionary fitness landscapes.
- Machine-learning-based network generation.

These may be compatible with admissibility-based frameworks but are orthogonal to the present goal.

---

## 6) Conceptual niche of this paper

This paper occupies a narrow but critical position:

- It is **not** an optimization model.
- It is **not** an empirical survey.
- It is **not** a replacement theory.

It is a **limits-and-classification paper** that:

- identifies surface minimization as a classical geometric saddle,
- delineates its domain of validity,
- and shows why a higher-order admissibility framework is logically unavoidable.

---

## 7) Citation intent

When published, this paper should be citable as:

- a clarification of the theoretical status of surface-minimization models,
- a boundary marker for optimization-based explanations,
- a motivation for admissibility- or consistency-based extensions.

It should not be cited as proposing a new universal model of physical networks.

---

## 8) Lock condition

This map is considered complete when:

- All cited work fits cleanly into one of the categories above.
- No section of the paper implicitly claims priority over anchor works.
- Reviewer confusion about “what problem is being solved” is minimized.

Any addition to scope must update this file first.

---
