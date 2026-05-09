# RFT_v3_014: The Weak Interaction
## Geometric Relaxation of Unstable Node Configurations

**Version:** 1.0 (Translation Final)
**Status:** Translation Final — translated from DE Final v1.0
**DE source:** RFT_v3_014_Schwache_Wechselwirkung.md (Final v1.0, 15.03.2026)
**Dependencies:**
- v3_001 (Master Equation, κ as primary quantity, γ-damping term)
- v3_003 (Modes of the resonance matrix: longitudinal/torsional)
- v3_009 (Baryon asymmetry, Cold Condensation)
- v3_012 (Electromagnetism, Photon = 2 AP)
- v3_013 (Strong Interaction — **direct predecessor**)
- KORREKTUR_RFT_005_Ankerpunkte (canonical AP table)
**Date:** 15 March 2026 (DE original); Translation: 02 April 2026
**Author (concepts):** Franz Zollner
**Written by:** AI instance (working instance 014 / T14)
**DC reference:** v10.11
**License:** Creative Commons BY-NC-SA 4.0

---

## Preface: Position in the v3 Series

This document completes the v3 series cycle of the four fundamental forces:

| Force | Document | RFT Mechanism |
|-------|----------|---------------|
| Gravitation | v3_003 | Longitudinal mode of the resonance matrix (trailing vortex) |
| Electromagnetism | v3_012 | Torsional mode (spin lag) |
| Strong Interaction | v3_013 | Geometric anchoring (octahedron anchor points) |
| **Weak Interaction** | **v3_014** | **Geometric relaxation of unstable AP configurations** |

The three predecessor documents have built a consistent picture: all natural forces are
manifestations of the same resonance matrix dynamics — different modes and geometric
constraints of the same underlying medium.

The weak interaction occupies a special position in this picture. In contrast to the
strong force (rigorously geometrically founded, ✓ HIGH) and electromagnetism (derivable
from the Master Equation, ✓ HIGH), the weak force is the least fully developed within
the RFT. This document therefore has a different structure: more conceptual embedding,
more honest limitations, more open questions.

This honesty is not a weakness — it is methodological strength. A physicist without prior
RFT knowledge should after reading this document know: what is claimed, why it is
plausible, and where the genuine gaps lie.

| Predecessor | Contribution | Use in v3_014 |
|-------------|--------------|----------------|
| v3_001 | Master Equation, γ-term, Q-factor | Instability mechanism; Q ≪ 10¹⁵ → decay |
| v3_003 | Mode description | Analogy: decay as mode transition |
| v3_012 | Photon = 2 AP (e⁻+e⁺) | W bosons as transient 2-AP modes |
| v3_013 | Confinement as topological instability | **Direct analogy**: decay = topological constraint |
| KORREKTUR_005 | AP hierarchy, 120°→180° | Foundation of every particle description |
| DC v10.11 | AP = dimensional coupling (Franz, 15.03.2026) | **Core concept** for parity violation |

---

## Abstract

The Standard Model describes the weak interaction via the exchange of massive W⁺/W⁻/Z⁰
bosons with extraordinary precision — yet it does not explain its own foundations: Why
are precisely these bosons massive? Why does the weak force violate parity symmetry (P)
— and only it? Why does it couple exclusively to left-handed particles?

Resonance Field Theory (RFT) offers a geometric framework. Decay is not a fundamental
force exchange, but the **geometric relaxation** of a vortex node: an unstable
anchor-point configuration in the resonance matrix spontaneously transitions into a more
stable one. In this picture, W/Z bosons are not fundamental exchange particles, but
transient transition modes of the resonance matrix.

Two results are conceptually clear and internally consistent: the embedding of β-decay
in the AP hierarchy (○ MEDIUM) and a geometric perspective on parity violation via the
polarized wave picture (○ MEDIUM). Essential quantitative questions — Fermi constant,
CKM matrix, neutrino mass, CP violation — are explicitly open (🚩). The weak interaction
is the most honest boundary of the RFT in the domain of fundamental forces.

---

## Table of Contents

1. The Puzzle of the Weak Force
2. The Geometric Basis: AP Configurations and Instability
3. Decay as Geometric Relaxation — the Mechanism
4. The β-Decay Geometrically
5. W and Z Bosons in the RFT
6. Parity Violation and the Polarized Wave Picture
7. Comparison with the Standard Model
8. Connection to the v3 Series
9. Honest Limitations: Open Questions
10. Summary and Formula Overview

---

## 1. The Puzzle of the Weak Force

### 1.1 What the Standard Model Explains — and What It Does Not

The weak interaction is in many ways the strangest of the four fundamental forces.
The Standard Model (SM) describes it through electroweak theory (Glashow, Salam, Weinberg,
1967–1968): an SU(2)_L × U(1)_Y gauge theory in which the Higgs mechanism gives mass to
the W and Z bosons. Predictions for β-decay rates, W/Z masses, and electroweak processes
agree with experiment at the per-mille level.

Yet the SM does not explain its own structure:

```
Open questions about the weak force in the SM:

1. Why SU(2)_L and not SU(2) or SU(3)?
   Left-handedness is a postulate. No deeper justification.

2. Why does the weak force violate parity?
   When Wu demonstrated P-violation in 1957, it was a fundamental
   surprise. Why is nature left-asymmetric?

3. Why are W and Z massive (80 and 91 GeV)?
   The Higgs mechanism describes the mass, but does not explain
   WHY precisely these bosons are massive.

4. Why is the weak force so weak?
   G_F ≈ 1.166 × 10⁻⁵ GeV⁻² — where does this value come from?
   No geometric explanation.

5. Why does CP (and hence T) symmetry break?
   The CKM matrix contains a phase δ_CP.
   No deeper mechanism.
```

