# RFT_v3_010: New Cosmology — Resolving the Dark Sector
## through Resonance Matrix Mechanics

**DOCUMENT-ID:** RFT_v3_010_New_Cosmology_Dark_Sector_EN
**VERSION:** v1.0-EN (Translation: 27 March 2026 | Source: DE v1.0, 06.03.2026)
**STATUS:** Translation Final
**AUTHOR:** Franz Zollner
**LICENSE:** Creative Commons BY-NC-SA 4.0
**Contact:** rft.projekt@posteo.de
**DEPENDENCIES:** RFT v3 Cosmogenesis (v3_009), RFT v3 Time Emergence (v3_006),
  RFT v3 Mathematical Foundations (v3_001), RFT v3 Gravitation and Spin Lag (v3_003)

**Note on terminology:** All "Dynamic Resonance Matrix / DRM" terminology replaces
the German "Raummatrix" and "Gitter". "DRM mechanics" = "Gittermechanik" (DE title).
"DRM strain" = "Gitterverspannung". The German title used "Gittermechanik" — a term
that implies rigid crystal structure and is explicitly prohibited in RFT (DC v10.8).
The canonical English title is: *Resonance Matrix Mechanics.*

---

## Foreword: Position in the v3 Series

This document completes the first full round of v3 cosmology. After v3_009 described
the origin of space and matter through Cold Condensation — the transition from Mode 0
(primordial chaos) to the ordered Dynamic Resonance Matrix — v3_010 addresses the
large-scale structure of the present universe: the cosmic web, observed gravitational
anomalies, and accelerated expansion.

| Document | Contribution | Relevant for v3_010 |
|----------|-------------|---------------------|
| v3_001 | Master Equation, Q-factor definition | ✓ Direct |
| v3_003 | Topological mass, G·m | ✓ Cross-reference |
| v3_006 | dQ/dt > 0, L_eff(Q) | ✓ Direct |
| v3_009 | Cold Condensation, filaments as condensation scars | ✓ Direct |

**Core thesis:** The "dark sector" (≈95% of the cosmic energy inventory in Λ-CDM)
is not a *What* — no new particle, no new field. It is a *How* — resonance matrix
mechanics of the Dynamic Resonance Matrix (DRM). Dark matter is filament strain.
Dark energy is space maturation. The Hubble tension is not a crisis: it is a
structural prediction.

---

## Abstract

The standard cosmological model Λ-CDM describes the evolution of the universe with
outstanding precision — CMB power spectrum, Baryon Acoustic Oscillations, Type Ia
supernovae. These achievements are uncontested. Yet Λ-CDM requires three components
whose physical nature remains completely unknown: dark matter (≈27%), dark energy
(≈68%), and an inflationary phase. Together, these account for 95% of the cosmic
inventory.

The Resonance Field Theory (RFT) offers a mechanical alternative: gravitational
anomalies on galactic scales arise from the intrinsic strain of cosmic filaments —
topological scars of the original Cold Condensation. Accelerated expansion is the
energetic signature of space maturation (dQ/dt > 0). The Hubble tension is not a
measurement inconsistency — it is a direct, qualitatively established consequence of
the Q-dependence of light propagation.

**Three core statements of this document:**

1. **Dark matter as filament strain:** The gravitational potential
   Φ_total = Φ_mat + Φ_fil contains a contribution from cosmic filaments.
   This contribution follows a logarithmic profile and produces flat rotation curves
   without any new particle.

2. **Dark energy as space maturation:** dQ/dt > 0 is qualitatively established
   (v3_006, v3_009). The temporal increase of the quality factor Q acts as a
   cosmological motor — it reproduces the effect of a cosmological constant but is
   dynamically motivated.

3. **Honest limits:** λ_fil (filament strain density) is not derived from RFT first
   principles. The parameters α_Q and β_L in the H(z) relation are free. Quantitative
   predictions carry the label ⚠️.

---

## Table of Contents

1. The Problem of the Dark Sector
2. RFT Foundations for Cosmology
3. Dark Matter as Filament Strain of the DRM
4. Dark Energy as Space Maturation
5. Hubble Tension — Structurally Expected
6. Further Cosmological Phenomena
7. Open Questions and Honest Limits (mandatory chapter)
8. Experimental Predictions
9. Summary and Formula Reference

---

## 1. The Problem of the Dark Sector

