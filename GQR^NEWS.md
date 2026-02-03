## News / Updates

**3 Feb 2026**

## More news.  

### Relation between Physical Neural Networks and the GQR / QGE programme

| Aspect | Physical Neural Networks (PNNs) | GQR / QGE with AOI |
|------|--------------------------------|-------------------|
| Historical origin | Predate GQR/QGE by decades (neuromorphic systems, memristors, reservoir computing) | Developed later as a geometry-first, ordering-based framework |
| Primary goal | Perform learning or inference using physical dynamics | Identify *when and why* physical systems exhibit memory and directional computation |
| Core computational resource | Continuous physical states (voltages, currents, phases, spins) | **Ordering-sensitive accessibility** (non-commuting updates) |
| Representation of memory | Stored in physical states or effective weights | **Process memory** encoded in irreversible ordering effects |
| Dependence on training | Often requires training, tuning, or optimisation | No training required; behaviour emerges from protocol and geometry |
| Role of geometry | Usually secondary or device-specific | **Primary control variable** (sets capacity and admissible paths) |
| Role of temporal ordering | Implicit, rarely formalised | **Explicit and central** (AB vs BA protocols, AOI ≠ 0) |
| Mathematical unifier | Largely phenomenological, system-dependent | **Accessibility–Ordering Invariant (AOI)** as a falsifiable diagnostic |
| Robustness to noise / decoherence | Varies by platform | High: memory survives noise because it is not state-based |
| Typical demonstrations | Task performance (classification, prediction) | Directional asymmetry, ratcheting, history-dependent transport |
| Scope | Specific devices or architectures | **Domain-agnostic** (condensed matter, mesoscopic systems, biomolecular transport) |
| Conceptual contribution | Shows that physical systems *can* compute | Explains *why* physical systems can remember and compute at all |

**Interpretive summary:**  
Physical neural networks demonstrate *instances* of computation and memory in matter.  
The GQR / QGE programme identifies a **minimal structural principle**—ordering-sensitive accessibility—that underlies many such behaviours across disparate physical systems.

## News

**Experimental convergence on ordering-governed transport.**  
A January 2026 *Nature* study reports robust Aharonov–Bohm interference in even-denominator fractional quantum Hall states in bilayer graphene, revealing transport behaviour that depends on the **history and ordering of control protocols**, not solely on instantaneous parameters. The observed flux periodicities, effective interfering charges, and statistical phase responses vary depending on whether the system is driven at constant filling or along controlled deviations that introduce bulk quasiparticles, indicating cumulative, history-dependent effects beyond static geometry or equilibrium transport coefficients.

These findings closely align with the **Accessibility–Ordering Invariant (AOI)** and **Quantum Geometry Engine (QGE)** framework developed within the GQR programme, which predicts that **non-commuting accessibility updates** can generate directional asymmetry and physical memory without invoking new forces, modified electrodynamics, or long-lived quantum state storage. The experiments provide independent evidence that *temporal ordering itself* can act as a first-class control variable in quantum transport.

see converging fields page


**2026+02-1**
field convergence note: 
Recent experiments have demonstrated protocol-dependent control of
topological order parameters in moiré materials using time-dependent
optical driving \cite{HuberNature2026}.
Such results indicate that temporal ordering can act as an effective
control variable alongside geometry and interactions.
The AOI--QGE framework identifies a minimal, invariant-level mechanism
by which such ordering dependence can arise independently of the
microscopic implementation.

Coincides with the publishing on Zenodo of the latest two additions to the GQR programme
**GQR40 SUTTON, J. (2026). Ordered Accessibility Invariants and Non-Commutative Aggregation (PaperX). Zenodo. https://doi.org/10.5281/zenodo.18392880**
**GQR41 SUTTON, J. (2026). (Paper C): Accessibility–Ordering Invariants and Geometry-Controlled Cumulative Transport in Dirac Fluids. 
Zenodo. https://doi.org/10.5281/zenodo.18429604**



**2026-01-26**  

## Programme Update: Index Creation, Field-Convergence Reorganisation, and AOI-Driven QGE Advance

The **GQR / QGE programme** has undergone a structural consolidation to reflect the maturation, internal consistency, and cross-domain convergence of the framework.

### Programme Index Established

A canonical **Programme Index** has been created and is now linked directly from the repository front page (`README.md`). This index provides a dependency-ordered map of the full programme, explicitly distinguishing **CORE**, **FORK**, and **INCIDENTAL** contributions, and recording conceptual and methodological precursors where required.

