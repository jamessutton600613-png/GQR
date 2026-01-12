# Build: QGE (Quantum Geometry Engine — core)

This directory describes the **core QGE (Quantum Geometry Engine) build**:
the engine-level generalisation of the earlier GQR framework.

It abstracts geometry-gated dynamics into a **domain-agnostic engine**
suitable for constrained inference, inverse design, and multi-scale use.

No production code is present here.

---

## Purpose of this build

**QGE (core)** exists to make the framework *computable* without tying it
to any single domain (chemistry, biology, or materials).

In this build:
- geometry, boundary conditions, and constraint are first-class objects
- admissible dynamical structure is inferred without exhaustive trajectory enumeration
- domain-specific assumptions are explicitly separated from the engine

This is the **kernel nucleus** that later builds instantiate.

---

## What is generalised here

Compared to pre-QGE GQR, this build:

- removes domain-specific language and assumptions
- formalises gating, constraint propagation, and admissibility
- allows for non-minimal or effectively extended Hamiltonian representations
  as a modelling choice driven by geometry and coupling
- supports integration with outputs from MD, QM/MM, AIMD, or experiment

---

## What this build is not

- Not a force-field engine
- Not an electronic-structure code
- Not a simulation package
- Not a black-box machine-learning system

QGE is an **inference layer**, not a trajectory generator.

---

## Relationship to other builds

- **GQR (pre-QGE):** provides the conceptual and methodological foundation
  from which this engine abstraction is derived.

- **WaterGate:** instantiates QGE for water splitting and OEC-scale
  geometry-gated catalysis.

- **CopperGate:** instantiates QGE for copper-based and correlated
  quantum materials, transport, and rectification.

All domain builds share this same core engine logic.

---

## Status

Core engine abstraction (design stage).

- No public API
- No implementation guarantees
- No performance claims

This directory exists to make the **engine boundary explicit** and to
support informed technical discussion and future development.
