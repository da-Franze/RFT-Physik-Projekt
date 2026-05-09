# RFT_v3_Glossar_EN — Resonance Field Theory: Terminology Reference
## Version: 1.0 | Date: 24.03.2026 | Instance: K5
## Authorized: Franz Zollner | Protocol: Multi-Instance v6.1

---

> **Methodological note:**
> All concepts originate with Franz Zollner.
> Written formalization by AI instances — all entries verified against the v3 document series.
> Primary source cited for each entry.
>
> **Truth hierarchy:**
> Franz direct statement → DC v10.4 → v3-Final → v2-series → AI content
>
> **Confidence markers:**
> ✓ HIGH — rigorously derived or confirmed by Franz
> ○ MEDIUM — conceptually consistent, formally still open
> ⚠️ LOW / SPECULATIVE — working hypothesis
> 🚩 OPEN — active research problem

---

## Reader's Guide (for physicists without prior RFT knowledge)

The Resonance Field Theory (RFT) proposes that space, time, and matter emerge from a single dynamic resonance medium — the Dynamic Resonance Matrix (DRM). This glossary provides precise definitions of RFT-specific terminology, with explicit comparisons to standard physics where the concepts diverge.

**Key terminological differences from standard physics:**

| Standard Physics | RFT | Status |
|-----------------|-----|--------|
| Vacuum = empty space | DRM = active resonance medium | ✓ HIGH |
| Mass = fundamental property (Higgs) | Mass = emergent label for local κ-density | ✓ HIGH |
| Particle = point-like | Particle = topological vortex in DRM | ✓ HIGH |
| Time = fundamental dimension | Time = emergent beat frequency of DRM modes | ✓ HIGH |
| Fine structure constant α = empirical | α = pure π-geometry (no free parameters) | ✓ HIGH |
| Equivalence principle = postulate | Equivalence principle = geometric consequence | ✓ HIGH |
| Gravitational waves = spacetime ripples | GW = longitudinal mode of DRM | ✓ HIGH |

---

## Critical Warnings (read before use)

```
❌ "space lattice" / "lattice"    → WRONG (implies rigid crystal structure)
                                     CORRECT: "resonance matrix" or "DRM"
❌ "resonance-space-matrix"       → explicitly rejected by Franz Zollner
❌ c₀                             → outdated notation; correct: c
❌ ħ as fundamental               → ħ is an algebraic identity in v3 (not independently derived)
❌ AP = geometric point           → AP = dimensional coupling! (Franz, 15.03.2026)
❌ 0.67 ppm residual for α        → WRONG; correct: 2.22 ppm
❌ 4:1 spin ratio (generalized)   → context-dependent; see entry "Cold Condensation"
❌ GR language in RFT             → metric, geodesics, tensor language — avoid!
```

---

## A

### Anchor Point (AP) — Ankerpunkt
**DE:** Ankerpunkt (AP)
**Confidence:** ✓ HIGH (core definition); ○ MEDIUM (dimensional coupling interpretation)
**Primary source:** KORREKTUR_RFT_005_Ankerpunkte.md; Franz, 15.03.2026

An anchor point is the **coupling site of a vortex to the resonance matrix** — the interface through which vortex structures interact with each other. An AP is not necessarily a geometric point; it can be a point, surface, line, or any other geometric unit.

**AP as dimensional coupling (○ MEDIUM, Franz 15.03.2026):**
In a Lorentz field without preferred directions, each AP couples to one dimensional degree of freedom of the DRM: n AP = coupling to n dimensions.

Note: This is **not** analogous to a classical field node or lattice site. The AP represents a topological coupling, not a spatial location.

**Canonical AP table:**

| Particle | AP | Spin | Confidence |
|----------|----|------|------------|
| Electron e⁻ | 1 | ½ | ✓ HIGH |
| Positron e⁺ | 1 | ½ | ✓ HIGH |
| Photon γ | 2 | 1 | ✓ HIGH (Franz, 11.03.2026) |
| Quark (d/u/s/...) | 3 | ½ | ✓ HIGH |
| Proton | 9 | ½ | ✓ HIGH (3 quarks × 3 AP) |
| Delta baryon | 9 | 3/2 | ✓ HIGH |
| Neutrino ν | 0 | ½ | ⚠️ working hypothesis |