The Programme Index is intended to serve as the authoritative entry point for readers, reviewers, and collaborators navigating the now multi-domain scope of the GQR/QGE effort.

### Field-Convergence Section Created

Material relating to **cross-domain convergence and unification** has been reorganised into a dedicated *Field Convergence* section. This separates mature, invariant-governed results from broader contextual synthesis and historical motivation, reflecting the programme’s transition from exploratory unification toward predictive, invariant-controlled structure.

### Deduplication and Chronological Correction

-  
**GQR-23 — *A Quantum-Coherent Vortex Engine Drives Water Splitting in Photosystem II*** and  
**GQR-25 — *A Quantum-Coherent Vortex Engine Drives Water Splitting in Photosystem II***  
were identified as **duplicate records of the same PSII/OEC manuscript (identical file and content)**.  
→ **GQR-23** is retained as the canonical entry; the duplicate **GQR-25** record has been removed.

-  
**GQR-18 — *Transient Directed Transport in a Minimal Time-Gated Quantum System*** has been reassigned to the **GQR-25 slot** to restore conceptual and chronological consistency within the core sequence.

These changes affect programme ordering and index clarity only; no scientific content has been altered.

### AOI as a Programme-Level Advance via Graphene-Gated QGE (GQR-36 → GQR-37–39)

The introduction of the **Accessibility–Ordering Invariant (AOI)** in

- **GQR-36 — *Time-Ordered Accessibility as a Constraint on Transport – Why Averaging Fails When Connectivity Is Transient***  
  *(CORE; Accessibility Ordering Invariant (AOI), Quantum Geometry Engine)*

provides the invariant foundation for a tightly coupled sequence of **graphene-instantiated Quantum Geometry Engine (QGE)** studies.

**GQR-37, GQR-38, and GQR-39 are all implemented within a graphene-gated QGE**, explicitly motivated by the combination of the AOI formalism introduced in GQR-36 and recent experimental reports of extreme (∼200×) Wiedemann–Franz violation in ultraclean Dirac fluids. Graphene is used throughout as the cleanest experimental realisation of ordering-sensitive transport, not as the source of the effect.

Within this block, Dirac physics functions as a diagnostic basis: it makes accessibility ordering visible, but does not generate the phenomenon.

The sequence proceeds as follows:

-  
**GQR-37 — *Invariant-Governed Quantum Geometry Engines: Ordering, Transport Decoupling, and the Limits of Zero-Dimensional Dynamics***  
*(CORE; AOI; Quantum Geometry Engine; graphene-instantiated)*  
Establishes invariant-enforced bounds and ordering-governed transport decoupling within a graphene-tuned zero-dimensional QGE, demonstrating that accessibility ordering alone is sufficient to suppress charge transport while preserving heat flow.

-  
**GQR-38 — *Invariant-Governed Mode Ordering and Extreme Wiedemann–Franz Violation in Dirac Quantum Fluids***  
*(FORK; AOI; Quantum Geometry Engine; graphene / Dirac focus)*  
Demonstrates that experimentally observed extreme Wiedemann–Franz violation in graphene arises from ordering-governed accessibility, without requiring explicit Dirac dynamics, Berry curvature, hydrodynamic closure, or material-specific scattering assumptions.

-  
**GQR-39 — *Ordering-Governed Transport Control Beyond Dirac Fluids***  
*(FORK; AOI; Quantum Geometry Engine; generalisation)*  
Generalises the graphene-instantiated AOI–QGE framework to non-Dirac materials and engineered systems, establishing ordering—not dispersion—as the controlling principle for transport decoupling.

### Programme Arc and Scope

Taken together, these works define a clear and continuous programme arc:

**geometry-gated enzymatic catalysis (GQR)**  
→ **multi-atom and zero-dimensional quantum geometry engines (QGE)**  
→ **graphene-instantiated ordering diagnostics (Dirac fluids)**  
→ **material-independent, ordering-governed transport control**

This progression demonstrates that the GQR/QGE framework is no longer domain-bound but **invariant-driven**—capable of governing transport, ordering, and coherence across biological, chemical, and condensed-matter systems.

### Status of Experimental Verification and Programme Methodology

The results reported in **GQR-37, GQR-38, and GQR-39** presently await direct experimental verification. This status is, however, fully consistent with the methodological pattern of the wider **GQR/QGE programme**.