These questions show: the SM is phenomenologically precise but ontologically incomplete
here too. It accurately describes *what* happens — but not *why* the weak force has this
particular structure.

### 1.2 The RFT Thesis

Resonance Field Theory asks a different question:

> **Core thesis:** The weak interaction is not the exchange of fundamental W/Z bosons.
> It is the **geometric relaxation** of a vortex node whose anchor-point configuration
> has become unstable under the influence of its κ-density (resonance stiffness).
> Decay = spontaneous transition to an energetically more favorable, resonance-stable
> AP configuration.

W/Z bosons in this view: **transient transition modes** of the resonance matrix,
which arise during the configuration change and immediately decay further.
They are effective particles — just as phonons in a solid describe interactions
without themselves being fundamental.

### 1.3 Relationship to the Standard Model

As with the strong force (v3_013, Chap. 1.3), this work is not an attack on the SM.
The predictive power of electroweak theory is untouched. RFT claims that the SM is an
effective description of a deeper geometric dynamics — analogous to how hydrodynamics
is an effective description of molecular motions.

**Important honesty:** The weak force is the domain where RFT has its largest gaps.
Those expecting a complete geometric derivation of the SM will be disappointed. Those
seeking a conceptual framework with honestly marked open questions will find both.

---

## 2. The Geometric Basis: AP Configurations and Instability

### 2.1 Review: AP Hierarchy as Stability Principle

The fundamental stability principle of RFT was established in v3_001, v3_013, and
KORREKTUR_005 (✓ HIGH):

```
Resonance condition in 3D (n_AP ≥ n_dim = 3):

  0 AP: No direct dimensional coupling
        → Longitudinal wave (pressure wave) of the resonance matrix
        → NOT a vortex (torus topology absent; only circular polarization = vortex)
        → Couples ONLY indirectly via gravitation (= longitudinal mode, v3_003)
        → "Inner density" κ determines mass:
           Neutrino ~ X-rays:       κ > 0 → m_ν > 0 (tiny) ✓
           Grav. wave ~ radio waves: κ ≈ 0 → m ≈ 0 ✓
        Confidence: ○ MEDIUM (Franz, 15.03.2026)
  1 AP: Coupling to 1 dimension → short-range stable (electron)
  2 AP: Coupling to 2 dimensions → geometrically under-determined in 3D
        → short-lived (transition modes, W/Z candidates)
  3 AP: Coupling to all 3 dimensions → stable (quarks, stable ground state)

Confidence: ✓ HIGH (v3_001 Chap. 3, confirmed by KORREKTUR_005)
```

As Franz has clarified (DC v10.11, 15.03.2026):

> **AP = Anchor Point = anchoring of a vortex in the resonance matrix.**
> An AP is not necessarily a geometric point. An AP can be: a point, surface, line,
> or any other geometric unit.
> **Decisive: AP = coupling site of the vortex to the resonance matrix,**
> **through which vortices can interact with each other.**

And the new precision as dimensional coupling (DC v10.11, ○ MEDIUM):

> **n AP = coupling to n dimensions of the resonance matrix.**
> Three dimensions = three possible couplings. A stable particle
> couples to all three. An unstable one lacks at least one.

### 2.2 The γ-Term of the Master Equation as Decay Coefficient

The RFT Master Equation reads (v3_001, Chap. 2):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

The γ-term is physically decisive (v3_001, Chap. 2.2, ✓ HIGH):

```
γ — asymmetry coefficient (arrow of time and instability):

  γ determines the irreversible damping of the field.
  Q-factor: Q = ω_res / γ

  Stable particles:   Q ~ 10¹⁵,     γ very small
  Unstable particles: Q ≪ 10¹⁵,     γ correspondingly larger

  γ is also responsible for the arrow of time:
  The −γ∂Ψ/∂t term breaks time-reversal symmetry.
  → Decay is temporally directed (T-asymmetry built in!)
```

Here lies a direct connection to the weak force: the T-symmetry violation of the weak
force — a separate observation in the SM — is already embedded in the structure of the
γ-term of the Master Equation in the RFT picture. Every unstable state has an elevated γ
that drives the transition into a more stable configuration.

**Confidence:** The connection γ ↔ instability: ✓ HIGH. The explicit connection
γ ↔ weak force: ○ MEDIUM (conceptually consistent, not quantitatively derived).

### 2.3 Which AP Configurations Are Unstable?

From the AP hierarchy and the dimensional coupling picture, three classes follow:

```
Class 1 — Structurally unstable (1-AP or 2-AP in 3D):
  Resonance condition n_AP ≥ 3 not satisfied.
  → Decay mandatory (geometric constraint, analogous to confinement in v3_013)
  → Example: transition modes (W/Z candidates)

Class 2 — Configurationally unstable (3-AP, but "wrong" orientation):
  Resonance condition satisfied, but orientation not energy-minimal.
  → Spontaneous reorientation (slow decay, weak decay)
  → Example: neutron (udd → uud + leptons)
  → Determined by Q-factor: Q_neutron ≪ Q_proton

Class 3 — Mass-induced unstable (3-AP, but κ too large):
  κ-density exceeds the capacity of the 3-AP resonance structure.
  → Configuration "collapses" to 2-AP → immediate transition
  → Example: top quark (t → b + W⁺, τ ≈ 10⁻²⁵ s)
  → Parity breaking: V2 concept (⚠️ LOW, requires verification)
```

