# RFT_v3_008: Black Holes as Mode Transition Phenomena
## Resonance Field Theory — Publication Series v3

**DOCUMENT-ID:** RFT_v3_008_Black_Holes_Mode_Transition_EN
**VERSION:** v1.0-EN (Translation: 26 March 2026 | Source: DE Draft v1.1)
**STATUS:** Translation Draft (pending Franz Zollner's Final declaration of DE v1.1)
**TOPIC:** The event horizon as mode transition boundary of the Dynamic Resonance Matrix; no singularity; information preserved in Mode 2
**DEPENDENCIES:** RFT v3 Space Topology & 3D Emergence (v3_007); RFT v3 Mathematical Foundations (v3_001); RFT v3 Gravitation and Spin Delay (v3_003); RFT v3 Time Emergence (v3_006)
**AUTHOR:** Franz Zollner
**LICENSE:** CC BY-NC-SA 4.0
**Contact:** rft.projekt@posteo.de

---

## Preliminary Note: How to Read This Document

This document uses a consistent notation for confidence levels:

- **✓ HIGH** — rigorous derivation or direct confirmation by Franz Zollner
- **○ MEDIUM** — conceptually consistent, formally still open
- **⚠️ LOW / SPECULATIVE** — working hypothesis only
- **🚩 OPEN** — active research problem

RFT is not a replacement for General Relativity (GR) or the Standard Model. Both are experimentally excellent. RFT proposes a mechanistic substrate from which their equations emerge as limiting cases. Where the two frameworks diverge, this document states so explicitly.

---

## Preliminary Note: Position in the v3 Series

This document closes the foundational series by treating the most extreme gravitational states. The preceding documents supply all necessary tools:

| Document | Contribution | Relevant for v3_008 |
|----------|-------------|---------------------|
| v3_001 | Master Equation, resonance stiffness κ, winding numbers | ✓ Direct |
| v3_003 | G·m as topological quantity | ✓ Direct |
| v3_006 | Time motor, Φ-asymmetry, Q-dynamics | ✓ Cross-reference |
| v3_007 | Anchor points, 4-AP mode transition | ✓ Direct |

**Core thesis:** What General Relativity describes as a mathematical singularity is, in RFT, an *ordered phase transition* — a mode transition of the resonance matrix into the next harmonic. The resonance matrix responds to extreme gravitational stress by halving its resonance wavelength (λ₂ ≈ λ₁/2). The physics remains finite everywhere; the singularity is an artefact of the effective spacetime description.

---

## Abstract

Black holes pose the sharpest challenge to any theory of quantum gravity. General Relativity predicts singularities — points of infinite curvature — where GR itself breaks down. The Resonance Field Theory (RFT) offers a mechanistically different interpretation: when gravitational stress in the Dynamic Resonance Matrix (DRM) exceeds the mode transition threshold, the DRM transitions from its normal state (Mode 1) to the next harmonic (Mode 2) — with halved resonance wavelength. The event horizon is the interface of this transition, not an absolute boundary.

From this perspective, three central statements follow:

1. **No singularity:** The collapse does not terminate at κ → ∞, but at a stable Mode 2 ground state. Physical quantities remain finite everywhere.

2. **Information preserved:** The infalling material is coherently encoded in the Mode 2 configuration Ψ₂(x,t). Unitarity is maintained; information is not lost, only relocated.

3. **Hawking radiation as thermal tunnelling process:** The thermal emission at the horizon is the continuous boundary process between both modes, consistent with the standard Hawking formula as the leading term.

Quantitative corrections from the mode structure are immeasurably small for stellar-mass black holes, but may become relevant for primordial black holes near the Planck mass.

---

## Table of Contents

1. Paradigm: Black Holes in Standard Physics and RFT
2. The DRM under Extreme Energy Density
3. The Mode Transition Mechanism
4. Event Horizon: Structure and Transition Zone
5. The Interior: Mode 2 Configuration
6. Hawking Radiation as Tunnelling Process
7. The Information Paradox
8. Gravitational Radius and Topological Connection
9. Cosmological Black Holes
10. Limits and Open Questions (mandatory chapter)
11. Summary and Formula Reference

---

## 1. Paradigm: Black Holes in Standard Physics and RFT

### 1.1 The Singularity Problem of GR

General Relativity describes black holes through the Schwarzschild metric:

```
ds² = −(1 − R_S/r)c²dt² + (1 − R_S/r)⁻¹dr² + r²dΩ²

with R_S = 2GM/c²  (Schwarzschild radius)
```

As r → 0, curvature invariants such as R_μνρσ R^μνρσ → ∞. This is not a coordinate singularity but a genuine geometric one: GR breaks down. Hawking's and Penrose's singularity theorems demonstrate that this breakdown is unavoidable under very general conditions — provided classical GR holds.

**The decisive caveat:** GR is an effective field theory. It correctly describes spacetime geometry for energy densities far below the Planck density. Near r = 0, the energy density far exceeds the Planck density — precisely the regime for which GR claims no validity from the outset.

### 1.2 Approaches in Quantum Gravity

Various theories address the singularity problem in different ways:

| Theory | Approach | Status |
|--------|----------|--------|
| String Theory | Strings prevent r→0 | No direct predictions |
| Loop Quantum Gravity | Discrete space structure stops collapse | Mathematically complex |
| Fuzzball Model | Horizon = string ball surface | Speculative |
| **RFT** | **Phase transition Mode 1 → Mode 2** | **Testable predictions** |

### 1.3 The RFT Alternative: Mode Transition instead of Collapse

The Resonance Field Theory interprets black holes as *topological phase states* of the DRM. Not κ → ∞ at r → 0, but a transition into a different, finite resonance mode.

```
Standard picture:  Collapse → κ → ∞ → singularity (physical failure)

RFT picture:       Collapse → mode transition threshold
                           → Mode 2 → stable ground state
```

**Paradigm comparison:**

| Aspect | GR | RFT |
|--------|-----|-----|
| r = 0 | Singularity (physical breakdown) | Stable Mode 2 ground state |
| Event horizon | Mathematically sharp (surface) | Transition zone of width ~L₀ |
| Information | Hawking: lost? | Encoded in Mode 2 configuration |
| Physics at horizon | Infinite gravitational time dilation | Mode transition boundary |

---

## 2. The DRM under Extreme Energy Density

### 2.1 The Master Equation and Its Limits

The entire dynamics of the DRM is governed by the Master Equation (→ v3_001, Ch. 2):

$$\frac{\partial^2 \Psi}{\partial t^2} = c^2 \nabla^2 \Psi \;-\; \gamma\frac{\partial \Psi}{\partial t} \;-\; c^2 \kappa^2 \Psi \;+\; \lambda|\Psi|^2 \Psi \;+\; \eta$$

The parameters take on the following significance under extreme conditions:

**κ — Resonance stiffness:** κ = 1/L₀ ≈ 1.18×10³⁵ m⁻¹. This is not a mass term, but the stiffness of the vacuum resonance matrix against deformation. Under normal conditions κ is constant. At extremely high energy density the question arises: can κ vary locally? ⚠️ OPEN — this remains an open research question; it has not been derived from first principles.

**γ — Damping coefficient:** Determines the arrow of time and particle lifetimes. At extreme compression, γ → γ_eff(r) might become position-dependent. ⚠️ This is a working hypothesis, not yet derived from the Master Equation.

**λ — Nonlinear coupling:** λ ≈ κ²/(8π³). The nonlinear term stabilises soliton structures (particles). At high amplitude density, many solitons compete for resonance matrix nodes.

### 2.2 Why L₀ → 0 Is Not Possible

In GR, matter collapses arbitrarily far. In RFT there is a fundamental limit: the nodes of the DRM cannot approach each other arbitrarily. The minimum node separation is of order L₀ = (π/6)·l_P ≈ 0.524·l_P.

This is not an ad hoc postulated UV cutoff, but follows from the resonance condition of the nested spheres (→ v3_001, Ch. 4–5; v3_007, Ch. 2–3). In geometric terms: L₀ is the sphere-to-cube volume ratio of the vacuum, materialised as a length.

**When matter is compressed to scales < L₀:**

The resonance matrix can no longer stably accommodate this deformation in its normal resonance mode (Mode 1). Two options:

1. The resonance matrix *breaks* — impossible in RFT, since the resonance matrix *is* space itself
2. The resonance matrix *transitions to a different resonance mode* — the mode transition

### 2.3 Critical Energy Density

The mode transition threshold is reached when the local energy density exceeds the characteristic matrix energy per cell volume:

```
ρ_crit ~ ħc / L₀⁴ ~ ħc / (π/6)⁴ · l_P⁴  ○

This corresponds approximately to the Planck density:
ρ_Planck = c⁵/(ħG²) ≈ 5.2×10⁹⁶ kg/m³
```

**⚠️ Status:** This identification is conceptually plausible, not rigorously derived. The exact threshold requires a complete analysis of the nonlinear Master Equation at high amplitude. Confidence: MEDIUM.

---

## 3. The Mode Transition Mechanism

### 3.1 Mode Structure of the Vacuum

**What are Mode 0, Mode 1, and Mode 2?**

The DRM can exist in qualitatively different resonance states — analogous to a trumpet, which can produce different natural tones without changing its length. In RFT, three fundamental modes are distinguished:

**Mode 0 — Primordial Chaos:**
Mode 0 in RFT is **not an empty space** — it is the **absence of space itself**. Unlike the quantum field theory vacuum (which is a state of minimum energy within existing space), Mode 0 precedes space. No DRM exists, no resonance nodes, no physics as we know it. Mode 0 is the *precondition* from which the DRM (Mode 1) emerges — not a resonance mode of space, but the state *before* space.

```
Mode 0:  No space, no DRM, no nodes
         Primordial chaos — precondition of existence
         (Relevant for: cosmogenesis, v3_009)
```

**Mode 1 — Our Universe:**
```
Mode 1:  Our universe
         DRM exists, resonates normally
         Normal physics applies
         Q > Q_crit1 = α⁻¹·π² ≈ 1352.7
```

**Mode 2 — Black Hole Interior:**
```
Mode 2:  Black hole interior
         DRM exists, oscillates at the next harmonic
         Modified physics (c₂, τ₂, κ₂ all altered)
         Q > Q_crit2  [working hypothesis]
```

**Terminological precision:** In RFT, these "modes" are not separate phases of a classical medium, but different solution branches of the Master Equation with different effective parameters. The DRM is the field itself — there is no external medium that chooses between modes.

### 3.2 Connection to the 4-AP Mode Transition (from v3_007)

v3_007, Ch. 4.4, has already identified a mode transition mechanism at the particle level:

```
3 anchor points (triangle):  minimally rigid in 3D  → stable ✓
4 anchor points (tetrahedron): over-determined in 3D → unstable → collapse or mode transition
```

The black hole as a macroscopic phenomenon is the collective manifestation of the same principle: when too many vortex structures are compressed into too small a space, the collective Mode 1 resonance matrix can no longer stably accommodate the gravitational stress. The collective mode transition takes place.

**Important:** In the Mode 2 region, 4-AP configurations might arise — but all derived physics is fundamentally different, because the resonance matrix itself oscillates in a different state (c₂, time progression τ₂, resonance length L₂ all modified). This is not the same as a 4-AP particle in Mode 1 physics.

```
Microphysics (v3_007):
  4 AP in 3D (Mode 1) → over-determination → mode transition of individual vortex

Macrophysics (v3_008):
  Extreme gravitational stress → collective over-determination of resonance matrix
  → Resonance matrix mode transition over volume ~ R_S³
  → In Mode 2 interior: different c, different τ, different resonance length
```

### 3.3 The Wavelength-Halving Mechanism

This is the physical core mechanism of the mode transition in RFT. The formulation comes from Franz Zollner:

> *"The spatial resonance can only absorb a maximum compression. After that, it must create a mode of higher order in order to become resonant again — with a shorter wavelength."*

Analogous to a trumpet that transitions to the next natural tone when the air pressure increases:

```
Mode 1:  Fundamental resonance, wavelength λ₁ = 2·L₀   (fundamental)
Mode 2:  First harmonic, wavelength λ₂ = L₀              (octave)

Ratio: λ₂ = λ₁/2   →   wavelength is halved at the mode transition
```

**Consequences of wavelength halving:**

Since all derived physical quantities depend on the resonance length, all local constants and derived quantities change in the Mode 2 region:

```
Effective resonance matrix node distance: L₂ ≈ L₁/2
Effective resonance stiffness: κ₂ = 1/L₂ ≈ 2κ₁   (stiffer)
Effective propagation speed: c₂ ≠ c₁               ○ direction and magnitude open
Effective time motor: Φ₂ ≠ Φ₁                      ○ time runs differently
```

⚠️ **Status:** The ratio λ₂ = λ₁/2 is the plausible first harmonic; higher harmonics λ₂ = λ₁/n (n > 2) may also occur. The quantitative determination of c₂ from the Master Equation is an open research problem. Confidence for the mechanism principle: HIGH; confidence for numerical values: LOW.

### 3.4 Phase Transition: Not Thermal, but Structural

The mode transition is not a thermal process (no "heating" of the resonance matrix), but a structural phase transition — analogous to ferromagnetism at the Curie temperature:

```
Ferromagnetism:  Individual spins → collective alignment
                 Order parameter: magnetisation M

Mode transition: Individual Mode 1 vortices → collective Mode 2 configuration
                 Order parameter: Ψ₂(x,t) / Ψ₁(x,t) amplitude ratio
```

**Reversibility:** ○ The Mode 1 → Mode 2 transition is in principle reversible (quantum tunnelling). The rate is, however, vanishingly small for macroscopic black holes (→ Ch. 6–7).

### 3.5 Dispersion Curves and Mode Transition Condition

Each mode has a characteristic dispersion relation ω(k). The mode transition occurs where the dispersion curves of both modes intersect:

```
Mode transition condition: ω₁(k*) = ω₂(k*)
```

This defines a critical wave number k*. Since the DRM is discrete, there is a maximum k — the inverse node distance 1/L₀. The mode transition at k* ~ 1/L₀ corresponds to a wavelength ~ L₀.

**⚠️ Quantitative details:** The exact dispersion relations ω_n(k) for Mode 1 and Mode 2 have not yet been derived from the Master Equation. The existence of the mode transition is conceptually grounded; the quantitative theory of the modes requires further analysis.

---

## 4. Event Horizon: Structure and Transition Zone

### 4.1 Schwarzschild Radius from Kinematic Condition

The Schwarzschild radius R_S = 2GM/c² results from a purely kinematic condition: the escape velocity from a mass M at radius r equals the speed of light:

```
v_escape = c  →  (1/2)mc² = GMm/r  →  r = 2GM/c² = R_S
```

This kinematic derivation is independent of the internal resonance matrix structure and holds unchanged in RFT. R_S is the scale at which the gravitational field is strong enough that Mode 1 signals can no longer escape.

**RFT interpretation:** The mode transition does not occur exactly at r = R_S, but in a transition zone of width δr ~ L₀ around R_S. This is a qualitative prediction that deviates from GR.

### 4.2 Connection to G·m Topology (from v3_003)

In RFT, G·m is not a product of independent quantities, but a topological property of the resonance matrix (→ v3_003, Ch. 1):

```
μ = G·m = c²·L₀·f(topology)    [m³/s²]
```

For a macroscopic black hole, μ is the collective topological stress strength of all contained vortex structures. The Schwarzschild radius follows from this:

```
R_S = 2μ/c² = 2G·m/c²
```

This is consistent with the canonical relation (from DC v10.7):

```
G·m/c² = L²/(4π·Φ)     [dimensionally consistent ✓]

with L = √(4π·Φ)·l_P ≈ 0.428·l_P and Φ = 2α/(1+α²) ≈ 0.01459
```

**⚠️ Note:** This formula is a consistency relation within the v3 formalism, not an independent derivation of the Schwarzschild radius. R_S = 2GM/c² remains the operative formula.

### 4.3 Transition Zone instead of Sharp Boundary

**GR picture:** The event horizon is a mathematically sharp surface at r = R_S. It has no physical thickness.

**RFT picture:** Since the resonance matrix is discrete (node distance L₀) and the mode transition is a continuous process, there is a transition zone of finite width:

```
δr ~ L₀ = (π/6)·l_P ≈ 0.524·l_P ≈ 8.5×10⁻³⁶ m
```

In this transition zone, the field Ψ describes neither pure Mode 1 nor pure Mode 2 configuration, but a superposition:

```
Ψ(r) = f₁(r−R_S) · Ψ₁(r) + f₂(r−R_S) · Ψ₂(r)

with transition functions f₁, f₂:
  for r >> R_S: f₁→1, f₂→0
  for r << R_S: f₁→0, f₂→1
```

**Experimental consequence:** For stellar-mass black holes, δr ~ 10⁻³⁶ m — far below any measurable scale. The transition zone is not directly detectable. For primordial black holes near the Planck mass, δr/R_S ~ 1, and the transition zone would dominate the entire structure.

---

## 5. The Interior: Mode 2 Configuration

### 5.1 No Singularity at r = 0

The fundamental result of the RFT description: the Master Equation has for r < R_S a finite solution Ψ₂(r) with well-defined boundary conditions:

```
Boundary condition at r → 0:  dΨ₂/dr|_{r=0} = 0  (spherical symmetry)
                               Ψ₂(0) = Ψ₂,₀ ≠ ∞    (finite ground state)
```

The physics at r = 0 is not "infinite", but corresponds to the Mode 2 vacuum ground state. This conceptually resolves the singularity problem of GR.

### 5.2 Time in the Mode 2 Region — RFT-Consistent Description

In RFT, time does not emerge as a dimension, but from the Φ time motor: the phase asymmetry of the resonance field (→ v3_006, Ch. 3):

```
Φ = 2α/(1+α²) ≈ 0.01459    [canonical, Mode 1]
```

In the Mode 2 region, the resonance matrix oscillates at a different harmonic (λ₂ ≈ λ₁/2). This changes the effective resonance geometry, and the time motor takes on a different effective value Φ₂:

```
Mode 1: Φ₁ = 2α/(1+α²) ≈ 0.01459   → normal time progression
Mode 2: Φ₂ ≠ Φ₁                     ○ time progression modified
```

**Physical consequence:** An observer in the Mode 2 region would experience a different local time rate than an external Mode 1 observer. This is not a coordinate singularity in the GR sense, but a genuine physical effect of the modified resonance matrix dynamics.

**External observation:** For a distant Mode 1 observer, time near the event horizon appears strongly slowed — this corresponds to the well-known gravitational redshift effect, which RFT derives from the modified local resonance frequency of the field.

⚠️ **Status:** The exact value of Φ₂ and its dependence on the mass M of the black hole has not yet been derived from the Master Equation. Confidence for the mechanism principle: MEDIUM.

### 5.3 Mode 2 Ground State and Mass

The Mode 2 configuration has an effective ground state energy Ψ₂,₀ that depends on the total mass M of the black hole. The core size (characteristic radius of the Mode 2 ground state) scales with M:

```
r_core ~ L₀ · √(M/M_Planck)     ○ working hypothesis
```

This means: more massive black holes have a *larger* stable core, not a smaller one. The interior does not collapse into nothing, but into an increasingly voluminous Mode 2 configuration.

---

## 6. Hawking Radiation as Tunnelling Process

### 6.1 Standard Hawking Mechanism

Hawking radiation arises from quantum field theory in curved spacetime. Virtual particle-pair creation near the horizon can become real when one particle falls into the black hole and the other escapes. The black hole appears as a thermal emitter with:

```
T_Hawking = ħc³ / (8π G M k_B)    [canonical]

Numerically for M = M_⊙:
T_H ≈ 6.2×10⁻⁸ K   (completely unobservable)
```

The standard derivation is valid in RFT as an effective description. This expression is independent of the Master Equation and serves as a solid starting point.

### 6.2 RFT Reinterpretation: Boundary Tunnelling

In RFT, Hawking radiation is a **continuous tunnelling process** at the mode transition boundary:

**Mechanism:**

1. **Fluctuations in Mode 2:** The field configuration Ψ₂(r,t) fluctuates quantum-mechanically around its ground state Ψ₂,₀.

2. **Tunnelling to the Mode 1 region:** At r ≈ R_S, Mode 2 fluctuations can tunnel through the transition zone and convert into Mode 1 quanta (real particles).

3. **Thermal spectrum:** The tunnelling probability as a function of energy reproduces the Bose-Einstein spectrum with T = T_Hawking.

4. **Energy balance:** The black hole loses energy through this process → evaporation.

```
Tunnelling amplitude: A ~ exp(−S_action/ħ)

For ω < ω_Hawking: transition thermally suppressed
For ω > ω_Hawking: transition possible → Hawking photon emitted
```

### 6.3 Mode Transition Corrections to the Hawking Temperature

The discrete mode structure can in principle supply corrections to the standard Hawking formula:

```
T_RFT = T_Hawking × (1 + δ_mode)
```

**Order of magnitude of the correction:**

The correction δ_mode scales with the ratio (L₀/R_S)²:

```
δ_mode ~ (L₀/R_S)²  ~  (l_P/R_S)²    ○ qualitative

For M = M_⊙:
R_S ≈ 3 km = 3×10³ m,   l_P ≈ 1.6×10⁻³⁵ m

δ_mode ~ (1.6×10⁻³⁵ / 3×10³)² ~ 3×10⁻⁷⁷   (completely negligible)
```

**For primordial black holes M ~ M_Planck:**

```
R_S ~ 2G M_Planck / c² ~ 2 l_P

δ_mode ~ (l_P / 2l_P)² = 0.25 → ~25% correction!
```

Mode transition corrections to the Hawking temperature are therefore relevant *only* for black holes with M ~ M_Planck. For every astrophysically known black hole, the corrections are immeasurable.

**⚠️ Caveat:** The exact expression for δ_mode depends on the Mode 2 parameters (c₂, κ₂), which have not yet been derived from the Master Equation. The qualitative scaling above is reliable; numerical values require further analysis. Confidence for scaling: MEDIUM.

---

## 7. The Information Paradox

### 7.1 The Classical Paradox

Hawking's original argument (1975): black holes evaporate into purely thermal radiation. Thermal radiation carries no information about the initial state. Consequently, information is lost.

This contradicts quantum mechanics fundamentally: unitary time evolution requires information conservation. Pure initial state → pure final state, never mixed state.

### 7.2 RFT Resolution: Information Encoded in Mode 2

The Resonance Field Theory resolves the paradox through the mechanistic description of the black hole interior:

**Core argument:**

Matter crossing the event horizon undergoes the mode transition Mode 1 → Mode 2. In Mode 2, it is determined as a field configuration Ψ₂(x,t) — through the Master Equation, which is fully deterministic. No information is lost; it is merely transformed into a state *inaccessible* to external Mode 1 observers.

```
System state:       |S_total⟩ = |Ψ₁⟩_outside ⊗ |Ψ₂⟩_inside

Unitarity:          |S_total⟩ evolves unitarily under the Master Equation
Apparent loss:      Partial trace over Ψ₂ → mixed state for outside observer

→ No fundamental violation of unitarity ✓
```

### 7.3 Return via Tunnelling

Hawking radiation is not an information-free process in RFT: since the fluctuations of Ψ₂ carry the encoded information, the tunnelled Mode 1 field (the emitted radiation) *in principle* carries traces of this information.

**Practical limitation:**

The tunnelling rate for a complete information bit is:

```
Γ_bit ~ exp(−S_BH/k_B)

with S_BH = k_B · A_horizon / (4 L₀² × (6/π)²)   (Bekenstein-Hawking entropy)
```

For a stellar-mass black hole (M = M_⊙):

```
A = 4π R_S² ≈ 1.1×10⁸ m²
S_BH/k_B ~ A/L₀² ~ 10⁸ / (10⁻³⁵)² ~ 10⁷⁸

Γ_bit ~ exp(−10⁷⁸)  →  complete information return
                        on timescale ~ τ_P × exp(10⁷⁸) ≈ 10¹⁰⁷⁷ s
```

This timescale is astronomical. Information returns *in principle* — but only after a time unimaginably longer than the age of the universe. For practical purposes, the system behaves like information loss. Fundamental unitarity is maintained.

### 7.4 Page Curve in RFT

The Page curve — entropy of Hawking radiation as a function of time — takes the following form in RFT:

```
t < t_Page:  Mode 2 → Mode 1 tunnelling inefficient
             Radiation ≈ thermal, S_radiation rising

t > t_Page:  Mode 2 destabilised (BH shrinking)
             Information increasingly tunnels back
             S_radiation falling (Page curve)
```

This qualitatively reproduces the expected unitary behaviour. The Page time t_Page ≈ M²/M_Planck² · t_Planck for a black hole of mass M.

---

## 8. Gravitational Radius and Topological Connection

### 8.1 Black Holes as Topological Objects

In RFT, particles are topological vortex structures (winding number n), and their gravitational effect is a topological property of the resonance matrix (→ v3_003). Black holes are macroscopic topological collectives: many winding numbers, compressed into the smallest space into a single Mode 2 configuration.

**Analogy to particle physics:**

```
Single quark:    Winding number n = 1/3 (colour charge), topologically stable
Proton:          n = 2 (SU(2) doubling), 3 quarks, 9 anchor points
Black hole:      N >> 1 windings, collective Mode 2 state
```

Gravitation follows in all cases from the same spin delay mechanism (→ v3_003), but scales with the total number of windings.

### 8.2 Mass as Gravitational Trailing Vortex Strength

The SI kilogram is not a law of nature, but a label for the gravitational **trailing vortex** strength (→ v3_003, Ch. 1.2):

```
μ = G·m = c²·L₀·f(topology)    [physically measurable in m³/s²]
```

For a black hole of "mass" M (in SI units):

```
R_S = 2μ/c²    [Schwarzschild radius as topological property]
```

The black hole is the limiting case in which the topological trailing vortex strength grows large enough that even light (n = 0, Mode 1 signals) can no longer escape.

### 8.3 G_hadron and Black Holes

In v3_003, two gravitational mechanisms were distinguished: G_elementary (quark misalignment) and G_hadron = 4π·G_elementary (colour charge alignment). For macroscopic black holes, G_hadron applies in practice, since all contained hadrons each gravitate via the 4π mechanism.

This is consistent with the observed G = G_hadron in all macroscopic measurements.

---

## 9. Cosmological Black Holes

### 9.1 Supermassive Black Holes

Supermassive black holes (SMBH, M ~ 10⁶–10¹⁰ M_⊙) at the centres of galaxies are, in RFT, Mode 2 regions of macroscopic extent. Their Schwarzschild radius is:

```
R_S(10⁹ M_⊙) = 2G × (10⁹ × 2×10³⁰) / c² ≈ 3×10¹² m ≈ 20 AU
```

For these objects, all corrections from the mode structure are completely negligible — the Mode 2 zone is macroscopically large, and the transition zone δr ~ L₀ is infinitesimal in comparison.

### 9.2 Connection to Q Gradients (v3_006)

In v3_006, the effect of Q gradients on cosmological scales was discussed (→ v3_006, Ch. 5; v3_010). Black holes as extreme Q concentrations might generate local Q gradients that exert additional gravitational effects — beyond the direct G·m action:

```
a_total = −GM/r² − (c²/Q)·(dQ/dr)    ○ [from v3_010]
```

For ordinary black holes, this Q gradient effect is negligible compared to direct gravitation. During the formation of SMBHs in the early universe (→ v3_009), it might be relevant.

**⚠️ The Q discrepancy (Q_cosm ~ 10³ vs. Q_res ~ 10⁷–10⁸) documented in the Domain Center remains unresolved for this document.** Confidence: LOW.

### 9.3 Early Black Holes and JWST Observations

The James Webb Space Telescope has discovered excessively massive black holes at z > 10, which are difficult to explain in standard cosmology through accumulated black hole growth.

In RFT, cold condensation (→ v3_009) offers an alternative formation mechanism: if the early universe rapidly condenses, primordial black holes could form directly from Mode 2 regions, without passing through the normal stellar collapse.

⚠️ This is a qualitative speculation; a quantitative prediction requires v3_009.

---

## 10. Limits and Open Questions (Mandatory Chapter)

### 10.1 Known Limits — Inherited from the v3 Series

**ħ circularity — structurally resolved, formally still open:**
The relation G·ħ = (36/π²)·c³·L₀² is an algebraic identity. The deeper question — whether G can be derived without ħ as input — has been structurally advanced: L₀ = 1/κ is now defined ħ-free (DC v10.7, 25.03.2026 ✓ HIGH). The full derivation chain from κ to G without ħ remains ongoing work.

```
🚩 Status: structurally advanced; formal closure in progress (DC v10.7)
```

**Lorentz invariance:**
Whether the discrete DRM possesses complete Lorentz invariance in the continuum limit has not yet been formally proved (→ v3_007, Ch. 8). At the event horizon, where the resonance matrix calibration reaches its limits, this question is particularly relevant.

```
⚠️ Status: formally open
```

### 10.2 Limits Specific to v3_008

**Mode 2 parameters unknown:**
The dispersion relation ω₂(k), the propagation speed c₂, and the stiffness parameter κ₂ in the Mode 2 state have not been derived from the Master Equation. All quantitative statements about Hawking corrections δ_mode remain conceptually plausible but numerically undetermined.

```
⚠️ Status: working hypothesis. DeepSeek verification recommended once approach formalised.
```

**4-AP → collective mode transition:**
The connection between the 4-AP mechanism from v3_007 and the macroscopic black hole mode transition is a structural analogy, not a formal derivation.

```
⚠️ Status: conceptually consistent, not formally derived. Confidence: MEDIUM.
```

**Mode 2 → Mode 1 back-transition:**
RFT postulates that Mode 2 → Mode 1 is possible through quantum tunnelling. The tunnelling path through the Mode 2 → Mode 1 boundary has not been explicitly calculated.

```
⚠️ Status: conceptually consistent, not formally derived. Confidence: MEDIUM.
```

**Rotating and charged black holes:**
This document treats only non-rotating (Schwarzschild) black holes. Extension to rotating (Kerr) and charged (Reissner-Nordström) black holes requires separate analysis and is not claimed here.

```
⏭️ Status: next documents
```

**Formal connection to QFT in curved spacetime:**
The Hawking formula originates from quantum field theory on a Schwarzschild background. The complete formal derivation of Hawking radiation from the RFT Master Equation — rather than by adopting the standard result — is still missing.

```
⚠️ Status: open. Adoption of the standard result as a starting point is legitimate
   and explicitly marked as such.
```

### 10.3 Experimental Tests

| Prediction | Deviation from GR | Instrument | Time horizon |
|------------|-------------------|------------|--------------|
| Horizon transition zone δr ~ L₀ | ~10⁻³⁵ m (unmeasurable) | None known | — |
| GW echoes after merger | Δt ~ ms (model-dependent) | LIGO/ET | 2025+ |
| Hawking correction δ_mode | ~10⁻⁷⁷ for M_⊙ | Not measurable | — |
| Primordial BH T_H deviation | ~25% at M ~ M_P | Fermi/CTA | Future |
| SMBH formation z>10 | Qualitatively different | JWST | Available |

**⚠️ Honest assessment:** The specific RFT corrections for black holes are not measurable for any known astrophysical object. The conceptual contributions (singularity resolution, information preservation) are important, but not directly testable with current technology.

---

## 11. Summary and Formula Reference

### 11.1 Central Statements

**1. No singularity (well-grounded):**
```
✓ Mode 1 resonance matrix transitions at threshold to Mode 2
✓ Mode 2 stabilises at finite ground state Ψ₂,₀
✓ Physics at r = 0 finite
✓ Conceptual basis: Master Equation + v3_007 4-AP argument
```

**2. Information preserved (well-grounded):**
```
✓ Mode 2 configuration deterministic under Master Equation
✓ Unitarity of total system (Mode 1 + Mode 2) maintained
✓ Apparent loss = partial trace, not fundamental non-unitarity
⚠️ Formal quantum mechanics of mode superposition not yet elaborated
```

**3. Hawking radiation as tunnelling process (conceptually consistent):**
```
✓ Standard formula T_H = ħc³/(8πGMk_B) confirmed as leading term
○ RFT corrections δ_mode ~ (L₀/R_S)² — conceptually plausible
⚠️ Quantitative Mode 2 parameters still unknown
```

**4. Connection to v3 series (rigorous):**
```
✓ G·m as topological primary quantity (v3_003)
✓ 4-AP mode transition as micro-basis (v3_007)
✓ Time dilatation at horizon = Φ time motor effect (v3_006) ○
```

### 11.2 Formula Reference

```
SCHWARZSCHILD RADIUS (canonical):
R_S = 2GM/c² = 2μ/c²    with μ = G·m [topological, v3_003]

HAWKING TEMPERATURE (standard, adopted):
T_Hawking = ħc³ / (8π G M k_B)

HAWKING CORRECTION (RFT, qualitative):
T_RFT = T_Hawking × (1 + δ_mode)
δ_mode ~ (L₀/R_S)²    ○ [Mode 2 parameters unknown]

BEKENSTEIN-HAWKING ENTROPY:
S_BH = k_B · A_horizon / (4 L₀² × (6/π)²)
     = k_B · π R_S² / L₀² · (π²/36)    ○ [in RFT notation]

TRANSITION ZONE:
δr ~ L₀ = (π/6)·l_P ≈ 0.524·l_P ≈ 8.5×10⁻³⁶ m    ✓ geometric

MODE TRANSITION CONDITION:
ω₁(k*) = ω₂(k*)    ⚠️ [ω₂(k) still unknown]

INFORMATION TUNNELLING RATE (qualitative):
Γ_bit ~ exp(−S_BH/k_B)    ○ [vanishingly small for M >> M_Planck]
```

### 11.3 Canonical Parameters (DC v10.7)

```
c               Fundamental input only
L₀ = (π/6)·l_P = 1/κ ≈ 0.524·l_P     [ħ-free primary definition ✓]
κ               Primary quantity (resonance stiffness)
α⁻¹ = 4π³+π²+π = 137.036 304   [2.22 ppm — NEVER 0.67 ppm!]
Φ   = 2α/(1+α²) ≈ 0.01459        [canonical ✓]
G·m/c² = L²/(4π·Φ)              [consistency relation]
Q_crit1 = α⁻¹·π² ≈ 1352.7       [✓ HIGH, 25.03.2026]
Photon: 2 AP, stable             [propagating wave, v3_012 canonical]
Electron: 1 AP                   [✓ HIGH, Franz 26.03.2026]
Mode 0: no space, no DRM         [primordial chaos, precondition]
Mode 2: λ₂ ≈ λ₁/2               [○ Franz concept, 28.02.2026]
```

---

## Dependencies and Follow-up Documents

**Prerequisites:**
- RFT v3 Mathematical Foundations (v3_001)
- RFT v3 Gravitation and Spin Delay (v3_003)
- RFT v3 Time Emergence (v3_006)
- RFT v3 Space Topology & 3D Emergence (v3_007)

**Direct follow-up documents:**
- RFT v3 Cosmogenesis and Cold Condensation (v3_009) — primordial BHs, JWST
- RFT v3 Dark Matter and Dark Energy (v3_010) — Q gradients, cosmological BHs

---

*RFT_v3_008 — Black Holes as Mode Transition Phenomena*
*Translation Draft | 26 March 2026 | Translation instance T8*
*Source: DE Draft v1.1 | Glossary: RFT_v3_Glossar_EN.md (v1.0 + Patch v10.8)*
*Key result: Event horizon = mode transition boundary; Mode 0 ≠ vacuum (absence of space)*
