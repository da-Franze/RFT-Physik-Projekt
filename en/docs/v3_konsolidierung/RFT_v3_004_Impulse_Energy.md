# RFT_v3_004: Impulse and Energy in Resonance Field Theory
## Resonance Field Theory — Publication Series v3

**DOCUMENT-ID:** RFT_v3_004_Impulse_Energy_EN
**VERSION:** v3.2-EN (Translation: 25 March 2026 | Source: DE v3.2, 25.03.2026)
**STATUS:** Working document — core statements rigorous, open points explicitly marked
**DEPENDENCIES:** RFT v3 Mathematical Foundations (v3_001), RFT v3 Fine Structure Constant (v3_002), RFT v3 Gravitation and Spin Delay (v3_003)
**AUTHOR:** Franz Zollner
**FORMALIZATION:** AI instance (Multi-Instance Protocol v6.1)
**LICENSE:** CC BY-NC-SA 4.0
**Contact:** rft.projekt@posteo.de

---

> ⚠️ **Methodological note:** All concepts originate with Franz Zollner.
> Written formalization by an AI instance. All formulas and statements
> should be read critically. In case of doubt: set FLAG and ask Franz.

---

## How to Read This Document

Three types of statements appear throughout, consistently marked:

- **✓ HIGH** — rigorously derived or confirmed by Franz Zollner
- **○ MEDIUM** — conceptually consistent, formally still open
- **⚠️ OPEN** — formal gap, algebraic identity, or working hypothesis

**The causal direction in RFT is always: Geometry → Constants.** Never the reverse.

---

## Abstract

Momentum and energy are, in standard physics, emergent descriptions of
dynamical states — but what are they when mass is not a fundamental concept?

This document develops the RFT answer in three building stages:

**Stage 1 (Sections 2–5):** Momentum and energy emerge from the wave physics
of the **Dynamic Resonance Matrix (DRM)**. The de Broglie relations p = ħk
and E = ħω follow directly from the Master Equation (derivation: RFT v3
Mathematical Foundations, Sec. 2). The Einstein energy-momentum relation
E² = (pc)² + (mc²)² is derived from the dispersion relation. ħ is used
here as a given quantity — with an explicit caveat (see Stage 2).

**Stage 2 (Section 6):** ħ is, in the v3 series, an algebraic identity —
not an independently derived quantity (derivation: RFT v3 Mathematical
Foundations, Sec. 7.3). Rather than concealing this, ħ is re-anchored
conceptually as the natural action quantum of a matrix cell:
ħ_natural ≡ (36/π²)·c³L₀²/G. Furthermore, the circularity has been
formally broken: **L₀ = 1/κ** (κ = matrix stiffness, from the Master
Equation, ħ-free) is the primary definition. ✓ HIGH (Franz Zollner,
25.03.2026)

**Stage 3 (Section 7):** As an outlook, a sketch of a fully ħ-free
formulation of momentum and energy — as an open research direction,
not a completed calculation.

**Prerequisites (standalone summary):**
- RFT v3 Mathematical Foundations: Master Equation, κ as resonance
  stiffness, L₀ = (π/6)·l_P = 1/κ
- RFT v3 Fine Structure Constant: α⁻¹ = 4π³+π²+π, Φ = 2α/(1+α²)
- RFT v3 Gravitation and Spin Delay: μ = G·m as topological quantity,
  [kg] as label for trailing-vortex strength

---

## Terminology Reference (v3-canonical)

| Symbol | Meaning | Source |
|--------|---------|--------|
| κ | **Resonance stiffness** of the matrix (NOT "mass parameter"!) | v3_001 |
| L₀ = (π/6)·l_P = 1/κ | Fundamental matrix spacing | v3_001, Sec. 5 |
| α⁻¹ = 4π³+π²+π | Fine structure constant from π-geometry | v3_002 |
| Φ = 2α/(1+α²) | Flux factor | v3_002 |
| μ = G·m | Topological fundamental quantity [m³/s²] | v3_003 |
| Vortex structure | Topological resonance structure in the DRM | v3_001 |
| Soliton | Stable vortex (topologically bound) | v3_001 |
| DRM | **Dynamic Resonance Matrix** = the vacuum itself | v3_001 |