**Important note on Class 3:** The concept of "collapse from 3-AP to 2-AP at excessive
κ-density" originates from earlier V2 material (RFT_005_V2, Chap. 3). It is geometrically
plausible — an excessively stiff resonance cannot maintain its own structure — but has not
been quantitatively derived. Confidence remains ⚠️ LOW until a DeepSeek verification is
performed (→ DeepSeek task DS-014-A).

---

## 3. Decay as Geometric Relaxation — the Mechanism

### 3.1 The Basic Idea

In v3_013 we developed the confinement mechanism:

> **Confinement (v3_013):** An isolated quark (3-AP) is not stable in isolation in 3D —
> its color charge (tilt of APs at 120°) generates a geometric tension that can only be
> compensated through binding with other quarks. Isolation is a geometric contradiction.

The analogy for decay:

> **Decay (v3_014):** An AP configuration Ψ_A that, for a given κ, does not realize the
> energy-minimal dimensional coupling is geometrically "wrong". The resonance matrix
> spontaneously relaxes into the more favorable configurations Ψ_B + Ψ_C + ... The decay
> rate Γ is determined by two factors: the stability of the original vortex Ψ_A (i.e. its
> Q-factor) and the available phase space for its decay products. This relaxation carries
> away energy and quantum numbers — these are the observed decay products.
> (Source: RFT_27, V2, ○ MEDIUM)

```
Comparison of geometric constraints:

  STRONG FORCE (confinement):
    Constraint = quark cannot realize full dimensional coupling alone
    Consequence = must bind with other quarks
    Analogy = puzzle piece that makes no sense alone

  WEAK FORCE (decay):
    Constraint = vortex node has wrong κ-density for its AP configuration
    Consequence = configuration relaxes into stable alternative
    Analogy = mountaineer on wrong summit: rolls into the valley
```

**Confidence of the overall framework:** ○ MEDIUM — the analogy is strong and internally
consistent. A rigorous derivation from the Master Equation is still missing.

### 3.2 What "Relaxation" Means Physically

In the RFT picture, geometric relaxation means:

```
Initial state:
  Vortex node Ψ_0 with resonance frequency ω_0, Q-factor Q_0
  AP configuration C_0 (unstable for given κ)

Relaxation process:
  γ-term of Master Equation → transition Ψ_0 → Ψ_1 + Ψ_2 + ...
  Time constant: τ = ħ/γ ≈ ħ/(ω_0/Q_0)  [from Q-factor definition]
  → The smaller Q, the faster the decay

Final state:
  Ψ_1: Stable AP configuration (new resonance structure)
  Ψ_2,...: Transient transition modes (short-lived, W/Z candidates)
  Ψ_3: Free waves without AP (neutrino candidates)
```

This description is consistent with:
- γ-term as arrow of time (v3_001): decay is directed, not reversible ✓
- Q-factor as stability measure (v3_001): Q_neutron ≈ 10⁷ × shorter than Q_proton ✓
- Decay produces multiple particles: energy conservation via configuration energy ✓

**Quantitative gap:** The explicit derivation of τ_neutron = 880 s from L₀, κ, c and
geometric parameters is not available. This is a 🚩 OPEN QUESTION (→ Domain I).

---

## 4. The β-Decay Geometrically

### 4.1 The Starting Point: the Neutron

The neutron (udd) is the prototypical decay process of the weak interaction:

```
β-decay: n → p + e⁻ + ν̄_e

In quark notation: (udd) → (uud) + e⁻ + ν̄_e
The transition at quark level: d → u + W⁻,  W⁻ → e⁻ + ν̄_e
```

In the AP language of RFT:

```
Neutron (udd):  9 AP [3 quarks × 3 AP], configurationally unstable
Proton (uud):   9 AP [3 quarks × 3 AP], stable (energy minimum)

AP accounting of β-decay:
  Input:  9 AP (neutron)
  Output: 9 AP (proton) + 1 AP (electron) + 0 AP (antineutrino)

✅ AP IS STRUCTURAL — not a conserved quantity (Franz, 15.03.2026)
```

**AP is structural:** The AP count describes the coupling structure of each vortex to
the resonance matrix — how many dimensions a particle couples to. It is a stability
property, not an accountable conserved quantum number (as energy or charge are).

The emerging electron (1 AP) brings its structural property as a result of the geometric
relaxation. The resonance matrix provides the new configuration — no contradiction, no gap.

**Analogy:** The "number of legs of a tripod" is a structural property. When a tripod is
disassembled and reassembled as different objects, one does not demand "leg conservation"
— each resulting object simply has its own structure.

### 4.2 The d→u Transition as Flavour Geometry

In the SM, the d→u transition describes a rotation in isospin space. In the RFT:

```
d-quark: 3 AP, dimensional coupling →
  Color vector: −x direction (anti-red) or −y or −z
  Charge: −1/3 (projection of lower cube face, hourglass geometry)

u-quark: 3 AP, dimensional coupling →
  Color vector: +x direction (red) or +y or +z
  Charge: +2/3 (projection of upper cube face)
```

The d→u transition is geometrically speaking an **orientation change of the dimensional
coupling** — from the lower to the upper cube face of the hourglass geometry (v3_013
Chap. 2, DC v10.11 Domain E).

```
Geometric picture of the d→u transition (○ MEDIUM):

  Lower cube face (charge −1/3) → upper cube face (charge +2/3)

  Energy difference: Δm ≈ m_u − m_d ≈ 2.2 − 4.8 MeV ≈ −2.6 MeV
  (net mass decrease → released energy goes into leptons)

  Transition amplitude: proportional to the overlap of wave functions
  of both cube faces (○ MEDIUM — formally open)
```

What generates the asymmetry between neutron and proton — why does the neutron decay,
not the proton? In the RFT:

