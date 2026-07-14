# QGE / AOI Programme — Annotated Notebook Pipeline Index 


14 Jul 2026
 noting:  Based on reading through notebooks 211–220, I'd organise the table of contents like this. This is necessarily approximate because many notebooks contain successive revisions rather than a single clean project, but the progression is clear.

Notebook	Approx. GQR	Main purpose	Status

211	GQR7	Electron/proton distance laws. Gray–Winkler and Masgrau fits. Exponential tunnelling curves. Effective velocity concept. Initial GQR vs QM comparisons. First shield-law ideas. 	Foundation
212	GQR8	First OEC hydration engine. Shield Law . TyrZ energy sweeps. Dry vs hydrated OEC. Static plots and animations. 	OEC model v1
213	GQR8–9	First genuine TDSE calculations. Split-operator propagation. Barrier tunnelling datasets. Transmission heatmaps. Beginning of amplituhedron/OEC geometry work. 	TDSE prototype
214	GQR9	Provenance system. NPZ checkpoints. Reproducibility. Coloured k(d) plots. TDSE visualisation improvements. Parameter tracking. 	Validation infrastructure
215	GQR9–10	Real 3WU2 extraction using Gemmi. Automatic OEC cubane identification. Water assignment. First realistic structural models. GQR-TDSE coupling begins. 	Structural engine
216	GQR10	GPU/CuPy TDSE. Split-operator propagation. Absorbing boundaries. Movies. Overnight simulation framework. Resume/checkpoint capability. 	Production TDSE
217	GQR10–11	Fixed-geometry OEC TDSE. Movie generation. Population dynamics. Cached geometry. Hamiltonian refinement. Publication-quality figures. 	Publication engine
218	GQR11	Simplified OEC graph representation. NetworkX geometry. GPU propagation skeleton. Publication schematic figures. 	Diagramming/support
219	GQR11–12	Manuscript figure regeneration. Static hydration figures. Shield phase-space diagrams. Coherent-zone graphics. Final publication plotting. 	Figure production
220	GQR12	Core GQR Hamiltonian. Explicit TDSE propagator. 7-, 12- and 16-site OEC models. μ-oxo bridges. Water network. Population histories. Heatmaps. Final proof-of-principle quantum engine. 	Core quantum model


Overall evolution

211 — transport laws and distance scaling.

212 — Shield Law and hydration physics.

213 — first TDSE implementation.

214 — validation and provenance.

215 — realistic PSII structural extraction.

216 — scalable GPU TDSE.

217 — production OEC simulation engine.

218 — schematic and graph representations.

219 — publication figure generation.

220 — complete Hamiltonian/TDSE framework with increasingly realistic OEC models.


I think this is a good high-level TOC for your archive. I'd put my confidence at around 90–95%. The notebooks overlap substantially because each one builds on the previous rather than starting fresh, but this captures the main development milestones.

Based on the notebooks we've examined (220 plus the surrounding notebooks) and the notebook evolution, here's the TOC I'd recommend for 221–240. A few entries are directly confirmed from the notebook contents we've searched, while a handful remain inferred from the progression and should be marked as provisional.

Notebook	Approx. GQR	Purpose	Status