To date, the GQR framework has not relied on bespoke experimental validation, but instead on a convergent body of evidence comprising:
(i) cross-domain field convergence,
(ii) consistency with and explanatory unification of existing experimental literature,
(iii) the absence of competing frameworks capable of resolving the same anomaly set,
(iv) internally consistent mathematical formalism,
(v) **the discovery of multiple invariant principles and standalone physics results (e.g. GQR-25, GQR-36)**, and
(vi) in-program constructive outputs whose behaviour suggests physical realism while remaining falsifiable.

Within this methodology, confidence accrues not from isolated prediction, but from the repeated ability of the framework to resolve long-standing anomalies across unrelated domains.

The present AOI–QGE results follow this same pattern. In particular, **Dirac fluids—previously resistant to tractable modelling of extreme Wiedemann–Franz violations—become systematically modellable** once transport is treated as an ordering-governed accessibility problem rather than a dispersion-governed one. Notably, this resolution does **not** require the deployment of explicit Dirac mathematical physics, hydrodynamic closure, or material-specific scattering models.

This is a deliberate and enabling feature of the framework: by remaining **geometry-first, invariant-governed, and lightweight**, the Quantum Geometry Engine retains speed, flexibility, and cross-domain applicability, while producing concrete, experimentally testable predictions that now await targeted verification.





**2026-01-19**  

### Newly released from pre-GQR (mid 2025) personal archives.

Two manuscripts (with alts, relateds) arising from the **Germinal Centre (GC)** research stream that became my two github (GQR and GC) communities, are now available.  

**The Quantum-Classical Tumbling Locomotion (QC-TCL) Hypothesis**  
DOI: https://doi.org/10.5281/zenodo.18299933  
A unifying biological framework proposing that **geometry-constrained tumbling, pivoting, and cyclic motion** underlies catalysis, self-assembly, and biological selection, without invoking long-lived quantum coherence.

Together, this selection of  related manuscripts explore how **thresholds, geometry, and constrained motion** shape immune and biochemical outcomes — concepts central to germinal centre dynamics, affinity maturation, and immune decision-making.

This work represents a **mechanistic bridge between early biochemical intuition and later geometry-first quantum formalism**.

**6D Rotary Engines: A Mechanistic Framework for Simplification of Delocalised π-Electron Catalytic Mechanisms**  
DOI: https://doi.org/10.5281/zenodo.18300110  
The paper introduces rotary, pivoting, and tethered geometries as a means of simplifying complex delocalised electronic behaviour, using Fourier-resolved wave amplification and geometry-gated tunnelling pathways.

## 📜 Why These Historical Drafts Are Being Released

These manuscripts are released in their historical form because they capture the **biological and biochemical reasoning layer that preceded formal physics (including Hamiltonians...), mathematical, and computer-science abstraction** within the wider programme.

They may be of assistance to readers because they:

- Show how problems were **first framed biologically**, before reduction into equations or code  
- Preserve **mechanistic intuitions** (geometry, thresholds, motion, lag) often lost after formalisation  
- Provide **conceptual entry points** for domain experts outside quantum physics or computational modelling  
- Document the **evolution of ideas**, not just their final filtered expressions  

These drafts are therefore not superseded.  
They are **foundational context**, explaining why later physics-, mathematics-, and code-level models took the form they did.



**2026-01-18**  

two highly relevant articles this week:

## GQR News — Topological Leaky Transport as Geometry-Gated Readout (Jan 2026)

**Recent experimental work in 1 (published 12 January 2026)** reports an on-chip *topological leaky-wave antenna* based on valley photonic crystals, demonstrating that **topologically protected transport and controlled radiation leakage can coexist within a single geometry-defined structure** [1].

Rather than treating radiation as an undesirable loss, the authors intentionally exploit **conical leakage from topological edge states** to achieve wide-angle beam scanning, frequency-division multiplexing, and bidirectional on-chip ↔ free-space coupling at terahertz frequencies. Crucially, emission directionality and robustness are governed primarily by **lattice geometry and boundary topology**, rather than fine-tuned material parameters or active electronic control.

This result is directly relevant to the **Gated Quantum Resonator (GQR)** programme, particularly:

- **GQR-XIV** — *Dynamic Proof of Geometry-Gated Transport*:  
  The reported device provides a photonic analogue of **geometry-gated transport**, where information flow is constrained by curvature and boundary conditions prior to energetic optimisation.

- **GQR-XV / GQR-XVI** — *Leakage as Readout, Not Loss*:  
  The use of structured topological leakage as a functional output channel aligns with the GQR view that **dissipation and emission can act as deterministic readout surfaces** rather than failure modes.