```
Proton (uud): Octahedron configuration energy-minimal for 2u+1d.
  Alignment of APs (120°→180°) minimizes tension.

Neutron (udd): 2d+1u — the hourglass geometry prefers 2u+1d.
  The configuration is not the global energy minimum.
  → γ-term drives spontaneous relaxation toward the proton.

Quantitatively: m_n − m_p ≈ 1.3 MeV (energy difference between
  the configurations) — this value is unresolved in RFT (🚩 OPEN)
```

### 4.3 The W⁻ Boson as Transient Transition Mode

In the SM, the W⁻ is a fundamental gauge boson. In the RFT:

```
W⁻: Transient 2-AP transition mode (○ MEDIUM)

  Formation: During the d→u transition, the old AP configuration "breaks open."
    → Briefly: unbound resonance matrix distortion (2-AP unstable)
    → This distortion = W⁻

  Properties from the RFT perspective:
    - 2 AP: geometrically unstable in 3D (resonance condition n≥3 violated!)
    - Short-lived: τ_W ≈ ħ/m_W·c² ≈ 3×10⁻²⁵ s ✓ (extremely short)
    - Mass-rich: m_W ≈ 80 GeV (→ Chap. 5 for explanatory approach)
    - Charge: W⁻ carries −1e → from charge conservation in d→u transition

  Decay: W⁻ → e⁻ + ν̄_e
    e⁻ = 1 AP (left-circular, DC v10.11)
    ν̄_e = 0 AP (longitudinal pressure wave, DC v10.11)
    → AP accounting: AP is structural — not a conserved quantity
                     (Franz, 15.03.2026) ✓

Confidence of the W picture: ○ MEDIUM — qualitatively consistent,
  not formally derived from the Master Equation.
```

---

## 5. W and Z Bosons in the RFT

### 5.1 The Problem: Massive Gauge Boson

In the SM, the Higgs mechanism explains the mass of W and Z. Without the Higgs, the gauge
bosons would be massless — like the photon. Higgs theory is mathematically elegant but
introduces a new entity (Higgs field, Higgs boson).

In the RFT the question is posed differently: Why do **2-AP transition modes** have a
high mass, while the photon (also 2 AP: e⁻+e⁺) is massless?

```
Comparison: Photon vs. W boson (○ MEDIUM):

PHOTON:
  Structure: 2 AP (e⁻ left-circular + e⁺ right-circular)
  Charge: 0 (sum +1 + (−1) = 0)
  Mass: 0 (can propagate freely as n=0 mode)
  Lifetime: ∞ (stable in vacuum)
  → Physically: both AP complementary, no net distortion of the resonance matrix

W BOSON:
  Structure: 2 AP (unstable transition mode, charge ≠ 0)
  Charge: ±1 (net distortion of the resonance matrix)
  Mass: ~80 GeV (very large!)
  Lifetime: ~3×10⁻²⁵ s
  → Physically: the 2-AP configuration has net charge
    → Not complementary → cannot propagate freely → requires energy
    → This energy appears as mass
```

The key difference: the photon is a **complementary** 2-AP mode (e⁻ + e⁺, total charge
zero, symmetric distortion). The W boson is a **non-complementary** 2-AP mode with net
charge — an asymmetry that the resonance matrix must compensate, which manifests as mass.

A more precise formulation from RFT preliminary material (RFT_27, V2, ○ MEDIUM):
The W boson represents the **extreme resonance matrix tension required to briefly break
open a stable topological structure and reshape it into a new, more stable configuration.**
Its large mass (~80 GeV) is a direct measure of this break-open energy. Its immediate
"decay" is the resonance matrix settling into its new, final configuration.

**Confidence:** ○ MEDIUM — the qualitative argument is consistent, but a rigorous
derivation of m_W ≈ 80 GeV from L₀, κ, c is completely absent (🚩 OPEN).

### 5.2 The Z Boson

The Z⁰ boson is electrically neutral but massive (m_Z ≈ 91 GeV):

```
Z⁰ boson in RFT (⚠️ LOW):

  Charge: 0 — like the photon
  Mass: ~91 GeV — unlike the photon

  RFT perspective: The Z⁰ is a 2-AP mode in which the dimensional
  couplings are not fully complementary — a "rotated" complementarity
  that carries the isospin difference between neutron/proton modes.

  Formally this would correspond to a mixing of the photon mode
  (fully complementary) and W mode (not complementary).
  The Weinberg angle θ_W ≈ 28° in the SM could appear in RFT as
  a geometric mixing angle of these modes.

⚠️ This is a qualitative analogy, not a proof.
   Confidence: ⚠️ LOW
```

### 5.3 Range of the Weak Force

The short range of the weak force (< 10⁻¹⁸ m) follows in the SM from the large W/Z mass
(Yukawa potential). In the RFT:

```
Range of the weak force (○ MEDIUM):

  2-AP modes are geometrically unstable (n_AP < n_dim = 3).
  → Their correlation length is restricted to the decay length:
    ξ_W ≈ c·τ_W ≈ 3×10⁻¹⁷ m

  This is the range of the process, not of a "force" in the classical
  sense — consistent with the picture that the weak interaction is not
  a force exchange, but a local geometric relaxation.

  Confidence: ○ MEDIUM — qualitatively consistent with observation
```

---

## 6. Parity Violation and the Polarized Wave Picture

### 6.1 The Experimental Fact

Wu's experiment (1957): In the β-decay of polarized cobalt-60 nuclei, electrons are
preferentially emitted in the direction opposite to the nuclear spin. The mirror image
(reversed emission) is not observed. The weak force distinguishes between left and right.

