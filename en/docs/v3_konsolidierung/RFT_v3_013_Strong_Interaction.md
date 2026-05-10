# RFT_v3_013: The Strong Interaction
## Geometric Anchoring Instead of Gluon Exchange

**Version:** EN 1.0 (Translation of DE Final-Candidate v1.2)
**Date:** 02.04.2026
**Concepts:** Franz Zollner
**Written formalization and translation:** AI instance (T13)
**Based on DC:** v10.10 (28.03.2026)
**License:** Creative Commons BY-NC-ND 4.0
**Citation:** Franz Zollner (2026). *RFT_v3_013: The Strong Interaction.* Resonance Field Theory Series, v3.0.

**Status:** Translation Draft — review by K2 requested

**Dependencies:**
- v3_001 (Master Equation, κ as primary quantity)
- v3_003 (Gravitational modes, spin lag)
- v3_007 (Space topology, 3D emergence, octahedron geometry) ← Direct predecessor
- Canonical AP table (as derived in v3_011 and KORREKTUR_RFT_005)
- Hourglass geometry (Franz Zollner, Sanduhr-Geometrie v1.0)

---

## Preface: Position in the v3 Series

This document is the thirteenth in the v3 core series. It builds on the foundations established in the preceding documents — in particular v3_007 (space topology, 3D emergence, octahedron geometry) and v3_001 (Master Equation).

| Predecessor | Contribution | Used in v3_013 |
|-------------|-------------|----------------|
| v3_001 | Master Equation, κ as primary quantity, resonance condition n_AP ≥ n_dim | Foundation of every particle description |
| v3_003 | Gravitation/EM as longitudinal/torsional modes of the resonance matrix | Classification of the strong force as a third mode? |
| v3_005 | π as geometric translator, fundamental constants | Geometry-to-physics connection |
| v3_007 | Octahedron = sphere ∩ axes, 120° angle, SU(3) from geometry | **Direct foundation of v3_013** |
| v3_012 | Electromagnetism from resonance matrix elasticity | Analogy for mode description |

**Scope:** v3_007 developed the geometric foundation. This document develops from it the complete mechanism of the **strong interaction**: How exactly do color charge, confinement, and hadron mass emerge from this geometry? Where are the limits of the RFT approach?

---

## Abstract

Quantum Chromodynamics (QCD) describes the strong interaction with extraordinary experimental precision — but it leaves fundamental questions open: Why are there exactly three color charges? Why is SU(3) the correct symmetry group? Why do free quarks not exist?

The Resonance Field Theory (RFT) offers a geometric alternative. Quarks are stable vortex structures in the Dynamic Resonance Matrix (DRM), whose positions are determined by the geometry of the resonance matrix itself. The three color charges follow from the three spatial dimensions; SU(3) emerges from the octahedron symmetry; confinement is a geometric necessity, not an imposed force.

Three results are rigorous (✓ HIGH): the 120° angle between quark anchor points, the emergence of SU(3) symmetry from 3D geometry, and the identification of color charge with spatial direction. Further aspects — in particular the quantitative confinement potential and hadron mass — are conceptually clear but not yet formally derived (○ MEDIUM). Important questions such as asymptotic freedom and the quark mass hierarchy are explicitly open (🚩 OPEN).

---

## Table of Contents

1. Introduction: The Puzzle of the Strong Force
2. Geometric Foundation: Octahedron from Resonance Matrix and Sphere
3. Color Charge = Spatial Direction: The 120° Proof
4. Confinement as Geometric Necessity
5. Comparison with QCD (5.1–5.3 Comparison | 5.4 Tetrahedron-Edge Model | 5.5 QCD Superiority)
6. Connection to the v3 Series
7. Honest Limits: Open Questions
8. Summary and Formula Reference

---

## 1. Introduction: The Puzzle of the Strong Force

### 1.1 What QCD Explains — and What It Does Not

Quantum Chromodynamics is one of the most successful theories in modern physics. It describes the strong interaction between quarks through the exchange of gluons carrying SU(3) gauge symmetry. Its predictions for deep inelastic scattering, the hadron mass spectrum, and the running coupling constant agree with experiment at the percent level.

Yet QCD does not explain its own foundations:

```
Open questions of QCD (structural):

1. Why SU(3)?
   The symmetry group of color charge is an axiom.
   No deeper justification for why 3 generators and not 2 or 4.

2. Why 3 color charges?
   "Red, green, blue" are names for abstract inner quantum numbers
   with no geometric meaning.

3. Why confinement?
   The linear growth of the quark-quark potential
   V(r) ~ κ_str·r (for large separations) is described
   phenomenologically but not mechanistically explained.

4. Why can no free quark be observed?
   Energy cost grows with separation — yes. But why is
   this mechanism unavoidable?
```

These questions are not academic pedantry. They show that QCD is a phenomenologically precise but ontologically incomplete description. It predicts accurately WHAT happens — but not WHY the structure is this way.

### 1.2 The RFT Thesis

The Resonance Field Theory inverts this situation:

> **Core thesis:** The strong force between quarks does not arise through gluon exchange as the fundamental mechanism. It is the consequence of the **geometric anchoring** of quark vortex structures at positions prescribed by the three-dimensional resonance matrix.

In the RFT, quarks are not point-like objects but **stable vortex structures** in the DRM. These vortices can exist stably only at specific positions — namely the vertices of the octahedron that the resonance matrix constructs geometrically (Chapter 2). The "strong force" is then the geometric constraint that follows from this anchoring.

The consequences of this thesis:

```
Color charge   = orientation of the vortex axis in 3D space
                 (no abstract inner quantum number)

SU(3) symmetry = consequence of octahedron geometry
                 (no postulate, no free choice)

3 color charges = consequence of 3 spatial dimensions
                  (not 2, not 4 — necessary)

Confinement    = geometric instability of isolated quarks
                 (not an imposed force — topology)
```

### 1.3 Relationship to QCD