### 1.1 Λ-CDM: Achievements and the 95% Problem

The Λ-CDM model (Lambda Cold Dark Matter) is the standard model of cosmology.
Its achievements are impressive:

- ✅ **CMB power spectrum (Planck 2018):** χ²/dof ≈ 1.02 over 2500 multipoles
- ✅ **Large-scale structure (SDSS, 2dFGRS):** filament network precisely predicted
- ✅ **BAO (Baryon Acoustic Oscillations):** standard ruler at ~150 Mpc
- ✅ **Type Ia supernovae:** accelerated expansion measured (Nobel 2011)
- ✅ **Primordial nucleosynthesis:** ⁴He, ²H abundances correct

Λ-CDM describes the cosmic universe with only 6 parameters (Ω_m, Ω_Λ, Ω_b, H₀, n_s, σ_8).
That is a remarkable compression of observational data.

The problem lies in the physics behind these parameters:

**Dark matter (≈27%):** 50 years of intensive search — no direct detection. XENON1T
(2020) excludes WIMPs below σ_SI < 4.1 × 10⁻⁴⁷ cm². Axions (ADMX), MACHOs, and
sterile neutrinos have been substantially constrained or excluded.

**Dark energy (≈68%):** Entirely phenomenological. The fine-tuning problem
Λ_obs/Λ_Planck ~ 10⁻¹²² ranks among the deepest unsolved problems of theoretical physics.

**Inflation:** Postulated for the horizon, flatness, and monopole problems. The inflaton
field has never been directly observed.

**The 95% problem:** 95% of the cosmic energy inventory has no directly observed
microphysical identity.

### 1.2 The Hubble Tension

A fundamental discrepancy in the measurement of the Hubble constant H₀:

- **Early universe (CMB, Planck 2018):** H₀ = 67.4 ± 0.5 km/s/Mpc
- **Late universe (Supernovae, SH0ES 2022):** H₀ = 73.0 ± 1.0 km/s/Mpc
- **Significance:** ~5σ

The discrepancy is too large to be explained by systematic errors. In Λ-CDM it remains
unexplained. RFT makes a clear statement: it is structurally expected (→ Chapter 5).

### 1.3 The JWST Challenge

The James Webb Space Telescope finds massive, structured galaxies at redshifts z > 10 —
earlier than Λ-CDM's bottom-up structure formation predicts. This finding has not been
fully accounted for theoretically, but places pressure on the hierarchical collapse
picture.

---

## 2. RFT Foundations for Cosmology

### 2.1 The Master Equation (brief reference)

The fundamental equation of RFT describes the resonance field Ψ(x,t):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

where:
- κ: resonance rigidity (the PRIMARY quantity — NOT a "mass term"!)
- γ: damping rate
- λ: nonlinear self-coupling
- η: inhomogeneity term

The quality factor Q = κ/γ describes the maturity of space. (→ v3_001)

**Critical distinction from standard QFT:**
- In QFT: mass is *input* → generates the −(mc/ħ)²Ψ term
- In RFT: κ is a *matrix property* (from geometry) → "mass" is output

### 2.2 The Minimal Length L₀ — ħ-Free Definition

```
L₀ = 1/κ    [PRIMARY DEFINITION — ħ-free!] ✓ HIGH (Franz, 25.03.2026)
   = (π/6)·l_P  [numerical verification, not definition]
```

The π/6 ratio is dynamically derived: π/6 = gcd(2π/3, π/2) = 2π/lcm(3,4), where
"3" = spin superposition −1 ⊗ +1/3 (matrix generation) and "4" = minimal 3D vortex
structure (tetrahedron, matter condensation). Both ratios are geometrically necessary
— no ħ, no l_P required in the primary derivation. ○ MEDIUM

**Note on ħ-circularity (historical open problem, now resolved):** Earlier versions
of v3_010 documented ħ-circularity as a high-priority open problem, arising from
L₀ = (π/6)·l_P containing l_P = √(ħG/c³). This circularity is structurally resolved
by the primary definition L₀ = 1/κ, which requires no ħ. The numerical identity
L₀ = (π/6)·l_P remains valid as a verification, not as a definition. ✓ (DC v10.7,
25.03.2026)

### 2.3 The Q-Factor as Cosmological Order Parameter

The quality factor Q measures the resonance quality of the DRM — its ability to sustain
stable oscillation patterns.