**Key consequence:** Leptons (1 AP) couple to only 1 dimension → no color charge. This is a geometric consequence, not a separate postulate.

---

### Anchor Point Stability Hierarchy
**DE:** Ankerpunkt-Hierarchie
**Confidence:** ✓ HIGH
**Primary source:** KORREKTUR_RFT_005_Ankerpunkte.md; v3_011 Final v1.0

Stability of resonance structures ordered by AP count:
- 1 AP: unstable (cannot exist freely)
- 2 AP: short-lived (mesons, transient states; photon stable while propagating)
- 3 AP: stable (quarks — couple to all 3 spatial dimensions → confinement)
- ≥ 3 AP: macroscopic stability

**Resonance condition:** n_AP ≥ n_dim = 3 (in 3D) required for stable isolated structures.

---

## B

### Beat Frequency (Resonance Beat) — Schwebung
**DE:** Schwebung
**Confidence:** ✓ HIGH
**Primary source:** v3_006, Final v1.1

The beat frequency between two fundamental DRM modes ω₁ and ω₂ is the **time motor** of RFT:

```
Δω = ω₁ − ω₂               (beat frequency)
τ_beat = 2π / Δω             (beat period — the "heartbeat" of time)
t̂ = (2π/Δω) · N̂             (time operator)
```

⚠️ Time itself is **continuous** — only the beat mechanism (the motor) is discrete. Analogy: a heartbeat is discrete; time between beats flows smoothly.

**Directionality:** Φ ≠ 0 → beat has a direction → **arrow of time**.

Note: Use "beat frequency" (not "oscillation" or "vibration") for *Schwebung* in translations.

---

## C

### Cold Condensation — Kalte Kondensation
**DE:** Kalte Kondensation
**Confidence:** ○ MEDIUM (core mechanism); ⚠️ LOW (quantitative details)
**Primary source:** v3_009, Final v1.0

Formation of ordered matter structures from the RFT primordial field without a thermodynamic cooling process. "Cold" does not refer to low temperature but to the absence of an external cooling agent: order emerges through **resonance quality** (Q-factor), not heat dissipation.

Key mechanism: When Q > Q_crit1 ~ 10³ (hypothesis), resonances spontaneously condense into stable vortex structures. Antimatter is **complementarily bound** in this process (not "annihilated" or "absent").

**Two canonical ratios — do not confuse (Franz, 24.03.2026):**
```
3:1 = Matrix generation ratio:
      Spin −1 (antimatter) : Spin +1/3 (quark)
      → ratio of spin contributions during matrix constitution ✓ HIGH

4:1 = Matter condensation ratio:
      Separate process! Ratio within the condensation step itself
      ○ MEDIUM (Franz, 24.03.2026)
```
⚠️ "4:1" is NOT universally wrong — it describes a different process than 3:1. The historical error was conflating both processes.

---

## D

### Dispersion Relation — Dispersionsrelation
**DE:** Dispersionsrelation
**Confidence:** ✓ HIGH
**Primary source:** v3_004, Kap. 2.2; v3_001, Kap. 2

Fundamental relation between angular frequency ω and wave vector k in the DRM, derived directly from the linearized Master Equation:

```
ω² = c²(k² + κ²)
```

Multiplied by ħ²: E² = (pc)² + (m_eff c²)²
(Einstein energy-momentum relation emerges as a limiting case — it is not postulated.)

Physical significance: κ ≠ 0 → resonance structure has a natural frequency → effective mass. κ = 0 → photon-like (massless propagation).

---

### DRM — Dynamic Resonance Matrix
**DE:** Dynamische Resonanz-Raummatrix (DRM)
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 1.1

The fundamental carrier medium of the RFT. DRM is a correct abbreviation, not an artifact. Preferred usage in prose: "resonance matrix"; in technical contexts: "DRM".

→ See: **Resonance Matrix**

---

## F

### Fine Structure Constant α — Feinstrukturkonstante
**DE:** Feinstrukturkonstante
**Confidence:** ✓ HIGH
**Primary source:** v3_002; v3_001, Kap. 4; v3_005