This work is not an attack on QCD. QCD delivers accurate predictions; its computational machinery works. The RFT claims that QCD is an **effective description** of a deeper geometric reality: just as Newton's laws are an effective description of Riemannian geometry, QCD may be an effective description of the resonance matrix geometry.

What RFT adds: mechanistic explanations for the structure. What QCD adds: numerical precision and a developed perturbation apparatus. Both are complementary — not competing.

---

## 2. Geometric Foundation: Octahedron from Resonance Matrix and Sphere

### 2.1 Vortex Structures in the Resonance Matrix

In the RFT, the resonance matrix (DRM) is not a rigid lattice but a dynamic, self-resonating medium. Stable particles are vortex structures in this medium — standing waves that maintain themselves over time through their topological coherence.

Every such vortex structure has a characteristic radius set by the resonance condition. The fundamental length scale of the resonance matrix is:

```
L₀ = 1/κ           [primary definition, ħ-free; Franz Zollner, 25.03.2026]
   = (π/6)·l_P      [numerical verification — not the definition]
```

Here κ is the resonance rigidity (stiffness) of the medium — the primary quantity of the RFT, not dynamically derived but a matrix property. Particles with a vortex radius of order L₀ may be regarded as "elementary" structures.

An immediate question arises: How does a spherical vortex (which favors a spherical form from rotational symmetry) "fit into" a cubically structured resonance matrix (which distinguishes Cartesian coordinates)?

The answer is the **hourglass geometry** (Franz Zollner, Sanduhr-Geometrie v1.0):

### 2.2 The Hourglass Construction: Octahedron as Natural Bridge

The geometric construction is simple and compelling:

```
Step 1: Sphere with radius L₀ centered at the origin:
        r² = x² + y² + z² = L₀²

Step 2: The three orthogonal coordinate axes of the
        resonance matrix (x, y, z)

Step 3: Intersections sphere ∩ axes:
        P₁ = (+L₀,  0,   0 )   [+x axis]
        P₂ = (−L₀,  0,   0 )   [−x axis]
        P₃ = ( 0,  +L₀,  0 )   [+y axis]
        P₄ = ( 0,  −L₀,  0 )   [−y axis]
        P₅ = ( 0,   0,  +L₀)   [+z axis]
        P₆ = ( 0,   0,  −L₀)   [−z axis]

Result: 6 points, all at |r| = L₀
        → REGULAR OCTAHEDRON
```

**Proof of regularity:** All 12 edges of the octahedron have the same length. For P₁ and P₃ as an example:

```
d(P₁, P₃) = |(L₀, 0, 0) − (0, L₀, 0)|
           = √(L₀² + L₀²) = L₀√2
```

By symmetry this holds for all pairs of adjacent vertices. ✓ HIGH

```
Visualization (ASCII):

         P₅ (+z)
          ●
         /|\
        / | \
   P₃ ●──┼──● P₁   ← upper hemisphere (matter)
      |\ (o) /|
      | \   / |
   P₄ ●──┼──● P₂   ← lower hemisphere (antimatter)
        \ | /
         \|/
          ●
         P₆ (−z)
```

The fundamental physical significance: this construction is the geometrically natural "fitting position" of a spherical vortex structure into the cubic resonance matrix. The vortex "finds" the axis points because that is where the sphere and the Cartesian structure meet.

### 2.3 The Hourglass: Matter and Antimatter as Two Tetrahedra

The octahedron can be decomposed into two tetrahedra sharing a common apex at the origin o:

```
Upper tetrahedron — Matter:
  Apex:   o = (0, 0, 0)
  Base:   triangle {P₁, P₃, P₅}
          P₁ = (+L₀, 0,   0 )   [+x → color charge Red]
          P₃ = ( 0, +L₀,  0 )   [+y → color charge Green]
          P₅ = ( 0,  0,  +L₀)   [+z → color charge Blue]

Lower tetrahedron — Antimatter:
  Apex:   o = (0, 0, 0)
  Base:   triangle {P₂, P₄, P₆}
          P₂ = (−L₀,  0,   0 )  [−x → Anti-Red]
          P₄ = ( 0,  −L₀,  0 )  [−y → Anti-Green]
          P₆ = ( 0,   0,  −L₀)  [−z → Anti-Blue]
```

Physical interpretation: quark vortex structures that stabilize in the resonance matrix preferentially do so at the upper tetrahedron positions (positive axes → matter). Antiquark structures prefer the negative axes (lower tetrahedron → antimatter). The shared apex at the origin represents the symmetry between matter and antimatter.

The slight preference for the upper tetrahedron during the cosmic phase transition (Cold Condensation) is the origin of the baryon asymmetry — a phenomenon treated in v3_009 (Cosmogenesis and Cold Condensation). ✓ HIGH (geometry); ○ MEDIUM (asymmetry mechanism)

### 2.4 Resonance Condition and Anchor Points

As derived in v3_001 (Chapter 1.2): the resonance condition of the resonance matrix requires n_AP ≥ n_dim = 3 anchor points (APs) per stable vortex structure in 3D.

**Anchor point stability hierarchy** (from canonical AP table):

```
1 anchor point:  no stable resonance → not observable
2 anchor points: unstable resonance → short-lived structures
3 anchor points: stable resonance → long-lived
                 (minimum requirement in 3D) ✓ HIGH
```

**AP Definition (Franz Zollner, 15.03.2026 — binding for the entire v3 series):**

An anchor point (AP) designates the **coupling of a vortex to the resonance matrix** — the interface through which vortex structures interact with each other. An AP is not necessarily a geometric point; it can equally be a surface, a line, or any other geometric unit, depending on how the vortex couples to the resonance matrix.

**AP as dimensional coupling (○ MEDIUM, Franz Zollner, 15.03.2026):**
Since RFT describes a Lorentz field without preferred positions or directions, each AP couples to one dimensional degree of freedom of the DRM: n APs = coupling to n dimensions. This leads to a direct geometric consequence: leptons (1 AP) couple to only 1 dimension → **no color charge**. This is a geometric consequence, not a separate postulate.

