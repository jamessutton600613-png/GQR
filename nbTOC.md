# QGE / AOI Programme — Annotated Notebook Pipeline Index 

29 Mar 2026








earlier draft (incomplete) This file is a working index of programme notebooks.

## 🔍 Quick Lookup

| Concept | Notebook |
|--------|---------|
| TDSE dynamics | 274 |
| Curvature (κ) | 252 / 273 |
| Δteeth observable | 273 |
| AOI channels | Gauge atlas |
| Ladder / defects | Floquet notebook |
| Fracture (S/H) | 322 |
---


For each notebook:
- **Purpose** = what it is for
- **Inputs** = files / structures / prior outputs needed
- **Outputs** = figures / CSV / NPZ / metrics produced
- **Depends on** = earlier notebooks or concepts
- **Feeds into** = later notebooks / papers
- **Status** = exploratory / core / paper / archive

## 178 — TPU Evolution Model
**Purpose:** Agent-based RNA / protoribosome evolution model with damage, repair, survival, checkpointing.  
**Inputs:** Simulation parameters, checkpoint directory, random initial population state.  
**Outputs:** Pickle checkpoints, pandas tables, population plots, RNA-damage plots.  
**Depends on:** None obvious; standalone early system.  
**Feeds into:** Conceptual AOI / selection-language background only.  
**Status:** Exploratory foundation.  
**Notes:** Useful as an early admissibility / survival analogue, but not a core physics notebook.

---

## 252 — Fe–S Cluster Base Model
**Purpose:** Initial real-system Fe–S geometry pipeline.  
**Inputs:** CIF file (notably 6LK1), PySCF, gemmi.  
**Outputs:** Cluster extraction, SCF density, curvature PDF, HOMO cloud plots, breathing proxy plots.  
**Depends on:** Real structural data.  
**Feeds into:** 253–260, 273, 332.  
**Status:** Core geometry foundation.  
**Notes:** First real geometry-to-curvature notebook. Keep as origin of the Fe–S line.

---

## 253–260 — Fe–S Pipeline Expansion
**Purpose:** Extend Fe–S curvature workflow toward comparison and comb / ladder analysis.  
**Inputs:** CIF structures, cluster definitions, SCF density outputs.  
**Outputs:** Histograms, PDFs, comparisons, early Δteeth-style observables.  
**Depends on:** 252.  
**Feeds into:** 259–260, 273, 332–333.  
**Status:** Transitional core.  
**Notes:** This is the development corridor where the observable begins to stabilise.

---

## 259–260 — Fe–S Refinement / Validation
**Purpose:** Improve cluster handling, compare active / inhibited or alternate structures.  
**Inputs:** Multiple Fe–S structures, refined cluster criteria.  
**Outputs:** Comparative curvature / trap metrics, more robust observable extraction.  
**Depends on:** 252–258.  
**Feeds into:** 273, 332, 333.  
**Status:** Core comparative layer.  
**Notes:** Worth tagging structure-by-structure in future.

---

## 273 — Shear / Distortion Engine
**Purpose:** Controlled Fe–S distortion notebook.  
**Inputs:** CIF registry, structure files, PySCF, CuPy, gemmi.  
**Outputs:** Base vs shear SCF runs, GPU Laplacian, HOMO density, NPZ saveouts.  
**Depends on:** 252–260.  
**Feeds into:** 273 Δteeth blocks, 332, 333.  
**Status:** Core perturbation engine.  
**Notes:** One of the most important real-system notebooks.

### 273A — Δteeth Measurement Blocks
**Purpose:** Define and compute the trap-count observable.  
**Inputs:** NPZ outputs from 273.  
**Outputs:** Δteeth vs Δr curves, composite plots.  
**Depends on:** 273.  
**Feeds into:** 332, 333, paper figures.  
**Status:** Core observable layer.  
**Notes:** This should probably be split conceptually from 273 in the index, even if still in one file.

---

## 274 — OEC / TDSE Engine
**Purpose:** Hamiltonian-based time evolution for OEC / PSII-like systems.  
**Inputs:** CIF structures, extracted coordinates, Hamiltonian parameters.  
**Outputs:** TDSE propagation, coupling g, decoherence γ, comparator vs QGE grids, per-structure maps.  
**Depends on:** Structural extraction logic.  
**Feeds into:** OEC runner notebooks, AOI–dynamics bridge, possible Schr/Heis bridge work.  
**Status:** Core dynamics notebook.  
**Notes:** This is the main Schrödinger-side dynamics layer in the real-physics stack.