- **Immature space (early universe):** Low Q → frequent resonance disruptions → unstable modes
- **Mature space (today):** High Q → stable resonances → stable matter and structures
- **Evolution:** dQ/dt > 0 — qualitatively established ✓ HIGH (v3_006, v3_009)

```
Canonical values (DC v10.8):
  Q_crit1 = α⁻¹·π² ≈ 1352.7    ✓ HIGH (derived, 25.03.2026)
             [space constitution, Mode 0→1]
  Q_crit2 ~ 10⁶–10⁸              ⚠️ WORKING HYPOTHESIS
             [vortex stability, visible matter]
  dQ/dt > 0                       ✓ HIGH (qualitative)
```

Note: Q_crit1 is now a derived quantity: Q_crit1 = α⁻¹·π², yielding ≈ 1352.7.
This is consistent with the earlier estimate "~10³" and is ħ-free.

### 2.4 Connection to Cosmogenesis (v3_009)

From v3_009 (Final, canonical ✓ HIGH):

- Cosmic filaments are **topological scars** of Cold Condensation — they formed at the
  first phase transition (Q > Q_crit1) as highly ordered resonance channels of the DRM.
- They are not *made of* matter. They *are* primary stress structures of the DRM.
- Baryonic matter subsequently condensed along these pre-existing filaments
  (Q > Q_crit2).
- Antimatter is not destroyed but complementarily bound in the DRM structure.
  ✓ HIGH (Franz Zollner, direct)

**Baryonic asymmetry** (updated, DC v10.7):
```
η_B = Δ_α² × (α⁻¹·π²)^(2/3) = 6.02×10⁻¹⁰    ✓ HIGH (25.03.2026)
      0.3% deviation from observed value
      ħ-free derivation ✓ (pure ratio of RFT parameters)
```

This is one of the most remarkable quantitative results of the v3 series: the baryonic
asymmetry emerges from the same geometric ratio (2/3 = (d−1)/d for d=3) that appears
in the mode space boundary and in the √(2/3) geometry of the DRM.

---

## 3. Dark Matter as Filament Strain of the DRM

### 3.1 The Rotation Curve Problem

Galactic rotation curves v(r) show asymptotically constant circular velocities.
Newtonian mechanics predicts v(r) ∝ 1/√r. The discrepancy begins beyond the galactic
luminous radius and is observed in all sufficiently isolated spiral galaxies.

Λ-CDM explains this through a massive dark matter halo (M_DM/M_vis ≈ 5–8). The source
of this mass is unknown and has not been directly detected after 50 years.

In RFT, dark matter requires no new particle. The gravitational anomalies attributed
to dark matter are produced by the intrinsic strain of cosmic filaments — topological
remnants of Cold Condensation. The filament strain contributes an additional gravitational
potential Φ_fil with a logarithmic profile, yielding flat rotation curves without
invoking undetected particles. ○ MEDIUM

### 3.2 RFT Explanation: Filament Potential

**Core principle** (✓ HIGH — from v3 Cosmogenesis, v3_009-consistent):

Cosmic filaments are primary stress paths of the DRM with intrinsic stress σ_fil(r).
This stress generates an independent gravitational potential, regardless of any
baryonic matter embedded within the filament.

The total gravitational potential Φ_total is a superposition:

```
Φ_total(r) = Φ_mat(r) + Φ_fil(r)

where:
  Φ_mat(r) ∝ −GM/r           [baryonic matter contribution, classical]
  Φ_fil(r) ∝ λ_fil · log(r)  [filament contribution, logarithmic]
```

The Poisson equation of the combined field:

```
∇²Φ(r) = −α_DRM · (σ_mat(r) + σ_fil(r))
```

where α_DRM is the DRM coupling constant (not the fine structure constant α!).

```
⚠️ α_DRM: This coupling constant appears in the field equation from v2-source
   material. Its relationship to κ (resonance rigidity), L₀, or Φ is not
   derived from RFT first principles. Status: free parameter in this equation.
```

**Derivation of flat rotation curves:**

The circular velocity is given by:

```
v²(r) = r · |dΦ_total/dr|
```

In the outer regions of a galaxy (r >> R_galactic), Φ_fil dominates over Φ_mat:

```
dΦ_fil/dr = λ_fil / r

→ v²(r) = r · λ_fil/r = λ_fil = constant

→ v(r) = √λ_fil = asymptotically constant   ✓
```

