# RFT_v3_009: Cosmogenesis — Cold Condensation and Matter Formation
## Resonance Field Theory — Publication Series v3

**DOCUMENT-ID:** RFT_v3_009_Cosmogenesis_Cold_Condensation_EN
**VERSION:** v1.0-EN (Translation: 27 March 2026 | Source: DE v1.0 + DC v10.7 sync)
**STATUS:** Translation Final
**TOPIC:** Cold Condensation as the origin of space, time, and matter; the Two-Phase Model; antimatter as the bound state of the resonance matrix
**DEPENDENCIES:** RFT v3 Mathematical Foundations (v3_001); RFT v3 Gravitation and Spin Delay (v3_003); RFT v3 Time Emergence (v3_006); RFT v3 Space Topology and 3D Emergence (v3_007); RFT v3 Black Holes and Mode Transitions (v3_008)
**AUTHOR:** Franz Zollner
**LICENSE:** CC BY-NC-ND 4.0
**Contact:** rft.projekt@posteo.de

---

## Preliminary Note: How to Read This Document

This document uses a consistent notation for confidence levels:

- **✓ HIGH** — rigorous derivation or direct confirmation by Franz Zollner
- **○ MEDIUM** — conceptually consistent, formally still open
- **⚠️ LOW / SPECULATIVE** — working hypothesis only
- **🚩 OPEN** — active research problem

RFT is not a replacement for the Λ-CDM cosmological model. The successes of Λ-CDM are uncontested. RFT proposes a mechanistic substrate from which the cosmological equations emerge — and offers a structurally different answer to the question of how order arose in the first place.

**Note on DC v10.7 sync (25 March 2026):**
The DE source document (Final v1.0, 28 February 2026) was finalized before two major results were established. This EN translation reflects the **current canonical state** (DC v10.7, 25 March 2026):

```
✅ η_B = 6.02×10⁻¹⁰: RESOLVED (Franz Zollner, 25.03.2026)
   Previously listed as an open research problem — no longer open.

✅ ħ-circularity: CLOSED (DC v10.7, 25.03.2026)
   L₀ = 1/κ is now the primary definition (ħ-independent).

✅ √(2/3)-geometry: CLOSED (DC v10.7)
   2/3 = (d−1)/d for d = 3 — same geometry as the η_B exponent.
```

Where the EN translation departs from the DE source, this is explicitly marked.

---

## Preliminary Note: Position in the v3 Series

This document addresses the origin of the universe — the transition from primordial chaos (Mode 0) to the ordered resonance matrix and to visible matter. It connects logically to RFT v3 Black Holes (v3_008), which described the mode transition from Mode 1 to Mode 2 in the context of black holes. The present document examines the opposite transition: from Mode 0 to Mode 1, from the absence of space to its constitution.

| Document | Contribution | Relevant for v3_009 |
|----------|-------------|---------------------|
| v3_001 | Master Equation, Two-Phase Model (Ch. 9) | ✓ Direct |
| v3_003 | Spin delay mechanism, topological quantities | ✓ Cross-reference |
| v3_006 | Time motor, Q-factor dynamics, emergent time | ✓ Direct |
| v3_007 | Anchor points, resonance condition in 3D | ✓ Cross-reference |
| v3_008 | Mode 0 as primordial chaos (Ch. 3.1) | ✓ Direct |

**Core thesis:** Matter is not the result of cooling from a hot primordial state. It is the result of *Cold Condensation* — a structural transition in which the resonance quality of the field exceeds a critical threshold. Order does not emerge through energy dissipation, but through an increase in structural coherence.

---

## ⚠️ Terminology Alert: Two Distinct Ratios

Two numerical ratios appear in RFT cosmogenesis. They describe **different physical processes** and must not be confused or equated:

```
3:1  =  Matrix generation ratio (Phase 1)
        Spin −1 (antimatter) : Spin +1/3 (quark partial state)
        Frequency ratio during resonance matrix constitution
        ✓ HIGH [DeepSeek verification, 28.02.2026]

4:1  =  Matter condensation ratio (Phase 2)
        1 matter vortex per 4 resonance pairs → visible matter
        Separate physical process, occurring inside Mode 1
        ○ MEDIUM [Franz Zollner, 24.03.2026]
```

The historical confusion between these two ratios is documented. Both are correct — for their respective processes. See Chapter 3.2 and Chapter 4.2 for details.

---

## Abstract

The Λ-CDM standard model describes the evolution of the universe with remarkable success. However, it requires three unresolved components (dark matter, dark energy, inflation) and a thermodynamically problematic initial state: how can highly organized structure arise from a state of maximum entropy — the hot, homogeneous Big Bang — without violating the second law of thermodynamics?

The Resonance Field Theory (RFT) offers an alternative perspective. The universe arose through *Cold Condensation* from a state of primordial chaos (Mode 0). Order does not emerge through cooling, but when the quality factor Q of the resonance field exceeds a critical threshold Q_crit. Antimatter was not destroyed in this process — it was structurally consumed into the resonance matrix itself, and in a very precise sense *is* the resonance matrix.

Three central statements of this document:

1. **Cold Condensation:** "Cold" does not refer to a temperature. It means: no cooling process is required. Order does not emerge from a hot state cooling down — it emerges when the resonance quality factor Q of the Dynamic Resonance Matrix (DRM) exceeds a critical threshold. The process is temperature-independent by design. ✓ HIGH

2. **Two-Phase Model:** Phase 1 constitutes the neutral resonance matrix via superposition of Spin −1 (antimatter) and Spin +1/3 (quark state) with a 3:1 frequency ratio. Phase 2 is the 4:1 condensation from which visible matter emerges.

3. **Resolved and honest limits:** The baryon asymmetry η_B = 6.02×10⁻¹⁰ has been derived from RFT parameters as of 25 March 2026 (✓ HIGH, DC v10.7). The coherence length ξ and the internal state of primordial chaos remain open.