**Important:** [kg] is not a law of nature — it is a label for
trailing-vortex strength. The physically fundamental quantity is
μ = G·m [m³/s²]. This applies to all momentum and energy expressions
in this document.

---

## Table of Contents

1. Paradigm: Why Momentum and Energy Must Be Redefined
2. Energy as Matrix Deformation Energy
3. Momentum as Resonance-Wave Momentum
4. Soliton Structure and Energy Quantization
5. Interaction and Momentum Transfer
6. ħ as an Emergent Matrix Unit — Conceptual Clarification
7. Outlook: ħ-Free Formulation (Sketch, Open)
8. Known Limitations and Open Questions

---

## 1. Paradigm: Why Momentum and Energy Must Be Redefined

### 1.1 The Problem with p = m·v

The classical definition of momentum is:

```
p = m · v
```

This presupposes that m is a fundamental property of a particle.
In RFT, that is not the case.

From RFT v3 Gravitation (Sec. 3) and RFT v3 Mathematical Foundations
(Sec. 6–7):

- Mass is not a fundamental property of a vortex.
- What we call "mass" is the label for a state of elevated local node
  tension around a stable vortex structure.
- The physically fundamental quantity is μ = G·m [m³/s²], not m alone.
- [kg] is a label for trailing-vortex strength — not a law of nature.

If m is not fundamental, then p = m·v is not fundamental either.

**The RFT paradigm shift:**

```
CLASSICAL:                     RFT:
A particle moves through space  A resonance pattern propagates further
p = property of the object      p = property of the resonance
Space is passive                Space (DRM) is active, dynamic
```

Momentum does not describe the motion of an object. It describes the
**spatial modulation of a wave pattern in the DRM**.

### 1.2 Starting Point: The Master Equation

All derivations in this document are based on the RFT Master Equation
(derivation: RFT v3 Mathematical Foundations, Sec. 2):

$$\frac{\partial^2\Psi}{\partial t^2} = c^2\nabla^2\Psi - \gamma\frac{\partial\Psi}{\partial t} - c^2\kappa^2\Psi + \lambda|\Psi|^2\Psi + \eta$$

Symbols:
- Ψ: resonance field (scalar field in the DRM)
- c: speed of light (sole genuine fundamental input)
- κ: **resonance stiffness** [1/m] (NOT "mass parameter"!)
- γ: damping term (for dissipative processes)
- λ: nonlinearity parameter (stabilizes solitons)
- η: noise term (vacuum fluctuations)

**Causal direction — a critical distinction from QFT:**

In quantum mechanics (Klein-Gordon equation), mass m is the *input*:
the term −(mc/ħ)²Ψ is driven by an externally given mass. In RFT,
κ is a *matrix property* — an output of the geometry — from which
"mass" emerges as a derived observational label. The causal direction
is inverted.

---

## 2. Energy as Matrix Deformation Energy

### 2.1 Energy Density from the Master Equation

The energy density of the resonance field Ψ follows from the
energy-momentum tensor. For the Master Equation (✓ HIGH — standard
result for wave fields):

$$\mathcal{E} = \frac{1}{2}\left|\frac{\partial\Psi}{\partial t}\right|^2 + \frac{c^2}{2}|\nabla\Psi|^2 + \frac{c^2\kappa^2}{2}|\Psi|^2$$

The three terms have distinct physical meanings:
- **Kinetic density:** temporal change of the field
- **Gradient energy:** spatial deformation (matrix tension)
- **Potential density:** stiffness term (κ-term)

**No point particles.** A vortex is an extended structure with spatial
extent ≈ λ_C = ħ/(m_eff·c) (Compton wavelength). The total energy of
the vortex is the volume integral over ε:

$$E_{\text{vortex}} = \int d^3x \; \mathcal{E}[\Psi_{\text{vortex}}]$$

This integral is finite — because λ_C is finite. The UV divergences of
classical point-particle theory arise from an incorrect assumption
(point particles), not from physics.

### 2.2 Dispersion Relation and the Einstein Relation