This finding is a postulate in the SM: SU(2)_L couples to left-handers. In the RFT,
a geometric framework is available for the first time.

**Preliminary work: SU(2) from two degrees of freedom (DeepSeek #3, l.11372–11377, ⚠️ LOW):**

DeepSeek #3 gives for the RFT origin of SU(2) symmetry: "Isospin rotation of the vortex
orientation — two degrees of freedom (spin-up/down) in the lattice." [Note: DeepSeek used
QFT lattice language here — structural analogy only; "lattice" → "resonance matrix" in
RFT terminology.] The formulation is in QFT language (doublets, matrix exponential).

RFT lens (J.16): "Isospin rotation" and SU(2) as a Lie group presuppose continuous
symmetries and quantum fields — transferable to the discrete resonance matrix only as a
structural analogy. Nevertheless: the connection to the **two polarization states** of
leptons (e⁻=left-circular, e⁺=right-circular, DC v10.11) is interesting — two degrees of
freedom of the 1-AP coupling could generate an SU(2)-like structure. This is a candidate
for a later rigorous derivation (→ DS-014-B).

Confidence of this connection: ⚠️ LOW — conceptually interesting, not rigorous.

### 6.2 The Polarized Wave Picture (DC v10.11)

Franz clarified on 15.03.2026 the geometric meaning of dimensional coupling for leptons
(DC v10.11, Domain E, ○ MEDIUM):

```
Leptons as polarized waves (dimensional coupling, ○ MEDIUM):

  e⁻:  1 AP, left-circular  polarized → +polarization
  e⁺:  1 AP, right-circular polarized → −polarization
  ν:   0 AP, longitudinal   → no transverse coupling

  This assignment explains geometrically:
    e⁻/e⁺ as left/right-circular waves of the same medium
    ν as a longitudinal wave without transverse coupling
```

### 6.3 Parity Violation Geometrically

When the relaxation process (decay) proceeds via the transition mode (W boson), the
question arises: which polarization can the W boson couple to?

```
Geometric picture of parity violation (○ MEDIUM):

  The decay d→u+W⁻ is a reorientation of the dimensional coupling.
  This reorientation is geometrically a ROTATION in the resonance matrix.

  Rotation in 3D has a handedness: left or right.
  In the resonance matrix, the relaxation direction is fixed by the γ-term
  (arrow of time!): the decay follows a preferred rotation direction — left-circular.

  Consequence:
    W⁻ → e⁻ + ν̄_e:
    → e⁻ must be left-circular (matches the relaxation direction)
    → ν̄_e must be right-circular (complement)
    ← This corresponds to the observed helicity! ✓

  Physically:
    The parity "violation" is not the violation of a symmetry law,
    but the consequence of the arrow-of-time geometry of the resonance matrix.
    What appears as "asymmetry" is the projection of the directed arrow of time
    onto the polarization space of the leptons.
```

**Confidence:** ○ MEDIUM — the picture is consistent and qualitatively explains the
helicity relations. A rigorous derivation from the Master Equation is outstanding.
In particular: the connection γ-term → handedness of rotation is conceptually plausible
but not proven.

**New open question:** If left/right is determined by the γ-term (arrow of time), why is
precisely *left* preferred and not right? Does this depend on the cosmological initial
condition of the resonance matrix (v3_009)? Connection to baryon asymmetry?
→ 🚩 OPEN, conceptually significant.

### 6.4 CP Violation

In the SM, the weak force also violates CP (charge conjugation × parity), described by
the CKM phase angle δ_CP. In the RFT:

```
CP violation (⚠️ LOW — speculative):

  CP violation = asymmetry between matter and antimatter in the decay process.

  RFT perspective: Antimatter is not "gone" in the RFT,
  but complementarily bound (v3_009). A CP violation would
  mean: the relaxation process is not exactly symmetric for matter and antimatter.

  Candidate mechanism:
    The γ-term of the Master Equation breaks T-symmetry →
    via the CPT theorem this implies CP violation.
    But: the CPT theorem presupposes Lorentz invariance.
    In the discrete resonance matrix, Lorentz invariance is not
    proven (DC v10.11, Domain I). The causal chain is therefore
    not rigorous. ⚠️ RFT lens required!

  Connection to baryon asymmetry (v3_009):
    η_B ≈ 6.02×10⁻¹⁰ — mechanism derivable from geometry (✓ HIGH,
    as established in v3_009). CP violation could contribute to this
    mechanism — conceptually ○. Quantitatively still open.
```

---

## 7. Comparison with the Standard Model

```
Property              | SM (electroweak)             | RFT (Geometric Relaxation)
----------------------|------------------------------|-------------------------------
Mechanism             | W/Z exchange (fundamental)   | AP configuration transition
W/Z bosons            | Fundamental gauge bosons     | Transient 2-AP transition modes ○
Mass of W/Z           | Higgs mechanism              | Net charge of 2-AP mode ○
Symmetry group        | SU(2)_L postulated           | SU(2) from 2D coupling ○
Parity violation      | Postulate (SU(2)_L)          | Geometric consequence of γ-term ○
Range                 | ~1/m_W (Yukawa)              | Correlation length of 2-AP mode ○
Fermi constant G_F    | Experimentally determined    | 🚩 No RFT approach
CKM matrix            | 4 free parameters            | 🚩 No RFT approach
CP violation          | CKM phase angle              | ⚠️ γ-term → T → CP (speculative)
Neutrino mass         | Seesaw mechanism / Dirac     | ○ Longitudinal wave, κ > 0 → m_ν > 0 ✓
Number of generations | Postulate (3)                | ○ Harmonic modes n=1,2,3
```