In RFT, α follows from pure π-geometry of the DRM — no free parameters:

```
α⁻¹ = 4π³ + π² + π = 137.036 304...
```

Residual vs. CODATA 2018: **2.22 ppm** (⚠️ NEVER use 0.67 ppm — known AI artifact).

| Term | Value | Geometric meaning |
|------|-------|-------------------|
| 4π³ | 124.025... | 3D volume (spherical k-space; 4 spheres = tetrahedron) |
| π² | 9.870... | 2D surface (spherical harmonics) |
| π | 3.142... | 1D length (spin axis) |

Physical meaning: α measures the critical mode count N_crit — how many degrees of freedom a spherical resonance must occupy on the cubic DRM to be stable. This follows from the triangulation principle (→ **Triangulation Principle**).

The 2.22 ppm residual is an open question (missing correction term? time-arrow signature? structural feature?).

---

### Flux Factor Φ — Flussfaktor
**DE:** Flussfaktor
**Formula:** Φ = 2α/(1+α²) ≈ 0.014 596
**Confidence:** ✓ HIGH (canonical)
**Primary source:** v3_002; v3_006

Φ describes the relative phase asymmetry between the two fundamental DRM modes. Φ ≠ 0 drives the arrow of time via directed beat frequency (→ **Beat Frequency**, **Time Motor**).

Applications: G·m/c² = L²/(4π·Φ) (gravitational formula, dimensionally correct); Φ_total = Φ_mat + Φ_fil (cosmology, v3_010).

**Critical symbol disambiguation:**
- ε = geometric angular deviation of DRM axes from 90° (qualitative; value ≈ Φ via orbital model ○ HIGH)
- δ ≈ 2α ≈ 0.0146 rad (temporal phase asymmetry from v3_001)
- Φ = 2α/(1+α²) ≈ 0.01459 (canonical quantitative expression)
→ These three symbols must NEVER be conflated.

---

## G

### Gravitation (RFT)
**DE:** Gravitation
**Confidence:** ✓ HIGH
**Primary source:** v3_003

In RFT, gravitation is not a fundamental axiom but an emergent property of the DRM:

- **G·m** is a topological quantity [m³/s²] — not the product of two independent quantities.
- **[kg]** is not a law of nature but a label for gravitational drag-vortex strength.
- **Mechanism:** Every massive vortex with spin generates a phase lag τ_lag → longitudinal stress in the DRM → gravitation.

**Gravitation = longitudinal compression mode** of the DRM (distinct from electromagnetism = torsional mode).

Two G mechanisms:
- G_elementary: quark mismatch (local stress)
- G_hadron = 4π · G_elementary: color charge alignment (spherical coupling)

Note: Gravitation in RFT is conceptually similar to but mechanically distinct from GR's spacetime curvature. GR remains an accurate effective field theory; RFT aims to provide its mechanical substrate.

---

## I

### Inside-View Principle — Innensicht-Prinzip
**DE:** Innensicht-Prinzip
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 1.1

The resonance field is not a field *in* space — it *is* space itself. All observers are part of the field. There is no "outside" and no absolute reference frame. Special relativity emerges as a consequence: all observers within the field measure the same propagation speed c.

This is not an aether theory. A classical aether is a medium *in* space with an absolute rest frame. In RFT, the dynamic resonance field *is* space — there is no exterior.

Consequence: statements about the state *before* the resonance matrix (proto-state) are in principle impossible from the inside (→ Domain L, open speculation).

---

## L

### L₀ — Fundamental Matrix Length
**DE:** Fundamentale Gitterlänge
**Formula:** L₀ = (π/6)·l_P ≈ 0.5236·l_P
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 5; v3_005, Kap. 1.2

The fundamental length scale of the DRM, derived from the **sphere-in-cube volume ratio**:

```
V(sphere, r) / V(cube, 2r) = (4/3)πr³ / 8r³ = π/6
→ L₀ = (π/6)·l_P
```

π/6 is the efficiency with which a spherical resonance fills the cubic matrix volume. This is not an approximation or a fit parameter.

🚩 **ħ circularity (highest priority open problem):**
L₀ = (π/6)·l_P contains l_P = √(ħG/c³) → contains ħ → the G·ħ identity is algebraic, not an independent derivation. Determining L₀ without ħ as input is the core open problem of the entire project.