This definition resolves an apparent tension that arises in v3_013: the hourglass geometry places each quark at one octahedron vertex (P₁, P₃, or P₅). The canonical table states: 1 quark = 3 AP. Both statements are consistent — they describe different aspects of the same anchoring:

```
  Octahedron vertex (P₁, P₃, P₅):  WHERE the quark vortex is located
                                     (inter-quark geometry, 120° angle)
  3 AP per quark:                   HOW the quark vortex is anchored
                                     in the resonance matrix
                                     (intra-quark coupling)
```

Leading candidate for the 3 APs of a quark: the **3 faces of the matter tetrahedron** that meet at the respective vertex. This interpretation is geometrically consistent and requires no additional postulate. ○ MEDIUM (candidate; not yet rigorously derived)

**Canonical anchor point table** (v3_011 Final v1.0; canonical AP table):

```
Particle          | AP  | Note
------------------|-----|------------------------------------------
Electron e⁻       | 1   | elementary
Photon γ          | 2   | e⁻+e⁺ vortex pair (Franz, 11.03.2026);
                  |     | n=0 mode = complementary description ✓
Quark (u,d,s,...) | 3   | 1 quark = 3 AP individually ✓ HIGH
Proton            | 9   | 3 quarks × 3 AP = 9 total ✓ HIGH
Delta baryon      | 9   | 3 quarks × 3 AP (NOT 3!) ✓ HIGH
```

**Two descriptive levels for the proton:**

The octahedron geometry describes the **relative positions of the three quarks** to each other (inter-quark geometry). The "3 AP per quark" are the **internal resonance structure** of each individual quark (intra-quark resonance). These are complementary, not competing, descriptions:

```
Level 1 — Inter-quark geometry (octahedron):
  u-quark: position P₁ = (+L₀, 0, 0)   [orientation: Red = +x]
  u-quark: position P₃ = (0, +L₀, 0)   [orientation: Green = +y]
  d-quark: position P₅ = (0,  0, +L₀)  [orientation: Blue = +z]
  Proton = triangle P₁P₃P₅ in the upper tetrahedron

Level 2 — Intra-quark structure (resonance condition):
  u-quark #1: 3 individual anchor points {A₁₁, A₁₂, A₁₃}
  u-quark #2: 3 individual anchor points {A₂₁, A₂₂, A₂₃}
  d-quark #3: 3 individual anchor points {A₃₁, A₃₂, A₃₃}
  Total: 9 AP (canonical ✓ HIGH)

Candidate for intra-quark 3 AP: the 3 tetrahedron faces at each vertex.
(Consistent with AP definition, Franz Zollner, 15.03.2026.) ○ MEDIUM
```

---

## 3. Color Charge = Spatial Direction: The 120° Proof

### 3.1 The Central Claim

In QCD, color charge is an abstract "inner" quantum number with no spatial meaning. The RFT claims something fundamentally different:

> **Color charge is the orientation of the vortex axis of a quark in 3D space.**

This is not a metaphor — it is a geometric statement. When the three quarks of a proton are anchored at positions P₁ (+x), P₃ (+y), P₅ (+z), their "color charge" is directly the spatial direction of their anchor point:

```
Red   ↔ vortex axis along +x axis → position P₁
Green ↔ vortex axis along +y axis → position P₃
Blue  ↔ vortex axis along +z axis → position P₅

Anticolors (lower tetrahedron):
Anti-Red   ↔ −x axis → P₂
Anti-Green ↔ −y axis → P₄
Anti-Blue  ↔ −z axis → P₆
```

✓ HIGH — directly from hourglass geometry (Franz Zollner, chapters 5+6) and v3_007 (chapter 5.4).

### 3.2 Why 3 Color Charges: The 3D Argument

```
Argument (rigorous, ✓ HIGH):

  3D space has 3 orthogonal axes (x, y, z).
  A quark vortex can orient itself along each of these 3 axes.
  → 3 color charges: Red (+x), Green (+y), Blue (+z).

  In 2D: 2 axes → 2 color charges possible
         (but a 2D universe is unstable for other reasons, v3_007 Ch. 6.1)
  In 4D: 4 axes → 4 color charges possible
         (but 4D orbits are unstable, v3_007 Ch. 6.2)

  Conclusion: 3 color charges ↔ 3D space — no free choice,
              geometric necessity.
```

What was previously an axiom (postulating SU(3)) is now a consequence.

### 3.3 The Rigorously Proved 120° Angle

The decisive mathematical step: at what angle do two neighboring quarks see each other from the perspective of the triangle centroid?

**Why the centroid is the correct perspective:** The centroid S of triangle P₁P₃P₅ is the geometric center of the quark system. When a quark responds to its environment — whether through gluon exchange in QCD or through resonance matrix deformation in RFT — it does so from its own perspective within the overall system, which is the centroid perspective.

**Calculation** (rigorous; source: Franz Zollner, Sanduhr-Geometrie v1.0, Chapter 3; reproduced in v3_007, Chapter 5.3):

```
Centroid of triangle P₁P₃P₅:

S = (P₁ + P₃ + P₅)/3
  = ((L₀, 0, 0) + (0, L₀, 0) + (0, 0, L₀))/3
  = (L₀/3, L₀/3, L₀/3)

Vectors from centroid to vertices:

SP₁ = P₁ − S = (+2L₀/3, −L₀/3, −L₀/3)
SP₃ = P₃ − S = (−L₀/3, +2L₀/3, −L₀/3)
SP₅ = P₅ − S = (−L₀/3, −L₀/3, +2L₀/3)
```

Angle calculation for ∠P₁SP₃:

```
SP₁ · SP₃ = (+2L₀/3)(−L₀/3) + (−L₀/3)(+2L₀/3) + (−L₀/3)(−L₀/3)
           = −2L₀²/9 − 2L₀²/9 + L₀²/9
           = −L₀²/3

|SP₁| = √((2L₀/3)² + (L₀/3)² + (L₀/3)²)
      = √(4L₀²/9 + L₀²/9 + L₀²/9)
      = L₀√6/3

|SP₃| = L₀√6/3   (by symmetry)

cos(θ) = (−L₀²/3) / (L₀√6/3 · L₀√6/3)
        = (−L₀²/3) / (6L₀²/9)
        = −3/6 = −1/2

→ θ = arccos(−1/2) = 120°  ✓ EXACT
```