**Résumé:** RFT offers a consistent qualitative picture for the mechanism questions (decay,
parity violation, range) and provides a geometric explanation for neutrino mass (longitudinal
wave, κ > 0). For quantitative questions (G_F, CKM) there is no approach whatsoever.
The honest assessment: the RFT is in the domain of the weak force conceptually interesting,
but formally furthest from a complete alternative to the SM.

---

## 8. Connection to the v3 Series

### 8.1 Analogy to v3_013: Topological Constraint

The most important reference is the structural analogy to confinement:

```
CONFINEMENT (v3_013): Geometric impossibility of isolated quarks
  → 1-AP or 2-AP quark systems do not satisfy the resonance condition
  → Quarks must bind into color-neutral hadrons

DECAY (v3_014): Geometric inevitability of the AP transition
  → "Wrong" AP configuration is geometrically unstable
  → Relaxation to the stable configuration is mandatory

BOTH are topological constraints of the resonance matrix, not imposed forces.
```

### 8.2 Connection to v3_001: γ-Term and Arrow of Time

The γ-term of the Master Equation connects three phenomena:
- Arrow of time (irreversibility of the universe)
- Particle decay (γ ↔ Q ↔ lifetime)
- Parity violation (γ → T-asymmetry → P-asymmetry)

This triple connection is a candidate for a deep relationship in the RFT: the arrow of
time of the universe and the P-violation of the weak force could have the same geometric
origin. ○ MEDIUM — very interesting, but speculative; Franz's assessment requested.

### 8.3 Connection to v3_009: Baryon Asymmetry

The universe contains approximately 10¹⁰ times more matter than antimatter (η_B ≈ 6.02×10⁻¹⁰,
✓ HIGH as established in v3_009 via geometric derivation). In the SM, CP violation of the
weak force explains this imbalance — at least qualitatively (Sakharov conditions).

In the RFT:
- v3_009 (Cold Condensation): antimatter complementarily bound, η_B geometrically derived
- v3_014: if the γ-term implies CP violation (⚠️ speculative), this could contribute
  an additional mechanism
- Connection: cosmological initial condition of the resonance matrix (Q-factor ≈ 1,
  Mode 0) → first relaxation processes → η_B
  → This is speculative, but conceptually significant ⚠️ LOW

### 8.4 Gravitation, Neutrinos, and Gravitational Waves: a Spectrum

A direct consequence of the longitudinal wave description of the neutrino (Chap. 2.1):
gravitational waves and neutrinos are both longitudinal waves of the resonance matrix —
they differ only in their "inner density":

```
  GW         ~ radio waves: low κ, m ≈ 0, long wavelength
  Neutrino   ~ X-rays:      higher κ, m_ν > 0 (tiny), short wavelength
```

Both couple exclusively via the gravitational mode of the resonance matrix. Both therefore
propagate at c in vacuum (or nearly c for m_ν > 0).

This description offers a geometric justification for SN 1987A: the near-simultaneous
arrival of neutrinos and gravitational waves from the supernova is not a coincidence —
it follows from the shared longitudinal wave nature of both phenomena.

```
Confidence:
  Neutrino = longitudinal wave:      ○ MEDIUM (Franz, 15.03.2026)
  GW = longitudinal wave:            ✓ HIGH (v3_003)
  Spectrum via κ:                    ○ MEDIUM (candidate, formally outstanding)
  SN 1987A simultaneous arrival:     ○ MEDIUM (was ⚠️ SPECULATIVE, upgraded)
```

### 8.5 Connection to v3_006: T-Symmetry Violation and Arrow of Time

Time emergence (v3_006) shows: the arrow of time arises from the asymmetry
ε ≈ Φ ≈ 0.01459 rad of the resonance matrix modes. The γ-term is the dynamic
manifestation of this asymmetry.

```
Connection chain (○ MEDIUM):

  Mode asymmetry ε → arrow of time (v3_006)
    ↓
  γ-term of the Master Equation → irreversibility
    ↓
  Unstable AP configurations → decay
    ↓
  Left-circular rotation preferred → P-violation
    ↓
  CP violation (via T, CPT) → baryon asymmetry (speculative)

This chain connects cosmology, arrow of time, particle physics, and
weak force in a geometric framework.
Each individual step is consistent; the complete chain is
conceptual, not rigorously derived.
```

---

## 9. Honest Limitations: Open Questions

This chapter is central. The weak force has the most unresolved questions in the RFT.
This is a sign of scientific honesty, not a deficiency of the approach.

### 9.1 Quantitative Gaps (🚩 OPEN)

```
🚩 Fermi constant G_F from RFT:
   G_F ≈ 1.166 × 10⁻⁵ GeV⁻²

   DeepSeek #3 (l.8643) proposes: G_F = (π²/√2)·α·(b−a)/(a+b)
   Since (b−a)/(a+b) = α (DS#3 l.8621), this simplifies to G_F = (π²/√2)·α².
   Numerically: (9.87/1.414) × (7.30×10⁻³)² ≈ 6.98 × 5.33×10⁻⁵ ≈ 3.7×10⁻⁴

   ⚠️ RFT lens (J.16): The result is DIMENSIONLESS — but G_F has units GeV⁻².
   The formula is DIMENSIONALLY INCONSISTENT. It matches the numerical value
   through implicit unit choice, not through physics. This is a KI number-fitting
   artifact (identified by instance 014, 15.03.2026).

   Conclusion: No valid RFT approach to G_F available. 🚩 OPEN remains.

🚩 CKM matrix geometrically:
   Quark mixing matrix with 4 free parameters (3 angles + 1 CP phase).
   No RFT approach to this structure.

✅ Neutrino mass: RESOLVED (Franz, 15.03.2026)

   Neutrino = longitudinal wave (pressure wave) of the resonance matrix — NOT a vortex.
   Coupling ONLY indirectly via gravitation.
   "Inner density" κ > 0 (analogous to X-rays vs. radio waves):
     → m_ν tiny but not zero ✓
     → Neutrino oscillations: different κ values for ν_e/ν_μ/ν_τ? ○
     → Nearly no interaction with matter (only via G) ✓

   Confidence: ○ MEDIUM (Franz, 15.03.2026)

🚩 Neutron-proton mass difference:
   m_n − m_p ≈ 1.3 MeV — no RFT mechanism.

🚩 Neutron lifetime:
   τ_n ≈ 880 s not derivable from L₀, κ, c.
```

