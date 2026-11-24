# RFT_v3_Kepler — The Keplerian Geometry of Charge: Why Quarks Have Third-Integer Charges

**Version:** v1.0 (EN Translation)
**Status:** Draft (review pending)
**Author:** Franz Zollner / RFT Project
**Original (DE):** RFT_v3_Kepler_Ladungsgeometrie.md
**Translation:** AI Instance T-Kepler | 09.05.2026
**Language:** EN
**License:** Creative Commons BY-NC-ND 4.0
**Citation:** Franz Zollner (2026). *RFT_v3_Kepler: The Keplerian Geometry of Charge — Why Quarks Have Third-Integer Charges.* Resonance Field Theory Series, v3.0.

**Dependencies:**
- v3_001 (Mathematical Foundations): Master Equation, resonance mode classification
- v3_002 (Fine Structure Constant): α⁻¹ = 4π³ + π² + π as dimensional translator
- v3_005 (The Translator): π as translator between Cartesian and spherical
- v3_007 (Space Topology / 3D Emergence): Space topology, octahedron geometry
- v3_013 (Strong Interaction): Strong interaction, SU(3) geometrically, 120° proof, confinement

---

## Preface: Position in the v3 Series

This document stands **outside the numbered v3 series** (v3_001–v3_020), because it is a cross-cutting result: it connects the derivation of α (v3_002, Fine Structure Constant), the π-translator thesis (v3_005, The Translator), space topology (v3_007, Space Topology / 3D Emergence), and the strong interaction (v3_013, Strong Interaction) through a new geometric thread — **Kepler sphere packing**.

