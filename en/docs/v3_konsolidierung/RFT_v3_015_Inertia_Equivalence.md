# RFT_v3_015: Inertia and Equivalence
## Resonance Field Theory — Publication Series v3

**DOCUMENT-ID:** RFT_v3_015_Inertia_Equivalence_EN  
**VERSION:** v1.2-EN-r1 (Translation: April 2026)  
**STATUS:** 🔶 Final Candidate — pending release by Franz Zollner  
**AUTHOR:** Franz Zollner  
**TRANSLATION:** KI Instance 015 (Multi-Instance Protocol v6.1)  
**LANGUAGE:** EN  
**DEPENDENCIES:** RFT_v3_001 (Master equation, κ), RFT_v3_003 (Spin-lag, G·m),
RFT_v3_004 (Impulse/Energy, ħ status), RFT_v3_012 (τ_lag canonical value)  
**LICENSE:** Creative Commons BY-NC-SA 4.0  

---

> ⚠️ **Methodological Ground Rule:** The concepts originate from Franz Zollner.
> The written formulation is produced by an AI instance. All formulae and
> statements should be scrutinised critically. When in doubt: set a FLAG and
> consult Franz.
>
> ⚠️ **DC Basis:** DC v10.12 (02.04.2026). In case of conflict with the
> current DC, the DC takes precedence (authority hierarchy J.1).

---

## Abstract

The Resonance Field Theory (RFT) draws a mechanistically clear distinction
between two phenomena that standard physics describes with a single quantity —
mass m:

**Inertial mass m_i** arises from the κ-field of the Discrete Resonance
Matrix (DRM). The κ-term in the master equation describes local resonance
stiffness: it is the resistance a vortex opposes to deformation of its
surrounding resonance field — inertia as a geometric lattice property of
the matrix.

**Gravitational mass m_g** arises from the spin-lag mechanism: every rotating
vortex generates a phase delay τ_lag = L₀/c in the space matrix, which
propagates as a trailing vortex (torsion field). This non-local, collective
property is what we measure as the gravitational field.

The equivalence principle (m_i = m_g) is in RFT not an external demand but
a geometric consequence: for hadrons, both mechanisms yield proportional
results because they share the same topological origin in the DRM geometry.
The proportionality is, however, not exact — it breaks at the topological
boundaries of the particle spectrum. The predicted deviation:

$$\eta_{Eq} = \Delta_\alpha^2 \cdot (\alpha^{-1} \cdot \pi^2)^{2/3} \approx 6{.}02 \times 10^{-10}$$

is currently at the frontier of the best Eötvös measurements and represents
a falsifiable prediction of RFT.

---

## Table of Contents