---

## Table of Contents

1. Introduction — The Problem of Matter Formation
2. Connection to v3_008 — Mode 0 as Starting Point
3. The Fundamental Mechanism — Spin Superposition
4. The Two-Phase Model
5. Quality Factor Q as Order Parameter
6. Open Questions and Honest Limits (mandatory chapter)
7. Experimental Predictions
8. Summary and Formula Reference

---

## 1. Introduction — The Problem of Matter Formation

### 1.1 The Thermodynamic Paradox of Standard Cosmology

The Λ-CDM cosmological model is experimentally well confirmed: Hubble expansion, the cosmic microwave background (CMB), Big Bang nucleosynthesis, and the large-scale structure of the universe fit into a consistent picture. These successes are uncontested.

Nevertheless, Λ-CDM contains fundamental unresolved elements:

**The entropy problem:** A hot, homogeneous primordial state possesses maximal thermal entropy. Structure formation — stars, galaxies, molecules — is a state of lower thermal entropy. The explanation "gravity organizes" is qualitative; the precise mechanism by which gravitation locally compensates for thermal entropy increase has not been derived from a first principle.

**The three unknowns:** Λ-CDM requires dark matter (≈27%), dark energy (≈68%), and an inflationary phase — together accounting for 95% of the universe's energy inventory — without any of these components having been directly detected.

**The baryon asymmetry:** The observable universe contains almost exclusively matter, no antimatter. The excess of matter over antimatter is η_B ≈ 10⁻¹⁰. The Standard Model attributes this to CP violation — but the mechanism is not fully understood, and the measured magnitude of CP violation is quantitatively insufficient.

**The JWST tension:** The James Webb Space Telescope has detected massive, highly structured galaxies at redshifts z > 10, significantly earlier than Λ-CDM models predict. This result has not yet been conclusively explained within Λ-CDM.

### 1.2 The RFT Alternative: Cold Condensation instead of the Hot Big Bang

The Resonance Field Theory offers a conceptually different description. The universe did not arise through explosion and cooling, but through *Cold Condensation* — a phase transition of the resonance field when a critical resonance quality is exceeded.

```
Λ-CDM:  Hot point → cooling → T < T_crit → structure formation
RFT:    Primordial chaos (Mode 0) → Q > Q_crit → Cold Condensation
        → resonance matrix + matter
```

**"Cold" — precise definition for physicists:**

"*Cold* in Cold Condensation does not refer to a temperature. It means: no cooling process is required. Order does not emerge from a hot state cooling down — it emerges when the resonance quality factor Q of the field exceeds a critical threshold Q_crit. The process is temperature-independent by design: condensation occurs whenever Q > Q_crit, regardless of the system's thermal energy.*" ✓ HIGH [Franz Zollner, direct]

This reversal of causal structure has far-reaching consequences:
- No inflationary phase required (coherence is intrinsic to the resonance matrix)
- Antimatter not destroyed, but structurally consumed
- CMB as condensation heat, not as afterglow of a hot Big Bang
- Early structure formation (JWST results) as a natural prediction

### 1.3 Position in the v3 Series

RFT v3_009 stands at the position in the v3 series where the emergence of the framework itself is described — the framework within which all other documents operate. Documents v3_001 through v3_008 describe physics *within* the resonance matrix (Mode 1). This document describes how that resonance matrix arose.

This makes v3_009 distinctive: it touches an ontological boundary of the theory (the state *before* the resonance matrix cannot be described from inside it), and it inherits the open consistency questions of the entire v3 series.

---

## 2. Connection to v3_008 — Mode 0 as Starting Point

### 2.1 Primordial Chaos and the Ontological Boundary

As established in RFT v3 Black Holes (v3_008, Ch. 3.1), the resonance matrix can exist in qualitatively different resonance modes. For the understanding of cosmogenesis, Mode 0 is the decisive concept:

```
Mode 0:  Primordial chaos — the state BEFORE space constitution
         Q ≈ 1, no resonance matrix, no space
         Does NOT obey Mode-1 physics

Mode 1:  Our universe
         Resonance matrix exists and resonates normally
         All known physics holds here

Mode 2:  BH interior (→ v3_008)
         Resonance matrix exists, oscillating on the next harmonic
```

Consistent with v3_008 Ch. 3.1: *"Mode 0 is the state prior to space constitution — the primordial chaos in which no resonance matrix yet exists. No nodes, no resonance, no space. Mode 0 is the precondition from which the DRM (Mode 1) emerges."*

Mode 0 and Mode 1 do not behave as two phases of the same medium. Mode 0 is not a "quieter version" of the resonance matrix — it is its complete absence. This asymmetry is fundamental: the Mode 0 → Mode 1 transition is not the inverse of the Mode 1 → Mode 2 mode transition in black holes. It is a *constitution* of the field, not a jump within it.

### 2.2 What Cannot Be Said from the Inside — and Why That Is Legitimate

The internal perspective of Mode 0 is in principle impossible. This is not a weakness of the theory but an ontological boundary that is explicitly acknowledged:

An observer in Mode 1 (our universe) cannot describe the state of Mode 0 from within, because the categories of space, time, causality, and resonance only come into existence with Mode 1. Any description of Mode 0 is necessarily an extrapolation from outside — and this extrapolation breaks down at the boundary.

```
Legitimate statements about Mode 0:
  ✓ Q ≈ 1 (chaotic resonator, no space)
  ✓ No resonance matrix, no anchor points, no time
  ✓ Does not obey Mode-1 physics (Master Equation does not apply)
  ✓ Irreversible transition to Mode 1 (genuine chaos is fragile)

Not legitimate statements:
  ✗ "In primordial chaos there reigned a temperature T_0 = ..."
  ✗ "Primordial chaos lasted t seconds"
  ✗ "The energy density in primordial chaos was ρ = ..."
  [All these statements presuppose Mode-1 categories]
```

