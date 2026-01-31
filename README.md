# Admissibility Beyond Classical Surface Minimization in Physical Networks
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18444240.svg)](https://doi.org/10.5281/zenodo.18444240)

**Author:** A. R. Wells  
**Affiliation:** Dual-Frame Research Group  
**License:** CC BY 4.0  
**Contact:** No solicitation for correspondence or media contact  
**Paper email:** arwells.research@proton.me  

---

## Overview

This repository contains the LaTeX source and supporting documentation for the
conceptual analysis paper

**_Admissibility Beyond Classical Surface Minimization in Physical Networks_**.

The paper provides a **structural limits analysis** of modern surface-minimization
models of physical networks (neuronal arbors, vascular systems, plant roots,
fungal hyphae, and related transport structures).

Surface-minimization models have recently achieved strong empirical success in
predicting **local geometric motifs**. This work does **not** challenge those
results. Instead, it clarifies a precise boundary:

> Surface minimization determines geometry within an admissible topology class,  
> but does not determine which topology classes or transitions are physically permitted.

The contribution is **conceptual and logical**, not dynamical or predictive.

---

## Central Claim

Surface minimization, when interpreted as a classical saddle-point evaluation of
a constrained geometric action, is **generically incomplete in principle**.

It cannot decide:

- topology selection,
- permissibility of topology-changing transitions,
- or resolution of competing constraints across scales.

Any complete theory of physical network organization therefore requires an
additional **admissibility principle** that governs which configurations and
transitions are allowed to enter consideration.

---

## Motivation

Recent work (notably Meng et al., *Nature*, 2026) demonstrates that modeling
networks as smooth embedded surfaces minimizing area under thickness/capacity
constraints explains a wide range of local motifs:

- stable trifurcations,
- angle asymmetries,
- orthogonal sprouts,
- and other geometric regularities.

However, empirical observations also show behaviors that are **not determined by
optimization alone**, including:

- thresholded topology changes,
- history dependence and hysteresis,
- persistence of locally non-optimal structures,
- and selective formation of loops (e.g., anastomoses).

These phenomena indicate a missing **decision layer** that cannot be reduced to
further optimization of the same functional.

This paper identifies that missing layer formally and names it **admissibility**.

---

## Core Idea: Optimization vs. Admissibility

### Surface minimization (geometry selection)

- Operates within a fixed configuration space
- Selects extremal shapes
- Determines local morphology

### Admissibility (configuration selection)

- Governs which configurations or transitions are permitted at all
- Acts categorically rather than incrementally
- Determines the domain over which optimization is meaningful

Surface minimization answers:

> "Given this topology, what shape is optimal?"

Admissibility answers:

> "Which topologies or transitions are allowed to occur?"

These roles are complementary and logically distinct.

---

## What This Paper Does *and Does Not* Claim

### Claims (in scope)

- Surface minimization is structurally incomplete as a standalone theory.
- This incompleteness follows from classical single-saddle variational structure.
- An admissibility layer is logically necessary to resolve topology selection.
- Admissibility implies qualitative, testable signatures (thresholds, hysteresis,
  history dependence).

### Non-claims (explicit)

- The paper does **not** replace surface minimization.
- It does **not** introduce a specific dynamical or biological mechanism.
- It does **not** propose new empirical datasets.
- It does **not** claim admissibility is a universal physical law.
- It does **not** supply a full constructive model.

This is a **limits and clarification paper**, not a new theory.

---

## Empirical Consequences

Introducing admissibility leads to qualitative behaviors that differ from pure
optimization:

- thresholded reorganization,
- path dependence,
- hysteresis,
- persistence of locally non-optimal states,
- selective topology switching.

Time-resolved imaging studies of vascular or developmental remodeling, where
stress accumulation, signaling activation, and topology changes can be tracked
simultaneously, provide natural experimental testbeds for distinguishing
admissibility-governed transitions from purely optimization-driven geometry.

---

## Repository Contents

```
admissibility-beyond-minimal-surfaces/
├── README.md
├── LICENSE
├── CITATION.cff
├── docs/
│   ├── CLAIMS_AND_LIMITS.md
│   ├── RELATED_WORK_MAP.md
│   └── TERMINOLOGY.md
└── paper/
    ├── admissibility_beyond_surface_minimization.tex
    ├── intro.tex
    ├── incompleteness.tex
    ├── admissibility.tex
    ├── conclusion.tex
    ├── refs.bib
    └── (build artifacts)
```

---

## Build Instructions

Requirements: latexmk with a standard LaTeX installation.

Build the paper:

```
cd paper
latexmk -pdf -interaction=nonstopmode -halt-on-error admissibility_beyond_surface_minimization.tex
```

Clean build artifacts:

```
latexmk -C
```

The compiled PDF will be located at:

```
paper/admissibility_beyond_surface_minimization.pdf
```

---

## Status

- Conceptual framework finalized
- Structural limits formally identified
- Admissibility principle articulated
- Empirical signatures specified
- No new dynamics or phenomenology introduced

- Version v1 DOI: https://doi.org/10.5281/zenodo.18444241
- All versions DOI: https://doi.org/10.5281/zenodo.18444240

---

## Citation

If you use or reference this work, please cite the Zenodo record corresponding to
the version used.

Recommended citation:

A. R. Wells (2026).  
*Admissibility Beyond Classical Surface Minimization in Physical Networks*. (v1)  
Zenodo. https://doi.org/10.5281/zenodo.18444241

This work is released under Creative Commons Attribution 4.0 (CC BY 4.0).
