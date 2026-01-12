# Methods: Molecular Dynamics and Geometry-Gated Dynamics

This document situates the **Gated Quantum Resonator (GQR / QGE)** framework
within the broader family of molecular dynamics methods.

It is intended to clarify **representation, scope, and limitations**, not to
replace formal derivations or results contained in individual manuscripts.

---

## Molecular dynamics as a class of methods

*Molecular dynamics (MD)* is not a single algorithm or trade name.
It refers to a class of questions concerned with how molecular systems
evolve in time under physical constraint.

Different MD families address these questions using different
representations, approximations, and computational strategies.

---

## Classical Molecular Dynamics (MD)

### Representation
Explicit particle trajectories evolving on empirical or semi-empirical
force fields.

### Method
Time-step integration of Newton’s equations of motion for nuclei.

### Strengths
- Large system sizes
- Long simulation times near equilibrium
- Structural sampling and diffusion

### Limitations
- No explicit electronic structure
- Rare events and activated processes are difficult to access
- Mechanistic inference requires extensive sampling

---

## Quantum Mechanics / Molecular Mechanics (QM/MM)

### Representation
Classical nuclear trajectories with selected regions treated
quantum mechanically.

### Method
Hybrid embedding of quantum chemistry (often DFT) within classical MD.

### Strengths
- Enzyme active sites
- Chemical reactions in complex environments
- Bridging chemistry and biology

### Limitations
- High computational cost
- Still trajectory-based
- Sensitive to partitioning and parametrisation choices

---

## Ab Initio Molecular Dynamics (AIMD / DFT-MD)

### Representation
Classical nuclear trajectories evolving on electronic structure
potential energy surfaces.

### Method
On-the-fly electronic structure calculations, typically using DFT.

### Strengths
- Explicit electronic effects
- Small systems, short timescales
- Reaction mechanisms at high resolution

### Limitations
- Extremely limited time and length scales
- Poor access to rare, gated, or strongly constrained events

---

## Geometry-Gated Molecular Dynamics (GQR / QGE)

### Representation
Admissible **dynamical structure** defined by geometry, constraint,
and gating — not by enumerated trajectories.

### Method
Direct inference on constrained state space, identifying which
transitions are geometrically allowed, suppressed, or forced,
without integrating full trajectories.

### Strengths
- Rare-event and gated dynamics
- Strong time-scale separation
- Non-equilibrium and driven systems
- Mechanistic discrimination using partial or indirect evidence
- Complementary to atomistic simulation outputs

### Limitations
- Lower local trajectory resolution
- Not intended to replace detailed short-time simulations
- Relies on correct identification of geometric constraints

---

## Conceptual distinction

Trajectory-based methods ask:

> *“How does the system evolve if we integrate its equations of motion?”*

Geometry-gated methods ask:

> *“Which dynamical structures are admissible under constraint, and which must collapse?”*

Both approaches study molecular dynamics.
They operate at **different representational levels** and are suited
to **different classes of problems**.

---

## Relationship to standard methods

The GQR / QGE framework:
- Does **not** replace MD, QM/MM, or AIMD
- Does **not** compete with force-field or electronic-structure development
- Is designed to sit **above** trajectory enumeration as an inference layer

In practice, geometry-gated inference may:
- Use atomistic simulations as inputs
- Constrain or interpret simulation results
- Identify regimes where brute-force simulation is infeasible

---

## Relationship to decoherence and quantum theory

The GQR framework:
- Is fully compatible with standard decoherence theory
- Does not rely on long-lived macroscopic coherence
- Concerns ultrafast, geometry-gated quantum transitions
  whose outcomes are fixed prior to environmental decoherence

---

## Intended use

GQR methods are most appropriate when:
- Rare events dominate behaviour
- Geometry enforces strong selection rules
- Time-scale separation defeats brute-force simulation
- Mechanistic understanding matters more than exhaustive sampling

They are **not** intended as a general replacement for
trajectory-based molecular dynamics.

---

## One-line takeaway

> **Classical MD, QM/MM, and AIMD simulate trajectories;  
> GQR / QGE infers dynamics from geometry and constraint.**