This result is **structural**: flat rotation curves follow directly from the logarithmic
character of the filament potential — without dark matter halos.

**Comparison: Λ-CDM vs. RFT**

| Phenomenon | Λ-CDM | RFT |
|-----------|-------|-----|
| Flat rotation curves | Dark matter halo (unknown particle) | Logarithmic Φ_fil of filaments |
| Gravitational lensing | DM halo increases effective mass | Φ_fil + Φ_mat combined |
| No DM particle found | Open problem | Not expected: no particle required |
| CMB anisotropies | Acoustic baryonic oscillations | DRM stress imprints |

### 3.3 Connection to the CMB

The spatial distribution of cosmic filaments corresponds to the ΔT/T anisotropies in
the CMB. The CMB map is in this interpretation a fossil map of the original stress
distribution of the DRM:

```
ΔT/T ∝ δσ_DRM(r)    ○ MEDIUM
```

The proportionality factor is not yet derived from RFT parameters. The connection is
conceptually plausible and consistent with v3_009 (Cold Condensation).

### 3.4 Q-Gradient Term in the Acceleration

The acceleration of a test mass in the inhomogeneous Q-field:

```
a_total = −GM/r² − (c²/Q) · (dQ/dr)     ○ MEDIUM
```

The second term produces an additional effective attraction in regions with dQ/dr < 0
(toward the galactic center, i.e., toward the higher-Q region). This provides a
dynamical picture complementary to the static Φ_fil description.

Note: The formal derivation of this term from the DRM Master Equation has not been
carried out. The expression is conceptually plausible but should be treated as a
working formula. ⚠️

---

## 4. Dark Energy as Space Maturation

### 4.1 The Acceleration Puzzle

Supernova observations show an accelerated cosmic expansion (ä > 0). In Λ-CDM this is
explained by a cosmological constant Λ — a constant vacuum energy density. The
fine-tuning problem (Λ_obs/Λ_Planck ~ 10⁻¹²²) remains unresolved.

### 4.2 RFT Interpretation: dQ/dt > 0 as Motor

**Core principle** (✓ HIGH — qualitatively established, v3_006, v3_009):

The DRM is not a static medium. dQ/dt > 0: the resonance quality grows monotonically
with time. Space "matures" — it becomes more coherent, more resonant, more ordered.
This process continuously redistributes energy. "Dark energy" is the energetic signature
of space maturation — not a mysterious constant field, but the mechanical consequence
of the DRM's ongoing self-organization.

The effective energy density of this Q-evolution:

```
ρ_eff^Q = (κ²/8πG) · (Q̇/Q)²     ○ MEDIUM
```

This quantity acts as a dynamic cosmological constant:

- It is positive (ρ_eff^Q > 0) as long as dQ/dt > 0
- It produces an effective expansion pressure
- It is **dynamic**: Λ_eff ≠ const., it changes over time

```
⚠️ KNOWN AI ARTIFACT — explicitly rejected:
  A v2 source claims: f_Q ≈ 1 − 1/3 ≈ 0.67, explaining DE = 68%
  by "self-consistency of Q-evolution."

  Audit result: 1 − 1/3 = 0.667 ≠ 0.68.
  This is a spurious derivation with no mathematical foundation.
  It is NOT adopted as canonical.

  Why DE ≈ 68% in RFT: UNRESOLVED 🚩 OPEN
```

### 4.3 Relationship to Λ-CDM

RFT dark energy is complementary to Λ-CDM, not incompatible:

- Λ-CDM: *What* is expanding (energy density ρ_Λ = const.)
- RFT: *Why* is it expanding (mechanism: dQ/dt > 0)

Both describe the same observation — accelerated expansion — through different
paradigms. The RFT approach is physically motivated (space maturation as mechanism),
but quantitatively not yet worked out.

Space maturation (dQ/dt > 0) mimics Λ effectively. This is a feature, not a
coincidence: as the DRM matures, it develops stronger coherence that resists
gravitational collapse at large scales. ○ MEDIUM

---

## 5. Hubble Tension — Structurally Expected

### 5.1 The Discrepancy and Its Significance

The Hubble tension (H₀ ≈ 67.4 km/s/Mpc early vs. ≈ 73.0 km/s/Mpc local) is an
open problem in Λ-CDM. Systematic errors are insufficient to explain the ~5σ
discrepancy.