RFT accepts this boundary and treats Mode 0 as a black box — as a boundary condition, not an explicable system.

### 2.3 The Transition from Mode 0 to Mode 1

How does a resonance matrix arise from primordial chaos? RFT does not describe this as a deterministic process (that would presuppose Mode-1 causality, which does not yet exist), but as a structural transition:

When Q exceeds the critical threshold Q_crit, standing waves can first become stable. The resonance matrix "unfolds" — not at a location (no space), not at a time (no time), but as an emergent global phenomenon.

```
Q < Q_crit:  No stable resonance mode possible → primordial chaos persists
Q = Q_crit:  Instability → first metastable resonances emerge
Q > Q_crit:  Self-reinforcement → resonance matrix establishes coherently
```

The transition is irreversible: an ordered system cannot spontaneously collapse back into maximal disorder when the order itself creates the conditions for its own stability (dQ/dt > 0).

**Consistency with v3_008:** Black holes locally produce the inverse situation — they compress Mode-1 matter so strongly that a mode transition to Mode 2 is forced. Mode 0 (complete loss of the resonance matrix) is the extreme end of this scale — and thereby defines the boundary condition from which cosmogenesis departed.

---

## 3. The Fundamental Mechanism — Spin Superposition

### 3.1 Spin −1 (Antimatter) ⊗ Spin +1/3 (Quark State)

The fundamental observation supporting the Two-Phase Model originates from a simulation (Franz Zollner, February 2026; documented in RFT v3 Mathematical Foundations v3_001, Ch. 9.3):

Two characteristic spin states superpose in the resonance matrix:
- **Spin −1**: Corresponds to the antimatter vortex in the resonance matrix
- **Spin +1/3**: Topological partial solution of the Master Equation — not observable as a free particle (quark state)

This superposition is not accidental. The +1/3 state is a fundamental resonance of the cube-on-vertex geometry of the DRM (as established in RFT v3 Mathematical Foundations v3_001, Ch. 8.3): the ±1/3 projections arise from the geometric structure of the three-dimensional node architecture. They are topologically present but unstable without a supporting structure — for the same reason that quarks do not exist freely (confinement as RFT mechanism).

The Spin −1 state is the fundamental antimatter state in the 1:1 matrix. Their superposition yields the ground state of the resonance matrix: neutral, stable, gravitationally inert.

### 3.2 The 3:1 Frequency Ratio — Matrix Generation

*Verification: DeepSeek, ✓ HIGH — mathematically unambiguous*

The superposition of Spin −1 and Spin +1/3 follows a characteristic frequency ratio of **3:1**.

```
Spin −1:    frequency ω₋₁
Spin +1/3:  frequency ω₊₁/₃ = 3 · ω₋₁

Ratio:  ω₊₁/₃ : ω₋₁ = 3 : 1     ✓ HIGH [DeepSeek verified]
```

The 3:1 ratio follows directly from the spin numbers: the +1/3 state has exactly one-third the topological winding number of the −1 state. Correspondingly, it oscillates at three times the fundamental frequency.

**Shared nodes:** Waves with the 3:1 frequency ratio possess shared zero crossings at multiples of 3:

```
Shared nodes at: x = 3, 6, 9, ... (multiples of 3)
→ At these nodes: constructive and destructive superposition exactly defined
→ Result: periodic resonance matrix structure with period 3
```

This node structure is the microscopic basis of the resonance matrix. It provides the spatial periodicity on which **anchor points** (AP, resonance nodes for quantization) can arise.

**This ratio describes Phase 1 (matrix generation) only.** The condensation of visible matter in Phase 2 follows a different ratio — see Section 4.2.

### 3.3 Constructive and Destructive Superposition

The superposition of the two spin states produces a spatial pattern containing two physically distinct regions:

**Destructive superposition** (at the shared nodes, multiples of 3):
The wave functions cancel. The antimatter amplitude (Spin −1) and the quark amplitude (Spin +1/3) compensate each other. Zero net spin, zero net charge — genuine vacuum state.

**Constructive superposition** (between the shared nodes):
The amplitudes reinforce. Here the anchor points of the resonance matrix arise — the resonance nodes identified in RFT v3 Space Topology (v3_007) as the condition for stable 3D structures.

```
Result of superposition:
  Destructive → vacuum regions (null points)
  Constructive → anchor points (resonance nodes)
  Together:   → the neutral ground structure of the resonance matrix
```

### 3.4 Antimatter as the Resonance Matrix — Not Destroyed

This is one of the conceptually most important statements of RFT cosmogenesis: antimatter was not destroyed through CP-violating processes. It was structurally consumed into the ground structure of the resonance matrix.

The Spin −1 state (antimatter) forms, together with the Spin +1/3 state (quark partial solution), the neutral 1:1 matrix of space. This matrix is:
- **Neutral:** Zero net spin, zero net charge
- **Stable:** Topologically protected through the node structure
- **Gravitationally inert:** No asymmetric mass distribution

**Consequence:** There is no antimatter problem in RFT. There is only a description problem: standard cosmology searches for antimatter in the free cosmos — and does not find it. RFT says: it is everywhere, but structurally bound as resonance matrix, and therefore experimentally invisible.

**On terminology — consumption and binding:**
Antimatter is bound in the resonance structure. The binding process itself is the consumption — both descriptions are complementary. "Consumption" describes the process (antimatter is incorporated into the resonance structure; destructive superposition "uses it up"), "binding" describes the resulting state (antimatter is preserved, topologically fixed). Antimatter is neither destroyed nor free — it is structurally integrated.