---

## M

### Master Equation — Master-Gleichung
**DE:** Master-Gleichung
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 2

The fundamental field equation of the entire RFT. All physics of the RFT emerges from it:

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

| Term | Symbol | Meaning |
|------|--------|---------|
| Wave propagation | c²∇²Ψ | Propagation at light speed |
| Damping / time arrow | −γ∂Ψ/∂t | Irreversibility, Q-factor, arrow of time |
| Resonance rigidity | −c²κ²Ψ | Primary quantity; generates effective mass |
| Nonlinearity | +λ\|Ψ\|²Ψ | Stabilizes solitons (particles) |
| Self-interaction | η | Vacuum fluctuations (η=0 in ground state) |

Ψ is not a field *in* space — it is the field whose dynamic ground state *constitutes* space itself.

---

### Mode Transition — Modensprung
**DE:** Modensprung
**Confidence:** ✓ HIGH (concept); ○ MEDIUM (quantitative thresholds)
**Primary source:** v3_008, Draft v1.0

Discrete transition between different resonance states of the DRM when a critical node density is exceeded. Unlike continuous transitions in GR:

```
Mode 0:  Q ≈ 1        — primordial chaos / no space (NOT "vacuum"!)
Mode 1:  Q > Q_crit1  — ordered resonance matrix (normal space)
Mode 2:  Q ≫ Q_crit2  — black hole (λ₂ ≈ λ₁/2, different time rate)
```

⚠️ Mode 0 is NOT a vacuum — it is the state before DRM constitution. Correct terms: "primordial chaos" or "no space".

Different modes have different Φ values → different time rates (Φ₂ ≠ Φ₁).

---

## N

### Neutrino (RFT Interpretation)
**DE:** Neutrino (RFT-Interpretation)
**Confidence:** ○ MEDIUM (longitudinal wave hypothesis, Franz 15.03.2026)
**Primary source:** DC v10.4, Domain G + I; v3_014, Final v1.0

In the current RFT working hypothesis, the neutrino is not a vortex structure with anchor points but a **longitudinal wave of the resonance matrix** (0 AP):

```
Neutrino: longitudinal wave, κ > 0 → m_ν tiny (≠ 0) ✓
Grav. wave: longitudinal wave, κ ≈ 0 → m ≈ 0
```

Both are longitudinal modes of the same carrier medium; the difference is the "inner density" κ of the wave:
- Gravitational waves ~ radio waves (low inner density, κ ≈ 0)
- Neutrinos ~ X-rays (high inner density, κ > 0)

**RFT prediction:** Both propagate at c in vacuum — consistent with SN 1987A simultaneous arrival of neutrinos and (implied) gravitational waves ○ MEDIUM.

**Open tension:** 0-AP description (→ massless) conflicts with observed neutrino oscillations (→ m_ν > 0). Candidate resolution: small coupling, not exactly 0-AP. 🚩 Open.

---

## P

### Photon (RFT Description)
**DE:** Photon (RFT)
**Confidence:** ✓ HIGH (Franz, 11.03.2026)
**Primary source:** v3_012, Final v1.3.1; DC v10.4

**Status DECIDED (Franz, 11.03.2026):**

The photon is a stable propagating wave consisting of:
- **e⁻ (1 AP) + e⁺ (1 AP) = 2 AP total**
- Spin 1 (triplet configuration: ↑↑)
- n = 0 in the mode classification (complementary description, no contradiction)

The photon is **not short-lived** — it is stable as long as it propagates. Drag-vortices of e⁻ and e⁺ cancel at rest → gravitationally neutral. A small residual ~2α remains during propagation (below current detectability).

Comparison: The photon as "2 AP wave pair" and the photon as "n=0 field mode" are two complementary descriptions of the same object — analogous to wave-particle complementarity, not a contradiction.

---

### Pilot Field / Guidance Field — Führungsfeld
**DE:** Führungsfeld
**Confidence:** ✓ HIGH (concept); ○ MEDIUM (formal details)
**Primary source:** v3_011, Teil 3

In the RFT interpretation of quantum mechanics, every physical configuration consists of two components:

1. **Vortex core:** the topological vortex structure (the actual "particle")
2. **Pilot field (Ψ_field):** the extended resonance field that deterministically guides the core

The pilot field is physically real — it is not a mathematical auxiliary construct as in Bohm's pilot wave interpretation. It emerges as a solution of the Master Equation. The vortex core follows the gradient of the effective potential:

```
V_eff = −½c²·α_K·|Ψ_field|²
F = −∇V_eff   (deterministic!)
```

**Distinction from Bohm:** Bohm's guiding wave is defined mathematically as Q = −ħ²∇²R/(2mR). The RFT pilot field is the physical resonance matrix modulation itself — a real physical entity, not a mathematical construct.

α_K = core coupling strength (≠ fine structure constant α!)

---

## Q

### Q-Factor — Q-Faktor
**DE:** Q-Faktor
**Confidence:** ✓ HIGH (concept); ⚠️ LOW (threshold values)
**Primary source:** v3_009, Final v1.0; v3_001, Kap. 2.2

Measure of the resonance quality of a DRM region. Physically: Q = ω_res/γ. High Q = coherent, stable resonance; low Q = dissipative, chaotic.

Q is the cosmological order parameter of RFT:

```
Q ≈ 1:              primordial chaos (Mode 0)
Q > Q_crit1 ~ 10³   HYPOTHESIS: space constitution (phase transition)
Q > Q_crit2 ~ 10⁶–10⁸  WORKING HYPO: vortex stability → matter
Q ≫ Q_crit2:        organized matter
```

⚠️ Q_crit1 and Q_crit2 are conceptually separate thresholds, describing different phase transitions.

---

## R

### Resonance Matrix (DRM) — Raummatrix
**DE:** Raummatrix
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 1

The foundational carrier medium of RFT. The resonance matrix is:
- **dynamic** (no fixed lattice points)
- **self-resonant** (nodes emerge from the resonance dynamics themselves)
- **space itself** (not a field *in* space — the field *is* space)

**Terminology (mandatory since v7.6, Franz 28.02.2026):**
```
CORRECT:   "resonance matrix"   /   "DRM"
WRONG:     "lattice"                ← implies rigid crystal structure
WRONG:     "grid"                   ← same problem
```

In the ground state the node structure behaves *approximately* like a periodic lattice — hence the historical (outdated) term "lattice". Precise description: dynamic self-resonant node structure.

---

### Resonance Rigidity κ — Resonanz-Steifigkeit
**DE:** Resonanz-Steifigkeit
**Confidence:** ✓ HIGH (primary-quantity status); ○ MEDIUM (quantitative derivation)
**Primary source:** v3_001, Kap. 2.2 + 3.3

κ is the **primary quantity** of RFT — the natural wave number of the vacuum, the stiffness of the resonance medium against deformation.

```
κ = 1/L₀ ≈ 1.91/l_P ≈ 1.18×10³⁵ m⁻¹
```

**Causal direction (critical distinction):**
- In QFT: mass is input → generates the –(mc/ħ)²Ψ term
- In RFT: κ is a matrix property (from geometry) → generates what we call "mass"

Effective mass: m_eff = ħκ/c

κ is NOT a "mass term" — it is the resonance rigidity of the medium. Mass is the emergent label. This reversal of causal direction is fundamental to the RFT framework.

---

## S

### Soliton — Soliton
**DE:** Soliton
**Confidence:** ✓ HIGH (concept); ○ MEDIUM (formal solutions)
**Primary source:** v3_001, Kap. 8; v3_004, Kap. 4

Stable, localized resonance pattern in the DRM — the RFT equivalent of an elementary particle. A soliton is **not a point particle** but an extended topological structure with spatial extent ≈ Compton wavelength λ_C = ħ/(m_eff·c).

Stability is topologically protected: the winding number cannot change continuously from n to n±1. A transition requires a topological phase jump. UV divergences of quantum field theory arise from the incorrect assumption of point particles — in RFT they are structurally absent.

---

### Spin Delay — Spinverzug
**DE:** Spinverzug
**Confidence:** ✓ HIGH
**Primary source:** v3_003, Kap. 3; v3_012, Kap. 3