In RFT, this discrepancy is **not an anomaly** — it is a direct, qualitatively
established consequence of the Q-dependence of light propagation.

**The Hubble tension is not a measurement inconsistency in RFT — it is a structural
prediction.** Because the quality factor Q evolves (dQ/dt > 0), the effective
propagation of light depends on Q. Early-universe measurements (CMB, z~1100) and
late-universe measurements (Cepheids, z~0) probe different Q-regimes, yielding
systematically different H₀ values. RFT predicts this discrepancy as a feature,
not a bug. ○ MEDIUM

### 5.2 The Gear Wheel Analogy

The propagation of light through the DRM is Q-dependent. A photon travels through the
DRM like a gear wheel (pinion) on a toothed rail:

- **Immature space (low Q, early epoch, z ~ 1100):** The meshing is imperfect. The
  photon "stumbles" — its effective propagation velocity fluctuates. Light travel times
  are systematically overestimated, distances appear larger, H₀ is determined too *low*.

- **Mature space (high Q, today, z ~ 0):** The meshing is precise. The photon rolls
  smoothly. Distances are correctly determined, H₀ appears *larger*.

The gear wheel analogy makes a clear qualitative statement: **different epochs
systematically measure different H₀ values.** This is not an error — it is physics.

### 5.3 H(z) Relation

The qualitative expectation of RFT is that H(z) runs flatter than in Λ-CDM:

```
H(z) = H₀ · (1+z)^(−γ)     ○ MEDIUM (qualitative form)

with γ = α_Q · β_L          ⚠️ free parameters, not derived
```

**Qualitative prediction** (✓ HIGH): H(z) is flatter at z = 1 than Λ-CDM.
The numerical value "~44% flatter" from v2 sources is ⚠️ not independently verified.

**Qualitative statement** (✓ HIGH): The Hubble tension is a structural prediction
of RFT, not an open problem.

---

## 6. Further Cosmological Phenomena

### 6.1 JWST — Early Massive Galaxies

**Observation:** JWST finds massive, structured galaxies at z > 10 that were not
predicted in Λ-CDM's hierarchical (bottom-up) structure formation scenario.

**RFT explanation** (✓ HIGH — qualitative, from v3_009 Final):

In RFT, structures form through **simultaneous nucleation** — vortex condensation
when Q > Q_crit2 globally. This process is coherent and rapid. Massive structures
can form early because condensation along pre-existing filaments occurs simultaneously
at many locations — not hierarchically through gravitational collapse.

```
Qualitative RFT prediction: Galaxies at z > 10–15 with M > 10¹⁰ M_☉ are possible.
                              Consistent with current JWST data  ○ MEDIUM (Hints)

⚠️ Quantitative estimates (number densities etc.) from v2 sources:
   Not independently verified — not adopted as established.
   
The James Webb Space Telescope finds massive, structured galaxies at z > 10 —
earlier than Λ-CDM predicts. In RFT, Cold Condensation allows early structure
formation without inflation. This is a qualitative prediction consistent with
JWST observations. ○ MEDIUM (not yet a quantitative confirmation)
```

### 6.2 CMB Low-ℓ Anomalies

**Observation:** The Planck satellite finds anomalies at large angular scales (ℓ < 10):
suppressed power compared to Λ-CDM expectations.

**RFT explanation** (○ MEDIUM):

At wavelengths λ > λ_J (Jeans length of the DRM), the resonance matrix is intrinsically
coherent — it oscillates as a whole. Power is suppressed at large scales because the
DRM does not allow independent fluctuations there; instead, it oscillates collectively
in a coherent mode.

The CMB anisotropies in this interpretation are stress imprints of the original DRM —
not purely acoustic baryonic oscillations.

### 6.3 Olbers' Paradox

**Question:** Why is the night sky dark, if the universe were infinitely old and
infinitely large?

**RFT answer** (✓ HIGH — elegant, from v3 Cosmological Structures):

The universe has a finite history in its ordered phase. When we look back into the
distant past, we observe a **low-Q era** in which stable, persistent light sources
(stars) had not yet efficiently formed. The DRM had Q < Q_crit2 — vortex condensation
had not yet occurred, or only locally. The night sky is dark because the cosmic history
of ordered structures is finite, not because the universe is finite in size.