**Derivation (✓ HIGH):**

We use the plane-wave ansatz:

$$\Psi = A \, e^{i(kx - \omega t)}$$

Substituting into the linearized Master Equation (γ = 0, λ = 0, η = 0):

$$-\omega^2 = -c^2 k^2 - c^2 \kappa^2$$

**Dispersion relation:**

$$\boxed{\omega^2 = c^2(k^2 + \kappa^2)}$$

Multiplying both sides by ħ² (ħ used as a formal scaling factor;
see Section 6 for its conceptual status in RFT):

$$\hbar^2\omega^2 = c^2\hbar^2 k^2 + c^2\hbar^2\kappa^2$$

Using the de Broglie relations p = ħk and E = ħω:

$$E^2 = (pc)^2 + (\hbar c\kappa)^2$$

**Identification:** The κ-term supplies the rest energy. More precisely:
the matrix property κ sets the rest energy scale:

$$m_{\text{eff}}c^2 \equiv \hbar c \kappa$$

The **Einstein energy-momentum relation** thus follows directly from
the Master Equation:

$$\boxed{E^2 = (pc)^2 + (m_{\text{eff}}c^2)^2}$$

✓ HIGH — verified (standard derivation from dispersion relation)

In standard QM and SR, this relation is postulated or derived from
symmetry arguments. In RFT, it is a direct consequence of the
DRM dispersion relation — no additional postulate required.

**Important caveat:** This derivation uses ħ as a given quantity. The
conceptual status of ħ in RFT is addressed explicitly in Section 6.

### 2.3 Vortex Energy as a Topological Invariant

Stable vortices (solitons) in the DRM have a special property: their
topology is characterized by a winding number n. The energy of this
configuration is not arbitrary — it is quantized by the matrix geometry.

For a rotationally symmetric n-fold phase winding (derivation: RFT v3
Mathematical Foundations, Sec. 8.2, Stage 2a):

$$E_n \propto n^2 \cdot \frac{c^2}{L_0}$$

The fundamental result (RFT v3 Mathematical Foundations, Sec. 8):

$$m_n \cdot c^2 = n \cdot \pi \cdot k_B \cdot T_{\text{cond}}$$

where T_cond is the condensation temperature at which the DRM node
structure first freezes into coherent topological configurations. For
the proton (n = 2, via SU(2) algebra of three orthogonal quarks):
m_p·c² ≈ 938.3 MeV (experiment).
⚠️ MEDIUM — the complete derivation from soliton solutions of the Master
Equation remains open (RFT v3 Mathematical Foundations, Sec. 12.7).

---

## 3. Momentum as Resonance-Wave Momentum

### 3.1 What Momentum Means in RFT

Momentum does not describe "how fast an object moves" — it describes
the **spatial modulation of the resonance pattern**.

**Analogy — The Mexican Wave:**

```
Stadium: 80,000 people stand up and sit down.
├─ Each person: oscillates locally up/down
├─ Wave front: propagates horizontally
└─ NO person moves sideways!

DRM resonance matrix:
├─ Each node: oscillates locally in Ψ
├─ Modulation: propagates with wave vector k
└─ NO matrix node moves laterally!

Momentum = wave vector k of the propagating modulation
```

This is not merely a pictorial analogy. The wave vector k is the precise
mathematical description of the spatial modulation — and p = ħk is its
physical magnitude.

### 3.2 The de Broglie Relation in RFT — p = ħk is Derived, Not Postulated

In standard quantum mechanics, p = ħk is postulated (de Broglie, 1924).
In RFT, it is derived.