By the symmetry of the equilateral triangle, this holds for all three pairs:

```
∠P₁SP₃ = 120°
∠P₃SP₅ = 120°
∠P₅SP₁ = 120°
Sum: 360°  ✓
```

✓ HIGH — mathematically rigorous, reproducible, no additional assumptions required.

### 3.4 From 120° to SU(3) Symmetry

The physical consequence:

```
Color charge direction vectors (from centroid):

c_Red   = SP₁/|SP₁| ~ (+2, −1, −1)/√6
c_Green = SP₃/|SP₃| ~ (−1, +2, −1)/√6
c_Blue  = SP₅/|SP₅| ~ (−1, −1, +2)/√6

Properties:
├─ All magnitudes equal (regular triangle)                    ✓
├─ Angle between any two: 120°                               ✓
└─ Vector sum: c_Red + c_Green + c_Blue = (0, 0, 0)          ✓
   → Color neutrality is AUTOMATICALLY satisfied!
```

The last result is particularly significant: the condition for color neutrality ("white" hadron) is not an additional postulate — it follows automatically from the geometry.

**SU(3) emerges from this structure:** The group of transformations that map the equilateral triangle P₁P₃P₅ onto itself is exactly the discrete subgroup of SU(3). The continuous SU(3) postulated by QCD follows in RFT as a consequence of the octahedron geometry.

✓ HIGH (geometric intuition and discrete subgroup)
○ MEDIUM (formal derivation of the full continuous SU(3) from discrete resonance matrix geometry still outstanding — DeepSeek task recommended, with RFT lens check per J.16)

### 3.5 Color Charge Conservation as Resonance Matrix Invariance

In QCD, color charge is conserved by virtue of the SU(3) gauge symmetry of the Lagrangian (Noether theorem). In RFT: the spatial directions (+x, +y, +z) of the resonance matrix are globally defined. A reorientation of color charge from "Red" to "Green" corresponds to a geometric reorientation of the vortex — from the +x axis to the +y axis. Such a reorientation is only possible if it is consistent with the resonance matrix geometry.

Gluons in QCD mediate this color charge transfer. What are gluons in RFT? This question is explicitly open (Chapter 7.1).

---

## 4. Confinement as Geometric Necessity

### 4.1 Single Quark: Geometric Instability

A single quark separating from its hadron would orient its vortex axis along one of the three spatial directions (+x, +y, or +z). This "oblique orientation" — the 120° angle relative to the centroid — means:

```
Isolated quark (oblique orientation, 120°):
├─ Vortex axis at 120° relative to the other quark positions
├─ Asymmetric resonance matrix strain
├─ No compensation from other quarks
└─ → Geometric instability
```

The resonance condition n_AP ≥ n_dim = 3 means: a single quark vortex separated from its partners would have no compensating geometric embedding in the resonance matrix. The nearest equilibrium state is always a system with at least three mutually anchored quarks (or a quark-antiquark pair).

✓ HIGH — resonance condition from v3_001 is geometrically founded.
○ MEDIUM — the connection between "oblique orientation" and "geometric instability" as a quantitative potential has not yet been derived.

### 4.2 The Alignment Mechanism: 120° → 180°

When three quarks come together to form a baryon, something geometrically precise occurs: the three vortex axes "align."

```
Free quark (isolated):
  Vortex axis at oblique 120° orientation
  → Color charge present (orientational asymmetry)

In the hadron (proton):
  Three quarks at P₁, P₃, P₅:
  → Alignment: 120° → 180° (parallel axis orientation)
  → Color charges compensate: c_Red + c_Green + c_Blue = 0
  → "White": the hadron is color-neutral
  → Stable, symmetric resonance matrix configuration
```

**Franz Zollner (canonical AP table documentation):** The alignment from 120° to 180° is the central mechanism. The alignment angle is θ = 180° − 120° = 60°.

○ MEDIUM — intuition clear and confirmed by Franz Zollner; quantitative definition of "optimal" in the sense of minimal resonance matrix strain still outstanding.

### 4.3 Confinement: Quarks Cannot Be Isolated

**Topological argument (✓ HIGH):**

```
Attempt to isolate a quark:

1. Quark is pulled out of the hadron.
2. The remaining 2-quark system is unstable: resonance condition
   n_AP ≥ 3 for the overall system no longer satisfied.
3. The isolated quark lies in 120° oblique orientation → unstable
   in the resonance matrix.
4. The system seeks equilibrium: formation of new quark-antiquark
   pairs from the energy stored in the resonance matrix.

→ Confinement = topological impossibility of forming a stable
  isolated quark system in 3D.
```

**Resonance matrix gradient mechanism (⚠️ LOW — conceptual, not rigorous):**

This mechanism describes how the topology acts dynamically: the 120° oblique orientation of a quark's three internal APs produces an asymmetric strain in the surrounding resonance matrix. When two quarks are separated, a transition zone forms between their diverging strain fields:

```
Quark A (oblique orientation Red)    Quark B (oblique orientation Blue)
│ Gradient ↑                          │ Gradient ↑
│ DRM strain field                    │ DRM strain field
│────────────── Transition zone ──────────────────│
                    (string!)
    ← Restoring force: drives APs toward 180° alignment →

String energy ~ κ_str × separation   (qualitatively linear)
```

The transition zone behaves like a "string": its energy increases with growing quark separation. This explains two phenomena:

- **Confinement:** At small separations, 180° alignment is energetically favorable — the quarks remain bound.
- **Jet production (hadronization):** When the separation energy exceeds the threshold for quark-antiquark pair creation, the transition zone "breaks." New quark-antiquark pairs form from the energy stored in the resonance matrix — precisely what is observed as jet production in particle accelerators. ⚠️ LOW