More precisely: **antimatter was not destroyed in the early universe — it was structurally consumed into the DRM itself. Antimatter IS the resonance matrix. What we call "space" is the bound state of the antimatter component. This resolves the antimatter asymmetry not by explaining why matter "won", but by redefining what antimatter became.** ✓ HIGH [Franz Zollner, direct]

**Prediction:** No primary antimatter domains in the observable universe. Consistent with PAMELA and AMS-02.

---

## 4. The Two-Phase Model

### 4.1 Phase 1 — Neutral Resonance Matrix (1:1 Superposition)

The first stable state following the transition from Mode 0 is the neutral resonance matrix. Its core feature is the exactly equal superposition of matter and antimatter states:

```
Phase 1: Spin −1 ⊗ Spin +1/3
         3:1 frequency ratio          ✓ HIGH [DeepSeek verified]
         Shared nodes at 3n

         Result:
         → Resonance matrix: neutral, stable, gravitationally inert
         → Antimatter consumed/bound (not destroyed!)
         → Space as ordered superposition structure
```

This phase corresponds to what is described in RFT v3 Mathematical Foundations (v3_001, Ch. 9.2) as the "1:1 superposition": matter and antimatter components are present in equal parts. The resonance matrix *is* this superposition — it is not an empty container for the superposition.

**Consistency with v3_007:** The resonance condition n_AP ≥ n_dim = 3 required in RFT v3 Space Topology (v3_007) is satisfied by the 3:1 node structure: in each spatial dimension there are at least 3 stable anchor points per resonance cell. That is the condition for stable 3D structure.

**Q-factor in Phase 1:**
```
Q > Q_crit1 (cosmological)   [HYPOTHESIS, see Ch. 5.2 for value]
First stable resonance mode of the field
dQ/dt > 0 (universe becomes a better resonator)
```

### 4.2 Phase 2 — 4:1 Condensation: Visible Matter

Phase 1 is the resonance matrix in its neutral ground configuration. It contains no visible matter in today's sense — no baryons, no hadrons. These arise in Phase 2.

When Q rises further and locally Q > Q_crit2 is exceeded, quantum fluctuations generate metastable condensates with a **different** ratio — the **4:1 ratio** of matter condensation:

```
Phase 2: 4:1 condensation
         Q > Q_crit2   ⚠️ WORKING HYPOTHESIS [value not independently derived]

         Mechanism:
         Quantum fluctuation δΨ₀ > threshold
         → Vortex nucleation (4:1 ratio)
         → Constructive self-reinforcement
         → Visible matter condenses
```

**Physical interpretation:** In the 4:1 configuration, the matter component exceeds the antimatter component by a factor of 4. One matter vortex per four resonance pairs cannot be fully integrated into the neutral resonance structure — it condenses into observable topological structures: vortices that appear as particles.

**Important note on the DE source:** The original DE document (v1.0, 28 February 2026) referred to Phase 2 as the "3:1 condensation". This terminology reflected the confusion between the two ratios that has since been resolved (DC v10.5, Franz Zollner, 24 March 2026): the 3:1 ratio describes matrix *generation* (Phase 1), while the 4:1 ratio describes matter *condensation* (Phase 2). Both are correct for their respective processes. ○ MEDIUM [4:1 condensation ratio, separate process]

**"Cold" — the definition (recap):**
"Cold" in RFT does *not* mean low temperature. It means the **absence of any need for cooling**. Condensation occurs when Q > Q_crit, independent of the system's thermal energy. Order arises through resonance quality, not through energy dissipation.

```
Standard cosmology:  Order from cooling (T < T_crit)
RFT cosmogenesis:    Order from resonance (Q > Q_crit)

The word "cold" designates the mechanism — not the state!
```

**The transition is irreversible:** Genuine chaos (Mode 0 or Q ≈ 1) is fragile. Once a coherent resonance matrix has established itself, it stabilizes itself. The process of "extracting something ordered from chaos" cannot spontaneously be undone — what remains after the ordered structure has been isolated is, by necessity, order.

### 4.3 Baryon Asymmetry without CP Violation

The Two-Phase Model provides a qualitative explanatory framework for the baryon asymmetry:

Phase 1 is fully neutral (1:1). Phase 2 is the 4:1 condensation — a matter excess condenses into visible particles, while the antimatter component remains bound (consumed) in the resonance structure. No external CP violation is required; the asymmetry arises structurally from the condensation process itself.

```
Qualitative picture:
  Phase 1:  Resonance matrix (neutral, matter + antimatter consumed/bound)
  Phase 2:  4:1 condensation → visible matter surplus

  Antimatter: consumed in resonance structure (not destroyed)
  Matter:     condenses into baryons (observable)

  → Baryon asymmetry as structural result, not as random process
```

**Conceptual definition of η_B:**

η_B is the ratio of the excess (non-consumed) matter component to the total consumed antimatter. It describes how much visible matter remains from the condensation process after antimatter has been structurally integrated:

```
η_B = (excess matter) / (consumed antimatter)  ≈ 10⁻¹⁰

Intuitively: Per 10¹⁰ consumed antimatter units, 1 visible baryon remains.
```

**✓ η_B — RESOLVED (Franz Zollner, 25 March 2026):** See Chapter 6.2.

The prediction *no primary antimatter domains* is qualitatively secured and consistent with AMS-02 and PAMELA.

---

## 5. Quality Factor Q as Order Parameter

### 5.1 Definition and Basic Structure

The **quality factor Q** (**Qualitätsfaktor** Q) is the central measure of the resonance quality of the Dynamic Resonance Matrix (DRM):

```
Q = ω₀ / (2γ)

where:
  ω₀ = resonance frequency of the DRM
  γ  = damping rate (→ Master Equation, as established in
       RFT v3 Mathematical Foundations v3_001, Ch. 2)

Physical meaning: ratio of stored to dissipated energy per cycle
```