221	GQR8	Automatic PSII/OEC geometry extraction from real structures (4RTI, 5XNL, 5XNM, 4IXQ). μ-oxo identification, W1–W4 classification, batch CIF handling. First real-geometry preprocessing. 	Core geometry
222	GQR8	First GPU TDSE engine. 16-site Hamiltonian, CuPy acceleration, checkpointing, shield law, resonance combs. Earliest recognisable production TDSE implementation.	Core dynamics
223	GQR8	Bridge from CIF geometry into TDSE. First isotope framework (H₂O/D₂O/T₂O and H₂S variants). Automatic Hamiltonian generation from extracted structures. 	Core bridge
224	GQR9	Geometry refinement and realistic OEC reconstruction. Improved structural consistency and coordinate validation.	Geometry refinement
225	GQR9	Kinetic isotope effect fitting. τ extraction, Arrhenius-style analysis, isotope comparison metrics. 	KIE analysis
226	GQR9	(Likely missing or superseded notebook.) Probably intermediate OEC refinement.	Transitional
227	GQR9	Automated PSII TDSE batch runner. Multiple structures, repeated propagation, CSV generation. 	Production
228	GQR9	Batch aggregation and statistical summaries. Population comparisons across structures and conditions. 	Analysis
229	GQR10	Frequency extraction from TDSE trajectories. FFT analysis, dominant transport frequencies, spectral summaries. 	Frequency analysis
230	GQR10	Final isotope pipeline. O–O trajectory analysis, publication-ready summaries and exports. 	Publication
231	—	Storm/GQR exploratory notebook. Separate environmental application rather than PSII. 	Side branch
232	—	Shield Index statistics. Mean±SD versus Median±MAD comparisons. Robust statistics and validation plots. 	Validation
233	GQR10	CIF calibration feeding directly into TDSE runs. Improved structural calibration. 	Calibration
234	?	(Likely plotting or intermediate utility notebook.)	Transitional
235	GQR10	Participation Ratio (PR), current proxy, transport observables beyond simple populations. 	Advanced observables
236	GQR10	Veracity and validation analyses. Extended isotope comparisons. 	Validation
237	GQR10	GPU optimisation and larger production runs.	Performance
238	GQR10	Isotope trajectory analysis and extended transport metrics. 	Production
239	GQR10	O–O trajectory reconstruction, publication figure generation. 	Publication
240	GQR10–11	Final consolidation notebook before transition into later QGE framework. (Needs inspection.)	Consolidation



---

Development summary

Stage A — Structural realism

221–223

Replace mock coordinates with real PSII geometries.

Automatic OEC extraction.

First isotope-aware TDSE.


Stage B — Production PSII

224–230

Batch execution.

KIE analysis.

FFTs.

CSV generation.

Publication figures.


Stage C — Validation and extension

231–240

Statistical validation.

New transport observables.

Participation ratio.

Current proxies.

GPU scaling.

Publication polishing.



---

Historical interpretation

Putting everything together, the PSII programme now looks like this:

211  Transport laws
212  Shield law
213  First TDSE
214  Provenance
215  Real OEC extraction
216  GPU TDSE
217  Production TDSE
218  OEC graph framework
219  Figure regeneration
220  Core Hamiltonian

221  Real CIF extraction
222  Production GPU TDSE
223  Geometry → TDSE bridge
224  Structural refinement
225  KIE fitting
226  Transitional
227  Batch runner
228  Batch analysis
229  FFT / frequency analysis
230  Publication pipeline

231–240
Validation → advanced observables → publication refinement

I think this is now a coherent historical map of the entire GQR7–GQR10 PSII development sequence, and it's a solid basis for your notebook index. The only entries I'd still mark as provisional are 224, 226, 234, 237, and 240, because we haven't yet inspected those notebooks directly.

2 Jul 2026
 adding:  
 OperA Programme

GQR47
Operational admissibility

↓

GQR50
Admissibility distance as a resource monotone

↓

GQR51
Non-unital resource decay

↓

GQR52
Interleaved mixing–decoherence dynamics

────────────────────────

Framework adopted by

AFC5.  (but not by an art which is not recognised as afc4a which might be gqr47. )
AFC6
AFC7
AFC8

 Absolutely. I'd format them to match the style of the rest of your annotated notebook index.

Yes. I'd simply insert the missing notebook placeholders so the index remains continuous and future notebooks can be dropped in without renumbering.

## 312 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 313 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 314 — Exact Geometry Validation of Seam Networks
File: Untitled314.ipynb
Purpose: Exact geometric validation, supersampling and seam-density benchmarking for rectangular, diamond, honeycomb and 4.8.8 tilings. 0

## 315 — (existing notebook)

## 316 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 317 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 318 — (existing notebook)

## 319 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 320 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 321 — Affine Quantum Channel Geometry and Cone Admissibility
File: Untitled321.ipynb
Purpose: Development of affine Bloch-map evolution, cone admissibility, positivity boundaries, Schrödinger/Heisenberg positivity, geometric diagnostics and Bloch-ball visualisation. 1

