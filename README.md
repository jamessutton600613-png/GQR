# Gated Quantum Resonator (GQR) Programme

The **Gated Quantum Resonator (GQR)** programme is a geometry-first framework
for molecular and quantum dynamics.

It reformulates molecular dynamics by inferring **admissible dynamical structure**
from geometry, gating, and constraint, rather than enumerating exhaustive
particle trajectories.

## Encouraging Results (Provisional)

Encouraging results have been obtained from applying the GQR framework to
high-resolution crystal structures across several well-characterised
systems, including:

- The oxygen-evolving complex (OEC) of photosystem II  
- Enzymes containing Fe–S clusters  
- YBCO (YBa₂Cu₃O₇₋ₓ) superconducting materials  

In each case, the analysis focuses on experimentally resolved geometries and
their role in constraining quantum-allowed transitions during bond formation,
electron transfer, or coupled multi-centre dynamics.

These results are derived from established structural data and standard
quantum-chemical formalisms, with GQR providing a geometry-conditioned
representation of the accessible transition space. No assumptions of
long-range coherence, macroscopic superposition, or sustained entanglement are
required.

The reported findings should be regarded as **provisional** and are currently
undergoing peer review. Further validation, independent replication, and
critical assessment will determine their scope and limitations.

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

“All physical claims remain within standard quantum chemistry; the framework introduces no new observables, operators, or postulates.”


- Does **not** invoke long-range quantum coherence, macroscopic superposition, nor sustained entanglement in biological systems

- Is fully compatible with standard decoherence theory

- Concerns ultrafast, geometry-gated quantum transitions whose outcomes are
  fixed prior to environmental decoherence

- In some applications, employs effective Hamiltonians of higher or unusual dimensionality, arising from geometric constraint, multi-centre coupling, or coarse-grained representations.
This reflects a modelling and representation choice, not new quantum postulates or modifications of quantum mechanics, and is standard practice when reducing or embedding geometry-conditioned subspaces.

---

## Archival record

- ChemRxiv: https://chemrxiv.org/engage/chemrxiv/search-dashboard?authors=James%20R%20F%20SUTTON
- Zenodo: https://zenodo.org/communities/gqr/records

  
For citation and long-term reference, please use the DOI-linked records.

## Addendum: Field Convergence and Context (Living List)

### Purpose of this section

The Gated Quantum Resonator (GQR) programme advances a **geometry-first,
constraint-driven perspective on physical dynamics** across quantum physics,
photonics, materials science, chemistry, and biology.

Individual journal articles necessarily operate within **tight, localised
scopes** and employ narrowly focused reference lists. Research programmes,
by contrast, mature through **contextual accumulation**: the comparison of
independently obtained results that reveal consistent structural patterns
across domains.

This section exists to document such **independent convergence**, even where
the original works:
- do not reference GQR,
- are framed conservatively or instrumentally,
- or fall outside the scope of any single manuscript.

The aim is **programme-level synthesis**, not substitution for article-level
demonstration.

---

### On contextual accumulation

Entries listed here are not presented as isolated proofs. They function as
**contextual support**, indicating where multiple, conservative lines of
research independently converge on ideas central to GQR, including:

- geometry- or boundary-condition-dominated dynamics,
- outcome selection without reliance on long-lived coherence,
- self-configuration and constraint-driven optimisation,
- non-kinetic or non-trajectory-first mechanisms.

Such accumulation is the standard mechanism by which broader physical
frameworks emerge and stabilise over time.

---

### Structure of the list

- Entries are listed **chronologically by publication year**.
- The list is **living**; numbering may change as earlier or intervening
  works are added.
- Inclusion indicates **conceptual relevance**, not endorsement,
  reinterpretation, or claimed equivalence with GQR.

---

### Independent field movements relevant to GQR (chronological)

1. **Constraint-selected multidimensional nonlinear wave structures (2025)**  
   Dieli *et al.* report the first experimental observation of lump solitons,
   long-predicted multidimensional solutions of integrable nonlinear equations,
   stabilised by global constraints rather than trajectory tracking.  
   *Relevance to GQR:* demonstrates how geometry and integrability conditions
   can pre-select stable outcomes in complex systems, independent of microscopic
   noise or detailed trajectory control.  
   **Reference:**  
   Ludovica Dieli *et al.*, *Observation of lump solitons*,  
   **Physical Review Letters** (2025).  
   DOI: https://doi.org/10.1103/ggbs-y21w

2. **Self-configuring, geometry-driven optical transformations (2025)**  
   Rocha *et al.* demonstrate that complex multi-plane optical transformations
   can be physically learned and stabilised *in situ*, without offline inverse
   Hamiltonian design, via hardware-embedded optimisation.  
   *Relevance to GQR:* supports geometry-first, boundary-condition-driven outcome
   selection in real, noisy systems, and illustrates physical self-configuration
   without reliance on long-lived coherence.  
   **Reference:**  
   José C. A. Rocha *et al.*, *Self-configuring high-speed multi-plane light conversion*,  
   **Nature Communications** (2025).  
   DOI: https://doi.org/10.1038/s41467-025-66798-2

3. **Cryogenic self-healing via internal field and energy-landscape minimisation (2025)**  
   Ding *et al.* report autonomous structural and optical self-healing in an
   organic crystal down to liquid-nitrogen temperatures, driven by dipolar and
   energy-landscape effects rather than thermal diffusion.  
   *Relevance to GQR:* undermines kinetics-first assumptions and supports
   constraint-dominated, non-Arrhenius pathways consistent with geometry-gated
   transition selection.  
   **Reference:**  
   Chengde Ding *et al.*, *Cryogenically self-healing organic crystals*,  
   **Nature Materials** (2025).  
   DOI: https://doi.org/10.1038/s41563-025-02411-7

---

### How to read this section

This section should be read as:
- **programme context**, not a claim of priority;
- **accumulated support**, not a single decisive argument;
- a **living map of convergence**, not a closed bibliography.

Readers concerned only with the validation of a specific result should rely
on the references within the relevant manuscript. Readers interested in the
broader intellectual positioning of the GQR programme may find this section
useful.