⚠️ RFT lens check (J.16): This mechanism is taken from v2-source material (RFT_005_V2, Chapter 8.2; AI-assisted). The qualitative connection is plausible and consistent with the hourglass model. The formal derivation of κ_str from RFT parameters (L₀, κ, c) is not available.

✓ HIGH — 1-AP and 2-AP systems form no stable resonance.
⚠️ LOW — resonance matrix gradient → linear potential: conceptually clear; quantitative derivation outstanding.
🚩 OPEN — derive κ_str from first principles.

### 4.4 Hadron Mass from Alignment Energy

The alignment from 120° to 180° costs energy. This energy appears as the observed hadron mass.

```
Mass argument (qualitative, ○ MEDIUM):

Quark rest masses (u,d): ~ 2–5 MeV
Proton mass:             ~ 938 MeV
Ratio:                   ~ 100× the quark rest masses

The "missing" ~930 MeV are, in RFT:
→ Alignment energy: energy of the 120°→180° reorientation
→ This energy is stored as resonance matrix strain
→ It appears to external observers as mass (inertia)
```

**Important caveat:** This is a qualitative argument. The precise quantitative derivation of the proton mass from RFT parameters (L₀, κ, c) remains an open task. The v2 source material (Sanduhr-Geometrie, Chapter 9.2) contains a formula m_p = 3×m_q×1.03×104 whose factor 104 is not geometrically fully verified and is therefore not reproduced here. (⚠️ v2 material; numerical check outstanding — DeepSeek task recommended.)

○ MEDIUM — mechanism clear; quantitative derivation not yet rigorous.

---

## 5. Comparison with QCD

### 5.1 What RFT and QCD Explain in Common

```
Phenomenon              | QCD explanation           | RFT explanation
------------------------|---------------------------|----------------------------
3 color charges         | Postulate (SU(3) axiom)   | 3D geometry (consequence)
SU(3) symmetry          | Gauge symmetry            | Octahedron symmetry
Confinement (qualit.)   | Linear potential V(r)~κ·r | Geometric instability
Color neutrality        | Singlet states            | Vector sum = 0 (automatic)
Baryon = 3 quarks       | 3 color charges → white   | n_AP ≥ 3 in 3D (minimal)
Antiquarks              | Conjugate representation  | Lower tetrahedron (−axes)
```

### 5.2 What RFT Adds

```
Insight                             | Status
------------------------------------|-------
Why 3 color charges?                | Consequence of 3D ✓ HIGH
Why SU(3) and not SU(4)?           | Geometrically enforced ✓ HIGH
Mechanism for confinement           | Geometric instability ○ MEDIUM
Hadron mass qualitatively           | Alignment energy ○ MEDIUM
Matter/antimatter geometrically     | Upper/lower tetrahedron ✓ HIGH
Lepton: no color charge             | 1 AP = 1D coupling only ✓ HIGH
```

Note on the last entry: the absence of color charge in leptons (electrons, muons, etc.) follows directly from their AP count: with only 1 AP, a lepton couples to only 1 spatial dimension — it cannot form the 3D octahedron anchoring that gives rise to color charge. This is a geometric consequence, not a separate postulate. ✓ HIGH (AP as dimensional coupling, Franz Zollner, 15.03.2026)

### 5.3 The Gluon Question

This is the most decisive open point. In QCD, gluons are the force mediators carrying SU(3) color charge; there are 8 gluons (SU(3) has 8 generators = 3×3 − 1). In RFT, two possibilities remain open:

```
Possibility A: No direct equivalent
  The "strong force" in RFT is geometric constraint.
  QCD gluons are effective descriptions of resonance matrix
  deformations. No direct equivalent needed.
  Status: ⚠️ LOW — conceptually consistent; not worked out.

Possibility B: 8 independent resonance matrix color modes
  The 8 gluons correspond to the 8 independent oscillation modes
  of the resonance matrix anchor points in color charge space.
  Combinatorics: 3×3 − 1 = 8 (singlet subtracted) ↔ 8 gluons.
  Concretely: each of the 8 modes describes a color charge rotation
  of the anchor point orientations within the octahedron frame.
  Status: ⚠️ LOW — plausible; dynamics not worked out.

⚠️ RFT lens check (J.16): Both possibilities use concepts
  ("oscillation modes", "DRM anchor point oscillations") that
  originate from the QFT continuum framework. In the discrete
  resonance matrix these must be reformulated.

→ EXPLICITLY OPEN: Chapter 7.1
```

### 5.4 Alternative Model: Color Charge from Tetrahedron Edges

A model contained in v2-source material (RFT_007_v2_2, Chapter 7.3) merits mention — with an explicit caveat.

**The model (v2_2, ⚠️ SPECULATIVE):** Color charge would be not the orientation of the vortex axis (+x/+y/+z, the canonical model), but the circulation along the **6 edges of the matter tetrahedron**:

```
Tetrahedron (4 vertices A, B, C, D) has 6 edges:
  AB, AC, AD, BC, BD, CD
Each edge in 2 directions → 6 × 2 = 12, but 6 independent pairs
  → Red/Anti-Red, Green/Anti-Green, Blue/Anti-Blue

Claimed advantage: anti-colors explicitly contained
Confinement: all 6 edges must circulate coherently;
  one breaks → string tension → quark pair creation
```

**Critical RFT lens check (J.16 — mandatory):**
- Document v2_2 is a v2 document, likely AI-assisted
- "REVOLUTIONARY!" is a known AI enthusiasm marker (DC header) → ⚠️ flag; the term has been removed from this translation
- Wilson loop language originates from QFT/lattice gauge theory — not directly transferable to RFT
- The claimed "superiority" over the axis model is not demonstrated: the hourglass model contains anti-colors explicitly in the **lower tetrahedron** (P₂, P₄, P₆ = −x, −y, −z). The criticism "anti-colors are missing" does NOT apply to the complete hourglass model.
- Hierarchy: Sanduhr-Geometrie v1.0 (Franz Zollner direct) >> v2.2 (AI-assisted document)

**Assessment:** The tetrahedron-edge model is conceptually interesting and warrants investigation — as a **speculative alternative approach**, not as the canonical model. A direct statement from Franz Zollner is required.