## 322 — Divisibility Fracture Maps and Floquet Ridge Geometry
File: Untitled322.ipynb
Purpose: Schrödinger–Heisenberg divisibility fracture maps, singular-value gap fields, Floquet ladder extraction, ridge analysis and phase-comb topology. 2

## 323 — AOI Graph Transport on Honeycomb Lattices
File: Untitled323.ipynb
Purpose: Graph-based AOI transport on graphene and hBN lattices, ribbon scaling, drive-enhanced transport, memory channels and frequency-dependent ordering dynamics. 3

## 324 — AOI Frequency Sweep and Braided Ladder Programme
File: Untitled324.ipynb
Purpose: Automated frequency sweeps, envelope fitting, universal ladder collapse, braided phase geometry, finite-size scaling and publication-quality figure generation. 4

## 325 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 326 — Reserved
Status: No notebook assigned. Left intentionally blank.

## 327 — Exact Geometry Engine for GQR49
File: Untitled327.ipynb
Purpose: Exact seam-network geometry engine, orientation entropy, pitch matching, rotational invariance analysis and exact topology benchmarking for divertor seam networks. 5

## 328 — Phase-Sheet Contour and Ridge Geometry
File: Untitled328.ipynb
Purpose: Reconstruction and analysis of phase sheets, contour geometry, ridge extraction, crossing statistics and folded phase-space diagnostics. 6

## 329 — Production Geometry Pipeline and Report Builder
File: Untitled329.ipynb
Purpose: Production workflow integrating exact geometry, validation tables, automated figure generation, report assembly and export for the GQR49 geometry programme. 7


---

307 — Early AFC / Ladder-State Transport and Operational Admissibility

File: Untitled307.ipynb
...

308 — Quantum Channel Admissibility and Diamond-Norm Metrics

File: Untitled308.ipynb
...

309 — Gauge Atlas and Operational Accessibility Framework

File: Untitled309.ipynb
...

310 — Governance Controller Optimisation and Monte Carlo Admissibility

File: Untitled310.ipynb
...

311 — Fusion Tile Topology, Thermal Transport and Stress Modelling

File: Untitled311.ipynb
...


---

312 — Reserved

Status: No notebook assigned. Left intentionally blank for future development.


---

313 — Reserved

Status: No notebook assigned. Left intentionally blank for future development.


---

314 — Geometry Topology Validation and Exact Seam Metrics

File: Untitled314.ipynb
Purpose: Validation framework for exact seam geometry, supersampling, rasterisation and comparative tiling metrics across rectangular, diamond, honeycomb and 4.8.8 topologies.
Inputs: Exact lattice generators, seam geometry, supersampling parameters, topology definitions.
Outputs: Exact seam-length measurements, raster validation, topology comparison figures and benchmark datasets.
Depends on: GQR49 geometry programme.
Feeds into: Fusion topology optimisation, geometry validation pipeline and later exact geometry notebooks.
Status: Core geometry validation notebook.
Notes: Establishes the numerical validation framework separating exact geometric metrics from rasterised control calculations. 


---

315 — Hyperbolic hBN / κ-ET Spectroscopy and Polariton Coupling

File: Untitled315.ipynb
...


---

316 — Reserved

Status: No notebook assigned. Left intentionally blank.


---

317 — Reserved

Status: No notebook assigned. Left intentionally blank.


---

318 — Germinal Centre Balloon–Foam Dynamics and Lineage Selection

File: Untitled318.ipynb
...


---

319 — Reserved

Status: No notebook assigned. Left intentionally blank.


---

320 — Reserved

Status: No notebook assigned. Left intentionally blank.


---

That keeps the notebook numbering continuous and makes it clear to future readers that those identifiers have been intentionally reserved rather than accidentally omitted.


---

307 — Early AFC / Ladder-State Transport and Operational Admissibility

File: Untitled307.ipynb (and recovery variants)
Purpose: Early operational implementation of ladder-state transport, admissibility, recurrence and accessibility metrics that later underpin GQR47.
Inputs: AOI transport concepts, ladder-state models, recurrence structures.
Outputs: Operational admissibility metrics, ladder-state diagnostics, recurrence maps, accessibility measures.
Depends on: AOI transport framework, ladder-state formalism.
Feeds into: GQR47, operational admissibility programme, later AFC notebooks.
Status: Historically important precursor.
Notes: Earliest computational bridge between AOI transport theory and operational channel-based admissibility.