---

## Paper 4 Gauge Atlas Notebook
**Purpose:** Channel-level AOI / ordering formalism.  
**Inputs:** Model parameters for gauge mixing, Kraus definitions, noise model, CVXPY / SDP setup.  
**Outputs:** Choi matrices, diamond distances, delta maps, qa/qb maps, atlas NPZ / PNG outputs.  
**Depends on:** Channel formalism, Kraus / Choi machinery.  
**Feeds into:** Fracture / ordering formalism, AOI channel theory, possible Fe–S bridge.  
**Status:** Advanced core formal notebook.  
**Notes:** This is effectively the channel / Heisenberg-facing layer.

---

## Floquet / AOI Paper Recreation Notebook
**Purpose:** Main toy AOI ladder / defect-law notebook.  
**Inputs:** Internal toy model definitions, λ sweeps, scaffold choice.  
**Outputs:** Branch index, missing-rung counts, D₀(n), residual defect laws, hysteresis CSV / NPZ / figures.  
**Depends on:** AOI toy formalism.  
**Feeds into:** Floquet / AOI paper, defect-law figures, programme-level theory.  
**Status:** Paper-core notebook.  
**Notes:** One of the cleanest theory-to-figure pipelines.

---

## 321 — Affine Bloch Admissibility
**Purpose:** Explore affine qubit-map admissibility.  
**Inputs:** Time-dependent affine parameters.  
**Outputs:** Cone margin maps, admissibility boundaries, predicted vs exact margin, S/G/K decomposition.  
**Depends on:** None external.  
**Feeds into:** 322, fracture theory.  
**Status:** Exploratory-core.  
**Notes:** Messier than 322, but important for physical intuition.

---

## 322 — Schrödinger–Heisenberg Gap Model
**Purpose:** Reduced non-commuting model for divisibility fracture.  
**Inputs:** Reduced map definitions (e.g. D·R vs R·D style structure).  
**Outputs:** Gap field Δ(s,t), boundary curves, fracture bands, ridge / ladder structure.  
**Depends on:** 321 conceptually.  
**Feeds into:** Divisibility-fracture theory, AOI / ladder unification.  
**Status:** Core-theory notebook.  
**Notes:** Cleanest fracture notebook. Probably the main formal entry point for that branch.

---

## 323 — Honeycomb AOI Transport
**Purpose:** Graphene / honeycomb ordered transport model.  
**Inputs:** Graph construction, protocol parameters, width / frequency choices.  
**Outputs:** AOI transport observables, frequency sweeps, width dependence, folded residual structure.  
**Depends on:** AOI transport formalism.  
**Feeds into:** 324, transport paper.  
**Status:** Core model-system notebook.  
**Notes:** First proper physical-style AOI lattice system.

---

## 324 — Dense Sweeps / Ladder Figures
**Purpose:** Paper-building continuation of 323.  
**Inputs:** 323 model plus larger parameter sweeps.  
**Outputs:** Multi-width phase sheets, residual ladder figures, controls, paper-ready plots.  
**Depends on:** 323.  
**Feeds into:** Transport paper and supplement.  
**Status:** Paper-assembly notebook.  
**Notes:** Use this as the publication-facing notebook for the graphene branch.

---

## 327 — Fusion Geometry Engine
**Purpose:** Exact seam-topology and tiling geometry comparisons.  
**Inputs:** Tiling definitions, ROI choices, pitch settings.  
**Outputs:** Seam metrics, entropy, orientation histograms, geometry comparisons.  
**Depends on:** None external.  
**Feeds into:** 329, fusion report / paper.  
**Status:** Core geometry method.  
**Notes:** Distinct branch; not an AOI ladder notebook.

---

## 328 — Phase Sheet Analysis
**Purpose:** Secondary analysis of phase-sheet / ridge complexity.  
**Inputs:** Outputs from graphene / sweep notebooks.  
**Outputs:** Ridge detection, contour crossings, complexity metrics.  
**Depends on:** 323–324.  
**Feeds into:** Supplementary analysis.  
**Status:** Analysis notebook.  
**Notes:** Bridge notebook rather than a main pipeline root.