This is one of the most conceptually elegant results of RFT cosmology: Olbers' paradox
resolves naturally from the Q-evolution of the DRM, without requiring a finite universe
age in the Λ-CDM sense.

### 6.4 Large-Scale Structure and Cosmic Voids

**Filaments as primary stress paths** (✓ HIGH):

The cosmic web of filaments, walls, and voids is in RFT not a *consequence* of
structure formation — it is the *scaffold*. Filaments formed at the first phase
transition (Q > Q_crit1) as topological scars of the DRM. Baryonic matter subsequently
condensed along this pre-existing structure.

```
Consequence: Voids = regions with locally low Q.
             Filaments = regions with locally highest Q.
             This Q-gradient is the origin of the dark matter effect.
```

**Jeans Length of the DRM:**

A characteristic length scale λ_J can be estimated from the Master Equation:

```
λ_J^DRM = c/κ · √(1 + Q⁻²)     ○ MEDIUM (conceptual; numbers ⚠️)
```

The observed scales of cosmic structures (~300 Mpc filaments, ~600 Mpc voids) would
be multiples of λ_J. This correspondence is conceptually interesting, but numerical
values are ⚠️ not independently derived from RFT parameters.

---

## 7. Open Questions and Honest Limits (Mandatory Chapter)

### 7.1 λ_fil — Filament Strain Density 🚩 CRITICAL

The parameter λ_fil in Φ_fil(r) = λ_fil · log(r) determines quantitatively the
strength of the filament contribution to gravitation. It is currently **not derived
from RFT first principles.**

The filament strain density λ_fil is not derived from RFT first principles. It is
a free parameter constrained by observation. Deriving λ_fil from L₀, α, and Φ is
a high-priority open research problem.

```
🚩 OPEN: λ_fil is a free parameter.
   What is missing: a mechanism deriving λ_fil from L₀, α, Φ, or Q_crit.
   Consequence: All quantitative rotation curve predictions
                inherit this free parameter.
```

### 7.2 α_Q and β_L as Free Parameters

The H(z) relation contains the exponent γ = α_Q · β_L. Both are free parameters —
numerical values from v2 sources (α_Q ≈ 0.40, β_L ≈ 0.030) were not derived from
RFT first principles and are likely AI artifacts. Do not use as established values.

```
⚠️ STATUS: Free parameters.
   v2 numerical values are suspected AI artifacts.
   Do not use as established!
```

### 7.3 Quantitative H(Q) Relation

The qualitative statement "H is Q-dependent" is established. A quantitative H(Q)
relation that follows from the Master Equation or from RFT fundamental parameters
is missing.

```
⚠️ STATUS: Open problem.
   Required: Derivation of the Friedmann-analogue equation in RFT
   (Q-dependent expansion from the Master Equation).
```

### 7.4 Dark Energy — Quantitatively Open

The effective energy density ρ_eff^Q is conceptually motivated. The question of why
ρ_eff^Q ≈ 0.68 · ρ_crit today — i.e., why DE ≈ 68% — is **not answered** in RFT.

```
🚩 OPEN: Dark energy quantitative fraction.
   The v2 derivation "1 − 1/3 ≈ 0.67" is an AI artifact.
   Considered definitively discarded.
```

### 7.5 Inherited Consistency Issues

v3_010 inherits all known open questions of the v3 series:

**Scale jump Planck↔QCD:**
```
⚠️ Why did the universe condense at QCD scales (~150 MeV), not at Planck scales?
   Open problem (→ v3_001, Chap. 12.9).
```

**Lorentz invariance:**
```
⚠️ Whether the discrete DRM model possesses full Lorentz invariance
   in the continuum limit has not been formally proven (→ v3_007, Chap. 8).
```

**ħ-circularity status:**
```
✓ RESOLVED (DC v10.7, 25.03.2026):
  L₀ = 1/κ is the primary definition — no ħ required.
  The identity L₀ = (π/6)·l_P remains valid as numerical verification.
  π/6 is dynamically derived from gcd(2π/3, π/2).
```

---

## 8. Experimental Predictions

### 8.1 LSST — H(z) Evolution

**Prediction** (qualitatively established ✓ HIGH):

H(z) runs flatter than Λ-CDM, because H is Q-dependent and Q was smaller in the past.