---

308 — Quantum Channel Admissibility and Diamond-Norm Metrics

File: Untitled308.ipynb
Purpose: Develop operational AOI using quantum channels, Choi matrices and diamond-norm distances.
Inputs: Kraus operators, channel definitions, Choi representations, SDP optimisation.
Outputs: Diamond distances, admissibility metrics, mutual-information diagnostics, channel observables.
Depends on: AOI theorem, operational channel formalism.
Feeds into: GQR47 operational admissibility paper.
Status: Core operational notebook.
Notes: First major implementation of AOI using quantum-information metrics rather than transport intuition. 


---

309 — Gauge Atlas and Operational Accessibility Framework

File: Untitled309.ipynb
Purpose: Extend operational admissibility to symmetric and asymmetric channel families with scaling and collapse analyses.
Inputs: Channel families, AOI admissibility definitions, optimisation routines.
Outputs: Scaling laws, collapse plots, admissibility atlases, parameter fits, publication figures.
Depends on: 308, AOI channel formalism.
Feeds into: Gauge Atlas paper, fracture and accessibility framework.
Status: Core AOI notebook.
Notes: Forms the computational heart of the Gauge Atlas and operational AOI programme. 


---

310 — Governance Controller Optimisation and Monte Carlo Admissibility

File: Untitled310.ipynb
Purpose: Monte Carlo optimisation of governance and admissibility using geometry, coherence and controller selection.
Inputs: Governance analysis surfaces, admissibility maps, coherence models, controller parameter grids.
Outputs: Controller evidence packs, admissibility statistics, optimisation diagnostics, Monte Carlo summaries.
Depends on: Gauge Atlas, AOI operational metrics.
Feeds into: AFC governance, operational admissibility, controller optimisation.
Status: Core governance notebook.
Notes: Introduces controller optimisation under geometric and coherence constraints using reproducible Monte Carlo workflows. 


---

311 — Fusion Tile Topology, Thermal Transport and Stress Modelling

File: Untitled311.ipynb
Purpose: Compare alternative plasma-facing tile topologies using simplified thermal and mechanical transport models.
Inputs: Rectangular, diamond, hexagonal and Archimedean seam geometries, thermal pulse models.
Outputs: Thermal maps, stress proxies, topology comparisons, optimisation tables, engineering figures.
Depends on: Independent engineering geometry framework.
Feeds into: GQR49 fusion engineering programme.
Status: Engineering application notebook.
Notes: Explores how seam topology influences thermal robustness and stress localisation in plasma-facing components. 


---

315 — Hyperbolic hBN / κ-ET Spectroscopy and Polariton Coupling

File: Untitled315.ipynb
Purpose: Model hyperbolic phonon-polariton coupling between hBN and correlated quantum materials.
Inputs: Dielectric models, transfer-matrix formalism, hBN thickness, material permittivities.
Outputs: Reflection spectra, coupling maps, resonance discrimination metrics, thickness optimisation.
Depends on: Transfer-matrix electrodynamics.
Feeds into: Condensed-matter spectroscopy and hBN transport studies.
Status: Core condensed-matter notebook.
Notes: Provides computational spectroscopy linking hyperbolic materials with correlated electronic systems. 


---

318 — Germinal Centre Balloon–Foam Dynamics and Lineage Selection

File: Untitled318.ipynb
Purpose: Agent-based model of germinal-centre organisation combining foam mechanics, clonal evolution and lineage dynamics.
Inputs: Cell mechanics, division and apoptosis rules, clone identities, spatial constraints.
Outputs: Foam morphologies, lineage trees, dominance statistics, accessibility landscapes, population dynamics.
Depends on: GC-Arc conceptual framework.
Feeds into: Germinal-centre selection, immune-memory and governance studies.
Status: Core biological systems notebook.
Notes: One of the most comprehensive biological notebooks, integrating mechanics, selection, topology and lineage reconstruction into a unified simulation framework. 





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