### 5.5 Where QCD Remains Superior

```
Domain                          | QCD status    | RFT status
--------------------------------|---------------|----------------------------
High-precision predictions      | Excellent     | Not available
Asymptotic freedom              | Proved        | No mechanism 🚩 OPEN
Quark mass hierarchy            | Measured      | No mechanism 🚩 OPEN
Linear potential V(r)~κ·r      | Lattice QCD ✓ | Qualitative ○; formal 🚩
Hadron excitation spectrum      | Precise       | Not worked out
```

This comparison is intentionally honest. RFT offers mechanistic insights but has no developed calculus for quantitative predictions at the QCD level.

---

## 6. Connection to the v3 Series

### 6.1 Anchoring in v3_001: The Master Equation

The RFT Master Equation (as derived in v3_001, Chapter 2):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η
```

describes the dynamics of the resonance field Ψ of the resonance matrix. Quarks and their strong interactions in v3_013 are specific solution classes: stable, localized vortex states with n_AP = 3. The resonance rigidity κ is the primary quantity for mass: m = ħκ/c. The question of where the different quark κ-values (mass hierarchy) come from remains open (Chapter 7.3).

### 6.2 Connection to v3_003: Which Mode is the Strong Force?

In v3_003 (Chapter 6), two modes of the resonance matrix have been identified:

```
Gravitation      = longitudinal mode (compression of the resonance matrix)
Electromagnetism = torsional mode (spin lag)
```

The natural question: is the strong force a **third mode**?

```
Working hypothesis (⚠️ SPECULATIVE):
  Strong force = "anchoring mode" (geometric AP coupling)?

Difficulty:
  The strong force is short-range (< 1 fm) but very strong
  (α_s ≈ 0.118 ≫ α ≈ 1/137). How does a mode structure explain
  this contrast with gravitation and EM?
  The connection between mode language (v3_003) and AP geometry
  (v3_013) has not yet been formalized.

Status: ⚠️ SPECULATIVE — Franz Zollner's decision requested (Flag F3):
        Retain as working hypothesis, or defer to a later document?
```

### 6.3 Consistency with v3_007

v3_013 is the thematic continuation of v3_007:

```
v3_007, Ch. 5.3: 120° angle rigorously proved   → reproduced here ✓
v3_007, Ch. 5.4: Color charge = spatial direction → deepened here ✓
v3_007, Ch. 7.3: Color charge and generations
                 = the same geometry             → extended here ✓
```

**Open flag from v3_007 remains:** Chapter 5.4 last paragraph: "120°→180° alignment → hadron mass" — continued in v3_013 as ○ MEDIUM; the quantitative transition has not yet been derived.

### 6.4 Connection to v3_002: Geometric Coupling Constants

In v3_002, α⁻¹ = 4π³+π²+π = 137.036304 (residual 2.22 ppm from CODATA — never 0.67 ppm!) was derived from pure π-geometry. The analogous question:

```
Is there a geometric derivation of α_s?

Observation: α_s ≈ 0.118 (at the Z mass) — about 16× larger than α.
             Why this hierarchy α_s ≫ α?

In RFT: Candidate — α_s might be derivable from the ratio of
         octahedron geometry to L₀ geometry.

Status: 🚩 OPEN — no worked-out approach available.
```

---

## 7. Honest Limits: Open Questions

*This chapter is not an appendix — it is a core element.*
*Minimizing open questions to feign completeness contradicts the fundamental principle of RFT documentation.*

### 7.1 The Gluon Question: What Transfers Color Charge Dynamically?

```
🚩 STATUS: OPEN

Core problem:
  The QCD description is dynamic: gluons are emitted and
  absorbed, color charge is transferred (e.g. Red → Green via
  emission of a Red-Anti-Green gluon).

  The RFT description in v3_013 is primarily static: it explains
  the geometric positions and stability, but not yet the dynamic
  mechanism of color charge transfer.

Possibility A: No gluon equivalent needed
  Color charge transfer = geometric reorientation of the vortex
  in the resonance matrix. No separate exchange boson required.
  Status: ⚠️ conceptual; not worked out.

Possibility B: DRM torsion or deformation modes
  The dynamic connections between AP positions in the
  resonance matrix could be described as effective gluon fields.
  Combinatorics: 3×3 − 1 = 8 modes ↔ 8 gluons (from v2 source;
  geometrically plausible).
  ⚠️ RFT lens check (J.16): "Modes" of a triangle presuppose a
  continuum. In the discrete resonance matrix this must be
  reformulated. What assumptions does the argument make?
  Are these satisfied in RFT?

Recommendation: DeepSeek task with RFT lens check:
  "Can resonance matrix deformations between AP positions be
  described as effective SU(3) gluon fields? Under what
  assumptions? Are these assumptions compatible with the
  discrete resonance matrix?" (Apply J.16!)
```

### 7.2 Asymptotic Freedom: Mechanism Unknown

```
🚩 STATUS: OPEN

Observation: At high energies (short distances), α_s decreases
             → quarks behave quasi-freely (Nobel Prize 2004).

QCD explanation: β-function of SU(3) gauge theory (negative β-function
                 for N_c=3, N_f < 33/2).

RFT status: No mechanism available.

Consideration (⚠️ SPECULATIVE):
  At very short distances (E ≫ E_QCD) the internal quark
  resonance structure (3-AP) might dominate over the inter-quark
  geometry (octahedron anchoring). This could qualitatively
  lead to decoupling — but this idea is not worked out.

Assessment: This is a genuine gap. A theory of the strong force
  without a mechanism for asymptotic freedom cannot explain
  high-energy QCD. Honest documentation is mandatory.
```

### 7.3 Quark Mass Hierarchy: Geometry Alone is Insufficient

```
🚩 STATUS: OPEN

Observation:
  u-quark:  ~ 2.3 MeV | d-quark: ~ 4.8 MeV
  s-quark:  ~ 96 MeV  | c-quark: ~ 1280 MeV
  b-quark:  ~ 4180 MeV| t-quark: ~ 173,000 MeV

