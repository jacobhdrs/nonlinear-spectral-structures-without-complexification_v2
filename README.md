# Dynamical Formalization of a nonlinear-spectral-structures-without-complexification_v2

<a href="https://zenodo.org/records/22688646"><img src="https://img.shields.io/badge/DOI-10.5281/zenodo.22688646-blue.svg" alt="DOI"></a>

Preprint and data for non-linear spectral structures without complexification (MSC 37-XX)

## 📐 Mathematical Architecture & Computation Flow

To help readers and contributors navigate the codebase and theoretical layout, this section clarifies the duality between our **Expository Structure (Top-down)** and **Computational Pipeline (Bottom-up)**.

### 📑 Execution Pipeline & Roadmap
This diagram illustrates the overall execution pipeline and the stage-indexed structural generation mechanism of the proposed framework.
<img width="861" height="822" alt="figure01_loadmap" src="https://github.com/user-attachments/assets/6d1e01a5-d2f7-4fae-b0b4-c32979beb2c9" />

## Why Undefined Primitive Relations (Red, Der)?

Most formalization papers avoid introducing undefined primitive 
relations — independence between structures is usually expressed 
through existing tools (e.g., analytic continuation, isomorphism) 
from complex function theory.

This framework, however, is developed **entirely within the real 
domain, without complexification** (see §4.8.1). Standard complex-
analytic tools for expressing structural independence therefore 
don't apply here.

Expressing that independence purely through set-theoretic operations 
(inclusion, intersection) would reduce a *qualitative* property — 
irreducibility and non-derivability between stages — to mere set 
membership, losing what actually makes the stages independent.

So instead of reducing `Red` (reduction) and `Der` (derivation) to 
existing structures, this framework treats them as **undefined 
primitives**, whose meaning is fixed entirely by the axioms that 
govern them (§2.1.3–2.1.4) — the same way `∈` is primitive in 
axiomatic set theory, or "point" and "line" are primitive in 
axiomatic geometry.