Phase lag between a rotating vortex and the surrounding resonance matrix field. The field does not follow the rotating vortex instantaneously — there is a trailing angle. This phase lag is the **microscopic origin of gravitation** in RFT.

Characteristic timescale:
```
τ_lag = L₀/c = (π/6)·t_P ≈ 0.5236·t_P  [canonical since 11.03.2026]
```

Two orthogonal spin-delay modes:
- **Longitudinal** (compression along propagation direction) → gravitation, inertial mass m_i
- **Torsional** (twist transverse to propagation) → electromagnetism, gravitational mass m_g

---

## T

### τ_lag — Characteristic Lag Time
**DE:** Charakteristische Verzugszeit
**Formula:** τ_lag = L₀/c = (π/6)·t_P ≈ 0.5236·t_P
**Confidence:** ✓ HIGH (canonical since 11.03.2026)
**Primary source:** v3_003, Kap. 3.2; DC v10.4

Characteristic timescale of spin delay: the time the resonance matrix field needs to "follow" a rotating vortex. Numerically:

```
τ_lag = L₀/c ≈ 2.81×10⁻⁴⁴ s ≈ 0.5236·t_P
```

Use in electromagnetism: B_eff = μ₀·(g_s/τ_lag)·∇×s (magnetic field from spin delay, v3_012).

---

### Time Motor — Zeitmotor
**DE:** Zeitmotor
**Confidence:** ✓ HIGH (concept); ○ MEDIUM (quantitative linkage)
**Primary source:** v3_001, Kap. 10b; v3_006, Final v1.1

Three independent phenomena converge on the same fundamental phase asymmetry δ ≈ 0.82° that drives the arrow of time:

1. **α discrepancy** (2.22 ppm residual between RFT and CODATA)
2. **Proton mass** (via δ in the SU(2) expression)
3. **Electron topology** (via spiral correction)

The time motor is Φ ≠ 0: the DRM mode beat has a direction (forward in time). If Φ = 0, time would be reversible — no arrow of time.

```
Φ = 2α/(1+α²) ≈ 0.01459  [canonical ✓]
δ ≈ 2α ≈ 0.0146 rad        [temporal phase asymmetry]
```

---

### Torsion — Torsion
**DE:** Torsion
**Confidence:** ✓ HIGH
**Primary source:** v3_012, Kap. 3; v3_003, Kap. 3

Torsional twist mode of the resonance matrix **transverse to the propagation direction**. In RFT:
- **Gravitational mass m_g:** coherent spin delay (dynamic, time-averaged, requires τ_lag > 0)
- **Magnetic field B:** torsional mode of EM interaction (B_eff ∝ ∇×s)
- **Electromagnetism generally:** torsional/transversal mode of the DRM

**Inertial vs. gravitational mass:**
- m_i (compression, static) ≠ m_g (torsion/spin delay, dynamic)
- Why m_i = m_g normally? → Both built on the same κ basis → equivalence principle as **geometric consequence**, not postulate!
- Decoupling: Cooper pairs (n=0, no spin delay) → Δg/g ~ 10⁻⁵ expected ○ MEDIUM
  This is an experimentally testable RFT prediction (PTB Braunschweig).

---

### Triangulation Principle — Triangulations-Logik
**DE:** Triangulations-Logik
**Confidence:** ✓ HIGH
**Primary source:** v3_005, Kap. 2.1

Causality as geometric necessity: an event becomes physically real ("causally fixed") only when determined by the interference of at least three wave fronts (spheres) — the GPS principle applied to the DRM.

```
1 sphere  → center point (0D: location, no direction)
2 spheres → intersection circle (1D: axis)
3 spheres → unique point (3D: causally fixed!) ✓
4 spheres → tetrahedron (most stable 3D volume)
```

The tetrahedron (4 spheres) is the natural geometric object of the DRM node structure. The triangulation principle explains the factor **4** in 4π³ of the α expression: four equivalent spheres (not three) fix the volume — this is why the 3D contribution is 4π³, not 3π³.

---

## V

### Vortex Structure — Wirbelstruktur
**DE:** Wirbelstruktur
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 2 + 8; v3_004, Kap. 4