1. [Paradigm: Mass Is Not a Unitary Concept](#1-paradigm)
2. [Inertial Mass: κ-Field and Compression Resistance](#2-inertial-mass)
3. [Gravitational Mass: Spin-lag and DRM Torsion](#3-gravitational-mass)
4. [The Equivalence Principle as a Geometric Consequence](#4-equivalence-principle)
5. [Quantitative Deviation: η_Eq](#5-quantitative-deviation)
6. [Topological Edge Cases: Where the EP Breaks](#6-topological-edge-cases)
7. [Experimental Predictions](#7-experimental-predictions)
8. [Limitations and Open Questions](#8-limitations)
9. [Summary and Glossary](#9-summary)

---

## 1. Paradigm: Mass Is Not a Unitary Concept

### 1.1 The Problem of the Simple Equation

In classical mechanics:

```
F_inertial     = m · a              (Newton, 2nd law)
F_gravitational = G · m₁ · m₂ / r² (Newton, gravitation)
```

Using the same symbol m in both equations is not a derivation — it is a
postulate. The equivalence principle (EP) was observed by Galileo and elevated
by Einstein to the foundation of General Relativity (GR). GR thereby achieves
a conceptual unification, but not a mechanistic explanation.

**The open question is:** Why do all bodies fall at the same rate? Or more
precisely: under what conditions does this hold — and when does it not?

### 1.2 The RFT Answer

RFT answers these questions by recourse to two distinct physical mechanisms,
both anchored in the master equation:

| Property | Symbol | Physical Origin | Character |
|----------|--------|----------------|-----------|
| Inertial mass | m_i | κ-term (resonance stiffness) | Local, instantaneous |
| Gravitational mass | m_g | Spin-lag torsion | Non-local, propagating |

The equality m_i = m_g is a good approximation for all hadrons, but not an
exact identity. The breaking of the EP is a predicted consequence of the
different topological depths of the two mechanisms.

### 1.3 Terminology (v3-canonical)

| Symbol | Meaning | Source |
|--------|---------|--------|
| κ | Resonance stiffness [1/m] — NOT "mass term"! | RFT_v3_001, Ch. 2.2 |
| L₀ = 1/κ | Primary length definition of the matrix (ħ-free) | RFT_v3_001, Ch. 5, Update 25.03.2026 |
| L₀ = (π/6)·l_P | Numerical verification (from resonance geometry) | RFT_v3_001, Ch. 5 |
| τ_lag = L₀/c | Characteristic spin-lag timescale | RFT_v3_003, Ch. 3.2 |
| m = ħκ/c | Effective mass (derived, not fundamental) | RFT_v3_001, Ch. 7 |
| μ = G·m | Topological base quantity [m³/s²] | RFT_v3_003, Ch. 1.2 |
| Trailing vortex | Torsion field behind a moving vortex | RFT_v3_003, Ch. 7 |
| DRM | Discrete Resonance Matrix | RFT_v3_001, Ch. 1 |
| AP | Anchor point: coupling of a vortex to the space matrix | Canonical since 11.03.2026 |

**Canonical clarification:** In RFT, κ is primary. The quantity m = ħκ/c is
a human label for what DRM geometry produces. The equivalence principle is
then the question: do the κ-field and spin-lag torsion produce the same
effective number m?

---

## 2. Inertial Mass: κ-Field and Compression Resistance

### 2.1 The κ-Term in the Master Equation

The RFT master equation (RFT_v3_001, Ch. 2) reads:

$$\frac{\partial^2\Psi}{\partial t^2} = c^2\nabla^2\Psi - \gamma\frac{\partial\Psi}{\partial t} - c^2\kappa^2\Psi + \lambda|\Psi|^2\Psi + \eta$$

The term −c²κ²Ψ is the decisive term for inertia.

**Causal direction (important!):**

```
Standard QFT:  m (mass term) → field equation
RFT:           Space matrix geometry → κ → what we call "mass"
```

κ is not a property of a particle — κ is a property of the DRM at every
location. The local resonance stiffness of the matrix imposes a restoring
term on the field Ψ. A stable vortex (soliton) sits in a region of elevated
Ψ amplitude — it "feels" the κ-term most strongly.

### 2.2 Inertia as Matrix Compression

What happens when we apply an external force to a vortex?

```
External force F → vortex shifts relative to the DRM
                ↓
     Location-dependent κ-field change
                ↓
     Restoring term: c²κ² · ΔΨ ≠ 0
                ↓
     Force on vortex opposing displacement
                = Inertial resistance
```

This is inertia as **local compression resistance** of the resonance field.
The force required to accelerate a vortex is proportional to the amplitude
change of the κ-field — this is m_i.

### 2.3 Formal Derivation of Inertial Mass

From the dispersion relation of the master equation (RFT_v3_004, Ch. 2.2):

$$\omega^2 = c^2(k^2 + \kappa^2)$$

differentiation with respect to the wave vector k gives the group velocity:

$$v_g = \frac{d\omega}{dk} = \frac{c^2 k}{\omega}$$

The energy of the vortex (with ħ as a formal factor, cf. RFT_v3_004, Ch. 6):

$$E^2 = (pc)^2 + (\hbar c\kappa)^2$$

Identification of inertial mass:

$$m_i c^2 \equiv \hbar c \kappa \quad \Longrightarrow \quad m_i = \frac{\hbar\kappa}{c}$$

**Confidence: ○ MEDIUM** — The derivation is algebraically consistent. The
conceptual status of ħ in RFT as an algebraic identity (not an independent
derivation) carries over to m_i: it is a consistent labelling of the κ-term,
not an independent mass measurement.

### 2.4 Locality of Inertial Mass

Inertial mass is **local**: it depends only on the κ-value at the vortex
location. Accelerating the vortex in region A does not affect the κ-value
in region B. Inertia is a property of the immediate DRM environment of the
vortex.

**Consequence:** Two identical vortices at different locations in the universe
(with the same local κ) have identical inertial mass — regardless of their
history.

---

## 3. Gravitational Mass: Spin-lag and DRM Torsion

### 3.1 The Spin-lag Mechanism

Every massive vortex carries a spin. This spin generates a phase delay
between the vortex and the surrounding space matrix. The DRM matrix does
not follow the rotating vortex instantaneously — there is a **trailing
angle**.

The characteristic timescale of this lag is (RFT_v3_003, Ch. 3.2,
✓ HIGH, canonically confirmed):

$$\tau_{lag} = \frac{L_0}{c} = \frac{\pi}{6} \cdot t_P$$

where t_P is the Planck time. This is the same geometric number L₀/l_P = π/6
that follows from the resonance condition of the nested spheres.

### 3.2 Trailing Vortex as Gravitational Field

The spin-lag generates a torsional structure in the DRM — a **trailing vortex**
that propagates radially around the vortex.

**Important distinction (DC v10.12, Domain C):**

```
Gravitational field  = longitudinal mode (compression of the space matrix)
Electromagnetism     = transverse/torsional mode (spin-lag, v3_012)
→ Both modes of the same carrier medium (Resonance Matrix)
```

The spin-lag τ_lag primarily generates the **torsional mode** (→ EM, v3_012).
The gravitational effect is the **longitudinal compression** that arises as the
long-range consequence of the trailing angle: the vortex "drags" the space
matrix behind it, locally compressing the field, which propagates radially as
a trailing vortex.

```
Rotating vortex (spin ½)
        ↓
  Phase lag τ_lag = L₀/c in the DRM
        ↓
  Trailing vortex propagates (v = c)
        ↓
  Other vortices in the DRM "feel" this torsion field
        ↓
  Coupling → force between vortices
        = Gravitation
```

The gravitational mass m_g is proportional to the trailing vortex amplitude.
The fundamental base quantity is not m_g alone, but the product
(RFT_v3_003, Ch. 1.2, ✓ HIGH):

$$\mu = G \cdot m_g \quad [m^3/s^2]$$

The [kg] is not a law of nature — it is a label for the trailing vortex
strength.

### 3.3 Non-locality of Gravitational Mass

In contrast to inertial mass, gravitational mass is **non-local and
collective**: a vortex generates a trailing vortex that propagates throughout
the entire DRM. Other vortices far away couple to this vortex.

**Consequence:** Gravitation is an emergent property of the entire DRM
network, not a local interaction between two isolated objects. G is not a
coupling constant — G is a geometric property of the DRM.

### 3.4 Two Gravitational Mechanisms (from RFT_v3_003)

RFT distinguishes two G mechanisms (✓ HIGH for conceptual level):

**G_elementary (quark mismatch):** A single quark vortex does not fit
perfectly to the DRM geometry → weak, local stress.

**G_hadron (colour-charge alignment):** During hadron formation, three
colour-charge vectors align spherically → 4π geometry factor:

$$G_{hadron} = 4\pi \cdot G_{elementary}$$

The factor 4π is the solid angle of the complete sphere — geometrically
necessary, not a free parameter.

---

## 4. The Equivalence Principle as a Geometric Consequence

### 4.1 Why m_i ≈ m_g for Hadrons

The equivalence principle holds in RFT not as a postulate but as a
**geometric consequence** of a structural coincidence:

For a hadron (proton, neutron):

1. **m_i** arises from the κ-term → determined by the internal vortex
   topology of the hadron (3 quarks, SU(2) structure)

2. **m_g** arises from the spin-lag → determined by the collective trailing
   vortex strength after colour-charge alignment

Both mechanisms are anchored in the DRM. Both depend on the same fundamental
matrix parameters (c, L₀, α). For hadronic geometry:

```
m_i ~ κ_hadron   (local stiffness)
m_g ~ trailing vortex amplitude after colour alignment
   ~ 4π · κ_elementary

If κ_hadron = 4π · κ_elementary:
→  m_i = m_g  ✓  (Equivalence Principle)
```

**Confidence: ○ MEDIUM** — The proportionality is conceptually plausible.
The quantitative proof that the 4π factor matches exactly in both mechanisms
has not yet been rigorously established. This is an open research task
(→ Chapter 8).

### 4.2 The EP in GR vs. RFT

| Aspect | GR | RFT |
|--------|-----|-----|
| EP status | Postulate (foundational axiom of GR) | Geometric consequence (approximate) |
| Validity range | Universal | Exact only for hadrons; topological exceptions |
| Mechanism | Geometrisation of gravitation | Two distinct DRM mechanisms |
| Falsifiability | Width of EP tests | Prediction of specific deviations |

The decisive argument: RFT makes a **quantitative statement** about where
and how large the deviation is. GR makes no such statement — it postulates
the EP as exact.

---

## 5. Quantitative Deviation: η_Eq

### 5.1 Origin of the Asymmetry

The α-formula of RFT gives:

$$\alpha^{-1} = 4\pi^3 + \pi^2 + \pi = 137{.}036304$$

The deviation from the CODATA value is Δ_α = 2.22 ppm (✓ HIGH, canonical).
This deviation is not a measurement uncertainty — it is the signal of the
residual phase asymmetry δ ≈ 0.82° of the DRM (the "time motor",
RFT_v3_001, Ch. 10b).

This asymmetry δ appears in **both** mechanisms, but not in the same way:

```
Inertial mass m_i:    κ-field responds instantaneously to δ (local)
Gravitational mass m_g: Trailing vortex propagates with lag τ_lag (non-local)
                     → δ-effect is modulated by propagation
                     → Residual difference between m_i and m_g
```

### 5.2 The η_Eq Parameter

The predicted equivalence principle violation for a system with different
electron/hadron composition:

$$\boxed{\eta_{Eq} = \Delta_\alpha^2 \cdot (\alpha^{-1} \cdot \pi^2)^{2/3} \approx 6{.}02 \times 10^{-10}}$$

**Numerical verification:**

```
Δ_α = 2.22 × 10⁻⁶    (canonical α-deviation, ✓ HIGH)

Δ_α² = (2.22 × 10⁻⁶)² = 4.93 × 10⁻¹²

Q_crit1 = α⁻¹ · π² = 137.036 × 9.8696 = 1352.7

(α⁻¹ · π²)^(2/3) = (1352.7)^(2/3)
                  ≈ 122.2

η_Eq = 4.93 × 10⁻¹² × 122.2 ≈ 6.02 × 10⁻¹⁰  ✓
```

**Confidence: ✓ HIGH** (Franz Zollner, 25.03.2026, canonically confirmed)

**Note on naming:** η_Eq is the Eötvös parameter (Equivalence, v3_015).
It must not be confused with the baryon-asymmetry parameter of v3_009.
Both quantities share the same numerical value ~10⁻¹⁰ but describe
entirely different physical phenomena.

### 5.3 Physical Interpretation

η_Eq is the **Eötvös parameter** of RFT: it measures the relative difference
in free-fall accelerations of two bodies with different electron-to-nucleon
mass compositions:

$$\eta = \frac{2|a_1 - a_2|}{a_1 + a_2}$$

Two test masses with different Z/A ratios (atomic number to mass number)
have different electron fractions of their total energy. Since electrons
(1 AP, no colour-charge alignment mechanism) have a slightly different
m_i/m_g ratio than nucleons, there is a Z/A-dependent deviation.

The order of magnitude: **η_Eq ≈ 6 × 10⁻¹⁰**.

---

## 6. Topological Edge Cases: Where the EP Breaks

### 6.1 The Electron: 1 Anchor Point, No Colour Charge

The electron is a vortex with exactly **1 anchor point** (AP) — a single
geometric coupling point to the DRM (canonically confirmed, Franz 11.03.2026).

Compared with the hadron:

| | Proton | Electron |
|-|--------|----------|
| Anchor points | 3 (1 per quark) | 1 |
| Colour-charge alignment | ✓ (G_hadron = 4π · G_el.) | ✗ (no colour charge) |
| Mechanism m_g | 4π sphere geometry | Only elementary spin-lag |
| Ratio m_i/m_g | ≈ 1 (exact from 4π coincidence) | ≈ 1 − η_Eq |

The electron falls in a gravitational field with a slightly different
acceleration than a proton — though the difference is very small.

**Prediction:**

$$\Delta g_{e^- \text{ vs. proton}} \approx \eta_{Eq} \cdot g \approx 6 \times 10^{-10} \cdot g$$

⚠️ **Note:** Earlier RFT versions cited Δg ~ 10⁻⁵ for electrons vs. hadrons
(DC v1.1, Dec 2025). The current calculation η_Eq = 6×10⁻¹⁰ supersedes this
value. The older figure is a historical rough estimate without a rigorously
calculated basis; η_Eq is the current canonical prediction.
🚩 **Open question:** Is the discrepancy between old 10⁻⁵ and new 6×10⁻¹⁰
fully resolved? Clarification by Franz required.

### 6.2 The Photon: 2 Anchor Points, Gravitationally Neutral

The photon is an e⁺e⁻ vortex pair with parallel spins (↑↑) and
**2 anchor points** (canonically confirmed, Franz 11.03.2026).

At rest, the trailing vortices of e⁻ and e⁺ cancel:

```
Trailing vortex(e⁻) + trailing vortex(e⁺) = 0
→ m_g = 0  (gravitationally neutral)
→ m_i ≠ 0  (inertia from κ-field remains)
```

The photon is an example of **inertia without gravitation** — or more
precisely: a body with m_i ≠ 0 at m_g = 0. This would be an extreme EP
violation, but it is not experimentally accessible in the photon's rest frame
(the photon exists only at v = 0 or v = c).

For the **propagating photon**, a small residual effect exists through the DRM
time asymmetry δ (→ RFT_v3_003, Ch. 6.2):

$$m_{g,\text{photon}} \approx 2\alpha \cdot m_{g,\text{electron}} \neq 0$$

This residual is many orders of magnitude below current measurement precision.

### 6.3 Cooper Pairs: Minimal Gravitational Mass

Cooper pairs (↑↓ spin-antiparallel) show a dramatic reduction in
gravitational mass (RFT_v3_004, Flag 4):

```
Cooper pair: e⁻↑ + e⁻↓
→ Spins antiparallel → spin-lags act in opposition
→ Trailing vortices cancel (almost)
→ m_g → 0
→ Inertial mass m_i remains (κ-field acts on both electrons)
```

The Cooper pair is thus the strongest available signal for an EP violation:

$$\eta_{Cooper} = \frac{m_i - m_g}{m_i} \approx 1 - 2\alpha \approx 0{.}9854$$

⚠️ **Confidence: ○ MEDIUM** — Sign and order of magnitude are conceptually
well-founded. The precise figure depends on the fine structure of the
spin-lag cancellation mechanism, which has not yet been fully formalised.

**Experimental consequence:** Superconductivity disappears above a critical
temperature because phonons decouple the Cooper pair spins — the gravitational
mass of the electrons becomes "active" again. RFT thereby connects
superconductivity directly to the EP mechanism. This is a qualitative
prediction addressable in Cooper-pair gravimetry experiments (PTB).

---

## 7. Experimental Predictions

### 7.1 Eötvös Test with Z/A Dependence

**Prediction:** Two test masses with different Z/A ratios fall at different
rates. The difference is:

$$\eta_{EP} = \eta_{Eq} \cdot \left|\frac{Z_1/A_1 \cdot m_e}{m_1} - \frac{Z_2/A_2 \cdot m_e}{m_2}\right| \cdot \mathcal{F}$$

where 𝓕 is a dimensionless geometric factor (○ MEDIUM, not yet formalised),
m_e the electron mass, and Z/A the ratio of atomic number to mass number.

**Estimate:** For Be (Z/A ≈ 0.44) vs. Ti (Z/A ≈ 0.45), the difference
Δ(Z/A) ≈ 10⁻². The prediction:

$$\eta_{EP} \lesssim \eta_{Eq} \times 10^{-2} \approx 6 \times 10^{-12}$$

**Current measurement frontier:** The best Eötvös tests reach 10⁻¹³ (MICROSCOPE,
2022). The RFT prediction sits at ~6×10⁻¹² — **factor 50 above current
measurement limit** and in principle testable.

🚩 **Confidence: ⚠️ LOW** — Factor 𝓕 not derived. The estimate has systematic
uncertainties of at least one order of magnitude.

### 7.2 Cooper-Pair Gravimetry (PTB Experiment)

**Prediction:** A superconducting body has a reduced gravitational mass
compared to its normal-conducting counterpart. The relative change in
free-fall acceleration at the normal → superconducting transition:

$$\frac{\Delta g}{g}\bigg|_{SC} \approx \frac{n_s}{n_e} \cdot \eta_{Cooper}$$

where n_s/n_e is the Cooper-pair density as a fraction of all conduction
electrons.

**Estimate:** For a well-developed superconductor (n_s/n_e ~ 10⁻⁴
at T/T_c = 0.5) and η_Cooper ~ 10⁻², this gives Δg/g ~ 10⁻⁶.

⚠️ **Confidence: ○ MEDIUM** — The concept is clearly founded in RFT. The
quantitative estimate contains several open parameters.

### 7.3 Direct Electron Gravimetry

**Idea (conceptual):** Compare atoms with different electron-to-nuclear mass
ratios in free fall. Hydrogen (electron = 0.054% of mass) vs. heavy atoms
(electron ~ 0.01% of mass).

**Challenge:** The precise prediction requires the not yet formalised factor
𝓕. Furthermore, the RFT prediction for normal matter (η_Eq ~ 10⁻¹⁰) is
already at the frontier of current measurement technology.

---

## 8. Limitations and Open Questions

### 8.1 Quantitative Proof of the 4π Coincidence

🚩 **Open question (Priority HIGH):**

The EP holds in RFT because the κ-field mechanism and the spin-lag mechanism
share the same 4π sphere geometry. This is conceptually compelling but
mathematically not yet rigorously proven.

**Sought:** A formal derivation showing:

```
m_i = ħκ_hadron/c = ħ(4π·κ_elementary)/c
m_g ~ 4π·G_elementary·m_elementary/G
    = 4π·κ_elementary·ħ/c  (if G·m = c²·L₀·f(κ))
→ m_i/m_g = 1 exactly for hadrons
```

This derivation requires that G·m can be expressed as a purely topological
quantity (→ RFT_v3_003, Ch. 8.1, Priority HIGH).

### 8.2 Formalisation of the η_Eq Expression

🚩 **Open question (Priority MEDIUM):**

The formula η_Eq = Δ_α² · (α⁻¹·π²)^(2/3) = 6.02×10⁻¹⁰ was confirmed by
Franz (25.03.2026, ✓ HIGH for the numerical value). The **mechanistic
derivation** — why precisely this combination of Δ_α and Q_crit1 — is not
yet fully formalised.

**Open:** Which physical process connects the α-phase asymmetry (2.22 ppm)
with the Q_crit1 factor (α⁻¹·π²)^(2/3)?

### 8.3 Discrepancy 10⁻⁵ vs. 6×10⁻¹⁰

🚩 **Open question (Priority MEDIUM):**

Older RFT documents (DC v1.1, Dec 2025) cite Δg ~ 10⁻⁵ for electrons vs.
hadrons (RFT_v3_004, Flag 4). The current canonical value is η_Eq ≈ 6×10⁻¹⁰.
This discrepancy of ~5 orders of magnitude requires a clarifying statement
from Franz:

- Do both numbers describe different observables?
- Was 10⁻⁵ a rough estimate for a different effect?
- Is 6×10⁻¹⁰ the correct Eötvös parameter?

### 8.4 Geometric Factor 𝓕

⚠️ **Open question:**

All quantitative experimental predictions (Ch. 7) contain a dimensionless
factor 𝓕 describing the geometric coupling between the Z/A ratio and the
η_Eq parameter. This factor has not been derived. Without it, the predictions
carry an uncertainty of at least one order of magnitude.

### 8.5 ħ-Free Formulation of m_i

○ **Known conceptual gap:**

m_i = ħκ/c contains ħ. Following the breakthrough of 25.03.2026 (L₀ = 1/κ
as the primary ħ-free definition), the ħ circularity is structurally broken.
A fully ħ-free formulation of m_i would read:

```
m_i = κ · (κ/c) · (dimensionless matrix unit)
    = κ² / c · (L₀ · c²/G) · ...
```

This formulation has not yet been written out. It is conceptually important
for the EP topic, because only then can m_i and m_g be expressed in the same
base quantities (c, L₀).

### 8.6 DS-015-A: Formal Proof m_i = m_g from Master Equation

🚩 **Open DeepSeek Task (DC v10.12, K.5):**

```
DS-015-A: m_i = m_g formally from the master equation (with RFT lens J.16!)

Sought: Show directly from the master equation why the κ-term
        and the spin-lag mechanism yield the same effective mass
        contribution for hadrons.

Challenge: The master equation describes a scalar field Ψ.
  m_i arises from the κ²Ψ term → local equilibrium property
  m_g arises from the spin-lag → dynamic, non-linear coupling

RFT lens mandatory: Standard arguments for EP (geodesic motion,
  Riemannian geometry) do not apply directly in RFT.
  → Argument must be formulated within the space matrix dynamics.

Status: 🚩 OPEN — recommended next step
```

---

## 9. Summary and Glossary

### 9.1 Core Results

| Statement | Confidence |
|-----------|-----------|
| Inertial mass m_i arises from κ-field (local compression resistance) | ✓ HIGH |
| Gravitational mass m_g arises from spin-lag torsion (trailing vortex) | ✓ HIGH |
| EP = geometric consequence, not a postulate | ○ MEDIUM (formally still open) |
| η_Eq = 6.02×10⁻¹⁰ (Eötvös parameter of RFT) | ✓ HIGH (Franz, 25.03.2026) |
| Electron (1 AP): m_i/m_g ≈ 1 − η_Eq | ○ MEDIUM |
| Photon (2 AP, ↑↑): m_g ≈ 0 at rest | ✓ HIGH |
| Cooper pair (↑↓): m_g strongly reduced | ○ MEDIUM |
| Quantitative proof of 4π EP mechanism | 🚩 OPEN |
| Factor 𝓕 for experimental predictions | 🚩 OPEN |

### 9.2 Conceptual Hierarchy

```
DRM Geometry (c, L₀, α)
        │
        ├─ κ-field (resonance stiffness)
        │       └─ m_i = ħκ/c    [LOCAL, instantaneous]
        │
        ├─ Spin-lag mechanism (τ_lag = L₀/c)
        │       └─ m_g ~ trailing vortex amplitude   [NON-LOCAL]
        │
        ├─ 4π coincidence (for hadrons)
        │       └─ m_i ≈ m_g   [Equivalence Principle]
        │
        └─ Phase asymmetry δ (time motor)
                └─ η_Eq = Δ_α² · Q_crit1^(2/3) ≈ 6×10⁻¹⁰  [EP break]
```

### 9.3 Open Flags (Priority)

```
🚩 Formally prove 4π coincidence         (Priority HIGH)
🚩 Derive mechanism of η_Eq             (Priority MEDIUM)
🚩 Clarify discrepancy 10⁻⁵ vs. 6×10⁻¹⁰  (Franz!)
⚠️ Geometric factor 𝓕                    (experimental predictions)
○  ħ-free formulation of m_i             (conceptual completeness)
```

### 9.4 Glossary

**Equivalence Principle (EP):** m_i = m_g. In standard physics a postulate;
in RFT an emergent geometric approximation.

**Anchor point (AP):** Coupling point of a vortex to the DRM. Electron = 1 AP,
photon = 2 AP (e⁺+e⁻). Structural property, not a conserved quantity.

**η_Eq (Eötvös parameter of RFT):** Predicted relative difference of
free-fall accelerations of two bodies with different electron fractions.
η_Eq = Δ_α² · (α⁻¹·π²)^(2/3) ≈ 6.02×10⁻¹⁰. Distinct from the
baryon-asymmetry parameter of v3_009 (same numerical value, different physics).

**κ (resonance stiffness):** Local matrix property [1/m] from the master
equation. Primary definition of L₀ = 1/κ (ħ-free). Sets the inertial mass:
m_i = ħκ/c.

**Trailing vortex:** Torsion field in the DRM behind a rotating vortex.
The physical carrier of the gravitational field in RFT.

**Spin-lag:** Phase delay τ_lag = L₀/c between a rotating vortex and the
surrounding DRM. Origin of gravitational mass.

**τ_lag:** Characteristic spin-lag timescale. τ_lag = L₀/c = (π/6)·t_P.
Canonically confirmed.

---

## References

- RFT_v3_001 v3.6: Mathematical Foundations (κ-definition, master equation,
  anchor points, δ-time motor), Feb/Mar 2026
- RFT_v3_003 v1.0: Gravitation and Spin-lag (trailing vortex, 4π mechanism,
  τ_lag), Feb 2026
- RFT_v3_004 v3.3: Impulse and Energy (dispersion relation, ħ status,
  Cooper pair Flag 4), Feb/Mar 2026
- RFT_v3_012: Electromagnetism (τ_lag canonical value, torsional mode), 2026
- Franz Zollner, direct confirmation η_Eq value, 25.03.2026
- CODATA 2018: α⁻¹ = 137.035999084 (reference value for 2.22 ppm deviation)
- MICROSCOPE mission (2022): Eötvös test η < 10⁻¹³

---

## Changelog

**v1.2-EN-r1 (April 2026):**
- Translation from DE v1.2 by KI Instance 015
- η_Eq naming confirmed distinct from baryon-asymmetry parameter (v3_009) — note added §5.2
- Canonical EN terminology: "trailing vortex", "spin-lag", "anchor point",
  "Discrete Resonance Matrix (DRM)" per v3-EN series standard
- All confidence markers converted: ✓ HIGH / ○ MEDIUM / 🚩 OPEN

---

## 📋 INTERNAL FEEDBACK BRIEF (Instance 015 → K2)

**Date:** April 2026 | **DC Basis:** v10.12 | **Instance:** 015

### Translation checks
```
✓ "Schleppwirbel"  → "trailing vortex"   (consistent with v3_003-EN)
✓ "Spinverzug"     → "spin-lag"          (consistent with v3_003-EN)
✓ "Ankerpunkt"     → "anchor point (AP)" (consistent with v3_011-EN)
✓ "Raummatrix"     → "Resonance Matrix"  (consistent with v3_series-EN)
✓ "Raumgitter"     → avoided (0 occurrences in DE source)
✓ η_Eq naming: no collision with baryon-asymmetry parameter → note added §5.2
✓ Confidence markers: ✓ HIGH / ○ MEDIUM / 🚩 OPEN / ⚠️ OPEN/SPECULATIVE
```

### Audit checks
```
Baryon-symbol occurrences (must be 0): 0 ✓
"Raummatrix" terminology: consistent ✓
Speed-of-light symbol: c throughout (no subscript) ✓
Version header: v1.2-EN-r1 ✓
```

### Open flags carried over from DE
```
🚩 DS-015-A: formal proof m_i = m_g (DeepSeek, with RFT lens)
🚩 Mechanism of η_Eq: value ✓ HIGH, physical derivation ○ MEDIUM
⚠️ Discrepancy 10⁻⁵ vs. 6×10⁻¹⁰: Franz clarification still open
⚠️ Ch. 3.2 (EM vs. gravitation modes): interpolation — Franz confirmation recommended
○  ħ-free formulation of m_i: conceptual completeness (not a blocker)
```

*Instance 015 | Final Candidate v1.2-EN-r1 | April 2026*

---

**© 2026 Franz Zollner — Resonance Field Theory Project**  
**License:** Creative Commons BY-NC-SA 4.0  
**Document-ID:** RFT_v3_015_Inertia_Equivalence_EN_v1.2
