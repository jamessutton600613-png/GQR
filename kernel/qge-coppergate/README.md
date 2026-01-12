# Build: QGE–CopperGate (copper and correlated materials)

This directory describes **CopperGate**, a domain-specific instantiation
of the QGE (Quantum Geometry Engine) applied to copper-based and
correlated quantum materials.

It exists to test and demonstrate the QGE engine in a **materials-physics
context**, particularly where transport, rectification, and noise-robust
behaviour emerge from geometric constraint.

No production code is present here.

---

## Purpose of this build

**CopperGate** instantiates the geometry-gated inference machinery of QGE
for systems where:

- transport behaviour is conditioned by lattice geometry and constraint
- strong coupling and non-integrable dynamics limit trajectory-based approaches
- directional or rectifying behaviour emerges without external bias
- coherence is short-lived but functionally constrained

The build focuses on **geometry-conditioned transport**, not microscopic
trajectory resolution.

---

## What is instantiated here

Relative to the core QGE engine, this build introduces:

- copper-oxide and related lattice geometries
- constraint patterns relevant to correlated and anisotropic materials
- transport-relevant gating structures (directional, selective, or suppressed)
- links to experimentally accessible transport and spectroscopic signatures

All such elements are **domain-specific instantiations**, not modifications
of the core engine.

---

## What this build is not

- Not a general solid-state simulation package
- Not a replacement for DFT, DMFT, or transport solvers
- Not a claim of long-lived macroscopic coherence
- Not a materials discovery black box

---

## Relationship to other builds

- **QGE (core):** provides the domain-agnostic inference machinery
  instantiated here.

- **GQR (pre-QGE):** provides the geometry-gated framework from which
  the engine abstraction originates.

- **WaterGate:** provides a contrasting biological instantiation,
  demonstrating cross-domain portability of the engine.

---

## Where the authoritative record lives

Formal analyses and application-specific results for CopperGate are
contained in the relevant GQR / QGE manuscripts hosted on Zenodo
and ChemRxiv.

This directory documents the **materials-physics instantiation boundary**.

---

## Status

Domain instantiation (correlated materials and transport).
Active development.
