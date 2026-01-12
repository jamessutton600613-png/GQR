# Gated Quantum Resonator (GQR) Programme

The **Gated Quantum Resonator (GQR)** programme is a geometry-first framework
for molecular and quantum dynamics.

It reformulates molecular dynamics by inferring **admissible dynamical structure**
from geometry, gating, and constraint, rather than enumerating exhaustive
particle trajectories.

This repository serves solely as a **navigation and orientation hub**
for a multi-manuscript research programme.
Authoritative, citable records are maintained on ChemRxiv and Zenodo.

---

## Repository structure and entry points

This is a live research programme under active development.
Readers are **not expected to read everything**.

- 📍 [How to read the GQR programme](docs/entry-points.md)
- 🧠 [Conceptual intuition and analogies](CONCEPTS.md)
- ⚙️ [Methods: molecular dynamics and geometry-gated dynamics](METHODS.md)
- 🧩 [Kernel design (geometry-first, model-agnostic)](kernel/README.md)

---

## Scope and compatibility

The GQR framework:
- Does **not** invoke long-range quantum coherence, macroscopic superposition,
  or sustained entanglement in biological systems
- Is fully compatible with standard decoherence theory
- Concerns ultrafast, geometry-gated quantum transitions whose outcomes are
  fixed prior to environmental decoherence
- In some applications, the effective Hamiltonian dimensionality is **unusual or extended**
  as a consequence of geometric constraint, coupling, or coarse-grained representation.
  This does not imply new quantum postulates, but reflects a modelling choice appropriate
  to geometry-gated and multi-centre systems.

---

## Archival record

- ChemRxiv: https://chemrxiv.org/engage/chemrxiv/search-dashboard?authors=James%20R%20F%20SUTTON
- Zenodo: https://zenodo.org/communities/gqr/records

  
For citation and long-term reference, please use the DOI-linked records.



## Addendum: Field Convergence and Context (Living List)

### Why this section exists

The Gated Quantum Resonator (GQR) programme spans multiple domains
(quantum physics, photonics, materials science, chemistry, and biology)
and advances a **geometry-first, constraint-driven view of physical dynamics**.

While individual GQR manuscripts contain focused reference lists appropriate
to their immediate scope, such article-level references do **not capture broader
field movements** that are relevant to GQR but may not yet be directly cited,
formally unified, or explicitly framed in compatible language by their original authors.

This section exists to record **independent, contemporaneous developments**
that converge on core GQR intuitions, even where those works:

- do not reference GQR,
- are framed conservatively or instrumentally,
- or fall outside the immediate scope of any single manuscript.

This is **context**, not authority-stacking.

---

### Why this list is separate from manuscript references

Journal articles require **tight, localised citation discipline**.
Research programmes require **longitudinal awareness of field shifts**.

Many results relevant to GQR are editorially orthogonal to any single paper,
yet programmatically central when viewed together.
Capturing such convergence inline within articles is often inappropriate or impractical.

This addendum therefore functions as:

- a **programme-level memory**,
- a **navigation aid for editors and reviewers**, and
- a record of **where the field is quietly moving**, regardless of terminology.

---

### Status of the list (important)

This list is **intentionally short**.

It is newly introduced (2025) and will grow **incrementally and conservatively**.
Entries are added only where a work demonstrates clear, independent alignment with
GQR-relevant concepts, such as:

- geometry- or boundary-condition-dominated dynamics,
- outcome selection without reliance on long-lived coherence,
- self-configuration or constraint-driven optimisation,
- non-kinetic or non-trajectory-first mechanisms.

Inclusion here **does not imply endorsement, reinterpretation, or claimed equivalence**
with GQR. It indicates **conceptual relevance**, not identity.

---

### Independent field movements relevant to GQR (non-exhaustive)

- **Self-configuring, geometry-driven optical transformations**  
  Rocha *et al.* demonstrate that complex multi-plane optical transformations
  can be physically learned and stabilised *in situ*, without offline inverse
  Hamiltonian design, via hardware-embedded optimisation.  
  *Relevance to GQR:* supports geometry-first, boundary-condition-driven outcome
  selection in real, noisy systems without reliance on long-lived coherence.  
  **Reference:**  
  José C. A. Rocha *et al.*, *Self-configuring high-speed multi-plane light conversion*,
  **Nature Communications** (2025).  
  DOI: https://doi.org/10.1038/s41467-025-66798-2

- **Cryogenic self-healing via internal field minimisation**  
  Ding *et al.* report autonomous structural and optical self-healing in an organic
  crystal down to liquid-nitrogen temperatures, driven by dipolar and energy-landscape
  effects rather than thermal diffusion.  
  *Relevance to GQR:* undermines kinetics-first assumptions and supports
  non-Arrhenius, constraint-dominated pathways consistent with geometry-gated
  transition selection.  
  **Reference:**  
  Chengde Ding *et al.*, *Cryogenically self-healing organic crystals*,
  **Nature Materials** (2025).  
  DOI: https://doi.org/10.1038/s41563-025-02411-7

- **Constraint-selected multidimensional nonlinear wave structures**  
  Dieli *et al.* report the first experimental observation of lump solitons,
  long-predicted multidimensional solutions of integrable nonlinear equations,
  stabilised by global constraints rather than trajectory tracking.  
  *Relevance to GQR:* illustrates how geometry and integrability can pre-select
  allowed outcomes in complex systems, independent of microscopic noise.  
  **Reference:**  
  Ludovica Dieli *et al.*, *Observation of lump solitons*,
  **Physical Review Letters** (2025).  
  DOI: https://doi.org/10.1103/ggbs-y21w

---

### How to read this section

This list should be read as:

- **programme context**, not a claim of priority;
- **evidence of convergence**, not proof by accumulation;
- a **living map**, not a closed bibliography.

Readers interested only in a specific manuscript should rely on that manuscript’s
references. Readers interested in the broader intellectual positioning of GQR
may find this section useful.