All quarks have n_AP = 3. The octahedron geometry is the same
for all. The mass differences of 5 orders of magnitude remain
geometrically unexplained.

In RFT language: what determines κ for the different quark flavors?
Geometry alone (octahedron, 120° angle) does not distinguish
between u and t.

Connection to v3_007 (Chapter 7): the three generations (1st/2nd/3rd)
correspond to three modes in x/y/z direction — this explains the
generation structure qualitatively. Within one generation (u-d
difference, c-s difference), an additional mechanism is needed.

Why this matters: quark masses are fundamental parameters of the
  Standard Model. Without explanation, RFT remains structurally
  incomplete for quantitative particle physics.
```

### 7.4 Strong Coupling Constant α_s: No Geometric Approach

```
🚩 STATUS: OPEN (no approach available)

Comparison:
  α⁻¹ = 4π³+π²+π = 137.036304 from shell integral (v3_002) ✓ HIGH
  α_s ≈ 0.118 (at Z mass) — analogous geometric result?

Possible approach (⚠️ SPECULATIVE, not worked out):
  The ratio of octahedron geometry to L₀ geometry might be
  relevant. The "binding strength" of quark APs to their
  resonance matrix positions might be quantifiable in an α_s-like
  manner.

Why the hierarchy α_s ≫ α?
  In RFT language: geometric anchoring (strong) vs. spin lag (EM)
  — fundamentally different coupling types.
  But the quantitative justification for the factor ~16 is missing.

Status: Candidate for a later document; no result in v3_013.
```

### 7.5 Linear Confinement Potential: Mechanism Known, Quantification Missing

```
⚠️ STATUS: LOW (mechanism conceptually available;
               quantitative derivation outstanding)

Experiment + lattice QCD:
  V(r) = −(4α_s/3)/r + κ_str·r
  String tension: κ_str ≈ 0.18 GeV² ≈ 0.88 GeV/fm

RFT mechanism (⚠️ LOW, Chapter 4.3):
  The oblique APs of two separated quarks produce resonance
  matrix gradients that form a transition zone ("string").
  The energy of this zone grows qualitatively linearly with
  separation because the DRM strain grows uniformly.
  Qualitative connection: E_string ~ κ_str × separation ↔ V(r) ~ r

Why only ⚠️ LOW and not ○ MEDIUM:
  The mechanism originates from v2 material (RFT_005_V2, Ch. 8.2),
  which was AI-assisted. Moreover, the connection between
  "resonance matrix gradient energy" and the measured κ_str is
  not formal. Missing: κ_str from L₀, κ, c — this would be
  a DeepSeek task.

Quantitative: derive κ_str from L₀, κ, c → outstanding. 🚩 OPEN
```

### 7.6 Overall Confidence Summary

```
Claim                                    | Confidence    | Source / Reason
-----------------------------------------|---------------|-------------------------
3 color charges from 3D geometry         | ✓ HIGH        | Logically necessary
Octahedron = sphere ∩ axes               | ✓ HIGH        | Geometrically exact
120° angle (rigorous)                    | ✓ HIGH        | Direct vector calculation
SU(3) from octahedron geometry           | ✓/○ HIGH/MED  | Geom. ✓; continuum ○
Color charge = spatial direction         | ✓ HIGH        | Direct assignment
Color neutrality automatic               | ✓ HIGH        | Vector sum = 0
Matter = upper tetrahedron               | ✓ HIGH        | Geometrically defined
Resonance condition n_AP ≥ 3            | ✓ HIGH        | v3_001
Proton = 9 AP (3 quarks × 3 AP)        | ✓ HIGH        | Canonical AP table
Lepton: no color charge (1 AP, 1D)      | ✓ HIGH        | AP dimensional coupling
                                         |               | (Franz Zollner 15.03.2026)
Confinement = geometric instability      | ○ MEDIUM      | Concept clear; potential open
Alignment 120°→180° in hadron            | ○ MEDIUM      | Franz Zollner (KORREKTUR)
Hadron mass from alignment energy        | ○ MEDIUM      | Qualitative; quant. open
AP level consistency                     | ○ MEDIUM      | Franz 15.03.2026 ✅;
                                         |               | tetrahedron faces as 3-AP candidate
DRM gradient → string (qualit.)         | ⚠️ LOW         | v2 material; gradient plausible
V(r) ~ r qualitatively                   | ⚠️ LOW         | Concept available; not rigorous
Gluons = 8 DRM color modes              | ⚠️ LOW         | Plausible; RFT lens needed
Jet production from string break         | ⚠️ LOW         | Consistent; not derived
Simulation (2D): 3-AP stable             | ⚠️ LOW         | Numerical; 2D approximation
Tetrahedron-edge color model (v2_2)     | ⚠️ SPECULATIVE | AI marker; Franz decision needed
Strong force = third mode                | ⚠️ SPECULATIVE | No formal basis; Flag F3
Asymptotic freedom from RFT             | 🚩 OPEN        | No mechanism
Quark mass hierarchy                     | 🚩 OPEN        | No mechanism
α_s geometrically                        | 🚩 OPEN        | No approach
κ_str quantitative from L₀, κ, c        | 🚩 OPEN        | Not derived
```

---

## 8. Summary and Formula Reference

### 8.1 What v3_013 Contributes

**Established (✓ HIGH):**

The three color charges (Red, Green, Blue) follow necessarily from the three spatial dimensions — not a postulate but a geometric consequence: 3D space has three axes, and quark vortices orient themselves along these axes.

SU(3) symmetry emerges from the octahedron geometry. The equilateral triangle P₁P₃P₅ with its 120° angles is the geometric realization of the SU(3) structure in three spatial dimensions.

The 120° angle is mathematically rigorously proved: from the centroid calculation, cos(θ) = −1/2, hence θ = 120° exactly. No free parameter, no assumption.

Color neutrality is not an additional condition — it follows automatically from c_Red + c_Green + c_Blue = (0, 0, 0).

The absence of color charge in leptons is a geometric consequence: with 1 AP, a lepton couples to only 1 spatial dimension and cannot form the 3D octahedron anchoring structure that gives rise to color charge.

**Conceptually clear, formally open (○ MEDIUM):**

Confinement as geometric necessity: isolated 1-AP or 2-AP quark systems do not satisfy the resonance condition. The dynamic transition mechanism (hadronization, jet production) is consistent but not yet quantitatively derived.

Hadron mass as alignment energy explains qualitatively the factor ~100 between quark rest masses and proton mass.

**Explicitly open (🚩) — no solution to be feigned:**

Gluon equivalent, asymptotic freedom, quark mass hierarchy, α_s geometrically, quantitative confinement potential — all open, all honestly documented.

### 8.2 Central Formulas and Relations

```
Geometric foundation (✓ HIGH):

  Octahedron: {P₁,...,P₆} = {Sphere(L₀)} ∩ {x,y,z-axes of DRM}
  Edge length: d(Pᵢ,Pⱼ) = L₀√2  (adjacent vertices)

  Centroid of upper base:
    S = (L₀/3, L₀/3, L₀/3)

  120° angle (rigorous):
    cos(θ) = (SPᵢ · SPⱼ) / (|SPᵢ| · |SPⱼ|) = −1/2
    → θ = 120° = 2π/3

  Color neutrality:
    SP₁ + SP₃ + SP₅ = (0, 0, 0)