The catalyst was not an open RFT question but an **external image**: a Christmas lecture about stacking cannonballs (Kepler's conjecture, 1611). The connection to the resonance matrix arose spontaneously — and proved formally verifiable.

| Document | Contribution | Relevance to this chapter |
|---|---|---|
| v3_001 (Mathematical Foundations) | Master Equation | Framework |
| v3_002 (Fine Structure Constant) | α = 1/(4π³+π²+π) | ✓ Direct: dimensional translator as sphere packing frustration |
| v3_005 (The Translator) | π as translator Cartesian↔spherical | ✓ Direct: sphere-in-cube problem |
| v3_007 (Space Topology / 3D Emergence) | Space topology, 3D emergence, octahedron | ✓ Hourglass ↔ octahedron ↔ FCC packing |
| v3_013 (Strong Interaction) | Strong interaction, SU(3), 120° proof, confinement | ✓ Direct: SU(3) as projection |

**Core thesis:** Quark charges ±1/3 and ±2/3 are not free parameters of nature. They are the **coordinates of the Cartesian basis vectors, projected onto the plane perpendicular to the space diagonal**. This projection is a single 3×3 matrix — no free parameters, no postulates. From the same geometry follow the SU(3) symmetry (120° angles), confinement (zero sum), and the connection to the fine structure constant via the dimensional translator π.

---

## Abstract

The Standard Model postulates quark charges (±1/3, ±2/3) as empirical facts and SU(3) color symmetry as an abstract gauge group. Resonance Field Theory (RFT) derives both from the geometry of the resonance matrix.

The key is **Keplerian frustration**: in 3D space, spheres (spherical resonance modes = vortices) do not fit without gaps into a Cartesian lattice (resonance matrix). The densest sphere packing (FCC/HCP, Kepler 1611, Hales 2005) has a 26% gap and a kissing number of 12.

In this document we show:
1. The fine structure constant α⁻¹ = 4π³ + π² + π quantifies the sphere-cube incommensurability as a sum over all three dimensions.
2. Quark charges arise as **projections** of the three spatial axes onto the plane ⊥ (1,1,1) — the only non-trivial symmetry plane of the cubic lattice.
3. SU(3) symmetry is the rotational symmetry of this projection plane.
4. Confinement follows as an algebraic necessity: three 120° vectors sum to zero.
5. The fundamental length L₀ = (π/6)·l_P connects sphere packing, kissing number, and color angles through a single quantity.

**No free parameters. No postulates. Only geometry.**

---

## Table of Contents

1. [The Charge Problem](#1-the-charge-problem)
2. [Connection: α and the Dimensional Translators](#2-connection-α-and-the-dimensional-translators)
3. [Keplerian Frustration in 3D](#3-keplerian-frustration-in-3d)
4. [The Projection Matrix P⊥ — Formal Derivation](#4-the-projection-matrix-p-formal-derivation)
5. [Quark Charges as Emergent Geometry](#5-quark-charges-as-emergent-geometry)
6. [Irrational Space and SU(3)](#6-irrational-space-and-su3)
7. [Confinement as Geometric Necessity](#7-confinement-as-geometric-necessity)
8. [Connection to α, L₀, and the Kissing Number](#8-connection-to-α-l₀-and-the-kissing-number)
9. [Experimental Predictions and Testable Consequences](#9-experimental-predictions-and-testable-consequences)
10. [Open Questions and Honest Limitations](#10-open-questions-and-honest-limitations)
11. [Summary](#11-summary)

---

## 1. The Charge Problem

### 1.1 What the Standard Model Postulates

The Standard Model of particle physics recognizes the following electric charges:

| Particle | Charge | How determined? |
|---|---|---|
| u, c, t quarks | +2/3 | Empirically (scattering experiments) |
| d, s, b quarks | −1/3 | Empirically |
| Electron, muon, tau | −1 | Empirically |
| Neutrinos | 0 | Empirically |

In addition, quantum chromodynamics (QCD) postulates an **SU(3) color symmetry** — three "colors" (red, green, blue) whose weight vectors stand at 120° angles. No quark can be observed in isolation (confinement).

### 1.2 What the Standard Model Does NOT Explain

- **Why exactly 1/3 and 2/3?** The third-integer charges are input values, not consequences.
- **Why exactly 3 colors?** The number 3 is a postulate (SU(3) rather than SU(N)).
- **Why 120°?** The angle follows from the Lie algebra of SU(3), but why SU(3)?
- **Why confinement?** It is simulated and confirmed in Lattice QCD, but the mechanism remains opaque.

### 1.3 The RFT Thesis

The resonance matrix has three fundamental directions (x, y, z). Vortices (quarks) couple to space through anchor points (AP). **Electric charge is not fundamental — it is emergent.** It arises as a geometric consequence of the coupling between vortex and resonance matrix.

---

## 2. Connection: α and the Dimensional Translators

In v3_002 (Fine Structure Constant) it is shown:

$$\alpha^{-1} = 4\pi^3 + \pi^2 + \pi = 137.036\,304...$$

The three terms are **dimensional translators** — they quantify how a spherical volume (vortex) fits into a Cartesian grid (resonance matrix):

| Term | Dimension | Geometric meaning |
|---|---|---|
| π | 1D | Circumference / diameter of a circle |
| π² | 2D | Circle area / square area (ratio ≈ 0.785) |
| 4π³ | 3D | Sphere volume / cube volume (prefactor from 4/3·π·r³) |

**The fine structure constant measures the total geometric frustration of space** — the impossibility of fitting spherical vortices exactly into a Cartesian grid.

In v3_005 (The Translator), π is identified as the "translator between Cartesian and spherical":

> *"π is not merely a number — it is the translator between Cartesian and spherical volumes."* — Franz Zollner

This document shows that **the same π also determines quark charges**.

---

## 3. Keplerian Frustration in 3D

### 3.1 Sphere Packing: 2D vs. 3D

Johannes Kepler conjectured in 1611 that the densest sphere packing in 3D is the **face-centered cubic** (FCC) or **hexagonal close-packed** (HCP) arrangement. Thomas Hales proved this in 2005 through computer-assisted verification.

**In 2D:** Six circles touch a central circle **without a gap** (hexagonal lattice). Kissing number = 6. Packing density = π/(2√3) ≈ 90.7%. **Perfect, frustration-free.**

**In 3D:** Twelve spheres touch a central sphere, but they do **not fill space without gaps**. Kissing number = 12. Packing density η = π/(3√2) ≈ 74.0%. **26% gap — geometric frustration.**

### 3.2 What the Gap Means

The 26% gap is not a technical weakness of the packing — it is a **fundamental property of 3D space**. Spheres and cubes are incommensurable in 3D: one cannot simultaneously fill a space perfectly spherically AND perfectly Cartesian-ly.

In RFT this is physically relevant: **vortices (quarks, leptons) are spherical resonance modes. The resonance matrix is a Cartesian structure.** The frustration between the two is not a defect — it is the source of α and, as we now show, also of charge quantization.

---

## 4. The Projection Matrix P⊥ — Formal Derivation

### 4.1 The Space Diagonal as Symmetry Axis

A cubic lattice has a distinguished direction: the **space diagonal** (1,1,1), which treats all three axes equally. The normalized vector is:

$$\hat{n} = \frac{1}{\sqrt{3}} \begin{pmatrix} 1 \\ 1 \\ 1 \end{pmatrix}$$

### 4.2 Decomposition: Parallel and Perpendicular to the Diagonal

Every vector **v** in 3D can be decomposed into two components:

- **Parallel** to the diagonal: v_∥ = (v · n̂) · n̂
- **Perpendicular** to the diagonal: v_⊥ = v − v_∥

The perpendicular plane ⊥ (1,1,1) is a **2D subspace** in which all three spatial axes appear symmetrically — no axis is preferred.

### 4.3 The Projection Matrix

The projection onto the plane ⊥ (1,1,1) is described by the matrix:

$$P_\perp = I - \hat{n} \otimes \hat{n} = I - \frac{1}{3} J$$

where **I** is the 3×3 identity matrix and **J** is the 3×3 all-ones matrix (all entries = 1).

Explicitly:

$$P_\perp = \begin{pmatrix} 2/3 & -1/3 & -1/3 \\ -1/3 & 2/3 & -1/3 \\ -1/3 & -1/3 & 2/3 \end{pmatrix}$$

**This matrix has no free parameters.** It follows exclusively from the geometry of a cubic lattice and its space diagonal.

### 4.4 Verification

```
P_⊥ is symmetric:    P_⊥ᵀ = P_⊥              ✓
P_⊥ is idempotent:   P_⊥² = P_⊥              ✓ (projection)
P_⊥ has trace 2:     Tr(P_⊥) = 2             ✓ (2D subspace)
P_⊥ · n̂ = 0:         diagonal is annihilated  ✓
```

---

## 5. Quark Charges as Emergent Geometry

### 5.1 Projection of the Cartesian Basis Vectors

Applying P_⊥ to the three unit vectors of the Cartesian lattice:

$$P_\perp \cdot \begin{pmatrix} 1 \\ 0 \\ 0 \end{pmatrix} = \begin{pmatrix} +2/3 \\ -1/3 \\ -1/3 \end{pmatrix}$$

$$P_\perp \cdot \begin{pmatrix} 0 \\ 1 \\ 0 \end{pmatrix} = \begin{pmatrix} -1/3 \\ +2/3 \\ -1/3 \end{pmatrix}$$

$$P_\perp \cdot \begin{pmatrix} 0 \\ 0 \\ 1 \end{pmatrix} = \begin{pmatrix} -1/3 \\ -1/3 \\ +2/3 \end{pmatrix}$$

### 5.2 Interpretation: Charge = Dominant Projection

In the RFT interpretation:
- Each Cartesian axis represents a **color direction** (red, green, blue)
- The **dominant component** of each projected vector (+2/3) corresponds to the charge of u/c/t quarks
- The **recessive components** (−1/3) correspond to the charge of d/s/b quarks
- The full Cartesian length (+1) corresponds to the lepton charge
- The projection of the diagonal itself (0) corresponds to the neutrino

### 5.3 Complete Charge Assignment

| Configuration | Projection | Charge | Particle type |
|---|---|---|---|
| Single axis (dominant) | +2/3 | +2/3 | u, c, t quarks |
| Single axis (recessive) | −1/3 | −1/3 | d, s, b quarks |
| Full lattice length | +1 = 3/3 | +1 | Electron (e⁻), muon, tau |
| Space diagonal (symmetric) | 0 | 0 | Neutrino |

### 5.4 Why This Is Not Retro-Fitting

The matrix P_⊥ was **not** constructed to deliver the values 1/3 and 2/3. It is the **unique** projection matrix onto the plane ⊥ (1,1,1) in a cubic lattice. The values 1/3 and 2/3 follow as a consequence of the fact that the space diagonal of a cube projects equally in all three directions — and 1 − 1/3 = 2/3. The third-integer division is an **arithmetic necessity of three equivalent axes**, not a built-in parameter.

---

## 6. Irrational Space and SU(3)

### 6.1 Franz Zollner's Geometric Insight

Franz Zollner described in discussions (2025) an "irrational space":

> *"The color charges are n/3 charges. The quarks form a 3D structure that lies obliquely to space. Through a central crossing point with the spatial axes, a 1/3 – 2/3 division of length 1 arises. The irrational space is a displaced space, whose directions stand at 60° or 120° to the space."* — Franz Zollner

### 6.2 Formal Confirmation: 120° Exactly

The three projected vectors p₁, p₂, p₃ (from section 5.1) lie in the 2D plane ⊥ (1,1,1) and have the mutual angle:

$$\cos\theta = \frac{p_i \cdot p_j}{|p_i| \cdot |p_j|} = \frac{-1/3}{2/3} = -\frac{1}{2}$$

$$\theta = \arccos\left(-\frac{1}{2}\right) = 120°$$

**Exactly 120° — the SU(3) weight vector angle.** The hexagonal lattice of the SU(3) Lie algebra is the projection of the cubic lattice onto the plane ⊥ (1,1,1).

### 6.3 SU(3) Is Not an Abstract Symmetry

In standard QCD, SU(3) is postulated as an abstract gauge group. In RFT, SU(3) is **the rotational symmetry of the projection plane** — the plane ⊥ (1,1,1) in the cubic lattice. The three color directions stand at 120°, because three equivalent axes projected onto a 2D plane produce exactly these angles.

| Standard QCD | RFT |
|---|---|
| SU(3) as postulate | SU(3) as projection of a cube |
| 3 colors (postulated) | 3 spatial axes (given) |
| 120° from Lie algebra | 120° from projection angle |
| Why SU(3)? — no answer | Because space is 3D |

**Limitation (✓ HIGH for discrete structure; ○ MEDIUM for full continuous symmetry):** The projection matrix P_⊥ delivers the **discrete** structure of SU(3) (the weight vectors and their angles). The transition to the full **continuous** SU(3) gauge symmetry additionally requires a continuum limit of the resonance matrix. This is implicit in RFT (the resonance matrix has a fundamental length L₀, but appears as a continuum on macroscopic scales), but has not yet been fully worked out formally (cf. DeepSeek review, question 3).

---

## 7. Confinement as Geometric Necessity

### 7.1 Color Neutrality = Zero Sum

The sum of all three projected vectors is:

$$p_1 + p_2 + p_3 = \begin{pmatrix} 2/3 \\ -1/3 \\ -1/3 \end{pmatrix} + \begin{pmatrix} -1/3 \\ 2/3 \\ -1/3 \end{pmatrix} + \begin{pmatrix} -1/3 \\ -1/3 \\ 2/3 \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix}$$

**Three quarks of different colors yield exactly the zero vector.** This is color neutrality — the condition for a bound hadron.

### 7.2 Why Isolation Is Impossible

A single projected vector (e.g. (+2/3, −1/3, −1/3)) has a **net direction** in the projection plane. It points in a specific direction. Only the combination of three 120° vectors cancels this direction. **An isolated quark would have a residual direction in charge space — which is not stable in the resonance matrix.**

In RFT language: A single vortex coupling to only one axis creates an asymmetric tension in the resonance matrix. Only three vortices (one per axis) compensate each other and produce a stable, tension-free state.

### 7.3 Comparison with Lattice QCD

Lattice QCD (Wilson, 1974) simulates confinement on a discrete lattice and finds: the quark-antiquark potential rises linearly with distance (linear confinement). RFT provides a **geometric justification**: the three directions of the cubic lattice enforce triplet combinations for tension-free states.

---

## 8. Connection to α, L₀, and the Kissing Number

### 8.1 The Fundamental Length as Phase Step

The RFT fundamental length is L₀ = (π/6)·l_P. The value π/6 appears as a natural phase step:

| Multiplier | × π/6 | Result | Meaning |
|---|---|---|---|
| 3 (spatial axes) | π/2 | 90° | Cartesian orthogonality |
| 4 (tetrahedron vertices) | 2π/3 | **120°** | **SU(3) angle = color angle** |
| 6 (2D kissing) | π | 180° | Half-revolution |
| 12 (3D kissing) | 2π | **360°** | **Closed phase cycle** |

The **kissing number 12** is the condition that 12 phase steps of π/6 yield a closed cycle: 12 = 2π/(π/6). The **tetrahedron vertex count 4** generates the color angle: 4 × π/6 = 120°.

### 8.2 Why Everything Depends on π/6

| Quantity | Formula | Contains π/6 |
|---|---|---|
| Fundamental length | L₀ = (π/6)·l_P | directly |
| Kissing number | 12 = 2π / (π/6) | as phase condition |
| Color angle | 120° = 4 × (π/6) × (180°/π) | as multiple |
| α⁻¹ (indirectly) | 4π³+π²+π = π(4π²+π+1) | π as factor |

### 8.3 What This Does NOT Mean

The sphere packing frustration (1−η ≈ 0.2595) is **not algebraically** connected to α⁻¹. DeepSeek formally showed (April 2026): π and √2 are algebraically independent over ℚ. An equation α⁻¹ = f(1−η) with algebraic f does not exist.

The connection exists not through a formula, but through a **common geometric source**: the incommensurability of sphere and cube.

---

## 9. Experimental Predictions and Testable Consequences

### 9.1 Direct Predictions

**P1: Charge quantization is exactly 1/3.**
The projection delivers exactly 1/3 and 2/3 — no deviations at higher order. This is consistent with experimental observation (no quark charge anomalies known). **Status: consistent with experiment. (Confidence: ✓ HIGH)**

**P2: No fourth color.**
The projection of a 3D lattice onto the plane ⊥ (1,1,1) generates exactly three equivalent directions. A "fourth color" is geometrically impossible (the plane is 2D; at most 3 symmetric vectors at 120°). **Status: consistent with experiment. (Confidence: ✓ HIGH)**

**P3: Confinement is absolute.**
The zero-sum condition is exact, not approximate. No mechanism can isolate a single quark without breaking the resonance matrix symmetry. **Status: consistent with Lattice QCD simulations. (Confidence: ✓ HIGH)**

### 9.2 Indirect / Difficult-to-Test Predictions

**P4: Mass differences between u/c/t and d/s/b.**
The projection gives charges, not masses. The mass would have to follow from the resonance frequency of the respective vortex mode. **Status: hypothesis. (Confidence: ⚠️ LOW)**

**P5: Space has a preferred diagonal.**
If the projection onto (1,1,1) is physically real, there should be on cosmological scales a weak anisotropy — a "preferred direction" of the vacuum. This is experimentally testable (CMB anomalies at low multipoles, "Axis of Evil"?). **Status: speculative. (Confidence: ⚠️ LOW)**

---

## 10. Open Questions and Honest Limitations

### 10.1 Formally Open

| # | Question | Confidence of resolution |
|---|---|---|
| O1 | Can the charge projection be **formally derived from the Master Equation**? (The transition vortex–AP coupling → P_⊥ → charge is conceptual, not formal.) | 🚩 OPEN |
| O2 | How does the **full continuous SU(3)** gauge symmetry arise from the discrete projection? (Continuum limit needed.) | ○ MEDIUM (DeepSeek: partial) |
| O3 | Why does nature choose the diagonal (1,1,1) as projection axis? (Symmetry argument: it is the only direction that treats all three axes equally. But: is this physically compelling?) | ○ MEDIUM (plausible) |
| O4 | Mass spectrum: Why are u/c/t heavier than d/s/b? The projection gives charges, not masses. | 🚩 OPEN |

### 10.2 What Has Been Clarified

- ✅ Quark charges ±1/3, ±2/3 are geometrically derivable (exact)
- ✅ SU(3) angle 120° follows from the projection (exact)
- ✅ Confinement is an algebraic necessity (exact)
- ✅ Neutrino charge 0 and lepton charge ±1 are consistent
- ✅ DeepSeek review confirms algebraic structure (April 2026)
- ✅ 12×(1−η) ≈ π is a coincidence, not an identity (verified)

### 10.3 What Is Not Claimed

This document does NOT claim:
- That the sphere packing frustration is algebraically connected to α (disproved)
- That the full SU(3) gauge symmetry follows without additional assumptions (partially open)
- That the quark mass hierarchy follows from the projection (open)

---

## 11. Summary

### 11.1 The Central Derivation in One Sentence

> **Quark charges ±1/3 and ±2/3 are the coordinates of the Cartesian basis vectors, projected onto the plane perpendicular to the space diagonal (1,1,1).**

### 11.2 The Formula

$$P_\perp = I - \frac{1}{3}J, \qquad q_i = \text{dom}(P_\perp \cdot \hat{e}_i)$$

### 11.3 What RFT Gains from This

| Before (v3_001–v3_014) | Now (this document) |
|---|---|
| α from π-geometry | α AND charges from the same geometry |
| SU(3) as goal (v3_013: "geometrically") | SU(3) as projection: 120° exactly derived |
| Confinement as thesis | Confinement as zero-sum identity: proved |
| Color charges as postulate | Color charges as spatial-axis projection: proved |

### 11.4 The Connection to the Development

The derivation arose on 21.04.2026 from the connection between a Christmas lecture (cannonballs/Kepler) and Franz Zollner's discussions about "irrational space" (2025). The Master Equation was **not changed**. The charge geometry is a consequence of space — not of the equation.

---

## References

1. Weitz, M. (2019). *Christmas Lecture 2019: Sphere Packings and Kepler's Conjecture.* HAW Hamburg. YouTube: https://youtu.be/C2s9mDQYxo4 — Primary source for the cannonball/Kepler connection in this document (origination 2026-04-21).
2. Kepler, J. (1611). *Strena seu de nive sexangula.* — Kepler's conjecture.
3. Hales, T. (2005). *A proof of the Kepler conjecture.* Annals of Mathematics.
4. Zollner, F. (2026). *v3_002 (Fine Structure Constant): α from shell integral.* RFT v3 Series.
5. Zollner, F. (2026). *v3_005 (The Translator): π as dimensional bridge.* RFT v3 Series.
6. Zollner, F. (2026). *v3_013 (Strong Interaction): SU(3) geometrically.* RFT v3 Series.
7. Wilson, K. (1974). *Confinement of quarks.* Physical Review D.
8. DeepSeek verification (2026-04-21). *Return package sphere packing/α/color charges.* Session protocol, RFT-VDB.

---

**© 2026 Franz Zollner — Resonance Field Theory (RFT)**
**License:** Creative Commons BY-NC-ND 4.0