---

## 329 — Fusion Pipeline Production Notebook
**Purpose:** Reproducible fusion workflow and figure export.  
**Inputs:** 327 geometry engine outputs.  
**Outputs:** Tables, figures, report assets.  
**Depends on:** 327.  
**Feeds into:** GQR-49 / fusion writeup.  
**Status:** Paper / production notebook.  
**Notes:** Treat as the polished continuation of 327.

---

## 331 — Data Aggregation / Panel Builder
**Purpose:** Aggregate outputs and build figure panels.  
**Inputs:** CSV / NPZ / SVG / saved runs.  
**Outputs:** Combined panels, summary graphics, comparative layouts.  
**Depends on:** Prior saved outputs.  
**Feeds into:** 332 and paper figures.  
**Status:** Utility + analysis.  
**Notes:** Important for figure assembly, not a conceptual root notebook.

---

## 332 — DFT Ladder Pipeline
**Purpose:** Full electronic-structure-to-ladder extraction workflow.  
**Inputs:** Structures, PySCF runs, curvature fields, histogram definitions.  
**Outputs:** Ladder / teeth extraction, distortion sweeps, harmonic / staircase tests.  
**Depends on:** 252–273, 331.  
**Feeds into:** 333 and related papers.  
**Status:** Core real-system ladder notebook.  
**Notes:** Major milestone notebook.

---

## 333 — Trap Topology / CAT1
**Purpose:** Move from histogram peaks to topological trap objects.  
**Inputs:** Curvature fields from prior Fe–S / DFT runs.  
**Outputs:** Positive / negative trap masks, connected-component counts, collapse-style observables.  
**Depends on:** 332.  
**Feeds into:** Topological observable papers / figures.  
**Status:** Core observable-topology notebook.  
**Notes:** Very important conceptual upgrade.

---

## 334 — AOI Field / Supersolid Toy
**Purpose:** Field-theory-style AOI pattern-forming model.  
**Inputs:** AOI field parameters, scaffold terms, nonlinear update rules.  
**Outputs:** Ordered/coherent field structures, toy supersolid-like behaviour.  
**Depends on:** AOI field concepts.  
**Feeds into:** Mechanism / theory branch.  
**Status:** Mechanism notebook.  
**Notes:** Explanatory rather than directly fitted to experiment.

---

## OEC Batch Runner Notebook
**Purpose:** Large-scale multi-CIF TDSE batch execution.  
**Inputs:** CIF directory, condition registry, Hamiltonian settings.  
**Outputs:** Per-run CSVs, master CSV, water-population tracking.  
**Depends on:** 274.  
**Feeds into:** Phase-trend and OEC aggregate analysis.  
**Status:** Core batch-application notebook.  
**Notes:** This is the production runner for the OEC / PSII line.

---

## H2O / Phase Trend Enrichment Notebook
**Purpose:** Enrich master OEC results with phase / time metadata and trend summaries.  
**Inputs:** Master CSV from batch runner.  
**Outputs:** Enriched master table, H2O trend table, S-state-aligned summaries.  
**Depends on:** OEC batch runner.  
**Feeds into:** OEC analysis and figures.  
**Status:** Analysis notebook.  
**Notes:** Aggregation layer, not primary simulation engine.

---

# Quick Lookup

| Task | Best Notebook |
|------|---------------|
| Real Fe–S geometry start | 252 |
| Fe–S perturbation / shear | 273 |
| Δteeth observable | 273A / 332 / 333 |
| Real-system quantum dynamics | 274 |
| Channel / Choi / diamond norm | Gauge Atlas |
| Toy ladder / defect law | Floquet recreation |
| Affine admissibility | 321 |
| Clean fracture model | 322 |
| Honeycomb AOI transport | 323 |
| Dense transport figures | 324 |
| Fusion tiling | 327 / 329 |
| OEC batch runs | OEC batch runner |
| OEC phase summaries | H2O enrichment |

---

# Suggested Future Metadata To Add

For each notebook, later add:
- exact filename
- last known good run date
- main output folder
- whether figures are still used in a paper
- whether superseded by a later notebook