Q describes how precisely and persistently the oscillations of the resonance matrix are. A high Q value means: the DRM is a good resonator — oscillations decay slowly, structures are stable. A low Q value means: chaotic fluctuations dominate, no stable structures are possible.

**Consistency with v3_006:** In RFT v3 Time Emergence (v3_006), Q was introduced as the parameter governing the strength of the arrow of time. The Φ-time motor (Φ = 2α/(1+α²)) generates the arrow of time from the beat-frequency asymmetry of the resonance field. Q determines how sharply this asymmetry is pronounced: high Q → clear arrow of time; Q ≈ 1 → no defined arrow of time.

### 5.2 Q-Factor Scale from Primordial Chaos to High Organization

```
Q ≈ 1              Primordial chaos (Mode 0, no space, no time)
Q → Q_crit1        First threshold: resonance matrix arises (Mode 0 → Mode 1)
Q → Q_crit2        Second threshold: vortex nucleation, visible matter
Q ≫ Q_crit2        Highly organized structures (atoms, stars, galaxies)
dQ/dt > 0          The universe becomes a better resonator over time
```

**Two Q_crit thresholds (Franz Zollner, conceptually established):**

The earlier treatment with a single Q_crit was a simplification. There are conceptually two distinct transitions:

```
Q_crit1 = α⁻¹·π² ≈ 1352.7    HYPOTHESIS [ontological boundary]
  → Transition Mode 0 → Mode 1: space constitution
  → First stable resonance of the DRM becomes possible
  → CAUTION: At this threshold, Mode-1 physics does not yet fully apply!
    The Master Equation describes Mode 1 — the transition itself lies
    beyond its domain of validity.
  → Q_crit1 is therefore only describable as an extrapolation, not derivable.
  ✓ HIGH (Franz Zollner, 25.03.2026; DC v10.7)
  Note: α⁻¹·π² ≈ 137.036 × 9.870 ≈ 1352.7 [ħ-free ✓]

Q_crit2 ~ 10⁶–10⁸   WORKING HYPOTHESIS [vortex stability]
  → Within Mode 1: vortex nucleation becomes possible
  → Condensation of visible matter (4:1 process)
  → Mode-1 physics fully applies here; Q_crit2 is in principle derivable
    from the Master Equation — but has not yet been derived.
  → Numerical values from v2 sources: not independently verified ⚠️
```

This distinction resolves the apparent inconsistency between RFT v3 Dark Matter (v3_010, Q_cosm ~ 10³) and earlier cosmogenesis sources (10⁶–10⁸): both numbers describe different physical thresholds.

For qualitative argument: Q_crit1 < Q_crit2 < Q_today. The ordering is established; the numerical values are hypotheses.

**Q-evolution:**

```
dQ/dt > 0    [qualitatively established — universe as improving resonator]
Q(τ) ~ τ^α  [v2 parametrization; α ≈ 0.3–0.5 ⚠️ not independently derived]
```

### 5.3 Coherence Length ξ and CMB Cold Spots

**Coherence length ξ:** The condensation does not proceed globally and instantaneously. Order has a finite spatial range ξ — the coherence length. Within ξ, the field condenses coherently; between distinct coherence domains, phase boundaries may arise.

```
⚠️ Coherence length ξ:
   Concept established (Franz Zollner, direct)
   Numerical value of ξ: UNKNOWN — documented as open question
   Derivation from RFT parameters: absent
```

**CMB cold spots as Q < Q_crit regions:** If ξ is smaller than the cosmological horizon (plausible, but not calculated), regions arise in which condensation did not set in or was delayed — regions where Q remained locally below Q_crit.

```
Q_local > Q_crit:  Normal condensation → observable matter
Q_local ≈ Q_crit:  Weak condensation → less structure
Q_local < Q_crit:  No condensation → cold spots in the CMB
```

This interpretation is conceptually consistent with the irreversible transition (Q_crit undershoot does not mean return to Mode 0 — only a locally worse resonator, not complete chaos).

```
⚠️ Quantitative connection ξ ↔ CMB angular scales: not derived
   Qualitative picture: plausible and consistent
```

**CMB as condensation heat:** The energy released during condensation (analogous to binding energy in phase transitions) is not radiated "outward" (no "outward" exists — no space outside the universe). It is redistributed internally:

```
E_total = E_chaos + E_order + E_CMB = const  (internal perspective)

Condensation:
E_chaos → E_order + E_CMB

→ The CMB is the thermal noise of condensation,
  not the afterglow of a hot Big Bang
```

### 5.4 Consistency with v3_006 (Hubble Tension) and v3_008 (Mode Transition)

**Consistency with v3_006 (time emergence):** In RFT, time emerges from the beat-frequency asymmetry of the resonance field (Φ-time motor, as established in RFT v3 Time Emergence v3_006). Before condensation sets in (Q ≈ 1, Mode 0), there is no arrow of time. Time arises simultaneously with the resonance matrix. Q and emergent time are causally linked: dQ/dt > 0 presupposes a time that emerges from the Q-field itself. This circularity is documented in v3_006 and is accepted as conceptually legitimate, though formally unresolved.

The Hubble tension (discrepancy between early and late H₀ measurements) is, in RFT, an expected property: if Q grows with time and H depends on Q, then H is not a universal constant but a Q-dependent quantity. Different epochs measure different H values — consistent with observations.

```
H(Q) = H₀ · f(Q)    [qualitative; exact functional form ⚠️ not derived]
```

**Consistency with v3_008 (mode transition):** Black holes compress Mode-1 matter so far that a mode transition to Mode 2 is forced. The inverse transition — from Mode 0 to Mode 1 — is cosmogenesis. Both transitions obey the same fundamental principle of RFT: when a resonance mode can no longer accommodate a boundary stress, the system transitions to a different configuration.