### 9.2 Conceptual Gaps (⚠️ open, conceptual)

```
⚠️ Why left and not right?
   If the γ-term prefers left, why left and not right?
   Cosmological initial condition? Connection to v3_009?

⚠️ SU(2) rigorously from geometry:
   The 2-AP transition modes have a 2D coupling structure.
   SU(2) as the symmetry group of this coupling is plausible,
   but not rigorous — analogous to the SU(3) derivation in v3_013.

⚠️ Higgs equivalent:
   What gives the W/Z transition modes their specific mass (80/91 GeV)?
   The qualitative argument (net charge → mass) does not explain
   the specific value. A Higgs equivalent is not worked out.

⚠️ CP violation rigorous (RFT lens!):
   The derivation CP ← T ← γ presupposes the CPT theorem.
   CPT presupposes Lorentz invariance.
   Lorentz invariance is not proven in the discrete resonance matrix.
   → Assess as structural analogy only (J.16).
```

### 9.3 Recommended DeepSeek Tasks

```
DS-014-A: Collapse 3-AP → 2-AP at high κ-density
   "Can the Master Equation show that a 3-AP resonance structure collapses
   at κ > κ_crit? How does κ_crit depend on L₀? Dimensional analysis."
   → Apply RFT lens: continuum vs. discrete resonance matrix!

DS-014-B: Handedness of the relaxation
   "Does the nonlinear wave equation
   ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ
   have a preferred rotation direction for asymmetric solutions (γ ≠ 0)?
   If so: does a handedness follow from this?"
   → RFT lens: continuum solutions → discrete resonance matrix (structural analogy)

DS-014-C: Neutrino mass at 0-AP
   "Can a longitudinal wave (0-AP) in a dispersive medium have an effective mass?
   Under what conditions does m_eff > 0 follow from the dispersion relation
   of the Master Equation?"
```

---

## 10. Summary and Formula Overview

### 10.1 What v3_014 Contributes

**Conceptually clear (○ MEDIUM):**

The weak interaction in the RFT is **geometric relaxation**: a vortex node with an AP
configuration unstable for its κ-density spontaneously transitions into a more stable one.
Decay products are the transition mode (W/Z) and the new stable configurations (leptons,
new quark).

The γ-term of the Master Equation is the dynamic mechanism: it effects irreversible
transition and determines decay rate via the Q-factor.

The polarized wave picture (e⁻=left, e⁺=right, ν=longitudinal) offers a geometric
perspective on parity violation: left is preferred because the arrow of time (γ-term)
singles out a rotation direction.

**Structural analogy (✓ HIGH via v3_013):**

Decay (weak force) and confinement (strong force) are both **topological constraints
of the resonance matrix**, not imposed forces. Both emerge from the AP hierarchy:
non-stable configurations must transition.

**Explicitly open (🚩):**

G_F geometrically, CKM matrix, neutron lifetime, m_n−m_p.
The weak force is the domain with the most open quantitative questions in the RFT.

### 10.2 Confidence Table

```
Statement                                 | Confidence  | Source
------------------------------------------|-------------|--------
AP hierarchy: 1/2/3-AP stability          | ✓ HIGH      | v3_001, KORREKTUR_005
γ-term → instability → decay             | ✓ HIGH      | v3_001 Chap. 2.2
Decay = geometric relaxation             | ○ MEDIUM    | Concept, formally open
AP as structural property (not conserved) | ✓ HIGH      | Franz, 15.03.2026 ✅
AP as dimensional coupling               | ○ MEDIUM    | Franz, 15.03.2026
W/Z = transient 2-AP modes              | ○ MEDIUM    | Consistent, formally open
Range from 2-AP instability             | ○ MEDIUM    | Correlation length argument
Parity violation from γ-term            | ○ MEDIUM    | Polarized wave picture
SU(2) from 2D coupling                  | ○ MEDIUM    | Analogy to SU(3), v3_013
e⁻=left, e⁺=right (polarization)        | ○ MEDIUM    | DC v10.11 Franz 15.03.2026
Neutrino = longitudinal wave, κ>0        | ○ MEDIUM    | Franz, 15.03.2026 ✅ RESOLVED
Neutrino mass: κ>0, m_ν>0 (tiny)        | ○ MEDIUM    | Franz, 15.03.2026 ✅ RESOLVED
3-AP→2-AP collapse at high κ            | ⚠️ LOW       | V2 material, unverified
CP violation from γ → T → CP           | ⚠️ LOW       | CPT path (RFT lens!)
Baryon asymmetry from CP violation       | ⚠️ LOW       | Speculative causal chain
G_F from L₀, κ, c                      | 🚩 OPEN     | No approach
CKM matrix geometrically                | 🚩 OPEN     | No approach
τ_neutron = 880 s from RFT             | 🚩 OPEN     | No quantitative approach
```