```
Test:           LSST (Vera Rubin Observatory, operational since 2025)
Prediction:     H(z) at z = 1 flatter than Λ-CDM
Quantitative:   ~44% difference (⚠️ from v2 source, not independently verified)
Falsification:  If H(z) follows the Λ-CDM profile exactly → RFT Hubble mechanism falsified
```

### 8.2 Euclid — Filament Asymmetries

**Prediction** (✓ HIGH — conceptually):

Q-gradients between filaments and voids are fundamental in RFT. Euclid should detect
systematic filament asymmetries in the mass distribution that exceed purely baryonic effects.

```
Test:           Euclid (ESA, operational since 2024)
Prediction:     Q-gradient asymmetries in filament mass distribution
Qualitative:    Established ✓ HIGH
Quantitative:   Depends on λ_fil (⚠️ free parameter)
```

### 8.3 CMB-S4 and LiteBIRD — Tensor-to-Scalar Ratio r

**Prediction** (✓ HIGH — qualitative):

In RFT there are no primordial gravitational waves from an inflationary phase (since
there is no inflation). The tensor-to-scalar ratio r should therefore be very small.

```
RFT prediction: r < 10⁻⁴
Λ-CDM (without inflation): similar
Λ-CDM (with inflation):    r ~ 0.001–0.01

Test:    CMB-S4 (~2030), LiteBIRD (~2032)
         Sensitivity: Δr ~ 0.001 (CMB-S4), Δr ~ 0.0003 (LiteBIRD)
```

This is a decisive test between inflationary and non-inflationary cosmology.

### 8.4 JWST — z > 15 Galaxy Count

**Prediction** (qualitative ✓ HIGH):

Simultaneous nucleation through Cold Condensation allows early, massive galaxies.
JWST should find significantly more massive galaxies at z > 15 than Λ-CDM predicts.

```
RFT prediction: More early galaxies than Λ-CDM
Quantitative:   5–10× more (⚠️ from v2 source, not independently verified)
Qualitative:    Consistent with current JWST findings  ○ MEDIUM (Hints)
```

### 8.5 Summary of Experimental Tests

| Test | Instrument | Prediction | Confidence | Timeline |
|------|-----------|-----------|-----------|---------|
| H(z) flatter | LSST | ~44% at z=1 | MEDIUM ⚠️ | From 2025 |
| Filament asymmetries | Euclid | Q-gradients | HIGH (qualitative) | From 2024 |
| r < 10⁻⁴ | CMB-S4, LiteBIRD | No inflation | HIGH | ~2030–2032 |
| z > 15 galaxies | JWST | 5–10× more | MEDIUM ⚠️ | Available |
| CMB low-ℓ suppression | Planck follow-up | Q-coherence | MEDIUM | Ongoing |

---

## 9. Summary and Formula Reference

### 9.1 The Core Statement

**The dark sector is not a What — it is a How.**

Dark matter, dark energy, and the Hubble tension are not signals of unknown substances
or fields. They are manifestations of the resonance matrix mechanics of the Dynamic
Resonance Matrix:

- **Dark matter** = gravitational effect of the intrinsic filament strain (Φ_fil ∝ log r)
- **Dark energy** = energetic signature of space maturation (dQ/dt > 0)
- **Hubble tension** = Q-dependence of light propagation (structurally expected)

### 9.2 Formula Reference

**Canonical parameters (invariant, v3 — DC v10.8):**
```
α⁻¹  = 4π³ + π² + π = 137.036 304    [2.22 ppm — NEVER 0.67 ppm!]
κ               PRIMARY QUANTITY (resonance rigidity, not "mass term")
L₀   = 1/κ = (π/6)·l_P ≈ 0.524·l_P   [primary def.: ħ-free!]
Φ    = 2α/(1+α²) ≈ 0.014596            [canonical ✓]
G·m/c² = L²/(4π·Φ)                     [dimensionally correct ✓]
τ_lag = L₀/c = (π/6)·t_P              [canonical since 11.03.2026]
```

**Cosmological parameters (qualitatively established):**
```
dQ/dt > 0                              ✓ HIGH
Q_crit1 = α⁻¹·π² ≈ 1352.7            ✓ HIGH (derived, 25.03.2026)
Q_crit2 ~ 10⁶–10⁸                     ⚠️ WORKING HYPOTHESIS
η_B = Δ_α² × (α⁻¹·π²)^(2/3) = 6.02×10⁻¹⁰   ✓ HIGH (25.03.2026)
```