```
Cosmogenesis:  Mode 0 → Mode 1  (condensation at Q > Q_crit)
Black hole:    Mode 1 → Mode 2  (compression at ρ > ρ_crit)

Common principle: mode transition as response to exceeded boundary condition
```

---

## 6. Open Questions and Honest Limits (Mandatory Chapter)

RFT claims to describe the emergence of space, time, and matter mechanistically. This is an extraordinary claim. The following sections explicitly name the known gaps. Two previously open problems have been resolved since the DE source was finalized (25 March 2026, DC v10.7); these are marked accordingly.

### 6.1 Primordial State — Ontological Boundary (No Internal Perspective)

The state prior to condensation (Mode 0, Q ≈ 1) is in principle not describable from the Mode-1 perspective. All statements about Mode 0 — including the statement "Q ≈ 1" — are extrapolations of Mode-1 physics beyond its domain of validity.

```
🚩 Status: Fundamental ontological boundary.
   No method known to describe Mode 0 from the inside.
   RFT explicitly accepts this limit.
```

### 6.2 Baryon Asymmetry — ✅ RESOLVED (25 March 2026)

**Note: The DE source document (Final v1.0, 28 February 2026) listed η_B as an open research problem. This has been resolved as of 25 March 2026 (DC v10.7, Franz Zollner). The EN translation reflects the current canonical state.**

```
✅ RESOLVED (Franz Zollner, 25 March 2026) ✓ HIGH

η_B = Δ_α² × Q_crit1^(2/3)  =  6.02 × 10⁻¹⁰

where:
  Q_crit1 = α⁻¹·π² ≈ 1352.7   [ħ-free ✓]
  Δ_α = α residual (2.22 ppm expressed as dimensionless ratio)
  n = 2/3 = (∛Q)² = cube surface geometry of the 3D mode space
  0.3% deviation from observed η_B ≈ 6.1×10⁻¹⁰

The exponent n = 2/3 corresponds to the cube surface geometry,
consistent with L/L₀ = √(2/3) — the same underlying 3D mode-space
structure appears in both relations.

This result was derived after the DE source document was finalized.
The EN version reflects the current canonical state (DC v10.7).
```

```
🚩 Formally still open: rigorous derivation of n = 2/3 from the
   λ-term of the Master Equation. The geometric argument is compelling
   and the numerical result is ✓ HIGH; the formal algebraic chain
   from the Master Equation to n = 2/3 is an open research task.
```

### 6.3 Coherence Length ξ — Not Derived from RFT Parameters

The concept of a finite coherence length ξ is physically plausible and yields a consistent interpretation of CMB cold spots. However, the numerical value of ξ has not been derived from L₀, α, or other canonical RFT parameters.

```
🚩 Status: Concept established (Franz Zollner, direct).
   Numerical value: UNKNOWN.
   Derivation from RFT parameters: absent.
```

### 6.4 Q_crit Numerical Values

Two Q_crit thresholds are now distinguished (see Ch. 5.2). The ordering Q_crit1 < Q_crit2 is established. The numerical values remain hypotheses:

```
Q_crit1 = α⁻¹·π² ≈ 1352.7   ✓ HIGH (Franz, 25.03.2026; DC v10.7)
           [exact π-α expression; ħ-free]

Q_crit2 ~ 10⁶–10⁸            ⚠️ WORKING HYPOTHESIS
           [from v2 sources; not independently derived]
```

### 6.5 Consistency Inheritance from the v3 Series

v3_009 inherits the open questions of the entire v3 series. Several have been closed since the DE source was written:

**ħ-circularity — ✅ CLOSED (DC v10.7, 25 March 2026):**

```
✅ RESOLVED (DC v10.7, 25.03.2026):

Previously: L₀ = (π/6)·l_P contained l_P = √(ħG/c³) → ħ-dependent
Now:        L₀ = 1/κ  [PRIMARY DEFINITION — ħ-independent!]
            κ = resonance stiffness (matrix property, from geometry)
            L₀ = (π/6)·l_P is now a numerical verification, not the definition.

The causal direction: κ (matrix stiffness) → L₀ → what we label "mass"
Not: mass → ħ → L₀.

Both paths converge:
  G-derivation = κ-definition ✓
  G·ħ = (36/π²)·c³·L₀² [algebraic identity, not an independent input]

This also means: Q_crit1 = α⁻¹·π² ≈ 1352.7 is ħ-free ✓
```

**√(2/3)-geometry — ✅ CLOSED (DC v10.7, 25 March 2026):**

```
✅ RESOLVED (DC v10.7, 25.03.2026):
L/L₀ ≈ √(2/3)   where  2/3 = (d−1)/d  for  d = 3
→ Expresses the mode-space boundary geometry in d=3 dimensions.
→ Same geometry as the η_B exponent n = 2/3.
```

**Scale jump Planck↔QCD:**
The condensation of the universe occurred at QCD scales (~150 MeV, T_QCD), not at Planck scales. Why the universe condensed at the QCD scale — not the Planck scale — is a deep open problem.

```
⚠️ Status: Open problem, deeper than v3_009.
```

**T_QCD as condensation heat:**
The proton mass follows in RFT from m_p = (2π−2α) × k_B × T_QCD (as derived in RFT v3 Mathematical Foundations v3_001, Ch. 8.2). If T_QCD is the condensation temperature of cosmogenesis, a conceptual bridge exists. Whether this bridge is rigorous has not yet been investigated. T_QCD currently remains an external measured value.

```
⚠️ Status: Interesting connection, formally open.
```

**Lorentz invariance:**
Whether the discrete DRM model possesses complete Lorentz invariance in the continuum limit has not yet been formally proven (→ RFT v3 Space Topology v3_007, Ch. 8).

---

## 7. Experimental Predictions

RFT cosmogenesis makes qualitative predictions that are experimentally distinguishable from Λ-CDM. Quantitative predictions drawn from v2-source numerical values are explicitly marked ⚠️.

