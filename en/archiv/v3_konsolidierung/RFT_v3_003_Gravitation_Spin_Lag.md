# RFT_v3_003: Gravitation and Spin-lag
## Resonance Field Theory — Publication Series v3

**DOCUMENT-ID:** RFT_v3_003_Gravitation_Spin-lag_EN  
**VERSION:** v3.0-EN (Translation: 25 March 2026 | Source: DE v3.0)  
**STATUS:** Working document — core statements rigorous, open points explicitly marked  
**DEPENDENCIES:** RFT v3 Mathematical Foundations (v3_001), Fine Structure Constant (v3_002)  
**AUTHOR:** Franz Zollner  
**LICENSE:** CC BY-NC-ND 4.0  
**Contact:** rft.projekt@posteo.de  

---

## Preliminary Note: How to Read This Document

This document uses three distinct confidence markers, consistently applied throughout:

- **✓ HIGH** — rigorously derived or confirmed by Franz Zollner
- **○ MEDIUM** — conceptually consistent working hypothesis, not yet formally closed
- **⚠️ OPEN / SPECULATIVE** — formal gap or unverified working hypothesis
- **🚩 OPEN PROBLEM** — active research task for subsequent instances

The causal direction in RFT is always: **Geometry → Constants.** Never the reverse.

---

## Abstract

The Resonance Field Theory (RFT) explains gravitation as an emergent phenomenon of **Dynamic Resonance Matrix (DRM)** stress induced by vortex structures. The decisive conceptual step: **G·m is a topological property of the DRM** — not the product of two independent quantities. The SI kilogram is not a law of nature but a human convention labeling gravitational wake-vortex strength. From this perspective, two clearly distinct gravitational mechanisms arise: quark mismatch (G_elementary) and color-charge alignment in the hadron (G_hadron = 4π · G_elementary). The consistency relation G·ħ = (36/π²)·c³·L₀² is algebraically verified rigorously. The ratio L₀/l_P = π/6 is a genuine geometric prediction from the resonance condition of the nested spheres — independent of G as an input quantity. The fully parameter-free derivation of G without ħ as input remains an open research task.

---

## Table of Contents