- **GQR-XXVII** — *Directional and Bidirectional Interfaces*:  
  The demonstrated time-reversal-symmetric bidirectional coupling (simultaneous transmission and reception without reconfiguration) supports the GQR position that **robust interfaces between protected internal dynamics and classical environments do not require long-lived macroscopic coherence**.

Overall, this work constitutes an **experimental photonic validation by analogy** of key GQR principles: geometry-first control, gated release of protected dynamics, and the reinterpretation of leakage as structured signal rather than noise.

---

### Reference
[1] W. Wang, Y. J. Tan, P. Szriftgiser, G. Ducournau, R. Singh,  
*On-chip topological leaky-wave antenna for full-space terahertz wireless connectivity*,  
**Nature Photonics** (2026).


## Secondly....the wormhole bridge side of GQR:

Since initial deposition, several independent works have appeared that clarify the
interpretation of Einstein–Rosen (ER) bridges as effective, non-classical structures
that do not correspond to traversable spacetime wormholes.

In particular, Gaztañaga et al. (Class. Quantum Grav. 43 (2026) 015023) provide a
reformulation of ER bridges as mathematical and geometric identifications in
Hilbert space, associated with discrete symmetries, superselection sectors, and
unitarity restoration in quantum field theory in curved spacetime. In this
framework, connectivity does not imply transport, and no exotic matter or
energy-condition violations are required.

These developments are conceptually compatible with the Gated Quantum Resonator
(GQR) framework, in which non-thermal transport arises only under resonance-gated
curvature conditions, and effective “bridge-like” behaviour appears in coherence
space rather than as a spacetime shortcut.  See SUTTON, J. (2026). GQR–XIV: Dynamic 
Proof of the 8F4I Quantum-Critical State as a Gated "Einstein–Rosen" Bridge. Zenodo. 
https://doi.org/10.5281/zenodo.18130489

***Relevant external reference:***
• E. Gaztañaga et al., “A new understanding of Einstein–Rosen bridges”,
  Classical and Quantum Gravity 43 (2026) 015023.
  https://doi.org/10.1088/1361-6382/ae3044

This description field is maintained as a living contextual note documenting
convergent developments across disciplines. It does not modify the original
manuscript and makes no claims of derivation or priority.



**2026-01-13**  
Two new manuscripts within the GQR / Quantum Geometry Engine (QGE) programme have been submitted for peer review:

- *The Shield Law: Curvature–Coherence Invariance in a Vibronically-Gated Five-Centre Quantum System* (GQR) — submitted to **F1000Research** for open-access peer review.  
  The decision to submit this work to F1000Research reflects the cross-disciplinary nature of the framework. The geometry-first approach does not align cleanly with the established scope boundaries of many specialist physics journals, which are necessarily selective and risk-aware in their remit. Open peer review was therefore chosen to enable transparent evaluation without constraining the work to a single disciplinary silo.

In addition, the standalone physics manuscript occupying the honorary **GQR18** slot,

- *Transient Directed Transport in a Minimal Time-Gated Quantum System*, is also submitted to a Physics journal for peer review,

is included here as a related contribution. This work is not formally part of the GQR series and represents a self-contained physics study that informed later geometry-first developments. It is referenced for conceptual continuity only and is intended to be evaluated independently, without reliance on the broader GQR programme. A dedicated physics repository is planned for such standalone works.

More broadly, there is no evidence of any conspiracy or intentional suppression of drug discovery. What likely occurred instead was a structural delay. Following widely cited decoherence arguments, quantum effects in biology became rhetorically bundled with speculative claims, making otherwise orthodox quantum-chemical phenomena less attractive to frame explicitly. At the same time, drug discovery incentives favoured approaches that scaled immediately within established pipelines, while geometry-gated, ultrafast transition mechanisms remained fragmented across disciplines.

In hindsight, this likely delayed the systematic exploitation of such mechanisms by approximately 10–20 years. The impact would have been most pronounced for drug classes in which catalytic geometry, reaction-path control, or transient electronic reorganisation dominate function, including enzyme inhibitors targeting metalloenzymes, redox-active therapeutics, proton-coupled electron transfer systems, covalent and time-dependent inhibitors, allosteric modulators, and drugs acting on highly dynamic or flexible active sites. These classes align closely with the primary targets of the GQR/QGE framework, where curvature-controlled coherence and selection-before-decoherence effects are expected to play a functional role.

This pattern is consistent with earlier historical delays in the acceptance and exploitation of enzyme tunnelling, allostery, protein dynamics, cryo-EM, and mRNA technologies, suggesting structural conservatism rather than malice as the dominant cause.

Dates and links will be updated as peer review progresses.