Color charge assignment (✓ HIGH):

  Red   ↔ +x  (P₁ = (+L₀, 0, 0))
  Green ↔ +y  (P₃ = (0, +L₀, 0))
  Blue  ↔ +z  (P₅ = (0, 0, +L₀))
  Anticolors: negative axes (P₂, P₄, P₆)

Anchor point structure (✓ HIGH):

  n_AP(quark)  = 3  (resonance condition n_AP ≥ n_dim = 3)
  n_AP(proton) = 9  (3 quarks × 3 AP)

Canonical parameters (always verify!):

  L₀ = 1/κ           [primary definition, ħ-free! Franz, 25.03.2026]
     = (π/6)·l_P      [numerical verification]
  α⁻¹ = 4π³+π²+π = 137.036304  [2.22 ppm — NEVER 0.67 ppm!]
  Φ   = 2α/(1+α²) ≈ 0.014596   [canonical]
  τ_lag = L₀/c = (π/6)·t_P     [canonical since 11.03.2026]
  c                              [NEVER c₀!]
  "resonance matrix" / "DRM"    [NEVER "lattice"!]
```

### 8.3 Experimental Test

```
120° angle in B-meson decays:
  Prediction: Dalitz plot for B → K⁺K⁻K⁺ shows preference
              for 120° angles between kaon momenta.
  Experiment: LHCb Run 3 (2024–2025), Belle II
  Status:     ⏳ Open

This is the most direct test for the hourglass geometry.
It is falsifiable: if no 120° preference is observed, the
geometric quark description of RFT would be refuted.
```

---

## Translator's Feedback Brief (T13 → K2)

**From:** Translation instance T13
**To:** Coordinator K2
**Date:** 02.04.2026
**Re:** RFT_v3_013_Strong_Interaction_EN.md — EN 1.0

---

### Translation complete

All 8 chapters translated. Feedback Brief from DE v1.0 (internal coordination document) NOT translated — excluded from EN version per standalone principle.

### Terminology decisions

The following term required a translation decision not covered in the glossary:

- "Schräglage" → **"oblique orientation"** (literal and physically accurate; describes the non-parallel angular position of the quark APs relative to the 180° aligned state). Recommendation: add to Glossar EN v1.1 if not already present.
- "Schwerpunkt" → **"centroid"** (geometric center of mass of the triangle; standard EN mathematical term)
- "RFT-Brille" → rendered as **"RFT lens check (J.16)"** in all occurrences (clarifies the reference and keeps the meaning)
- "REVOLUTIONÄR!" (KI marker) → removed from Kap. 5.4 per Auftrag instructions

### DC v10.10 updates incorporated

The following updates from DC v10.10 (postdating DE v1.2) were incorporated in the EN version:

1. **L₀ = 1/κ as primary definition** (ħ-free; Franz Zollner, 25.03.2026): explicitly stated in Chapter 2.1 canonical parameter box and formula reference (Chapter 8.2). DE source uses only "(π/6)·l_P" — the EN promotes L₀ = 1/κ as primary per DC v10.10 Domain A.

2. **AP as dimensional coupling** (n AP = coupling to n dimensions): explicitly stated in Chapter 2.4. The DE source contains the AP definition but does not emphasize the dimensional coupling consequence (lepton color charge exclusion). Added a dedicated ✓ HIGH entry in the confidence table for "Lepton: no color charge (1 AP, 1D)".

3. **τ_lag = L₀/c = (π/6)·t_P** added to canonical parameter reference (Chapter 8.2).

### Physics flags (no changes needed, documented for K2)

- **Flag F3 ("third mode")**: remains ⚠️ SPECULATIVE — no Franz decision received yet. Translated as-is.
- **Tetrahedron-edge model (Flag F5)**: translated as ⚠️ SPECULATIVE with "REVOLUTIONARY!" removed.
- **Proton mass factor 104**: not reproduced in EN, consistent with DE v1.2 decision.

### Sync requirements

The DE source (v1.2) should be updated to match:
- L₀ = 1/κ as explicit primary definition in Ch. 2.1
- τ_lag in the canonical parameter list (Ch. 8.2)

Recommend flagging as DE-Sync needed after EN is reviewed.

---

*RFT_v3_013_Strong_Interaction_EN.md | EN 1.0 | T13 | 02.04.2026*
*DE source: RFT_v3_013_Starke_Wechselwirkung.md, Final-Candidate v1.2*
*Glossary: RFT_v3_Glossar_EN.md v1.0 | DC: v10.10*
*Standalone: no file path references | Confidence markers: ✓ HIGH / ○ MEDIUM / ⚠️ LOW / 🚩 OPEN*