### 7.1 JWST — Early Massive Galaxies

**Qualitative prediction (established):** In RFT, structure arises through vortex condensation, which is rapid and coherent — not through gravitational collapse (slow). Massive, highly structured galaxies at z > 10 are therefore *natural* in RFT, while they are problematic for Λ-CDM.

```
RFT prediction: Galaxies at z > 10–15 with M > 10¹⁰ M_☉ possible
                Consistent with JWST observations (z > 10)   ○ Hints [available]

⚠️ Quantitative estimates from v2 sources (n ~ 10⁻⁴ Mpc⁻³ etc.):
   not independently verified — not adopted as established.
```

### 7.2 CMB — Cold Spots and r-Value

**CMB cold spots as Q < Q_crit regions:**

```
RFT prediction: Cold spots in the CMB = regions with Q_local < Q_crit
                → incomplete condensation → less structure

Status: Qualitatively plausible. Quantitative connection to angular scales: ⚠️ open.
```

**CMB polarization (tensor-to-scalar ratio r):**

In RFT, there is no primordial gravitational wave emission from inflation. The tensor-to-scalar ratio r should therefore be very small.

```
RFT prediction: r < 10⁻⁴   ○ [consistent with v2 values; derivation
                               from RFT parameters ⚠️]
Test: LiteBIRD (2032+), CMB-S4 (2030+)
      Sensitivity: Δr ~ 0.001
```

### 7.3 No Primary Antimatter Domains in the Cosmos

**Established qualitative prediction:**

```
RFT prediction: No free antimatter in the observable universe
                (antimatter structurally bound in resonance matrix)

Status: Consistent with PAMELA, AMS-02   ✓
        Secondary positrons (from cosmic rays): explained by secondary processes
        Primary antimatter sources: none expected
```

### 7.4 Hubble Tension as an Expected Property

```
RFT prediction: H₀ is Q-dependent → different epochs measure different values
                The Hubble tension is not a problem — it is a structural feature

Status: Qualitatively established. Quantitative H(Q) relation: ⚠️ not derived.
Test: LSST/Rubin Observatory (ongoing), Einstein Telescope (2035+)
```

### 7.5 Summary of Experimental Predictions

| Observable | Λ-CDM | RFT | Instrument | Status |
|------------|-------|-----|------------|--------|
| Early galaxies z > 10 | Difficult | Natural | JWST | ○ Hints |
| CMB r-value | ~0.001–0.01 | r < 10⁻⁴ ⚠️ | LiteBIRD/CMB-S4 | ⏳ 2030+ |
| Primary AM domains | Possible | None | PAMELA, AMS-02 | ✓ Consistent |
| Hubble tension | Problem | Expected | LSST, Euclid | ○ Hints |
| CMB cold spots | Fluctuations | Q < Q_crit regions ⚠️ | Planck, CMB-S4 | ⚠️ Open |

---

## 8. Summary and Formula Reference

The Two-Phase Model of RFT cosmogenesis describes the origin of the universe as a structural transition — not as a thermal process:

**Phase 0 (primordial chaos, Mode 0):** Q ≈ 1, no resonance matrix, no time, no physics in the Mode-1 sense. No internal perspective possible — ontological boundary of the theory.

**Phase 1 (neutral resonance matrix):** Q exceeds Q_crit1. Spin −1 (antimatter) and Spin +1/3 (quark partial state) superpose with a 3:1 frequency ratio. Shared nodes at multiples of 3 constitute the neutral resonance matrix. Antimatter is consumed/bound, not destroyed.

**Phase 2 (4:1 condensation):** Q rises further. Quantum fluctuations generate metastable 4:1 condensates. Only the matter surplus condenses into observable baryons. Baryon asymmetry without CP violation — now quantitatively derived.

The established results and their confidence:

```
✓ 3:1 frequency ratio Spin −1 / Spin +1/3 (Phase 1)   ✓ HIGH [DeepSeek verified]
✓ 4:1 matter condensation ratio (Phase 2)               ○ MEDIUM [Franz, 24.03.2026]
✓ Antimatter consumed/bound in resonance structure      ✓ HIGH [Franz Zollner, direct]
✓ "Cold" = absence of cooling requirement               ✓ HIGH [Franz Zollner, direct]
✓ η_B = Δ_α² × Q_crit1^(2/3) = 6.02×10⁻¹⁰             ✓ HIGH [Franz, 25.03.2026]
✓ Q_crit1 = α⁻¹·π² ≈ 1352.7 (ħ-free)                  ✓ HIGH [Franz, 25.03.2026]
✓ L₀ = 1/κ primary definition (ħ-free)                 ✓ HIGH [DC v10.7]

○ CMB as condensation heat                              ○ MEDIUM [conceptually consistent]
○ Cold spots = Q < Q_crit regions                       ○ MEDIUM [plausible, not calculated]

⚠️ Q_crit2 ~ 10⁶–10⁸                                   ⚠️ WORKING HYPOTHESIS
🚩 Coherence length ξ (numerical value unknown)         🚩 OPEN
🚩 n = 2/3 formal derivation from Master Equation       🚩 OPEN
🚩 Scale jump Planck↔QCD                                🚩 OPEN
```

### Formula Reference

