# Build: GQR (pre-QGE)

This directory describes the **GQR framework build prior to the full QGE
(Quantum Geometry Engine) abstraction**.

It exists to separate:
- the *framework-level* concepts and scope (GQR), from
- the later *engine-level* generalisation (QGE).

No production code is present here.

---

## What this build covers

**GQR (pre-QGE)** is the geometry-first framework phase in which:

- geometry, boundary conditions, and constraint are treated as primary selectors
  of quantum and molecular dynamics
- “gating” is used to express admissible vs suppressed transitions
- the programme is developed largely through chemistry/biology/catalysis-facing
  problems, before the kernel is fully generalised as an engine

This build provides the conceptual and methodological spine that later
engine components inherit.

---

## What this build is not

- Not a standalone MD engine
- Not a replacement for MD, QM/MM, AIMD, or electronic-structure methods
- Not a claim of macroscopic quantum coherence in biology
- Not a finished software artefact

---

## Where the authoritative record lives

Formal statements, evidence, and derivations are contained in the cited
GQR manuscripts (ChemRxiv / Zenodo DOI records).

This repository serves as navigation and orientation only.

---

## Relationship to later builds

- **QGE (core engine):** generalises the framework into an explicit,
  model-agnostic geometry engine suitable for broader inverse-design
  and multi-scale use cases.
- **WaterGate / CopperGate:** represent domain instantiations of QGE,
  used to test and demonstrate the engine across biological and
  materials contexts.

---

## Status

Framework build (pre-engine generalisation). Active development.