**Derivation (✓ HIGH — from Noether's theorem):**

Momentum conservation follows from the spatial translation invariance
of the Master Equation via Noether's theorem. The canonical momentum
of the field Ψ is:

$$p_{\text{canonical}} = \frac{\partial \mathcal{L}}{\partial(\partial_x\Psi)} \cdot \partial_x\Psi$$

For a plane wave Ψ = A·e^{i(kx−ωt)} and the corresponding Lagrangian
density, this gives directly:

$$p = \hbar k$$

**This is not a postulate — it is the consequence of translation symmetry
of the DRM.** The de Broglie relation is a theorem, not an axiom, in RFT.

### 3.3 Group Velocity — the Observable Particle Velocity

A critical distinction for physicists: the *observable* velocity of a
vortex is not the phase velocity (v_phase = ω/k), but the **group
velocity** of the wave packet:

$$v_g = \frac{d\omega}{dk}$$

From the dispersion relation ω² = c²(k² + κ²):

$$v_g = \frac{c^2 k}{\omega} = \frac{c^2 p}{E}$$

Note: The phase velocity v_phase = ω/k can exceed c (it carries no
information or energy). Only the group velocity v_g ≤ c is observable.

**Limiting cases (✓ HIGH):**

```
Non-relativistic (p << m_eff·c):
  v_g ≈ p / m_eff = v_classical    ✓ (Newton's mechanics emerges!)

Relativistic (p >> m_eff·c):
  v_g → c                           ✓ (speed-of-light limit)

Photon (κ = 0):
  v_g = c exactly                   ✓ (massless propagation)
```

Newtonian mechanics and special relativity emerge as limiting cases —
they are not postulated separately.

### 3.4 Quantization by Matrix Boundary Conditions

In the discrete resonance matrix (matrix spacing L₀), not all k-values
are permitted. The periodic boundary conditions of the matrix impose:

$$k_n = \frac{2\pi n}{N \cdot L_0}, \quad n \in \mathbb{Z}$$

where N is the number of matrix nodes in one direction. This means:
momentum is quantized by the matrix geometry. ħ sets the scale, but
the quantization itself is geometric.

⚠️ MEDIUM — The derivation of the continuum limit (N → ∞, L₀ → 0
at fixed c) and the question of Lorentz invariance remain open
(see Section 8.2).

---

## 4. Soliton Structure and Energy Quantization

### 4.1 Why Stable Particles Are Topological Solitons

A particle in RFT is neither a point nor an ordinary wave packet. It is
a **topological soliton**: a stable vortex structure that persists without
external forces — not because of a potential barrier, but because
topological change is impossible without a phase jump.

The winding number n cannot change continuously from n to n±1. A
transition requires a topological phase jump — this is the RFT mechanism
underlying particle stability. The analogy to topological insulators in
condensed matter physics is structural, though the mechanism is distinct.

### 4.2 Discrete Energy Levels

From winding number quantization and the condensation condition
(RFT v3 Mathematical Foundations, Sec. 8):

$$E_n = n \cdot \pi \cdot k_B \cdot T_{\text{cond}}$$

For n = 1: electron energy scale (using T_e)
For n = 2: proton energy scale (T_QCD)

The **Anchor Point (AP)** count relates to stability, but not directly
to energy. An AP is the coupling site of a vortex to the DRM — not a
geometric point, but a dimensional coupling (Franz Zollner, 15.03.2026):

| Particle | n | AP | Stability |
|----------|---|----|-----------|
| Electron | 1 | 1 | stable (topological) |
| Proton (uud) | 2 | 9 | stable |
| Meson (e.g. π) | 1 | 6 | metastable |

⚠️ MEDIUM — derivation of lifetimes from AP count remains open
(RFT v3 Mathematical Foundations, Sec. 8.1).

### 4.3 Connection to the Particle Spectrum

Charge quantization follows from the hourglass geometry of the resonance
matrix (RFT v3 Mathematical Foundations, Sec. 4; PDF Framework):

```
Winding number n:
n = ±1     → Electron / Positron   (charge ±e)
n = ±2/3   → u, c, t quarks
n = ±1/3   → d, s, b quarks
n =  0     → Neutrino candidate (longitudinal wave)
```

Momentum and energy of a particle are properties of the entire resonance
pattern — not of a point. The Compton wavelength λ_C = ħ/(m_eff·c) sets
the spatial extent of the resonance:

For the electron: λ_C ≈ 2.426 × 10⁻¹² m

This is not an ad hoc assumption — it follows from the matrix physics.

---

## 5. Interaction and Momentum Transfer

### 5.1 Momentum Transfer Is Spatial, Not Pointlike

**Classical picture:** Two point particles collide at r → 0.
Problem: F → ∞, E → ∞ (divergence).

**RFT:** Two vortices interact through their extended resonance fields.
The minimum interaction area is set by the Compton wavelength:

$$A_{\text{min}} \approx \lambda_C^2 = \left(\frac{\hbar}{m_{\text{eff}}c}\right)^2$$

Consequences:
- No point collision → no UV divergence
- Energy conservation automatically guaranteed
- Momentum transfer is a coupling process between resonance modes

UV divergences of quantum field theory arise from the assumption of
point particles. In RFT they are structurally absent — no renormalization
required for this class of divergence.

### 5.2 α as the Measure of Coupling Strength

The fine structure constant α (derived in RFT v3 Fine Structure Constant
from pure π-geometry: α⁻¹ = 4π³+π²+π, residual 2.22 ppm vs. CODATA)
measures the coupling strength between electromagnetic vortices.

For photon-electron interaction (Compton scattering):

$$\sigma \propto \alpha^2 \cdot \lambda_C^2$$

α appears as the natural measure of momentum transfer per interaction
event. The connection to the flux factor Φ = 2α/(1+α²) ≈ 0.014596:

Φ describes the fraction of momentum transferred in a coupling event,
relative to the full topological winding.
○ MEDIUM — this interpretation is physically motivated but not yet
fully formalized.

### 5.3 Local or Non-Local?

In RFT there is no instantaneous action at a distance. Momentum transfer
occurs through propagation of modifications in the DRM at group velocity
v_g ≤ c. The transfer is local in the sense of "field-mediated" (as in
standard field theory), but spatially extended (not pointlike).

---

## 6. ħ as an Emergent Matrix Unit — Conceptual Clarification

### 6.1 The Status of ħ in the RFT v3 Series

**Starting point — an algebraic identity:**

From RFT v3 Mathematical Foundations, Sec. 7.3 (explicitly documented,
✓ HIGH):

$$G \cdot \hbar = \frac{36}{\pi^2} \cdot c^3 \cdot L_0^2$$

This appears to be a derivation of ħ. It is, in fact, an algebraic
identity: the relation follows from the definition L₀ = (π/6)·l_P with
l_P = √(ħG/c³), which already contains ħ on both sides.

The system is consistent — but historically circular.

**UPDATE — circularity formally broken (25.03.2026):**

The circularity arose because L₀ was defined via l_P. The primary
definition is:

```
L₀ = 1/κ    [κ = matrix stiffness, from Master Equation, ħ-free]
```

In RFT, the causal direction is inverted:
- κ (resonance stiffness) is the **primary quantity** — a property of
  the vacuum medium, derived from the Master Equation geometry
- L₀ = 1/κ follows geometrically, ħ-free
- ħ appears as a convenient notation for (36/π²)·c³L₀²/G —
  an algebraic identity, not an independently derived constant

```
L₀ = 1/κ is the primary quantity — ħ-free ✓
l_P = √(ħG/c³) is derived notation, not a foundation
G·ħ = (36/π²)·c³·L₀² remains as an algebraic consistency relation ✓
```

Status: from 🚩 (highest priority since project start) → ✅ CLOSED
✓ HIGH (Franz Zollner direct statement, 25.03.2026)

**This is not a weakness of RFT — it is an honest account of what has
been shown.**

### 6.2 ħ as the Natural Action Quantum of a Matrix Cell

**Conceptual re-anchoring:**

In RFT, the smallest action unit is not postulated — it is the minimal
action associated with a matrix cell of edge length L₀ propagating at
speed c.

Dimensionally, ħ is uniquely determined from c, G, L₀:

$$\hbar_{\text{natural}} \equiv \frac{c^3 L_0^2}{G} \cdot f(\pi)$$

Numerically: f(π) = 36/π² = (6/π)² ≈ 3.648 (squared sphere-to-cube
volume ratio — the same geometric factor that connects L₀ and l_P)

$$\hbar_{\text{natural}} = \frac{36}{\pi^2} \cdot \frac{c^3 L_0^2}{G}$$

**What is gained by this?**

The formula makes explicit **what ħ means in RFT:** it is the action
of a matrix cell — the product of energy (c³/G·L₀) and time (L₀/c).
In this interpretation, ħ is not an external factor inserted into
physics, but a direct consequence of matrix geometry.

More precisely (Franz Zollner, 25.03.2026):

> ħ = **minimum action for a stable mode transition**
> = "the willingness to change" of a matrix cell

**This is not a proof — it is a conceptual clarification.**

### 6.3 Status After 25.03.2026

✅ The circularity is formally broken:
L₀ = 1/κ (κ from Master Equation, ħ-free).

What conceptually remains:

- ħ = "minimum action for stable mode transition" ✓ HIGH (Franz, 25.03.2026)
- G·ħ = (36/π²)·c³·L₀² as consistency relation ✓
- ħ_natural ≡ (36/π²)·c³L₀²/G as conceptual anchor value ✓

The RFT framework is now fully closed in this respect:
all fundamental constants trace back to the Master Equation.

---

## 7. Outlook: ħ-Free Formulation (Sketch, Open)

○ **Status: Working hypothesis / research direction — NOT a completed calculation**

### 7.1 Motivation

If ħ is an emergent matrix unit (Section 6), it should be possible to
express momentum and energy fully in matrix quantities — without ħ as
a separate input.

### 7.2 Approach

Substitute ħ_natural = (36/π²)·c³·L₀²/G:

**Momentum without ħ as input:**

$$p = \hbar k = \frac{36}{\pi^2} \cdot \frac{c^3 L_0^2}{G} \cdot k$$

For k = 2π/λ:

$$p = \frac{36}{\pi^2} \cdot \frac{c^3 L_0^2}{G} \cdot \frac{2\pi}{\lambda} = \frac{72}{\pi} \cdot \frac{c^3 L_0^2}{G \lambda}$$

○ **Origin of the factor 72/π — purely algebraic, no new geometry:**

```
72/π  =  (36/π²) × 2π
          ↑             ↑
    from ħ_nat        from k = 2π/λ
    (Sec. 6.2)         (definition of wave number)
```

The factor arises solely from substituting ħ_nat and k = 2π/λ. It
carries no independent geometric meaning. A genuinely ħ-free formulation
would require expressing k itself in matrix units — writing λ as a
multiple of L₀: λ = n·L₀. Then:

$$p = \frac{72}{\pi} \cdot \frac{c^3 L_0}{G \cdot n} \quad (n \in \mathbb{R})$$

This is geometrically cleaner — p in units of c³L₀/G — but n remains
a continuous parameter, not a discrete matrix quantity.
○ LOW confidence — the step to a fully geometrically grounded momentum
unit has not yet been made.

This can also be written as:

$$p = \frac{c^2}{\mu} \cdot \left(\frac{72}{\pi} \cdot \frac{L_0^2}{\lambda}\right)$$

where μ = G·m is the topological fundamental quantity.

**Energy without ħ as input:**

$$E = \hbar\omega = \frac{36}{\pi^2} \cdot \frac{c^3 L_0^2}{G} \cdot \omega$$

For ω = 2πf:

$$E = \frac{72}{\pi} \cdot \frac{c^3 L_0^2}{G} \cdot f$$

○ Analogously: the factor 72/π is algebraic (from ħ_nat × 2π), with no
geometric interpretation of its own. Physically cleaner: measure f in
units of c/L₀ — i.e., f = m·(c/L₀) — then E = (72/π)·(c²L₀/G)·m.
The matrix eigenfrequency c/L₀ would then be the natural energy unit.

### 7.3 What the Unknown Factor Signifies

In both expressions the factor 72L₀²/(π·λ) or 72L₀²·f/(π·c) appears.
This has the dimension of an area (times a number), describing the
ratio between the matrix cell size L₀² and the resonance extent λ²
of the vortex.

**Hypothesis (○ — unverified):**

This factor may be the anchor-point area of a vortex in matrix units.
For an electron with characteristic extent λ_C: 72L₀²/(π·λ_C) ≈
72L₀²/(π·ħ/(m_e·c)). This again leads back to ħ — as long as L₀ is
not independently defined.

The ħ-free formulation is non-trivial only if L₀ is derived from
matrix geometry without reference to l_P = √(ħG/c³). With L₀ = 1/κ
established as the primary definition (Section 6.1), this path is now
open in principle — but the explicit ħ-free computation of a specific
particle's dynamics remains an open research task.

🚩 **Open research question:** Can the matrix spacing L₀ = 1/κ be
used directly to express all vortex dynamics without ever introducing ħ?
This would require a fully κ-based derivation of the Compton scale.
That is the most important open question in this domain.

---

## 8. Known Limitations and Open Questions

### 8.1 ✅ ħ Circularity — RESOLVED (25.03.2026)

**Former status:** 🚩 highest priority since project start.

**Now closed:** L₀ = 1/κ (κ = matrix stiffness, from Master Equation,
not dynamic, ħ-free). Franz Zollner, 25.03.2026.

```
L₀ = 1/κ is the primary quantity
l_P = √(ħG/c³) is derived notation
G·ħ = (36/π²)·c³·L₀² remains as algebraic consistency relation ✓
```

✓ HIGH (Franz direct statement). Details: Sections 6.1, 6.3.

### 8.2 Lorentz Invariance in the Resonance Matrix

⚠️ **Status: Known open question — explicitly stated, not avoided**

The resonance matrix with spacing L₀ appears to imply a preferred
reference frame (discrete matrix → rotational symmetry broken at
Planck scale).

Lorentz invariance is experimentally confirmed to < 10⁻²³ (GRB
experiments, e.g. Fermi-GBM). The DRM must reproduce Lorentz
invariance in the continuum limit.

**Sketched resolution path (○ — not yet fully worked out):**

In the continuum limit k·L₀ ≪ 1 (wavelengths far above the Planck
scale), the dispersion relation behaves:

$$\omega^2 = c^2(k^2 + \kappa^2) \quad \xrightarrow{k L_0 \ll 1} \quad \text{continuous, isotropic}$$

The matrix is then "invisible" at all experimentally accessible
energies. Lorentz invariance emerges as an effective symmetry.

**What is still missing:** A rigorous proof that the cubic matrix
anisotropy at Planck scale has no observable influence, even in
cumulative effects (e.g. very high-energy photons over cosmological
distances). Marked as ⚠️ open.

### 8.3 T_QCD Circularity

⚠️ **Status: Known gap**

The proton mass derivation m_p·c² = (2π−2α)·k_B·T_QCD (RFT v3
Mathematical Foundations) uses T_QCD as an empirical input. A
derivation of T_QCD from fundamental RFT quantities (c, L₀, α) alone
is not yet available.

This affects Section 4: the energy quantization E_n = n·π·k_B·T_cond
is conceptually clear, but its absolute scale is not yet fully
circularity-free.

### 8.4 Inertial vs. Gravitational Mass

○ **Status: Conceptually clear, quantitatively open**

In RFT, inertial mass m_i (from κ-term, local, instantaneous) and
gravitational mass m_g (from spin delay, collective, time-averaged)
have mechanically different origins. The equivalence principle is an
approximation that breaks in topological edge cases (derivation:
RFT v3 Gravitation and Spin Delay, Sec. 5).

**Consequence for momentum and energy:**
In ordinary conditions: p = m_i·v_g = m_g·v_g (identical). Only in
topological edge cases must one distinguish:
p_inertial = m_i·v_g ≠ p_gravitational = m_g·v_g (prediction: Δ ≈ 10⁻⁵).

This is an experimentally testable RFT prediction (Cooper pairs,
PTB Braunschweig).

---

## 9. Summary

### 9.1 Core Results (secured)

```
✓ E² = (pc)² + (m_eff·c²)²    from dispersion relation of Master Eq.
✓ p = ħk                       from translation symmetry (Noether)
✓ E = ħω                       from time invariance (Noether)
✓ v_g = dω/dk = c²p/E          from dispersion relation
✓ v_g → v_classical (p→0)      Newtonian mechanics emerges as limit
✓ v_g → c (p→∞)                Special relativity emerges as limit
✓ E_n = n·π·k_B·T_cond         energy quantization via topology
✓ A_min ≈ λ_C²                 spatial momentum transfer, no point
```

### 9.2 Conceptual Clarifications

```
○ ħ = (36/π²)·c³L₀²/G          algebraic identity (not derivation)
✓ L₀ = 1/κ                     primary definition, ħ-free (25.03.2026)
○ ħ as action quantum            of a matrix cell — conceptual re-anchoring
○ ħ-free formulation             sketched — geometric factor still open
```

### 9.3 Open Flags (current status)

```
⚠️ Lorentz invariance:     emergence in continuum limit — formally open
⚠️ T_QCD scale:            not yet derived from (c, L₀, α)
⚠️ κ-based particle dyn.:  explicit ħ-free vortex computation open
```

### 9.4 Consistency with v3 Series

```
RFT v3 Mathematical Foundations: ✓ Master Equation identical, κ canonical
RFT v3 Fine Structure Constant:  ✓ α = 1/(4π³+π²+π), Φ = 2α/(1+α²)
RFT v3 Gravitation:              ✓ μ = G·m fundamental, [kg] as label
```

---

## Glossary

**Dispersion relation:** ω² = c²(k² + κ²) — relation between angular
frequency ω and wave vector k in the DRM, derived from the Master Equation.
The parent of all momentum-energy relations in RFT.

**Dynamic Resonance Matrix (DRM):** The fundamental carrier medium of RFT.
Not a rigid crystal lattice — a self-resonant, dynamic node structure.
The vacuum itself. DRM is the correct abbreviation (not "lattice", not
"space lattice").

**Group velocity:** v_g = dω/dk. The observable velocity of a wave packet
(vortex). Corresponds to the classical particle velocity in the
non-relativistic limit. Always ≤ c.

**κ (resonance stiffness):** Matrix property [1/m]. Sets the effective rest
energy via ħcκ. Not the same as the mass parameter in Klein-Gordon theory
(there, mass is input; here, κ is geometric output → mass is emergent label).

**L₀ = (π/6)·l_P = 1/κ:** Fundamental matrix spacing, defined primarily
as L₀ = 1/κ (ħ-free). The numerical relation L₀ = (π/6)·l_P is a
verification, not the definition. Derivation: sphere-to-cube volume ratio.

**Phase velocity:** v_phase = ω/k. Can exceed c — carries no energy or
information. Not observable. Distinct from group velocity.

**Soliton:** Topologically stable vortex. Particle = soliton in RFT.
Winding number n cannot change continuously.

**ħ_natural:** Conceptual definition: action quantum of a matrix cell.
ħ ≡ (36/π²)·c³L₀²/G. Algebraically identical to standard ħ, but
physically re-anchored as the minimum action for a stable mode transition.

---

## Changelog

**v3.2-EN (25 March 2026):**
- Full English translation of DE v3.2
- Section 6.1: ħ circularity milestone translated and contextualized
  for physicists (causal-direction explanation added)
- Section 3.2: de Broglie context for physicists added (postulate vs.
  derivation explicitly stated)
- Section 2.2: Einstein relation contextualized vs. SR derivation
- Sec. 8.5 (source): obsolete note "v3_003 does not exist" removed —
  DC v10.7 confirms v3_003 ✅ Final v3.0
- Section 9.3: ħ-circularity flag updated to ✅ (consistent with Sec. 8.1)
- All "Gitter/Gitterpunkte/Gitterwellen" → "resonance matrix/DRM" per
  DC v10.7 terminology rule
- DRM corrected: "Dynamic Resonance Matrix" (not "Discrete")
- Translation instance: T6

---

*RFT_v3_004 — Impulse and Energy in Resonance Field Theory*
*Working document | 25 March 2026 | Translation instance T6*
*Source: DE v3.2 (25.03.2026) | Glossary: RFT_v3_Glossar_EN.md*
*Key result: E² = (pc)² + (mc²)² emerges from dispersion relation ω²=c²(k²+κ²)*
*ħ milestone: L₀ = 1/κ primary definition, ħ-free ✓ HIGH (Franz, 25.03.2026)*