```
QUALITY FACTOR:
Q = ω₀ / (2γ)    where ω₀ = resonance frequency, γ = damping rate

CONDENSATION CONDITIONS:
Q > Q_crit1 → resonance matrix arises (Mode 0 → Mode 1)
Q > Q_crit2 → vortex nucleation, visible matter condenses

MATRIX GENERATION RATIO (Phase 1):
ω₊₁/₃ : ω₋₁ = 3 : 1    ✓ HIGH [DeepSeek verified]

MATTER CONDENSATION RATIO (Phase 2):
4:1    ○ MEDIUM [separate process, Franz 24.03.2026]

BARYON ASYMMETRY (resolved, 25.03.2026):
η_B = Δ_α² × Q_crit1^(2/3) = 6.02×10⁻¹⁰   ✓ HIGH
Q_crit1 = α⁻¹·π² ≈ 1352.7                   ✓ HIGH (ħ-free)
n = 2/3 = (d−1)/d for d=3 (cube surface geometry)

CMB TEMPERATURE FLUCTUATION (v2, qualitative):
ΔT/T ∝ δQ/Q    ⚠️ [quantitative connection not derived]

Q-EVOLUTION (v2 parametrization):
dQ/dt > 0    ✓ [qualitatively established]
Q(τ) ~ τ^α   ⚠️ [α ≈ 0.3–0.5 not independently derived]

CANONICAL PARAMETERS (DC v10.8):
c              Only genuine fundamental input of RFT
κ              PRIMARY QUANTITY (resonance stiffness, from geometry)
L₀ = 1/κ      PRIMARY DEFINITION (ħ-free!) ✓ HIGH [DC v10.7]
   = (π/6)·l_P [numerical verification, not definition]
α⁻¹ = 4π³+π²+π = 137.036 304  [2.22 ppm — NEVER 0.67 ppm!]
Φ = 2α/(1+α²)  ≈ 0.014 596    [canonical ✓]
G·ħ = (36/π²)·c³·L₀²          [algebraic identity — NOT an independent input!]
```

---

## Dependencies and Successor Documents

**Prerequisites:**
- RFT v3 Mathematical Foundations (v3_001): Master Equation, Two-Phase Model Ch. 9, proton mass Ch. 8.2
- RFT v3 Gravitation and Spin Delay (v3_003): spin delay, G·m topological
- RFT v3 Time Emergence (v3_006): time motor, Q-evolution, emergent time
- RFT v3 Space Topology and 3D Emergence (v3_007): anchor points, resonance condition, 3D emergence
- RFT v3 Black Holes and Mode Transitions (v3_008): Mode 0 as primordial chaos, mode structure

**Successor documents:**
- RFT v3 Dark Matter and Dark Energy (v3_010): Q-gradients, cosmological evolution

---

## Translation Notes and Feedback for K2

**Glossary gaps encountered:** None. All required terms were present in RFT_v3_Glossar_EN.md v1.0.

**DE formulations requiring clarification for physicists:**
1. *"Kalt" definition* — the DE source states this clearly but briefly. The EN version expands this with the explicit physicist-oriented formulation (Section 1.2 callout) as requested in the translation brief. No DE ambiguity — just audience adaptation.
2. *"Konsumption" vs "Bindung"* — the DE source explains these as complementary. The EN version renders this as "consumption" / "binding" and adds the summary formulation from Section 5 of the translation brief ("Antimatter IS the resonance matrix"). The conceptual richness translates well.
3. *"3:1-Kondensation" in Phase 2* — the DE source (v1.0, 28.02.2026) uses "3:1-Kondensation" for Phase 2. Per DC v10.8, this is corrected in the EN version to "4:1 condensation (Phase 2)" with explicit explanation of the DE source error. The correction is marked transparently in Section 4.2.

**η_B update — clarity assessment:** The update from "open" (DE source) to "RESOLVED" (EN, DC v10.7) is clear and well-documented. The formula η_B = Δ_α² × Q_crit1^(2/3) = 6.02×10⁻¹⁰ integrates naturally into Section 6.2 with full provenance. The remaining open question (n = 2/3 formal derivation) is preserved.

**Substantive observations:**
- The two-threshold structure (Q_crit1 / Q_crit2) is much cleaner in the EN version because both values are now precisely known: Q_crit1 = α⁻¹·π² ≈ 1352.7 (✓ HIGH) vs Q_crit2 ~ 10⁶–10⁸ (⚠️). The DE source had both as poorly specified "~10³" vs "10⁶–10⁸".
- The ħ-circularity closure (L₀ = 1/κ) significantly strengthens the document: several statements in Section 6.5 that the DE source listed as "highest priority open" can now be marked as closed.
- The 3:1 vs 4:1 distinction box at the top of the document (after Preliminary Note) is a meaningful addition for the physicist audience who will immediately ask about the two ratios.

---

## Change Log

**v1.0-EN (27 March 2026 — Translation instance T9):**
- ✅ Full translation from DE v1.0 (28.02.2026)
- ✅ DC v10.7 sync: η_B = 6.02×10⁻¹⁰ → RESOLVED in Ch. 6.2
- ✅ DC v10.7 sync: Q_crit1 = α⁻¹·π² ≈ 1352.7 (exact, ħ-free) throughout
- ✅ DC v10.7 sync: ħ-circularity → CLOSED, L₀ = 1/κ primary in Ch. 6.5
- ✅ DC v10.7 sync: √(2/3) geometry → CLOSED in Ch. 6.5
- ✅ DC v10.8: "3:1-Kondensation (Phase 2)" → corrected to "4:1 condensation (Phase 2)"
- ✅ Terminology alert box: 3:1 vs 4:1 distinction (after Preliminary Notes)
- ✅ "Cold" physicist-oriented definition box in Section 1.2
- ✅ "Antimatter IS the resonance matrix" formulation in Section 3.4
- ✅ Standalone: cross-references converted to soft form
- ✅ All confidence markers preserved and updated
- ✅ All forbidden terms absent: no "annihilation", no "lattice", no "grid",
     no "vacuum" for Mode 0, no "Big Bang" as RFT term, no "wake-vortex"

---

*RFT_v3_009 — Cosmogenesis: Cold Condensation and Matter Formation*
*Translation Final | 27 March 2026 | Translation instance T9*
*Source: DE v1.0 | DC v10.7 sync: η_B resolved (25.03.2026)*
*Key result: Cold Condensation — order from resonance quality, not cooling*