**Dark matter (conceptually established, quantitatively open):**
```
Φ_total(r) = Φ_mat(r) + Φ_fil(r)     ✓ HIGH (conceptual)
Φ_fil(r) ∝ λ_fil · log(r)            ✓ HIGH (form); λ_fil 🚩 OPEN
∇²Φ = −α_DRM(σ_mat + σ_fil)          ○ MEDIUM; α_DRM ⚠️ free parameter
a_total = −GM/r² − (c²/Q)·(dQ/dr)   ○ MEDIUM
v(r → ∞) = √λ_fil = const.           ✓ (structural result)
```

**Dark energy (conceptually established, quantitatively open):**
```
ρ_eff^Q = (κ²/8πG)·(Q̇/Q)²           ○ MEDIUM
```

**Hubble tension (qualitatively established):**
```
H₀(early) < H₀(local)                ✓ HIGH (structural)
H(z) flatter than Λ-CDM              ✓ HIGH (qualitative)
H(z) = H₀·(1+z)^(−γ), γ = α_Q·β_L  ⚠️ free parameters
```

### 9.3 Confidence Overview

| Statement | Confidence | Basis |
|-----------|-----------|-------|
| Filaments = topological scars | ✓ HIGH | Franz + v3_009 |
| Φ_total = Φ_mat + Φ_fil | ✓ HIGH | v3-consistent |
| v(r) → const. (structural) | ✓ HIGH | Mathematical from log-potential |
| dQ/dt > 0 | ✓ HIGH | v3_006, v3_009 |
| Hubble tension structurally expected | ✓ HIGH | qualitative |
| JWST early galaxies natural | ✓ HIGH | v3_009 |
| Olbers' paradox resolved | ✓ HIGH | Low-Q era argument |
| η_B = 6.02×10⁻¹⁰ | ✓ HIGH | 25.03.2026 |
| L₀ = 1/κ (ħ-free) | ✓ HIGH | 25.03.2026 |
| CMB = condensation afterglow | ○ MEDIUM | v3_009-consistent |
| a_total with Q-gradient term | ○ MEDIUM | v2 source, plausible |
| ρ_eff^Q formula | ○ MEDIUM | v2 source, plausible |
| H(z) quantitative (~44%) | ⚠️ | v2 source, not verified |
| λ_fil numerical value | 🚩 | Free parameter |
| α_Q, β_L | ⚠️ | Free parameters |
| DE ≈ 68% quantitative | 🚩 | Unresolved |

---

## Flags for Franz

```
F1. Photon status (since DC v7.3): KORREKTUR_005 ("2 AP, short-lived") vs.
    v3_001 Chap. 13.3 ("n=0, stable"). Contradiction still open.
    → Affects v3_010 peripherally (photon propagation in Q-inhomogeneous space).
    → Clarify before a potential v3_010.1 update.

F2. Q_crit normalization question: v2 source gives Q_crit ≈ 1.645 (different Q
    normalization). DC v10.8 has Q_crit1 = α⁻¹·π² ≈ 1352.7 as canonical.
    → This supersedes the v7.6-era Q_crit normalization question (F2 from v7.6).
    → Consider closed for EN translation purposes.

F3. Ur-Chaos terminology: "−1 before the time arrow" = neutral asymmetry. New
    designation pending (DC v10.6). Does not affect v3_010 directly.

F4. λ_fil: Is there a mechanism to derive λ_fil from L₀, α, Φ?
    → High-priority open research question for the RFT program.
    → Potentially linked to the η_B derivation structure (2/3 geometry).
```

---

*RFT_v3_010 — New Cosmology: Resolving the Dark Sector through Resonance Matrix Mechanics*
*Translation Final | 27 March 2026 | Translation instance T10*
*Source: DE v1.0 (06.03.2026) | Glossary: RFT_v3_Glossar_EN.md*
*Key results: DM = filament strain | DE = space maturation | Hubble tension = structural prediction*
*Updated vs. DE source: Q_crit1 = α⁻¹·π² ≈ 1352.7 (✓ HIGH); η_B = 6.02×10⁻¹⁰ (✓ HIGH);*
*L₀ = 1/κ primary definition (ħ-free); "Gitter/Gittermechanik" → DRM/resonance matrix mechanics*
