# College of Finite Symbolic Mechanics

**College:** Finite Symbolic Mechanics (FSM)  
**Organisation:** School of Geofinitism  
**Founder:** Kevin R. Haylett  
**Motto:** *Simul Pariter* — Together, at the same time  
**Status:** Scaffold — cross-listing from Attralucian Studies; formal development ongoing

---

## Mission

The College of Finite Symbolic Mechanics develops the formal apparatus of Geofinitism. Where the College of Philosophy asks what kind of world makes measurement-first knowledge possible, FSM asks how finite symbolic processes actually work: how they unfold in time, how they interact, how they compose, and what structure is hidden inside their apparently static forms.

FSM is the engineering workshop of the School of Geofinitism. It provides the formal tools that the other colleges use. The finite overlap operator $\mathcal{O}(f,g;\delta)$ underlies signal processing and dynamical systems. Finite Process Unfolding (FPU) explains what log-space delay embeddings recover. Non-commutativity explains why symbolic order is irreversible — why you cannot always undo a compression. Quaternions show how spatial and temporal transformations compose. These are not abstract curiosities; they are the formal spine of the programme.

**Central questions:**
- What is the temporal structure hidden inside apparently static symbolic forms — and how does FPU recover it?
- Why is symbolic composition in general non-commutative — and what does this imply for meaning, order, and reversibility?
- What is the finite overlap operator $\mathcal{O}(f,g;\delta)$, and how does it generalise classical convolution under measurement constraints?
- How do quaternions and geometric algebra enter the Geofinite programme?
- What is the Geofinite treatment of computability, complexity, and inference?

---

## Directory Structure

```
college-finite-symbolic-mechanics/
├── README.md           ← this file
├── essays/             ← .md summaries of essays (cross-listed from Attralucian)
├── lessons/            ← lesson .md files (learning outcomes + concepts)
├── papers/             ← .md summaries of technical papers
├── monographs/         ← extended thesis treatments (pending)
├── bridges/            ← entry-point documents for external disciplines (pending)
└── stubs/              ← new ideas not yet processed
```

---

## §1 — Papers

### Primary Papers

| ID | Title | Primary college | FSM relevance |
|---|---|---|---|
| P04 | [The Finite-Symbol Embedding Theorem (Takens-Haylett Theorem)](../college-machine-intelligence/papers/P04_finite_symbol_embedding_theorem_summary.md) | Machine Intelligence (co-primary FSM) | The formal licence for Takens reconstruction on finite symbolic systems; the Geofinite Embedding Principle |
| P06 | [The Measured World: Where Compression Replaces Correspondence](../college-language-dynamics/papers/P06_measured_world_compression_summary.md) | Language Dynamics (secondary FSM) | Compression as the fundamental symbolic operation; ADC as the measurement model |
| P07 | [Geofinitism: Decompressing Meaning](../college-language-dynamics/papers/P07_decompressing_meaning_summary.md) | Language Dynamics (secondary FSM) | Decompression as FPU in experiential form |

---

## §2 — Cross-listed Essays from Attralucian Studies

The FSM core currently resides in `college-attralucian-studies` (ATT_51–54, ATT_63). These are the primary FSM essays and will be formally cross-listed here.

### Core FSM Essays

| Essay | Title | Key FSM contribution |
|---|---|---|
| ATT_51 | On Non-Commutativity | Why the order of symbolic operations matters — non-commutativity as a fundamental property of finite symbolic systems |
| ATT_52 | Finite Process Unfolding (FPU) | Recovering the temporal structure hidden inside static symbolic forms; the theoretical basis for log-space delay embedding |
| ATT_53 | Bayesian Inference: A Finite Process Unfolding | Bayesian inference reframed as a finite process unfolding under measurement constraints |
| ATT_54 | Finite Symbolic Mechanics: On Quaternions | How quaternions encode finite symbolic transformations; geometric composition under FSM |
| ATT_63 | Finite Overlap and Convolution | The finite overlap operator $\mathcal{O}(f,g;\delta) = \sum_{k \in K} I(f(k), g(k-\delta))$; generalisation of classical convolution |

### Supporting Essays

| Essay | Title | FSM relevance |
|---|---|---|
| ATT_23 | The Generon: Process, Measurement, and Completion | The generonic process as the atomic FSM event — a distinction stabilising into an admissible mark |
| ATT_31 | The Generonic Ledger | Accounting for the cost of the ink — FSM's energy and resource accounting |
| ATT_65 | Mathematics as a Stabilised Sub-Regime of Language Dynamics | The deepest FSM statement: mathematical structure emerges from the dynamics of finite symbolic processes |
| ATT_59 | The Geofinite Kolmogorov Complexity Thesis | $K^{\mathbb{M}}$ — complexity under resource bounds; FSM's treatment of information content |
| ATT_57 | The Geofinitist Computability Thesis | Computability under finite admissibility — the FSM treatment of the Church–Turing thesis |

---

## §3 — Key Concepts and Formalisms