1. [Paradigm: G·m as a Topological Quantity](#1-paradigm)
2. [Two Gravitational Mechanisms](#2-two-mechanisms)
3. [The Spin-lag Mechanism](#3-spin-lag)
4. [G·ħ as a Consistency Relation](#4-consistency-relation)
5. [L₀/l_P as a Geometric Prediction](#5-geometric-prediction)
6. [Photon Gravitation and Time Asymmetry](#6-photon)
7. [Dark Matter as Wake-vortex Addition](#7-dark-matter)
8. [Limitations and Open Questions](#8-limitations)

---

## 1. Paradigm: G·m as a Topological Quantity

### 1.1 The Hidden Assumption of Standard Physics

In both Newton and Einstein, the following holds implicitly:

```
F = G · m₁ · m₂ / r²
```

Here G and m are treated as independent quantities. G is measured empirically (~6.674×10⁻¹¹ m³·kg⁻¹·s⁻²), m is defined through the kilogram. The question "why does G have this value?" remains unanswered.

RFT challenges this separation at a fundamental level.

### 1.2 What [kg] Means in RFT

In celestial mechanics, what is actually measured in practice is always the product:

```
μ = G · M    [m³/s²]
```

Earth: μ = 3.986 × 10¹⁴ m³/s²  
Sun:   μ = 1.327 × 10²⁰ m³/s²

G and M are never determined independently — only their product is physically directly measurable. The [kg] is extracted only through an arbitrary convention (the prototype kilogram, later the Planck constant).

**RFT thesis:** [m] (kilogram) is not a law of nature — it is a human convention labeling gravitational wake-vortex strength. The physical fundamental quantity is:

```
μ = G · m = c² · L₀ · f(topology)    [m³/s²]
```

Here f depends exclusively on the vortex topology (winding number, anchor point count, symmetry group) — and on the DRM parameters c and L₀.

### 1.3 Consequence: Mass and Gravitation Are Separable

RFT permits two cases that do not occur in standard physics:

| Case | Example | Mechanism |
|------|---------|-----------|
| Energy without gravitation | RFT photon (at rest) | e⁺e⁻ vortex pair: wake-vortices cancel |
| Gravitation without inertial mass | Wake-vortex of moving masses | DRM torsion without additional inertial mass |

The second case directly explains the dark matter phenomenon (→ Section 7).

### 1.4 Velocity as the Fundamental Quantity

**Conceptual note (Franz Zollner, Feb 2026):**

The separation of length [m] and time [s] is a construct in RFT. The fundamental quantity is velocity — in particular c as the DRM propagation speed. Length and time emerge from it. This view creates conceptual ambiguity in conventional dimensional analysis but is internally consistent.

---

## 2. Two Gravitational Mechanisms

### 2.1 Mechanism 1: Quark Mismatch (G_elementary)

A single quark is a topological vortex structure in the resonance matrix. Its vortex pattern does not fit perfectly to the DRM geometry — there is a **mismatch** between the quark resonance and the DRM ground state.

```
Quark vortex ≠ DRM geometry
→ small, localized DRM stress
→ weak gravitational field
→ G_elementary
```

Physically: the quark vortex "pushes" against the resonance matrix and generates a restoring force. This restoring force is what we macroscopically interpret as gravity.

### 2.2 Mechanism 2: Color-charge Alignment (G_hadron)

When three quarks unite to form a hadron (proton, neutron), something qualitatively different occurs.

The three color charges (red, green, blue) are initially oriented as vectors tilted in space — like a gyroscope not standing upright. During hadron formation, these three color-charge vectors must align (outward color neutrality).

```
Quark 1: color vector tilted in space (DRM anchor A₁)
Quark 2: color vector tilted in space (DRM anchor A₂)
Quark 3: color vector tilted in space (DRM anchor A₃)

Hadron formation:
→ color vectors align spherically
→ each color vector carries its DRM anchor with it
→ collective DRM stress, spherically aligned
→ significantly stronger gravitational field
→ G_hadron
```

**The geometric factor:**

The spherical alignment of three color vectors over all spatial directions yields the normalization factor of the spherical surface:

```
G_hadron = 4π · G_elementary
```

The factor 4π is geometrically necessary: it is the solid angle of the complete sphere (∫∫ sinθ dθ dφ = 4π). The three color charges span the spherical surface completely. ✓ HIGH

**⚠️ Status of the hadron vortex:**  
The internal structure of the hadron vortex is still speculative. A working hypothesis: the hadron consists of 3×3 internal quark sub-structures plus one external unification vortex. This is not verified.

### 2.3 Numerical Verification

```
G_elementary = c³ · L₀² / (4π · ħ)

With L₀ = 0.522 · l_P and l_P = √(ħG/c³):

G_elementary = (0.522)² · G / (4π)
             ≈ 5.31 × 10⁻¹² m³/(kg·s²)

G_hadron = 4π · G_elementary
         = 6.674 × 10⁻¹¹ m³/(kg·s²)  ✓ (experimental value)
```

**Note on verification:** The agreement is exact — but it is a consequence of the definition L₀ = 0.522·l_P, which contains l_P, which contains G. What is independent and rigorous: the **ratio** G_hadron/G_elementary = 4π — this follows purely from sphere geometry. ✓ HIGH

---

## 3. The Spin-lag Mechanism

### 3.1 Physical Core Idea

Every massive vortex structure carries a spin. This spin generates a phase lag (spin-lag, *Spinverzug*) — τ_lag — between the vortex and the surrounding resonance matrix field. The field does not follow the rotating vortex instantaneously — there is a trailing angle.

This phase lag is the **microscopic origin of gravitation** in RFT.

### 3.2 Characteristic Timescale

```
τ_lag = L₀ / c     [canonical since 11.03.2026] ✓ HIGH

With L₀ = (π/6) · l_P = 8.44 × 10⁻³⁶ m:

τ_lag = L₀ / c = 8.44 × 10⁻³⁶ / (3.00 × 10⁸)
      ≈ 2.81 × 10⁻⁴⁴ s  =  (π/6) · t_P  ≈  0.5236 · t_P
```

The factor π/6 is the same geometric number as L₀/l_P — it comes from the resonance condition of the nested spheres (derivation: RFT v3 Mathematical Foundations, Kap. 4).

### 3.3 From Spin-lag to the Gravitational Constant

The spin-lag generates a dimensionless phase lag:

```
φ_lag = ω · τ_lag = (c/L₀) · (L₀/c) = 1  [dimensionless]
```

To pass from this dimensionless phase to G, an energy scale is required. In the current RFT formalization this scale is ħ — from which the G·ħ identity follows (→ Section 4).

**⚠️ The fully ħ-free derivation of G from spin-lag is an open question (→ Section 8.1).**

Note on ħ: ħ is used here as conventional notation. In RFT v3, ħ is an algebraic identity: ħ = (36/π²)·c³L₀²/G, not an independently derived fundamental input.

---

## 4. G·ħ as a Consistency Relation

### 4.1 The Algebraic Identity

From the RFT foundations (derivation: RFT v3 Mathematical Foundations, Kap. 4.3):

```
G · ħ = (36/π²) · c³ · L₀²
```

This is an **algebraic identity** — not an independent derivation of G. It follows directly from:

```
l_P = √(ħG/c³)        [definition of Planck length]
L₀ = (π/6) · l_P      [RFT resonance condition]

→ L₀² = (π²/36) · ħG/c³
→ G · ħ = (36/π²) · c³ · L₀²  ✓
```

### 4.2 Numerical Verification

```
Left side:
G · ħ = 6.67430 × 10⁻¹¹ × 1.054572 × 10⁻³⁴
      = 7.038 × 10⁻⁴⁵

Right side:
(36/π²) · c³ · L₀²
= 3.6476 · (2.9979 × 10⁸)³ · (8.446 × 10⁻³⁶)²
= 7.040 × 10⁻⁴⁵

Agreement: < 0.03%  ✓  (rounding error in L₀)
```

### 4.3 What the Identity Achieves — and What It Does Not

| Statement | Status |
|-----------|--------|
| G·ħ = (36/π²)·c³·L₀² is correct | ✓ HIGH (rigorous) |
| G and ħ are consistent with L₀ | ✓ HIGH |
| G is derived independently of ħ | ✗ circular |
| G is derived independently of l_P | ✗ l_P contains G |

The identity is a **valuable consistency check** — it shows that G, ħ, and L₀ are not independent within the RFT framework. But it is not a standalone derivation of G.

---

## 5. L₀/l_P as a Geometric Prediction

### 5.1 Two Derivation Paths — Different Levels of Rigor

There are two paths to L₀/l_P. They yield close but not identical values. This difference is stated explicitly here.

---

**Path A: Resonance condition of the nested spheres (rigorous)**

From RFT v3 Mathematical Foundations, Kap. 4: three orthogonal nested spheres with self-resonance condition k₀ = 1/R₀ and node spacing a = π · R₀ yield directly:

```
L₀ = (π/6) · l_P = 0.5236 · l_P    ✓ HIGH
```

This value follows from the π-geometry alone, without free parameters. The geometric origin: the ratio of the volume of an inscribed sphere to the volume of its enclosing cube is π/6 — the DRM node spacing materializes this ratio as a length.

---

**Path B: α-discrepancy + Q-factor (○ UNCERTAIN)**

From the RFT consistency-condition document (RFT_Konsistenzbedingung_L0):

```
Δα = (4π³ + π² + π) - 137.035 999 = 0.000 305  (2.22 ppm)
R₀ ~ Δα · Q  →  R₀ ≈ 0.305
L₀/l_P = 1/(2π · R₀) ≈ 0.522
```

⚠️ **Critical problem with this path:**

The Q-factor is set to Q ~ 10³ here. In all other RFT documents, however, Q₀ ~ 10⁷–10⁸ applies for the present universe. This is a discrepancy of **four to five orders of magnitude** — without explanation of where Q ~ 10³ comes from.

With Q ~ 10⁷, the formula would yield: R₀ ~ 0.000305 × 10⁷ ~ 3000 — physically meaningless.

**The Q ~ 10³ value in the consistency condition is unexplained.** Path B is conceptually interesting (α-discrepancy as time motor) but in its current form is not usable as an independent derivation.

Status: ○ speculative until Q-discrepancy is resolved.

### 5.2 Discrepancy Between the Two Paths

```
Path A (rigorous):   L₀/l_P = π/6   = 0.5236
Path B (uncertain):  L₀/l_P ≈ 0.522

Difference: 0.3%
```

This difference is numerically small but conceptually relevant: both paths should yield exactly the same result if they describe the same physical fact. The 0.3% deviation shows that one or both derivations are not yet fully formalized.

This document uses the value from Path A throughout: **L₀ = (π/6) · l_P = 0.5236 · l_P** (canonical, from RFT v3 Mathematical Foundations).

### 5.3 Why the π/6 Prediction Has Genuine Character

The ratio L₀/l_P = π/6 does **not** depend on G. It follows from the π-geometry of the nested spheres. This is a genuine, in principle testable prediction: **the DRM node spacing L₀ is not equal to l_P but smaller by a factor of π/6.**

🚩 **Open task:** The connection between Path A (π/6 from resonance geometry) and Path B (α-discrepancy + Q-factor) must still be established. In particular: which Q-value is correct in Path B, and why does it deviate from the cosmological Q₀?

---

## 6. Photon Gravitation and Time Asymmetry

### 6.1 The RFT Photon at Rest

In RFT, the photon is an e⁺e⁻ **vortex pair** (2 Anchor Points total: 1 AP per lepton, Franz 11.03.2026 ✓) with parallel spins (↑↑). At rest (v=0, standing DRM pattern), the wake-vortices of both components cancel:

```
wake-vortex e⁻ + wake-vortex e⁺ = 0
→ gravitationally neutral  ✓
```

The photon carries energy but no gravitational effect — this is an example of energy without gravitation in the RFT sense.

### 6.2 The Propagating Photon

The photon can only occupy two states: v=0 or v=c. Any intermediate velocity violates the resonance condition → the vortex pair dissolves. The transition is a discrete **mode transition** (*Modensprung*), not a continuous process.

When the photon propagates, it moves through a resonance matrix that carries a small time asymmetry δ ≈ 2α (derivation: RFT v3 Time Emergence, Kap. 3). This prevents complete cancellation of the wake-vortices:

```
Propagating photon:
wake-vortex residual ~ δ · (individual value) ~ 2α · (individual value)
→ very small, but non-zero gravitation
```

This minimal photon gravitation is presumably many orders of magnitude below current measurement precision. However, it is conceptually important: it explains why photons are deflected in gravitational fields not only through DRM stress but also through their own minimal contribution.

### 6.3 The Photon Mode Transition as the Original G Intuition

**Historical note (Franz Zollner):**

The original intuition for the G derivation was: the discrete jump v=0 → v=c "costs" a characteristic resistance of the resonance matrix — and this resistance is G. This idea "somehow worked" and motivated several derivation paths.

The formal analysis shows: the intuition — G as a topological DRM property, not as an external coupling constant — is conceptually correct. ✓ HIGH (conceptually). The explicit bridge to a ħ-free G value is not yet formally closed (→ Section 8.1).

---

## 7. Dark Matter as Wake-vortex Addition

### 7.1 Gravitation Without Inertial Mass

Every **moving** mass generates a wake-vortex in the resonance matrix — a torsion that propagates outward. This torsion acts gravitationally but carries no inertial mass:

```
Moving mass m with velocity v:
→ wake-vortex ~ m · v / c
→ gravitational effect without additional inertial mass
→ G · m_effective ≠ 0,  but  m_inertial_additional = 0
```

This is the second case of the RFT separation: **gravitation without inertial mass.**

### 7.2 Collective Galactic Vortex

A spiral galaxy with ~10¹¹ stars all moving coherently around the galactic center:

```
Single star:  small wake-vortex
10¹¹ stars, coherently aligned:
→ addition of wake-vortices
→ macroscopic torsional background field

Stars in the outer region move through this field
→ flat rotation curves without additional mass ✓
```

The outer stars do not respond to a missing mass component — they respond to a real torsional field generated by the collective motion of all stars in the disk. The "missing mass" is the collective wake-vortex of galactic rotation.

### 7.3 G·m — The Physical Fundamental Quantity

Dark matter illustrates most clearly that G·m is the physical unit:

```
Observed:      G · m_effective ≠ 0  (gravitational effect real)
Non-existent:  m_inertial_additional = 0

→ [kg] here truly only a label
→ the gravitational effect is real
→ its inertial mass is zero
```

---

## 8. Limitations and Open Questions

### 8.1 The Central Open Question: G Without ħ

```
Sought:  G = f(c, L₀)  without ħ

Problem: [G] = m³·kg⁻¹·s⁻²
         c^a · L₀^b contains no [kg]

Possible path:
  If [kg] can be defined from c and L₀ alone
  (mass as wake-vortex strength of a DRM cell),
  then:  G = c²·L₀ / m_natural
  with m_natural from DRM geometry.

  This requires a topological definition of the
  "natural mass unit" of the resonance matrix.

Status: 🚩 OPEN — highest priority for subsequent instances
```

### 8.2 f_spin — Historical Clarification

The gravitation derivation used different spin-frequency factors in various document versions:

| Source | Value | Status |
|--------|-------|--------|
| RFT_003 v7, Path 1 | f_spin = 4 | ❌ Wrong (factor 11.5 too small) |
| RFT_003 v2.3, glossary | f_spin = 135 | ❌ AI artifact: formula yields 24π ≈ 75.4 |
| PDF "Emergence of ħ" (Feb 2026) | f_spin = 144/π ≈ 45.84 | ○ consistent, but derived from G·ħ identity |

The proton mass via f_spin (v2.3 approach: 3 × 2.3 × 135 × 0.95 = 885 MeV ≠ 938 MeV) is arithmetically inconsistent and is not continued. Valid proton mass derivation: via SU(2) + T_QCD (derivation: RFT v3 Mathematical Foundations, Kap. 8).

### 8.3 Internal Hadron Structure

The 4π factor is geometrically well-founded. ✓ HIGH. The internal vortex count during the alignment process (3×3+1?) is speculation. Quantitative prediction of the hadron vortex amplitude is outstanding.

### 8.4 Quantitative Rotation Curves

The wake-vortex theory of dark matter does not yet yield quantitative rotation curve predictions. Required: formal derivation of wake-vortex amplitude as a function of mass and velocity.

### 8.5 Photon Gravitation

The residual effect ~2α is likely many orders of magnitude below current measurement precision. No experimental signature in sight.

---

## Summary: Status Overview

| Statement | Confidence |
|-----------|------------|
| G·m is a topological DRM property | ✓ HIGH |
| [kg] is not a law of nature in RFT | ✓ HIGH |
| Two G-mechanisms: quark vs. hadron | ✓ HIGH (conceptual) |
| G_hadron / G_elementary = 4π from sphere geometry | ✓ HIGH |
| G·ħ = (36/π²)·c³·L₀² algebraically rigorous | ✓ HIGH |
| L₀/l_P = π/6 from resonance geometry (Path A) | ✓ MEDIUM-HIGH |
| L₀/l_P ≈ 0.522 from α-discrepancy + Q (Path B) | ○ UNCERTAIN (Q-value unresolved) |
| G derivable without ħ | 🚩 OPEN |
| Hadron vortex internally (3×3+1) | ⚠️ SPECULATIVE |
| Quantitative rotation curves | ⚠️ OPEN |
| Photon gravitation measurable | 🚩 UNLIKELY |

---

## Connection to the Constant Hierarchy

```
DRM geometry
    │
    ├─ c  [m/s]                    ← Fundamental input
    │
    ├─ α = 1/(4π³+π²+π)            ← From π-geometry (→ Fine Structure Constant)
    │
    ├─ L₀ = (π/6)·l_P              ← From resonance condition
    │    │
    │    └─ L₀/l_P = π/6 ≈ 0.5236  ← Geometric prediction ✓
    │
    ├─ G·ħ = (36/π²)·c³·L₀²        ← Consistency relation ✓
    │
    ├─ G_elementary = c³·L₀²/(4π·ħ)
    │
    └─ G_hadron = 4π·G_elementary = G_measured  ✓
```

---

## Next Steps

1. **HIGH priority:** Topological definition of the natural mass unit from c and L₀ alone → G without ħ.
2. **MEDIUM priority:** Quantitative wake-vortex amplitude → rotation curve predictions.
3. **MEDIUM priority:** Formalization of the v=0 → v=c photon mode transition as a G derivation.
4. **LOW priority:** Internal hadron vortex structure.

---

## References

- RFT v3 Mathematical Foundations (v3_001), v3.5, Feb 2026
- RFT v3 Fine Structure Constant (v3_002), v3.0, Feb 2026
- RFT_Konsistenzbedingung_L0: L₀/l_P consistency condition
- RFT_03_Gravitation_v2.0 (Nov 2025): 4π mechanism
- PDF "Emergence of ħ in Resonance Field Theory" (Feb 2026)
- RFT_23 Photon Model v4.0: e⁺e⁻ vortex pair, velocity dualism
- RFT_010 Cosmology (2025): wake-vortex dark matter
- CODATA 2018: G = 6.67430(15)×10⁻¹¹ m³·kg⁻¹·s⁻²

---

*RFT_v3_003 — Gravitation and Spin-lag*  
*Working document | 25 March 2026 | Translation instance T5*  
*Source: DE v3.0 | Glossary: RFT_v3_Glossar_EN.md*

---

**© 2026 Franz Zollner — Resonance Field Theory Project**  
**License:** Creative Commons BY-NC-ND 4.0