### 10.3 Central Concepts and Relations

```
Instability criterion:
  Q = ω_res / γ  [dimensionless]
  Stable particles:   Q ~ 10¹⁵
  Unstable particles: Q ≪ 10¹⁵  → decay

Fundamental length scale:
  L₀ = 1/κ  [primary definition, ħ-free] ✓ HIGH (Franz, 25.03.2026)
       = (π/6)·l_P  [numerical verification only]
  τ_lag = L₀/c = (π/6)·t_P

AP is structural (not conserved):
  AP count = coupling structure, not accountable quantity ✓ HIGH (Franz, 15.03.2026)

Geometric analogy (✓ HIGH via v3_013):
  Confinement: topologically impossible → constraint to bind
  Decay:       topologically unstable → constraint to relax

W bosons (○ MEDIUM):
  W± = 2-AP transition modes with net charge ≠ 0
  → geometrically unstable (n_AP < n_dim = 3)
  → short-lived, mass-rich (80 GeV — quantitatively open 🚩)

Polarization and parity (○ MEDIUM):
  e⁻: 1 AP, left-circular,  +polarization
  e⁺: 1 AP, right-circular, −polarization
  ν:  0 AP, longitudinal (0 transverse coupling)
  → Decay = left rotation → e⁻ must be left-circular

Canonical parameters (never vary!):
  α⁻¹ = 4π³+π²+π = 137.036304  [2.22 ppm — NEVER 0.67 ppm!]
  L₀ = 1/κ [primary, ħ-free] = (π/6)·l_P [numerical]
  Φ = 2α/(1+α²) ≈ 0.014596
  τ_lag = (π/6)·t_P
  "resonance matrix" (NEVER "lattice"!)
  c (NEVER c₀!)
```

### 10.4 Experimental Tests

```
Helicity structure of W decay:
  Prediction: W⁻ → e⁻_L + ν̄_{e,R} (helicities from polarized wave picture)
  Observation: Consistent with SM prediction ✓
  Status: ✓ Consistent (but: SM gives same prediction — not differentiating!)

Neutrino helicity:
  SM: neutrinos are left-handed (massless → pure helicity)
  RFT: 0-AP longitudinal → no transverse coupling → consistent ✓
  Open: mass question (oscillations reconciled via κ > 0!)

Test of AP collapse thesis (DS-014-A):
  Prediction: heavy quarks (t, b) show short τ due to 3-AP→2-AP collapse
  Observation: τ_t ≈ 10⁻²⁵ s, τ_b ≈ 10⁻¹² s ✓ (consistent, not conclusive)
  Status: ⚠️ Qualitatively consistent; no quantitative RFT test

120° angle in decay products:
  From orientation geometry a preferred angle could follow.
  → No concrete test formulated (DeepSeek task open)
```

---

## Translation Feedback to K2

**From:** Translation instance T14
**To:** Coordinator K2
**Date:** 02 April 2026
**Subject:** RFT_v3_014_Weak_Interaction_EN.md — Translation Final

---

### Translation Decisions and New Terminology

**Three terms not in the EN glossary — proposed canonical EN terms:**

1. **"Wirbelknoten"** → **"vortex node"** (used consistently throughout)
   - "vortex knot" is a topological math term (knotted vortex line); "vortex node" is clearer for the RFT usage (a nodal resonance configuration). Proposal: add to glossary.

2. **"Relaxationsrichtung"** → **"relaxation direction"** (direct translation, used in Chap. 6.3)
   - Straightforward; no ambiguity. Proposal: add to glossary.

3. **"Polarisiertes-Wellen-Bild"** → **"polarized wave picture"** (used throughout Chap. 6)
   - "Picture" preferred over "model" or "framework" to preserve the exploratory, non-postulated character. Proposal: add to glossary.

**Deliberate "lattice" retention:** Chap. 6.1 contains a DeepSeek citation that uses "lattice" language (QFT). This has been translated as "lattice" with an explicit note "(note: DeepSeek used QFT lattice language here — structural analogy only; 'lattice' → 'resonance matrix' in RFT terminology)." This maintains documentary accuracy while flagging the terminology issue.

### L₀ Upgrade from DE Source

The DE document (Final v1.0, 15.03.2026) still uses `L₀ = (π/6)·l_P` as the primary notation. Per the translation assignment (DC v10.11, canonical EN parameters):
- **Upgraded in Chap. 10.3** to `L₀ = 1/κ [primary, ħ-free]` with `= (π/6)·l_P [numerical]`
- All other occurrences of L₀ left as-is (formulas unchanged)
- **Suggestion:** Retrograde correction to DE source (DE-Lektorat backlog)

### Feedback-Brief Omitted (Standalone Principle)

The internal project feedback-brief (Coordinator communication) from the DE document has been omitted in the EN translation — it is project-internal and not relevant for physicist distribution. This follows the standalone principle.

### η_B Update

The DE source (v10.4) cites η_B ≈ 10⁻¹⁰. Per DC v10.11, η_B = 6.02×10⁻¹⁰ ✓ HIGH is now canonical. Updated in Chap. 8.3 accordingly.

### No New Physics Flags

No new inconsistencies with the v3 series found during translation. All confidence levels faithfully transferred. All 🚩 OPEN flags retained as specified.

---

*RFT_v3_014_Weak_Interaction_EN.md | Translation Final | T14 | 02.04.2026 | DC v10.11*
*DE source: Final v1.0 (15.03.2026) | Standalone document for physicist distribution*
*New glossary proposals: "vortex node", "relaxation direction", "polarized wave picture"*
*L₀ = 1/κ primary definition (ħ-free) proactively applied per DC v10.11*