| Concept / Symbol | Definition | Primary source |
|---|---|---|
| **FSM** | Finite Symbolic Mechanics — the formal framework for finite symbolic processes under measurement constraints | ATT_51–54, ATT_63 |
| **FPU** | Finite Process Unfolding — recovering temporal structure from static symbolic forms; the process that log-space delay embedding performs | ATT_52 |
| $\mathcal{O}(f,g;\delta)$ | Finite Overlap Operator: $\sum_{k \in K} I(f(k), g(k-\delta))$ — generalised finite convolution | ATT_63 |
| **Non-commutativity** | $A \circ B \neq B \circ A$ in general for finite symbolic operations — order is not reversible | ATT_51 |
| **Nexil** | Minimum admissible finite symbolic distinction carrier — "the minimum finite bead of ink" | ATT_65, ATT_23 |
| **Generonic Process** | A measurement event: distinction stabilises sufficiently to form an admissible symbolic mark | ATT_23, ATT_65 |
| **Generonic Sphere** | The finest measurement distinguishable at a given epoch — bounds the finite index set $K$ | ATT_63, ATT_62 |
| **Generonic Potential** | The possibility of finite distinction formation under admissible interaction — Geofinitism's minimal ontological commitment | ATT_65 |
| $K^{\mathbb{M}}_{U,\tau,B}(x)$ | Measured Kolmogorov Complexity — resource-bounded, measurement-conditioned | ATT_59 |
| **Distinction → Formation → Stabilisation** | The three-stage foundational process of FSM — replaces ontology/epistemology | ATT_65 |
| **Admissible Stabilisation Trajectory** | The fundamental unit of FSM — the process that becomes an admissible symbol | ATT_65 |
| $E_x \rightarrow E_n$ | Exogenous → Endogenous measurement chain — from world to symbol | ATT_62, ATT_65 |
| **Tilde Convention** | $\tilde{\cdot}$ marks a Geofinite commitment — finite, measurement-conditioned, provenance-tracked | ATT_34, ATT_62 |

---

## §4 — The FSM Programme

FSM provides the formal grounding for results across the School:

```
Atomic level: Generonic Process (ATT_23)
              A distinction becomes an admissible mark
                      ↓
Composition level: Non-Commutativity (ATT_51)
                   Order matters — symbolic composition is directional
                      ↓
Temporal level: Finite Process Unfolding (ATT_52)
                Static forms hide temporal structure — FPU recovers it
                      ↓
Overlap level: Finite Overlap Operator (ATT_63)
               How two finite processes interact — generalised convolution
                      ↓
Geometric level: Quaternions (ATT_54)
                 How transformations compose in finite symbolic space
                      ↓
Licence level: Geofinite Embedding Principle (P04)
               FPU applied to language: Takens reconstruction is valid
               for finite symbolic systems
                      ↓
Application level: MARINA (P01), P02, P08, P09
                   The formal programme applied to LLMs and language
```

---

## §5 — Five Pillars in This College

FSM primarily engages P3 and P5, with P2 and P1 as essential supporting pillars:

| Pillar | Role in FSM |
|--------|-------------|
| **P3 — Dynamic Flow** (primary) | Symbolic processes as dynamical trajectories; FPU as temporal unfolding; non-commutativity as directional flow; the generonic process as the minimal dynamical event |
| **P5 — Finite Reality** (primary) | All FSM formalisms are explicitly finite: finite index sets $K$, finite overlap, finite delay schedules, bounded complexity $K^{\mathbb{M}}$ |
| **P2 — Approximations/Measurements** | The finite overlap operator as a measurement instrument; $K^{\mathbb{M}}$ as measured complexity; the generonic sphere as the finest distinguishable resolution |
| **P1 — Geometric Container** | The Alphon lattice as the container of FSM operations; nexil as the minimum geometric unit; the Takens manifold as the FSM-licensed reconstruction target |

---

## §6 — Suggested Reading Order

**For a reader arriving from signal processing or DSP:**
1. ATT_63 (Finite Overlap Operator — most directly familiar)
2. ATT_52 (FPU — temporal structure recovery)
3. ATT_51 (Non-Commutativity)
4. P04 (Takens-Haylett Theorem — formal licence)
5. P01 (MARINA — applied to language)

**For a reader arriving from abstract algebra or logic:**
1. ATT_51 (Non-Commutativity — algebraic structure)
2. ATT_54 (Quaternions — geometric composition)
3. ATT_65 (Mathematics as stabilised sub-regime — deepest philosophical statement)
4. ATT_57 (Computability thesis)

**For a reader arriving from machine learning:**
1. P04 (Geofinite Embedding Principle — the formal foundation)
2. ATT_52 (FPU — why log-space delays are the right inductive bias)
3. ATT_63 (Finite Overlap — generalised attention)

---

## §7 — Pending

| Item | Action |
|---|---|
| Essay cross-list files | Create essay .md stubs in `essays/` for ATT_51–54, ATT_63, ATT_23, ATT_31, ATT_57–59 |
| Lessons | Create lesson .md files for ATT_51–54, ATT_63 |
| Bridge documents | Entry-point for signal processing; entry-point for algebraists |
| Original FSM papers | Formal papers on FPU, the finite overlap operator, FSM foundations |

---

*Kevin R. Haylett — School of Geofinitism*  
*Simul Pariter.*