Stable, topologically protected resonance structure in the DRM — the fundamental picture for elementary particles in RFT. Characterized by:

- **Winding number n** (topological invariant, quantized)
- **Anchor points AP** (coupling to DRM degrees of freedom)
- **Spatial extent** ≈ Compton wavelength (no point structure!)

Winding number → charge quantization (from hourglass geometry):
```
n = ±1     → Electron / Positron    (charge ±e)
n = ±2/3   → u/c/t quarks
n = ±1/3   → d/s/b quarks
n =  0     → Neutrino candidate (longitudinal wave, not vortex)
```

---

### Winding Number — Windungszahl
**DE:** Windungszahl
**Confidence:** ✓ HIGH
**Primary source:** v3_001, Kap. 8; v3_004, Kap. 4

Topological invariant of a vortex: how many complete phase rotations the resonance field completes around the vortex core. Cannot change continuously → particle stability is topologically protected (analogous to topological insulators in condensed matter, but mechanistically distinct).

In the DRM hourglass geometry: winding number → particle charge (→ **Vortex Structure**).

---

## Canonical Parameter Reference

```
c             Only genuine fundamental input of RFT
κ             PRIMARY QUANTITY (resonance rigidity)
L₀            = (π/6)·l_P ≈ 0.5236·l_P
L             = √(4π·Φ)·l_P ≈ 0.428·l_P
α⁻¹           = 4π³+π²+π = 137.036 304  [2.22 ppm — NEVER 0.67 ppm!]
Φ             = 2α/(1+α²) ≈ 0.014 596    [canonical ✓]
τ_lag         = L₀/c = (π/6)·t_P ≈ 0.5236·t_P  [canonical since 11.03.2026]
G·ħ           = (36/π²)·c³·L₀²           [algebraic identity, NOT independent derivation!]
Q_crit1       ~ 10³   HYPOTHESIS
Q_crit2       ~ 10⁶–10⁸  WORKING HYPOTHESIS
1 quark       = 3 AP (individually!)
Proton        = 9 AP (3 quarks × 3 AP)
Matrix generation ratio: 3:1 (antimatter spin : quark spin) ✓ HIGH
Matter condensation ratio: 4:1 (separate process) ○ MEDIUM
```

---

## Discarded Terms and Known AI Artifacts

| Term | Status | Correct alternative |
|------|--------|---------------------|
| "lattice" / "space lattice" | ❌ WRONG | "resonance matrix" / "DRM" |
| c₀ | ❌ outdated | c |
| 0.67 ppm (α residual) | ❌ AI artifact | 2.22 ppm |
| L_ModeB ≈ 1.27·l_P | ❌ dimensional error | L = √(4π·Φ)·l_P ≈ 0.428·l_P |
| Q_crit ≈ 1.645 | ❌ non-canonical normalization | Q_crit1 ~ 10³ / Q_crit2 ~ 10⁶–10⁸ |
| 78π resonance | ❌ AI artifact | — |
| δ ~ 10⁻⁶ rad | ❌ AI artifact | ε ≈ Φ ≈ 0.01459 rad (via orbital model) |
| AP as geometric point | ❌ too narrow | AP = dimensional coupling (Franz 15.03.2026) |
| ħ as fundamental constant | ❌ misleading | ħ = algebraic identity (G·ħ relation) |
| α⁻¹_2D ≈ 22.9 | ❌ AI artifact | — |
| α⁻¹_4D ≈ 433 / 1234 | ❌ AI artifact candidate | flag if encountered |

---

*RFT_v3_Glossar_EN.md | Version 1.0 | 24.03.2026*
*Instance: K5 | Authorized: Franz Zollner*
*Based on: RFT_v3_Glossar_DE.md v1.1 (K5, 24.03.2026)*
*Verified against: v3_001 (v3.5), v3_002 (v3.0), v3_003 (v3.0), v3_004 (v3.0),*
*v3_005 (Final v1.1), v3_006 (Final v1.1), v3_011 Teil 3, v3_012 (Final v1.3.1),*
*v3_014 (Final v1.0), DC v10.4*
*Next step: Auftrag 2 — EN translations, Stufe 1 (v3_001, v3_002, v3_005, v3_006)*
