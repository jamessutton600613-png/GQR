# Build: QGE–WaterGate (water splitting and OEC)

This directory describes **WaterGate**, a domain-specific instantiation
of the QGE (Quantum Geometry Engine) applied to water splitting and
Photosystem II (PSII)–scale catalytic systems.

It exists to test and demonstrate the QGE engine in a **biological
and enzymatic context** without introducing biology-specific postulates
into the core engine.

No production code is present here.

---

## Purpose of this build

**WaterGate** instantiates the geometry-gated inference machinery of QGE
for systems where:

- catalytic function is enforced by strong geometric constraint
- rare, gated quantum transitions dominate mechanism
- electronic, vibrational, and protonic degrees of freedom are tightly coupled
- classical trajectory-based sampling is insufficient

The build focuses on *mechanistic discrimination*, not brute-force simulation.

---

## What is instantiated here

Relative to the core QGE engine, this build introduces:

- water- and oxygen-evolving–relevant geometric constraints
- multi-centre gating structures characteristic of the OEC
- coupling patterns relevant to proton, electron, and vibronic transfer
- experimental consistency checks drawn from spectroscopy and isotope effects

All such elements are **domain-specific instantiations**, not changes to
the engine itself.

---

## What this build is not

- Not a general biology model
- Not a claim of macroscopic quantum coherence in photosynthesis
- Not a replacement for QM/MM or AIMD studies of PSII
- Not a standalone enzymology simulator

---

## Relationship to other builds

- **QGE (core):** provides the domain-agnostic inference machinery
  instantiated here.

- **GQR (pre-QGE):** provides the framework context and early
  catalytic motivation for this instantiation.

- **CopperGate:** provides a contrasting materials-physics instantiation,
  demonstrating engine portability across domains.

---

## Where the authoritative record lives

Formal analyses, evidence, and application-specific results for WaterGate
are contained in the relevant GQR / QGE manuscripts hosted on ChemRxiv
and Zenodo.

This directory exists to document the **instantiation boundary**.

---

## Status

Domain instantiation (biological catalysis). Active development.
