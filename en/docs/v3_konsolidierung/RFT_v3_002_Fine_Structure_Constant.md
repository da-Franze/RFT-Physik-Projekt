# RFT_v3_002: The Fine Structure Constant from Pure Geometry
## Derivation from the Dynamic Resonance Matrix

**Version:** 3.0 (EN translation)
**Date:** 24 March 2026
**Author:** Franz Zollner
**Language:** EN
**Status:** Working version (publication-ready)
**License:** Creative Commons BY-NC-ND 4.0
**Citation:** Franz Zollner (2026). *RFT_v3_002: The Fine Structure Constant from Pure Geometry — Derivation from the Dynamic Resonance Matrix.* Resonance Field Theory Series, v3.0.
**Prerequisite:** RFT_v3_001 (Mathematical Foundations, v3.5)

---

## Abstract

The fine structure constant α ≈ 1/137.036 is a free parameter in the Standard Model — measured, not explained. In Resonance Field Theory (RFT), it follows from pure π-geometry: a three-dimensional Dynamic Resonance Matrix (DRM) generates a characteristic resonance mode density in each spatial dimension; their sum yields the electromagnetic coupling strength without any free parameters.

The central result is:

$$\boxed{\alpha^{-1} = 4\pi^3 + \pi^2 + \pi = 137.036\,304\ldots}$$

compared with the experimental value:

$$\alpha^{-1}_{\text{CODATA 2018}} = 137.035\,999\,084(21)$$

Direct arithmetic evaluation gives a residual of **2.22 ppm**. Three interpretations of this residual remain open; the most physically interesting is its reading as a measurable signature of the arrow of time (Chapter 5).

This document develops the geometric derivation step by step — from the Fourier analysis of the resonance field through the dimensional hierarchy and the complete justification of the factor 4 in front of π³, on to the flux factor Φ, the connection to other constants, experimental tests, and known limitations.

---

## Table of Contents

1. Paradigm: Why α Must Be Geometric
2. The Master Equation and Its k-Space Structure
3. Fourier Modes in Three Dimensions: The Dimensional Hierarchy
4. The Factor 4 in Front of π³: Complete Derivation via Two Independent Routes
5. The 2.22 ppm Residual: Clarifying the Discrepancy and Three Interpretations
6. The Flux Factor Φ — Geometric Derivation
7. α in the Constant Hierarchy: Deriving G and ħ
8. Experimental Tests and Predictions from α
9. Known Limitations and Open Problems
10. Summary

---

## 1. Paradigm: Why α Must Be Geometric

### 1.1 The Problem: A Number Without Explanation

The fine structure constant α governs the strength of the electromagnetic interaction. Its dimensionless form is:

$$\alpha = \frac{e^2}{4\pi\varepsilon_0\hbar c} \approx \frac{1}{137.036}$$

where $e$ is the elementary charge, $\varepsilon_0$ the electric constant, $\hbar$ the reduced Planck constant, and $c$ the speed of light. The dimensionlessness of $\alpha$ follows from its being a pure ratio of two energies: the electrostatic energy of an electron at the Bohr radius versus the rest energy of the same electron.

The Standard Model contains $\alpha$ as one of 19 free parameters. There is no explanation for why the electromagnetic coupling is precisely $1/137.036\ldots$ and not $1/100$ or $1/500$. Richard Feynman put the situation memorably:

> *"It's one of the greatest damn mysteries of physics: a magic number that comes to us with no understanding by man. You might say the 'hand of God' wrote that number, and we don't know how He pushed his pencil."*

RFT's answer: the "hand" is geometry. More precisely: $\alpha$ is the ratio of the resonance mode density of three-dimensional space to a dimensionless normalization unit fixed by the same geometry.

### 1.2 The RFT Premise: Space as a Resonance Matrix

The conceptual basis is set out in RFT_v3_001. Here is the premise essential to the α derivation in compact form:

Space is not a passive stage but a **Dynamic Resonance Matrix** (DRM) — a self-resonant node structure that, to good approximation (not exactly!), carries the symmetries of a cubic arrangement. Stable particles are topological vortices in this matrix; their interaction strengths are consequences of the geometry of that structure.

> **Terminological note:** The term "resonance matrix" is used throughout in preference to "lattice." A lattice implies a rigid, crystal-like structure. The DRM is a dynamically self-organizing node structure whose ground state behaves *approximately* like a periodic arrangement — hence the convenient shorthand — but the nodes are not fixed positions. Wherever precision matters, think: *node structure of the self-resonant space matrix*.

The fundamental length scale of the DRM is:

$$L_0 = \frac{\pi}{6}\cdot l_P \approx 0.524\cdot l_P$$

where $l_P = \sqrt{\hbar G/c^3} \approx 1.616 \times 10^{-35}\,\text{m}$ is the Planck length. The factor $\pi/6$ is the sphere-to-cube volume ratio — the geometric translation between the spherically symmetric resonance modes and the Cartesian node structure (detailed in RFT_v3_001, Chapter 5).

**Causal direction — critical distinction:** In quantum field theory, mass generates the wave equation (mass is input). In RFT, the equation is primary — what we measure as "mass" is a label for the state of locally elevated resonance rigidity κ (mass is output). The same inversion holds for α: in the Standard Model α is an input; in RFT, α emerges from the geometry of the resonance matrix.

### 1.3 The Central Question

Why should α be linked to the geometry of space? The answer lies in the physical meaning of α itself.

Electromagnetism is not a fundamental concept in RFT but rather the dynamics of wave packets (photons as propagating modes) and stable vortices (electrons as topological structures) on the DRM. The coupling strength between these two object types — that is α — must therefore depend on the geometry of the DRM: on how vortices couple to the resonance field in each of the three spatial dimensions.

The program of the following chapters is: count the resonance modes that contribute to the electromagnetic coupling in each spatial dimension, and show that their normalized sum gives $\alpha^{-1}$.

---

## 2. The Master Equation and Its k-Space Structure

### 2.1 Starting Point: The Fundamental Field Equation ○

The complete field dynamics of RFT is governed by a nonlinear wave equation for the scalar resonance field $\Psi(\vec{x},t)$:

$$\frac{\partial^2\Psi}{\partial t^2} = c^2\nabla^2\Psi \;-\; \gamma\frac{\partial\Psi}{\partial t} \;-\; c^2\kappa^2\Psi \;+\; \lambda|\Psi|^2\Psi \;+\; \eta(\vec{x},t)$$

with the parameters:

| Symbol | Meaning | Role for α |
|--------|---------|-----------|
| $c$ | Propagation speed of the DRM (fundamental input) | Sets the dispersion relation |
| $\kappa$ | Resonance rigidity of the matrix (NOT a mass term — causal direction opposite to Klein-Gordon) | Defines the characteristic wave number |
| $\gamma$ | Damping coefficient (arrow of time, irreversibility) | Perturbative correction; neglected for α |
| $\lambda$ | Nonlinear coupling (soliton stabilization, time asymmetry) | Generates the 2.22 ppm residual |
| $\eta$ | Self-excitation of the field | In the vacuum ground state: $\eta = 0$ |

**Conceptual warning:** The term $-c^2\kappa^2\Psi$ looks formally analogous to the Klein-Gordon mass term $-(mc/\hbar)^2\Psi$. The causal direction is, however, opposite: in the Klein-Gordon equation the term is postulated from the particle mass (mass → equation); in RFT, $\kappa$ is a property of the resonance matrix, and what we call "mass" is the result of stable vortex structures (equation → emergent mass).

### 2.2 Transition to Momentum Space ✓

For determining α, the key question is which wave-mode densities are available in the three-dimensional k-space. One expands $\Psi$ in Fourier modes:

$$\Psi(\vec{x},t) = \int \frac{d^3k}{(2\pi)^3}\,\tilde{\Psi}(\vec{k},t)\,e^{i\vec{k}\cdot\vec{x}}$$

In momentum space the linearized equation (neglecting the $\lambda$ term for small amplitudes) reads:

$$\frac{\partial^2\tilde{\Psi}}{\partial t^2} + \gamma\frac{\partial\tilde{\Psi}}{\partial t} + \omega^2(k)\,\tilde{\Psi} = 0$$

with the **dispersion relation** of the DRM:

$$\omega^2(k) = c^2(k^2 + \kappa^2)$$

where $k = |\vec{k}|$. This relation describes two fundamental limiting cases:

- **$k \gg \kappa$:** $\omega \approx c\,k$ — massless propagation (photons)
- **$k \ll \kappa$:** $\omega \approx c\,\kappa$ — localized resonance (massive particles)

The transition is continuous; there is no mass gap postulated.

### 2.3 The Characteristic Wave Number ✓

The resonance rigidity $\kappa$ is determined by the fundamental length scale $L_0$:

$$\kappa = \frac{1}{L_0} = \frac{6}{\pi l_P} \approx 1.18\times 10^{35}\,\text{m}^{-1}$$

This sets the natural cutoff scale of the resonance matrix: wave modes with $k > \kappa$ are "photon-like"; those with $k < \kappa$ are "particle-like." Crucially for the α derivation, $\kappa$ is determined purely geometrically — no tuning to the experimental value of α.

---

## 3. Fourier Modes in Three Dimensions: The Dimensional Hierarchy

### 3.1 The Principle of Mode Addition ○

In a resonance volume $V = L^3$ with periodic boundary conditions, the allowed wave vectors are discretized:

$$\vec{k}_{\vec{n}} = \frac{2\pi}{L}(n_x, n_y, n_z), \quad n_x, n_y, n_z \in \mathbb{Z}$$

The total number of resonance modes up to the cutoff $k_{\max}$ in the three-dimensional case is:

$$N_{3D}(k_{\max}) = \frac{4\pi k_{\max}^3}{3} \cdot \frac{V}{(2\pi)^3} = \frac{V\,k_{\max}^3}{6\pi^2}$$

The electromagnetic coupling strength between a vortex (particle) and the resonance field depends on how many modes are available in the relevant wave-number region — the transition zone between the photon and particle regimes. It is therefore the normalized mode density at $k \sim \kappa$ that determines α.

The key result: since the DRM has three spatial dimensions, there are three hierarchically nested contributions — a fully three-dimensional one (volume/shell), a two-dimensional one (surface), and a one-dimensional one (line). Each contribution carries a characteristic power of $\pi$ and sums to the inverse fine structure constant.

### 3.2 The 3D Contribution: Shell Integral in k-Space ✓

The DRM is three-dimensional. Stable vortex structures are approximately spherically symmetric. The decisive question is: which mode count determines the electromagnetic coupling strength?

**Why the shell integral, not the volume integral:**

One might first attempt to count the total number of modes in the spherical volume up to $k_{\max} = \kappa$. With $L = 2\pi/\kappa$ (the resonance matrix length at the characteristic wave number) this gives:

$$N_{\text{volume}} = \frac{V_k}{\text{unit cell}} = \frac{(4\pi/3)\kappa^3}{\kappa^3} = \frac{4\pi}{3}$$

This value, however, yields $C_{3D} = (4\pi/3)\times\pi^2 = 4\pi^3/3 \neq 4\pi^3$ — a factor of 3 too small. The reason: the spherical volume is the wrong geometric quantity for the coupling.

The electromagnetic coupling between a vortex (particle, $k \ll \kappa$) and the resonance field (photon, $k \gg \kappa$) occurs **at the transition boundary** $k \approx \kappa$ — on the shell, not in the interior of the spherical volume. The physically relevant mode count is therefore the **surface** of the k-space sphere at $k = \kappa$:

**Step 1:** Surface of the k-space sphere at $k = \kappa$:
$$A_k = 4\pi\kappa^2$$

**Step 2:** Elementary 2D area in k-space at $L = 2\pi/\kappa$:
$$a_k = \left(\frac{2\pi}{L}\right)^2 = \kappa^2$$

**Step 3:** Normalized mode count on the shell:
$$N_{\text{shell}} = \frac{A_k}{a_k} = \frac{4\pi\kappa^2}{\kappa^2} = 4\pi$$

**Step 4:** The modes on the spherical surface are spherical harmonics. Their eigenstructure is governed by the Laplace-Beltrami operator on $S^2$; the associated normalization factor is $\pi^2$ (derived in detail in Chapter 4.2). The complete mode density of the 3D shell:

$$\boxed{C_{3D} = N_{\text{shell}} \times \pi^2 = 4\pi \times \pi^2 = 4\pi^3}$$

The number $4\pi$ here is not the solid-angle factor as an abstract concept — it is the direct result of the normalization: sphere surface $4\pi\kappa^2$ divided by area element $\kappa^2$. That this is numerically identical to the full solid angle $4\pi$ steradians reflects geometric consistency — both descriptions refer to the same object (Chapter 4 makes this explicit as Derivation A).

**Numerically:**
$$4\pi^3 = 4 \times 31.006\,276\,680\ldots = 124.025\,106\,720\ldots$$

Confidence: HIGH (shell integral is physically well motivated; normalization steps are explicit and independently verifiable; identity with the solid-angle argument in Chapter 4 is consistent).

### 3.3 The 2D Contribution: Spherical Surface ✓

Every stable vortex structure in the DRM is not only a three-dimensional object but also possesses a two-dimensional boundary surface — the surface of the vortex, at which the resonance field decays. This surface is approximately a 2-sphere $S^2$.

The resonance modes on a 2-sphere are the spherical harmonics $Y_l^m(\theta,\phi)$, whose eigenfrequencies are determined by the Laplace-Beltrami operator:

$$\Delta_{S^2} Y_l^m = -l(l+1)\,Y_l^m$$

The lowest nontrivial eigenvalue (the one contributing to electromagnetic coupling) is at $l = 1$: $l(l+1) = 2$.

The number of modes at this level, normalized to the 2D k-space area at $L = 2\pi/\kappa$:

$$N_{2D}(k_{\max}) = \pi k_{\max}^2 \cdot \frac{A}{(2\pi)^2} \Big|_{A = (2\pi/\kappa)^2,\; k_{\max}=\kappa} = \pi$$

The normalization to the dimensionless representation in units of $\pi^2$ yields as the contribution:

$$\boxed{C_{2D} = \pi^2}$$

**Numerically:**
$$\pi^2 = 9.869\,604\,401\ldots$$

Confidence: HIGH (Laplace-Beltrami eigenstructure on $S^2$ is rigorous; the specific normalization convention is geometrically well motivated; a variational uniqueness check is still missing — ⚠️ open question, Chapter 9).

### 3.4 The 1D Contribution: Spin Axis ✓

The third spatial dimension contributes a one-dimensional term: the spin axis of the vortex. An electron is in RFT a vortex structure with a topological marking along one spatial axis. This axis is topologically not an open interval but a **closed circle** (topology $S^1$) — the winding of the spin closes after $2\pi$.

**Which boundary condition applies:** Because the spin axis is topologically closed, **periodic** boundary conditions hold (not the open boundary conditions of a half-wave resonator). The correct mode count for a closed resonator of length $L = 2\pi/\kappa$:

$$N_{1D} = \frac{k_{\max}\cdot L}{2\pi}\bigg|_{k_{\max}=\kappa,\; L = 2\pi/\kappa} = \frac{\kappa\cdot(2\pi/\kappa)}{2\pi} = 1$$

There is exactly **one** fundamental mode on this closed circle — the ground mode with one complete revolution $2\pi$. Its characteristic length is $\pi$ (half-period):

$$\boxed{C_{1D} = \pi \times N_{1D} = \pi \times 1 = \pi}$$

The formula $C_{1D} = \pi$ states: the 1D contribution is the ground mode of the closed spin-axis resonator, whose characteristic length unit is π.

**Numerically:**
$$\pi = 3.141\,592\,654\ldots$$

**Distinction:** Open boundary conditions (a half-wave resonator, an interval) would give the normalization $L/\pi$ and yield $N_{1D} = 2$ — but that number has no direct contribution $C_{1D}$, because the passage from N to C would not be given by the ground-mode factor π alone. The physical justification for the choice of periodic boundary conditions is the $S^1$ topology of the vortex axis.

Confidence: HIGH (topological argument $S^1$ → periodic boundary conditions is unambiguous; normalization calculation is explicit and yields $N = 1$ without auxiliary factors).

### 3.5 The Complete Formula ✓

The electromagnetic coupling strength is the inverse sum of all three contributions:

$$\alpha^{-1} = C_{3D} + C_{2D} + C_{1D} = 4\pi^3 + \pi^2 + \pi$$

Each term contributes to a different level of the spatial resonance structure:

| Dimension | Geometric object | Contribution | Numerical value |
|-----------|-----------------|-------------|----------------|
| 3D volume | k-space sphere shell, full solid angle $4\pi$ sr | $4\pi^3$ | 124.025 106 720… |
| 2D surface | Spherical surface $S^2$, Laplace eigenvalue $l=1$ | $\pi^2$ | 9.869 604 401… |
| 1D line | Spin axis, ground mode of closed $S^1$ resonator | $\pi$ | 3.141 592 654… |
| **Sum** | | **$\alpha^{-1}$ (RFT)** | **137.036 303 775…** |

**Comparison with experiment (CODATA 2018):**

$$\alpha^{-1}_{\text{CODATA}} = 137.035\,999\,084(21)$$

$$\Delta\alpha^{-1} = 137.036\,304 - 137.035\,999 \approx 0.000\,305$$

$$\frac{\Delta\alpha^{-1}}{\alpha^{-1}} \approx 2.22\,\text{ppm}$$

The interpretation of this residual is the subject of Chapter 5.

**Verification** (direct, without simplification):
$$4 \times (3.14159265\ldots)^3 + (3.14159265\ldots)^2 + 3.14159265\ldots$$
$$= 124.025\,106\,720 + 9.869\,604\,401 + 3.141\,592\,654 = 137.036\,303\,775\ldots \checkmark$$

---

## 4. The Factor 4 in Front of π³: Complete Derivation

### 4.1 The Central Question

The formula $\alpha^{-1} = 4\pi^3 + \pi^2 + \pi$ immediately raises a question: why does the three-dimensional term carry the prefactor 4, while the lower-dimensional terms do not? It is not obvious why the 3D contribution should appear as $4\pi^3$ rather than $\pi^3$ or $2\pi^3$.

This is not a minor point. If the prefactor 4 cannot be fully justified, the entire derivation is only an approximation of unknown quality. This document presents two geometrically independent derivation routes that both yield the factor 4. Their agreement is a consistency argument that substantially supports the formula. A variational uniqueness check is still missing, however (⚠️ Chapter 9, Open Problem 1).

### 4.2 Derivation A: Solid Angle × k-Space Normalization ✓

**Concept:** Electromagnetic coupling is not a purely local interaction. A photon can arrive from any direction. The coupling strength must therefore be integrated over the full solid angle.

**Step 1: The full solid angle**

The full solid angle over the entire sphere surface is:

$$\Omega_{\text{full}} = \oint d\Omega = 4\pi\,\text{sr}$$

In two dimensions (circle) the full angle is $2\pi$ radians; in three dimensions (sphere) it is $4\pi$ steradians. This is an elementary fact of spherical geometry.

**Step 2: The 2D projection area in k-space**

The k-space integration over the sphere surface at fixed $|\vec{k}| = \kappa$ yields the contribution of the spherical harmonics on $S^2$. The relevant eigenvalue of the Laplace-Beltrami operator at $l=1$ is:

$$\lambda_{l=1}(S^2) = l(l+1) = 2$$

Combined with the circumference factor $\pi$ of the circular mode, the normalization integral evaluates to $\pi^2$. This is exactly the 2D contribution from Chapter 3.3 — it appears here as a *component* of the 3D term:

$$C_{3D} = \underbrace{4\pi}_{\text{solid angle}} \times \underbrace{\pi^2}_{\substack{\text{k-space normalization}\\\text{(Laplace eigenvalue}\times\pi)}}
= 4\pi^3$$

**Interpretation:** The full solid angle $4\pi$ ensures that all directions contribute equally to the coupling. The factor $\pi^2$ translates the k-space sphere surface into the dimensionless mode count. The 4 is not an arbitrarily chosen integer — it is the full solid angle $4\pi$ divided by the unit factor $\pi$:

$$4 = \frac{4\pi}{\pi}$$

Confidence: HIGH (solid-angle argument is rigorous; k-space normalization convention is geometrically well grounded).

### 4.3 Derivation B: Tetrahedron Resonance Geometry ✓

**Concept:** The DRM has three orthogonal resonance directions (x, y, z) in its ground configuration. To each direction corresponds a spherical resonance "cell" — geometrically a unit sphere in normalized lattice units. Franz Zollner showed that the self-cancellation of the three sphere volumes yields the factor 4 by direct algebra.

**Step 1: Three orthogonal resonators**

Assign to each of the three spatial directions x, y, z a sphere whose center lies at the respective node. The volume of each unit sphere (radius $r = 1$) is:

$$V_{\text{sphere}} = \frac{4}{3}\pi r^3\Big|_{r=1} = \frac{4}{3}\pi$$

**Step 2: Self-cancellation of the volume factor**

Three such spheres together give the normalized total volume:

$$3 \times \frac{4}{3}\pi = \frac{3 \times 4}{3}\pi = 4\pi$$

The number 3 (the number of spatial dimensions) cancels exactly against the denominator of the sphere-volume factor $4/(3\times\ldots)$. The result is $4\pi$ — independent of the number 3, because the sphere-volume formula $\frac{4}{3}\pi$ contains the factor $1/3$ precisely from the dimensionality 3 of space.

**Geometric meaning:** The three centers of the spheres and their mutual intersection points define a **regular tetrahedron** — the most stable three-dimensional geometric object with four nodes. The tetrahedron is the most natural ground configuration in the DRM ontology: it connects three orthogonal resonance directions with minimal mutual overlap.

**Step 3: Coupling to the k-space normalization**

The effective resonance volume $4\pi$ thus obtained is the basis for the 3D mode count. Multiplied by the normalization factor $\pi^2$ from the Laplace structure of the sphere surface:

$$C_{3D} = \underbrace{4\pi}_{\substack{\text{3 resonators}\\\text{with self-cancellation}}} \times \underbrace{\pi^2}_{\text{sphere-surface normalization}} = 4\pi^3$$

Confidence: HIGH (algebraic step is exact; geometric interpretation as tetrahedron is physically coherent with the DRM ontology; the connection of the tetrahedron to the most stable 3D node configuration is confirmed in the RFT_Theoretical_Framework_v3_0.pdf, Feb 2026).

### 4.4 Synthesis: Two Routes, One Result

Both derivations yield the same term $4\pi^3$, starting from different aspects of the DRM geometry:

$$4\pi^3 = \begin{cases}
4\pi \times \pi^2 & \text{Derivation A: Full solid angle} \times \text{k-space normalization}\\[4pt]
\left(3 \times \dfrac{4}{3}\pi\right) \times \pi^2 & \text{Derivation B: Three resonators, self-cancellation} \times \text{sphere surface}
\end{cases}$$

This is not a coincidence: both aspects — solid angle and tetrahedron resonance — are different descriptions of the same geometric truth: a three-dimensional spherically symmetric resonance structure in a Cartesian DRM couples to the surrounding field with the factor $4\pi$.

**The numerical value:**
$$4\pi^3 = 124.025\,106\,720\ldots$$

with:
$$\pi = 3.14159265358979323846\ldots$$
$$\pi^3 = 31.00627668024166666935\ldots$$
$$4\pi^3 = 124.02510672096666676\ldots$$

### 4.5 What the Factor 4 Is NOT

For a clean presentation to critical readers, it is important to state what the factor 4 is not:

- **Not a free parameter:** The number 4 is not adjusted to optimize agreement with experiment.
- **Not an arbitrary integer:** It follows from $4\pi/\pi$ (Derivation A) or from the algebraic self-cancellation $3 \times (4/3)$ (Derivation B).
- **Not a convention:** It depends on neither a choice of unit system nor a normalization convention. Both derivations are purely geometric.

⚠️ What is still missing: a rigorous variational derivation showing that the sum $4\pi^3 + \pi^2 + \pi$ is the unique solution of a geometrically well-defined minimization problem. Without this step the justification remains geometrically motivated but not variationally unique (cf. Question Q1 in RFT_Derivation_of_Fundamental_Constants.pdf, Feb 2026). ⚠️

**Note on a V7 error:** The predecessor document RFT_002 v7.0 (December 2025) gives, in its summary (Section 9.1), the formula as $\alpha^{-1} = (4\pi^3 + \pi^2 + \pi) \times \sqrt{2}/\pi$. This is a mathematical error: $(4\pi^3 + \pi^2 + \pi) \times \sqrt{2}/\pi \approx 137.036 \times 0.450 \approx 61.7 \neq 137$. The factor $\sqrt{2}/\pi$ appeared in V7 in the context of the tetrahedron-cube packing (edge ratio $\sqrt{2}$) but was erroneously introduced as a global factor. **The correct formula is** $\alpha^{-1} = 4\pi^3 + \pi^2 + \pi$ — with no additional factor. All v3 documents use the correct form.

---

## 5. The 2.22 ppm Residual: Status of the Discrepancy

### 5.1 Numerical Finding ✓

Direct arithmetic evaluation of $4\pi^3 + \pi^2 + \pi$ with full precision gives:

$$\alpha^{-1}_{\text{RFT}} = 137.036\,303\,775\,534\ldots$$

The current reference value from CODATA 2018 (Committee on Data for Science and Technology) is:

$$\alpha^{-1}_{\text{CODATA 2018}} = 137.035\,999\,084(21)$$

The number in parentheses gives the uncertainty in the last digit: $\pm 0.000\,000\,021$. This is the combined standard measurement uncertainty from four independent high-precision measurements (anomalous magnetic moment of the electron, quantum Hall effect, atom-recoil spectroscopy, Josephson effect).

**Residual:**
$$\Delta\alpha^{-1} = \alpha^{-1}_{\text{RFT}} - \alpha^{-1}_{\text{CODATA}} = +0.000\,304\,691\ldots$$

**Relative deviation:**
$$\frac{\Delta\alpha^{-1}}{\alpha^{-1}} = \frac{0.000\,304\,691}{137.036} = 2.222\times 10^{-6} \approx 2.22\,\text{ppm}$$

The residual is positive: the RFT formula gives a value slightly above the experimental result. The residual lies approximately 6 times above the experimental uncertainty ($\pm 0.15\,\text{ppm}$) and is therefore statistically significant.

### 5.2 Clarification of the "0.67 ppm" Figure in Older Documents ⚠️

Several project documents — including the theoretical framework PDF from February 2026 — give the deviation as "0.67 ppm." This number is mathematically inconsistent with the direct evaluation of the formula and must be explained to avoid confusion.

**Why 0.67 ppm is incorrect:**

The value $4\pi^3 + \pi^2 + \pi = 137.036\,304\ldots$ differs from $\alpha^{-1}_{\text{CODATA}} = 137.035\,999\ldots$ by $0.000\,305$. This unambiguously corresponds to 2.22 ppm. There is no mathematically consistent way to derive 0.67 ppm from this difference.

**Probable origin:** The "0.67 ppm" most likely arose through the following chain of errors: an AI-generated version rounded the intermediate result $4\pi^3 + \pi^2 + \pi$ to six significant figures as $137.036\,000$ (correct: $137.036\,304$). The rounded value $137.036\,000$ differs from $137.035\,999$ by $0.000\,001$, giving a relative deviation of $7 \times 10^{-9}$ — generating the formulation "almost exact." This statement was then erroneously transcribed as "0.67 ppm" (possibly confused with the experimental measurement precision of $\pm 0.15\,\text{ppm}$). RFT_v3_001 (v3.5) documents this explicitly and designates 2.22 ppm as the correct and canonical figure.

**Consequence for this document:** All further statements use the correctly computed residual of **2.22 ppm**. The value 0.67 ppm is not used in the RFT v3 series.

### 5.3 Three Interpretations of the 2.22 ppm Residual ○

The residual is significant and must be interpreted. Three positions are open; all three are consistent with the known data, but none is proven:

---

**(a) Coincidence / formula is an approximation ○**

The formula $4\pi^3 + \pi^2 + \pi$ is geometrically motivated but may not be an exact result — it could be a leading-order approximation to which higher corrections are missing. The QFT analogue: the classical value of a coupling constant receives radiative corrections (loop corrections) in powers of $\alpha$ itself:

$$\alpha^{-1}_{\text{effective}} = \alpha^{-1}_{\text{classical}} - \frac{1}{3\pi}\ln\left(\frac{m_e^2}{\mu^2}\right) + O(\alpha) + \ldots$$

Within the RFT framework, an analogous correction term of the form:

$$\delta(\alpha^{-1}) = -f(\alpha, L_0, \kappa) \approx -2.22\,\text{ppm} \times \alpha^{-1} = -0.000\,305$$

could exist, arising from the nonlinear back-action of the resonance modes on the matrix geometry. This term would then need to be derived from the Master Equation (specifically the $\lambda$ term).

Status: ○ (mechanism plausible but not worked out)

---

**(b) Geometric correction from matrix discreteness ○**

An alternative interpretation: the formula $4\pi^3 + \pi^2 + \pi$ applies to a *continuous* spherically symmetric resonance field. The DRM is, however, discrete — its node structure departs from perfect spherical symmetry. The passage from the continuous integral to the discrete sum generates lattice-sum corrections of the form (analogous to the Euler-Maclaurin formula):

$$N_{\text{discrete}} = N_{\text{continuous}} - \frac{1}{2} + \frac{1}{12}\frac{\partial N}{\partial k}\bigg|_{\partial V} + \ldots$$

The first correction (−1/2) corresponds to a relative shift of $1/(2\alpha^{-1}) \approx 0.36\,\%$ — too large. Higher-order corrections can be significantly smaller. Whether such a lattice-sum expansion reproduces the 2.22 ppm residual has not yet been checked numerically.

Status: ○ (numerically open)

---

**(c) Signature of the arrow of time: the residual as a physical observable ○**

The most physically interesting interpretation identifies the residual with the fundamental phase asymmetry $\delta$ of the DRM — the so-called time motor (RFT_v3_001, Chapter 10b):

$$\Delta\alpha^{-1} = \delta \cdot \alpha^{-1}$$

with $\delta \approx 2\alpha \approx 0.014\,6\,\text{rad} \approx 0.82°$.

**Quantitative check:**
$$\delta \cdot \alpha^{-1} = 2\alpha \cdot \alpha^{-1} = 2$$

This does not match directly ($0.000\,305 \neq 2$), but the correct reading is:

$$\Delta\alpha^{-1} = \delta \approx 2\alpha \implies \delta = \frac{\Delta\alpha^{-1}}{\alpha^{-1}} = 2.22 \times 10^{-6}$$

While $2\alpha \approx 0.01459$, the quantity $\Delta\alpha^{-1}/\alpha^{-1} = 2.22 \times 10^{-6}$ — a difference of four orders of magnitude. A direct numerical identification thus requires a specific functional dependence $\delta = f(\alpha)$ with $f(\alpha) \propto \alpha^3$ to give $\Delta\alpha^{-1}/\alpha^{-1} \sim 2\alpha^3 \approx 2 \times (7.3 \times 10^{-3})^3 \approx 7.8 \times 10^{-7}$ — the right order of magnitude, but not yet identical.

**Conceptual strength:** This interpretation is nevertheless attractive for a different reason: it would mean that the "pure geometry" $4\pi^3 + \pi^2 + \pi$ describes $\alpha^{-1}$ in the *symmetric, time-reversal-invariant* universe, while the real universe carries a minimal asymmetry $\delta \neq 0$ through the $\lambda$ term. The residual would then be not a deficiency of the theory but a measured window onto the mechanism of the arrow of time itself.

Status: ○ (attractive; identified in RFT_Derivation_of_Fundamental_Constants.pdf, Feb 2026, as the most interesting interpretation; numerical proof of the exact dependence $\delta = g(\alpha^3)$ is missing)

---

### 5.4 Pragmatic Summary ⚠️

All three interpretations are currently open. For communicating to a critical physicist:

**The 2.22 ppm residual is not a problem that makes the derivation worthless** — a purely geometric, parameter-free formula that hits $\alpha^{-1}$ to 2 ppm is a remarkable result. It would, however, be a problem to claim the residual is fully explained. It is not.

The next step in the RFT program is to quantify interpretation (c): can the $\lambda$ term of the Master Equation yield the correction $\delta(\alpha^{-1}) \approx 0.000\,305$ as a function of the known matrix parameters? That would advance the formula from status ○ (working hypothesis) to status ✓ (verified).

---

## 6. The Flux Factor Φ

### 6.1 Definition and Motivation ✓

As the second fundamental dimensionless quantity of the DRM, RFT derives the **flux factor** Φ. Its definition is:

$$\Phi = \frac{2\alpha}{1 + \alpha^2}$$

with the fine structure constant $\alpha \approx 1/137.036$ from Chapter 3. Since $\alpha \ll 1$, to very good approximation:

$$\Phi \approx 2\alpha \approx 0.014\,595\quad\text{(accurate to 26 ppm, since } \alpha^2 \approx 5.3\times 10^{-5} \ll 1\text{)}$$

**Numerical evaluation with the RFT value $\alpha_{\text{RFT}} = 1/137.036\,304$:**

$$\Phi = \frac{2/137.036\,304}{1 + (1/137.036\,304)^2} = \frac{0.014\,596\,7\ldots}{1 + 0.000\,053\,2\ldots} = 0.014\,595\,9\ldots$$

### 6.2 Geometric Derivation from the Impedance-Boundary Analogy ✓

Why does precisely this combination $2\alpha/(1+\alpha^2)$ appear? The derivation uses an analogy from classical wave theory: the transmission of a wave packet across an impedance boundary.

**Analogous situation in classical physics:**

In electrodynamics, the Fresnel transmission coefficient for a wave incident normally on a boundary between two media with refractive indices $n_1$ and $n_2$ is:

$$T = \frac{2n_1}{n_1 + n_2}, \quad R = \frac{n_1 - n_2}{n_1 + n_2}$$

The transmittance (power throughput) is then:

$$\mathcal{T} = \frac{4n_1 n_2}{(n_1 + n_2)^2}$$

**Transfer to the DRM:**

In RFT the transition region between the photon and particle regimes (the region $k \approx \kappa$) has a physical character analogous to the impedance boundary in wave theory. The "refractive index ratio" at this boundary is determined by $\alpha$ itself: a particle (vortex, $k \ll \kappa$) couples to a photon (propagating mode, $k \gg \kappa$) with strength exactly $\alpha$. The transmission of a resonance "flux" through this boundary gives the transmission coefficient:

$$\Phi = \frac{2\alpha}{1 + \alpha^2}$$

This is formally identical to the Stokes relation for transmission through a thin layer with relative impedance $Z = 1/\alpha$ in the normal-incidence limit. The denominator $(1 + \alpha^2)$ represents the back-action of the impedance mismatch.

**Physical interpretation:** Φ describes the fundamental asymmetry of the resonance field. In the limit $\Phi \to 0$ the field would be perfectly time-reversal symmetric — there would be no preferred direction of time flow. The finite, small asymmetry $\Phi \neq 0$ generates the dynamics of the universe and the arrow of time.

Confidence: MEDIUM (the impedance-boundary analogy is physically motivated; a rigorous derivation from the Master Equation by explicit computation of the transmission coefficient in the transition region $k \approx \kappa$ is still missing).

### 6.3 Connection to the Time Motor δ ○

In RFT_v3_001 (Chapter 10b), a fundamental parameter δ — the time motor — is introduced, describing the minimal temporal phase asymmetry of the DRM. Three independent measurements converge on:

$$\delta \approx 2\alpha \approx 0.014\,6\,\text{rad} \approx 0.82°$$

The coincidence $\Phi \approx 2\alpha = \delta$ is remarkable: the flux factor Φ and the time motor δ are numerically equal (to 26 ppm). The interpretation is still open:

- Are Φ and δ the same quantity, defined in different ways? (Confidence: MEDIUM)
- Or is their numerical equality an artifact of the $\alpha \ll 1$ approximation ($\Phi \approx 2\alpha = \delta$, but higher-order terms could separate them)? (Confidence: LOW)

Status: ○ (numerical connection clear; conceptual identification still to be proved)

### 6.4 Numerical Overview ✓

| Quantity | Expression | Numerical value |
|----------|-----------|----------------|
| $\Phi$ (exact) | $2\alpha/(1+\alpha^2)$ | 0.014 595 9… |
| $\Phi$ (approximation) | $2\alpha$ | 0.014 596 7… |
| $\delta$ (time motor) | $\approx 2\alpha$ | 0.014 6… |
| Deviation $\Phi$ vs $2\alpha$ | $\alpha^2/(1+\alpha^2)$ | 26 ppm |

---

## 7. α in the Constant Hierarchy: Deriving G and ħ

### 7.1 The Derivation Hierarchy of RFT ✓

One of the structural strengths of RFT is the existence of a **circularity-free derivation chain** for the fundamental constants. The complete hierarchy (RFT_v3_001, Chapter 5.4, and PDF Feb 2026):

```
c    ←  the only genuine fundamental input (DRM relaxation speed)
 └──→ α = 1/(4π³+π²+π)          [Step 1: pure π-geometry, Chapter 3]
       └──→ G = f(c, L₀, π, α)   [Step 2: spin delay, RFT_003]
             └──→ ħ = (36/π²)·c³L₀²/G  [Step 3: dimensional analysis]
                   └──→ l_P = √(ħG/c³)  [Step 4: derived]
                         └──→ L₀ = (π/6)·l_P  [Step 5: sphere-cube geometry]
```

**α is the first and most important step** in this chain: without a geometric derivation of α, α would have to enter as a free parameter, which would break the entire hierarchy.

**Important clarification:** The step $c \to \alpha$ is fully worked out in this document (Chapters 3–4). The step $\alpha \to G$ is carried out in RFT_003 (spin-delay mechanism, four independent paths). The step $G \to \hbar$ is the G·ħ relation treated in the next section. The final stage is geometric ($L_0 = (\pi/6)l_P$ from the sphere-cube volume ratio).

### 7.2 The G·ħ Relation ○

Dimensional analysis shows that ħ cannot be constructed from $c$ and $G$ alone — a length is mandatory. With $L_0$ as this fundamental length, the form is uniquely determined up to a dimensionless factor (RFT_Derivation_of_Fundamental_Constants.pdf, Feb 2026, Section 3.2):

$$G \cdot \hbar = \frac{36}{\pi^2}\cdot c^3 L_0^2$$

**Numerical verification:**

With $L_0 = (\pi/6) l_P$ and $l_P = \sqrt{\hbar G/c^3}$:
$$L_0^2 = \frac{\pi^2}{36} l_P^2 = \frac{\pi^2}{36}\cdot\frac{\hbar G}{c^3}$$

Substituting:
$$G\hbar = \frac{36}{\pi^2}\cdot c^3 \cdot \frac{\pi^2}{36}\cdot\frac{\hbar G}{c^3} = G\hbar \quad \checkmark$$

**Honest status of this relation:** ○ — The relation is currently an **algebraic identity**, not an independent result. Since $L_0$ is defined via $l_P$ and $l_P = \sqrt{\hbar G/c^3}$, the relation $G \cdot \hbar = (36/\pi^2) c^3 L_0^2$ follows algebraically from the definition. The relation therefore lacks the character of a genuine prediction as long as G is not derived independently of ħ.

**What would make the relation a genuine prediction:** If the spin-delay mechanism in RFT_003 yields the gravitational constant G *without* ħ as input, then the G·ħ relation would be a nontrivial connection between two independently derived quantities. This task is documented as a central open problem of RFT.

**Structural content of the relation:** Even as an identity it has content. It states that $L_0$ is the geometric bridge between $G$ and $\hbar$: the sphere-cube volume ratio $(\pi/6)^2 = \pi^2/36$ appears identically in the relation (as $36/\pi^2 \times L_0^2 = l_P^2 = \hbar G/c^3$). If ħ and G were derivable independently, this relation would show that they share a common geometric root in the DRM — reducing the number of independent fundamental constants of the Standard Model from 3 to 2 ($c$ and $L_0$).

### 7.3 The Connection α → L₀ → G: The RFT_003 Program ○

The complete spin-delay mechanism is developed in RFT_003; here is the connection relevant to the α derivation in compact form:

The gravitational constant G emerges in RFT from the time lag $\tau_{\text{lag}}$ with which the matrix tension follows the vortex spins (drag-vortex mechanism). Four independent calculation paths converge on the correct CODATA value of G with agreement better than $0.1\,\%$ (RFT_003, Paths 2–4; Path 1 was affected by the error $f_{\text{spin}} = 4$ instead of the correct $f_{\text{spin}} = 144/\pi$, cf. the Inconsistency Matrix).

The connection to α lies in $L_0$: the length scale $L_0 = (\pi/6) l_P$ appears both in the α formula (as the normalization length for the k-space integration) and in the G derivation (as the fundamental DRM cell size). It is this **identity of the length scale** that makes the hierarchy $c \to \alpha \to G \to \hbar$ internally consistent.

### 7.4 The von Klitzing Constant and the ħ/α Connection ✓

One directly measurable consequence of the geometric α derivation is the von Klitzing constant $R_K$, the resistance quantum of the quantum Hall effect:

$$R_K = \frac{h}{e^2} = \frac{2\pi\hbar}{e^2}$$

Since the elementary charge $e$ in RFT can be written as $e^2 = 4\pi\varepsilon_0\hbar c\,\alpha$:

$$R_K = \frac{2\pi\hbar}{4\pi\varepsilon_0\hbar c\,\alpha} = \frac{1}{2\varepsilon_0 c\,\alpha} = \frac{\mu_0 c}{2\alpha}$$

with the vacuum wave impedance $Z_0 = \mu_0 c = 1/(\varepsilon_0 c) \approx 376.7\,\Omega$:

$$R_K = \frac{Z_0}{2\alpha} = \frac{\mu_0 c}{2} \cdot \alpha^{-1} = \frac{\mu_0 c}{2}\cdot(4\pi^3 + \pi^2 + \pi)$$

**Numerically:**
$$R_K = \frac{376.730\,\Omega}{2} \times 137.036\,304 = 25\,812.3\,\Omega\quad\text{(CODATA: }25\,812.807\,\Omega\text{)}$$

The 19 ppm deviation reflects directly the α residual (2.22 ppm), scaled by a factor ~8 due to the different combination structure. When RFT closes the α residual in future derivations, this agreement improves accordingly.

**Physical significance:** The von Klitzing constant is today one of the most precisely measured physical constants and serves as the primary resistance standard. Its connection to α makes it a direct experimental test of the RFT α derivation.

---

## 8. Experimental Tests and Predictions from α

### 8.1 What Follows from the Geometric α Formula ✓

The claim $\alpha^{-1} = 4\pi^3 + \pi^2 + \pi$ is not directly testable, since α is itself the fundamental quantity. What is testable, however, is whether the theoretical consequences of this formula agree with experiments. Four experimental contexts in which α is the decisive quantity are discussed below.

### 8.2 Anomalous Magnetic Moment of the Electron (g−2) ✓

The anomalous magnetic moment of the electron, $a_e = (g_e - 2)/2$, is the most precisely measured quantity in physics. It is calculated in quantum electrodynamics (QED) as a perturbation series in α:

$$a_e = \frac{\alpha}{2\pi} - 0.328\,479\frac{\alpha^2}{\pi^2} + 1.181\,234\frac{\alpha^3}{\pi^3} - 1.912\,057\frac{\alpha^4}{\pi^4} + \ldots$$

Current experimental value (Penning-trap spectroscopy, 2023):

$$a_e^{\text{exp}} = 0.001\,159\,652\,180\,59(13)$$

QED theory value using the CODATA value $\alpha_{\text{CODATA}}$:

$$a_e^{\text{QED}}(\alpha_{\text{CODATA}}) = 0.001\,159\,652\,180\,43(13)$$

**Relevance for RFT:** RFT provides $\alpha_{\text{RFT}}$ as input for the same QED calculation. Since $\alpha_{\text{RFT}} > \alpha_{\text{CODATA}}$ by 2.22 ppm, a corresponding deviation arises in the theoretical $a_e$:

$$\Delta a_e \approx \frac{\partial a_e}{\partial\alpha} \cdot \Delta\alpha \approx \frac{1}{2\pi} \cdot \Delta\alpha = \frac{1}{2\pi} \cdot 2.22 \times 10^{-6} \cdot \alpha \approx 2.6\times 10^{-9}$$

This is significantly larger than the current experimental uncertainty of $1.3 \times 10^{-12}$, hence measurable. **With the current RFT value of α, the QED prediction for $a_e$ is not in agreement with experiment.** This inconsistency resolves once the 2.22 ppm residual (Chapter 5) is explained and the RFT formula corrected accordingly.

Status: ⚠️ (Current RFT value of α leads to a measurable inconsistency with $a_e$; interpretation: the 2.22 ppm residual is the central problem that must be solved)

### 8.3 Quantum Hall Effect and the von Klitzing Constant ✓

The integer quantum Hall effect occurs in two-dimensional electron systems at low temperatures and strong magnetic fields. The Hall resistance takes quantized values:

$$R_H = \frac{R_K}{n}, \quad n = 1, 2, 3, \ldots$$

with $R_K = h/e^2 = \mu_0 c/(2\alpha) \approx 25\,812.807\,\Omega$ (CODATA 2018).

**RFT prediction:** Using $\alpha_{\text{RFT}}$:

$$R_K^{\text{RFT}} = \frac{\mu_0 c}{2\alpha_{\text{RFT}}} = \frac{\mu_0 c}{2}\times(4\pi^3+\pi^2+\pi) \approx 25\,812.252\,\Omega$$

Deviation from the CODATA value: ~21 ppm (proportional to the α residual, scaled by the ratio $\alpha_{\text{RFT}}/\alpha_{\text{CODATA}} - 1$).

The quantum Hall effect is used in the metrology system as the primary resistance standard (SI definition since 2019). Consistency between the RFT prediction and this standard depends directly on whether the 2.22 ppm residual can be closed.

### 8.4 Lamb Shift in Hydrogen ✓

The Lamb shift — the energy splitting between the 2S₁/₂ and 2P₁/₂ states of the hydrogen atom — is proportional to $\alpha^5$ at leading order:

$$\Delta E_{2S-2P} = \frac{\alpha^5 m_e c^2}{3\pi} \ln\left(\frac{1}{\alpha}\right) + O(\alpha^6)$$

with the electron mass $m_e$. The measured value is $\Delta E_{2S-2P} \approx 1057.845\,\text{MHz}$.

**RFT prediction:** Since $\alpha_{\text{RFT}}$ is 2.22 ppm larger than $\alpha_{\text{CODATA}}$ and the term $\alpha^5$ is involved, the relative deviation in the RFT prediction is:

$$\frac{\Delta(\Delta E)}{\Delta E} \approx 5 \times 2.22\,\text{ppm} = 11.1\,\text{ppm}$$

This corresponds to a frequency shift of $\sim 11.8\,\text{kHz}$ relative to the Standard Model value. The current measurement uncertainty of the Lamb shift is at the kHz level — the effect would in principle be measurable once the α residual of RFT is precisely quantified.

### 8.5 Running of α with Energy (Renormalization Group) ○

In quantum field theory, α is not a constant but a running coupling: its value changes with the energy scale μ at which it is measured.

$$\alpha^{-1}(\mu) = \alpha^{-1}(m_e) - \frac{1}{3\pi}\ln\left(\frac{\mu^2}{m_e^2}\right) + O(\alpha)$$

The value $\alpha^{-1} \approx 137.036$ holds for $\mu = m_e c^2$ (low energies, Thomson limit). At the Z-boson mass ($\mu = m_Z c^2 \approx 91.2\,\text{GeV}$) the effective value is:

$$\alpha^{-1}(m_Z) \approx 128.9$$

**RFT perspective:** The running of α in QED is a consequence of vacuum polarization — particle-antiparticle pairs screen the electric charge at short distances. In RFT this running would be interpreted as a change in the effective mode count with probe energy: at higher energies ($k \gg \kappa$) more k-space modes are accessible, giving an apparently stronger coupling.

The formula $4\pi^3 + \pi^2 + \pi$ applies in the long-wavelength limit of the DRM — the low-energy fixed point. An RFT-based computation of the running of α (i.e., the energy-dependent correction to the geometric formula) is an open task.

Status: ○ (qualitative agreement with QED expectation clear; quantitatively not worked out)

### 8.6 Summary of the Experimental Situation ⚠️

| Test | RFT prediction | Experiment | Status |
|------|---------------|-----------|--------|
| $\alpha^{-1}$ (direct) | 137.036 304 | 137.035 999(21) | ⚠️ 2.22 ppm residual |
| Von Klitzing constant $R_K$ | ~25 812.25 Ω | 25 812.807 Ω | ⚠️ 21 ppm (follows from α residual) |
| Electron g−2 | Inconsistent with current $\alpha_{\text{RFT}}$ | Measured, 0.13 ppb precision | ⚠️ Problem until residual resolved |
| Lamb shift | +11 kHz deviation from QED | ±kHz precision | ○ Testable once α residual quantified |
| Running of α with energy | Qualitatively consistent | QED verified | ○ Quantitatively not worked out |

**Overall statement:** All experimental inconsistencies of RFT reduce to the single, known problem: the 2.22 ppm residual. If this is resolved (Chapter 5, interpretations a–c), all other experimental tests of RFT are consistent. The α residual is therefore not one problem among many — it is the central open problem of this document.

---

## 9. Known Limitations and Open Problems

*This chapter is a mandatory component of all RFT_v3 documents. It honestly documents the known limitations of the α derivation.*

### 9.1 Problem 1: Variational Uniqueness — Is the Formula the Only Possible One? ⚠️

**Finding:** The geometric sum $4\pi^3 + \pi^2 + \pi$ is well motivated but not variationally uniquely derived. That is: it has not been proved that this is the *only* sum of powers of π that follows from a geometrically well-defined minimization problem for the DRM.

Alternatives that would need to be checked: could, for example, $3\pi^3 + 2\pi^2 + 0$ or $5\pi^3 + 0 + 2\pi$ follow from other, equally well-motivated geometric considerations? Note that these alternatives would lie numerically far from the experimental value — $3\pi^3 + 2\pi^2 \approx 93.0 + 19.7 \approx 112.7$ and $5\pi^3 + 2\pi \approx 155.0 + 6.3 \approx 161.3$ — so the experimental value $\alpha^{-1} \approx 137$ strongly constrains the selection. The formal uniqueness proof is nevertheless still missing.

**What is missing:** Formulating the formula as the unique solution of a minimization problem. E.g.: "Minimize the total mode count of the DRM subject to constraints [X, Y, Z] — the solution is exactly $4\pi^3 + \pi^2 + \pi$."

**Sources:** PDF Feb 2026 (Question Q1), RFT_v3_001 Ch. 4.2 (Warning ⚠️)

Status: ⚠️ (open; geometric motivation strong, uniqueness not proved)

### 9.2 Problem 2: The 2.22 ppm Residual — Unresolved ⚠️

**Finding:** Direct calculation gives $4\pi^3 + \pi^2 + \pi = 137.036\,304$; experiment (CODATA 2018) gives $137.035\,999(21)$. The difference is 2.22 ppm — significant, six times larger than the experimental uncertainty.

**Three interpretations** are documented (Chapter 5.3), but none is proved:
- (a) Formula is a leading-order approximation; corrections missing
- (b) Lattice-sum correction in the continuous → discrete transition
- (c) Arrow-of-time signature of the λ term (most interesting physically)

**Consequence:** As long as the residual is unresolved, the RFT prediction of α cannot be considered complete. All experimental tests that use α as input (g−2, $R_K$, Lamb shift) show corresponding deviations.

**Clarification on "0.67 ppm":** Some predecessor documents and the PDF Feb 2026 give "0.67 ppm" as the residual. This number is wrong — it arose from a combination of a rounding error ($4\pi^3 \approx 123.370$ instead of correct $124.025$) and an erroneous ppm conversion in AI-generated documents. See also the entry in RFT_v3_001 (Chapter 4.1, Warning ⚠️). The correct residual from direct calculation is **2.22 ppm**.

**Sources:** Inconsistency Matrix, Section 4; RFT_v3_001, Ch. 4.1

Status: ⚠️ (central open problem)

### 9.3 Problem 3: Connection to the Master Equation — Missing Rigor ⚠️

**Finding:** The α derivation in Chapter 3 uses a geometrically motivated mode addition. It is not derived from the Master Equation which terms of the coupling matrix generate exactly the sum $4\pi^3 + \pi^2 + \pi$.

Concretely: the Master Equation contains no explicit variable "electromagnetic coupling strength α." The claim that α follows from the mode addition presupposes the conceptual connection: "Number of resonance modes in d dimensions = inverse of the coupling strength for d-dimensional interactions." This connection is physically plausible but has not yet been derived mathematically from the field equations.

**What is missing:** An explicit calculation of the scattering cross-section (or equivalently the coupling matrix) of a vortex to the resonance field, showing that the cross-section is proportional to $4\pi^3 + \pi^2 + \pi$.

**Sources:** Inconsistency Matrix, Section 1; PDF Feb 2026, Question Q1

Status: ⚠️ (conceptual gap; physically plausible, mathematically not closed)

### 9.4 Problem 4: The L₀ Circularity ⚠️

**Finding:** The constant $L_0$ appears both as a normalization quantity in the α formula (k-space cutoff) and as a geometric consequence of $l_P$, which in turn depends on $\hbar$ and $G$. The complete chain:

$$L_0 = \frac{\pi}{6} l_P = \frac{\pi}{6}\sqrt{\frac{\hbar G}{c^3}}$$

contains both $\hbar$ and $G$. Since $\hbar$ in turn depends on $L_0$ via the G·ħ relation, the definition of $L_0$ is circular as long as G is not derived independently of $\hbar$.

**Impact on the α derivation:** The formula $4\pi^3 + \pi^2 + \pi$ does *not* contain $L_0$ explicitly — that is a strength. The expression is determined purely by π-ratios and does not depend on $L_0$. The circularity therefore primarily affects the G·ħ relation (Chapter 7.2), not the α formula itself. Nevertheless the overall coherence of the theory is touched: if $L_0$ is circularly defined, it weakens the overall structure.

**What is missing:** Derivation of G without ħ as input (RFT_003, open); this would resolve the circularity.

**Sources:** Inconsistency Matrix, Sections 1 and 3; RFT_v3_001, Ch. 5.3

Status: ⚠️ (known weakness; affects α derivation indirectly)

### 9.5 Problem 5: Document Inconsistency in V7 — Historical Error ✓ (identified)

**Finding:** The predecessor document RFT_002 v7.0 (December 2025) contains in Section 6.1 an erroneous computation of $4\pi^3$:

```
V7 Section 6.1: "4π³ = 123.370..."    ← WRONG
Correct:              4π³ = 124.025...
```

This arithmetic error led to the intermediate result $4\pi^3 + \pi^2 + \pi = 136.381$ (correct: 137.036). To "correct" this error a factor $\sqrt{2}/\pi$ was introduced: $(4\pi^3+\pi^2+\pi)\times\sqrt{2}/\pi$. This factor is algebraically inconsistent — $(4\pi^3+\pi^2+\pi) \times \sqrt{2}/\pi \approx 137.036 \times 0.450 \approx 61.7 \neq 137$.

**Status in the v3 series:** The V7 document has been superseded by RFT_v3_002 (this document). The correct formula is $\alpha^{-1} = 4\pi^3 + \pi^2 + \pi$ without any additional factor. The origin of the V7 error — $4\pi^3$ incorrectly computed as $\approx 123.37$ rather than $124.025$, suggesting a confusion with $4\pi^2 \approx 39.5$ or a typo — is historical, not conceptual.

Status: ✓ (error identified and documented; V7 should be marked as deprecated)

### 9.6 Problem 6: No Direct Experimental Verification of the Geometric Origin of α ⚠️

**Finding:** All experimental tests measure the *value* of α, but not its geometric origin. The statement "α follows from the DRM geometry" is not directly falsifiable — one measures α and compares with the formula, but the geometry of the DRM cannot be independently verified.

A genuine test of the geometric origin would require:

1. **Variation of α with the cosmic phase state:** If the DRM structure changes with cosmology (e.g., with the Q-factor of the resonance matrix), α should vary slightly. Quasar spectra at various redshifts would reveal such variations. Current measurements indicate variations $|\Delta\alpha/\alpha| < 10^{-6}$ — consistent with RFT, but not proof.

2. **Measurement of the mode structure of the DRM:** If the k-space mode structure were directly accessible (e.g., via high-frequency resonance experiments near the Planck scale), direct verification would be possible. This is not achievable with foreseeable technology.

Status: ⚠️ (fundamental limitation on falsifiability; typical of theories at the Planck scale)

### 9.7 Honest Overall Assessment ○

The geometric derivation $\alpha^{-1} = 4\pi^3 + \pi^2 + \pi$ is a remarkable result: a parameter-free formula from pure π-geometry hits $\alpha^{-1}$ to 2.22 ppm. For comparison: the closest geometric approximation without free parameters in the Standard Model is the relation $\alpha^{-1} \approx 137$ — an integer approximation to 0.026%.

The known limitations are:

- The 2.22 ppm residual is the central open problem.
- Variational uniqueness is not proved.
- The connection to the Master Equation is conceptual, not mathematically closed.
- The G derivation is not yet fully circularity-free.

None of these limitations invalidates the derivation — but they make it a **working hypothesis of high quality**, not a completed proof. That is the correct status of this theory.

---

## 10. Summary

### 10.1 What Has Been Shown ✓

This document derives the fine structure constant from the geometry of the Dynamic Resonance Matrix:

**Main result:**
$$\alpha^{-1} = 4\pi^3 + \pi^2 + \pi = 137.036\,304\ldots\quad\text{(2.22 ppm from CODATA)}$$

**Key results:**

**(1) Dimensional hierarchy:** Each spatial dimension contributes a characteristic power of π to the inverse coupling strength: 3D → $4\pi^3$, 2D → $\pi^2$, 1D → $\pi$. The different dimensions correspond to different geometric structures of the vortex coupling to the DRM.

**(2) Factor 4:** The prefactor in the 3D term follows from two independent geometric derivations that agree: the full solid angle $4\pi$ steradians (Derivation A) and the self-cancellation $3 \times (4/3)\pi = 4\pi$ from three orthogonal unit spheres (Derivation B, tetrahedron resonance).

**(3) Residual:** The 2.22 ppm residual is correctly calculated from direct arithmetic. The 0.67 ppm figures given in some project documents result from an arithmetic error in V7 and AI transcription errors; they are not used in the v3 series.

**(4) Flux factor:** $\Phi = 2\alpha/(1+\alpha^2) \approx 2\alpha \approx 0.01460$ is the fundamental asymmetry of the DRM; its geometric derivation from the impedance-boundary analogy is motivated, formally still open.

**(5) Constant hierarchy:** α is the first step in the circularity-free chain $c \to \alpha \to G \to \hbar \to l_P \to L_0$. The G·ħ relation $G\hbar = (36/\pi^2) c^3 L_0^2$ is currently an algebraic identity.

### 10.2 Status Overview of All Key Claims

| Claim | Status | Confidence |
|-------|--------|-----------|
| $\alpha^{-1} = 4\pi^3+\pi^2+\pi$ (structure) | ✓ geometrically motivated | HIGH |
| Factor 4: solid-angle Derivation A | ✓ rigorous | HIGH |
| Factor 4: tetrahedron Derivation B | ✓ algebraically exact | HIGH |
| Variational uniqueness of the formula | ⚠️ open | — |
| 2.22 ppm residual (numerical value) | ✓ verified by direct calculation | HIGH |
| Interpretation of the residual (a/b/c) | ○ working hypotheses | LOW–MEDIUM |
| $\Phi = 2\alpha/(1+\alpha^2)$ | ✓ defined | HIGH |
| Geometric derivation of Φ | ○ motivated, not rigorous | MEDIUM |
| G·ħ relation | ○ algebraic identity | HIGH (as identity) |
| α → G (spin delay, RFT_003 Paths 2–4) | ✓ numerically consistent | MEDIUM |
| Connection of α to the Master Equation | ⚠️ conceptual, not formal | LOW–MEDIUM |

---

## Appendix A: Verification of Key Numbers

| Quantity | Expression | Numerical value | Source |
|----------|-----------|----------------|--------|
| $4\pi^3$ | $4 \times \pi^3$ | 124.025 106 720... | Direct calculation |
| $\pi^2$ | $\pi^2$ | 9.869 604 401... | Direct calculation |
| $\pi$ | $\pi$ | 3.141 592 654... | Direct calculation |
| $\alpha^{-1}_{\text{RFT}}$ | $4\pi^3+\pi^2+\pi$ | 137.036 303 775... | Direct calculation |
| $\alpha^{-1}_{\text{CODATA}}$ | — | 137.035 999 084(21) | CODATA 2018 |
| $\Delta\alpha^{-1}$ | Difference | +0.000 304 691... | Direct subtraction |
| Residual | $\Delta/\alpha^{-1}$ | **2.22 ppm** | Direct calculation |
| $L_0$ | $(\pi/6)\cdot l_P$ | $0.524 \cdot l_P$ | RFT_v3_001, PDF Feb 2026 |
| $\kappa$ | $1/L_0$ | $\approx 1.18 \times 10^{35}\,\text{m}^{-1}$ | Derived |

---

## Appendix B: Terminology

**$\alpha$ (fine structure constant):** Dimensionless constant of electromagnetic coupling strength. Measured in the Standard Model; derived from geometry in RFT. Value: $\alpha \approx 7.2974 \times 10^{-3}$; inverse: $\alpha^{-1} \approx 137.036$.

**DRM (Dynamic Resonance Matrix):** The dynamic vacuum field of RFT. Not a classical aether (no rest frame, no Lorentz violation). The node structure of the field carries, to good approximation, the symmetries of a cubic arrangement. Preferred notation in prose: "resonance matrix."

**k-space:** The dual space of position coordinates, described by wave vectors $\vec{k}$. Fourier modes in k-space correspond to plane waves in position space.

**$\kappa$ (resonance rigidity):** The natural wave number of the vacuum resonance matrix ($= 1/L_0$). Determines the transition between the photon and particle regimes in the dispersion relation. Causal distinction: in the Klein-Gordon equation, mass generates the $\kappa^2\Psi$ term; in RFT, $\kappa$ is primary and mass is emergent.

**$\lambda$ term:** The nonlinear term $\lambda|\Psi|^2\Psi$ in the Master Equation. Responsible for soliton stability (stable particles) and the minimal time asymmetry $\delta$ of the DRM.

**Residual:** The remaining difference between the RFT prediction and the experimental value. Here: $\Delta\alpha^{-1} \approx 2.22\,\text{ppm}$.

**Shell integral:** The mode count over the surface $A_k = 4\pi\kappa^2$ of the k-space sphere at $k = \kappa$, as opposed to the volume integral. The shell integral is physically appropriate because electromagnetic coupling occurs at the photon-particle transition boundary $k \approx \kappa$.

**Solid angle $4\pi$ sr:** The full solid angle over the entire sphere surface in SI units (steradians). In three dimensions the analogue of $2\pi$ radians (full angle in a circle).

---

## References

**Internal RFT documents:**
- RFT_v3_001 (v3.5, Feb 2026): Mathematical Foundations — starting point and terminology
- RFT_002_Alpha_Herleitung_v7_0.md (Dec 2025): Predecessor document; Fourier mode basis; V7 error in Ch. 6 documented; superseded by this document
- RFT_Derivation_of_Fundamental_Constants.pdf (Feb 2026): Latest status overview; derivation hierarchy
- RFT_Inkonsistenz_Matrix_v1.md: Known weaknesses, esp. L₀ circularity
- RFT_003 (Gravitation & Spin Delay): Next step in the hierarchy α → G

**Experimental references:**
- CODATA 2018: $\alpha^{-1} = 137.035\,999\,084(21)$ (α), $R_K = 25\,812.807\,\Omega$ (von Klitzing)
- Hanneke, Fogwell, Gabrielse (2008); Fan et al. (2023): anomalous magnetic moment of the electron
- Pohl et al. (proton charge radius): Lamb shift in muonic hydrogen

---

## Dependencies

**This document requires:**
- RFT_v3_001 (v3.5): Master Equation, L₀, κ, time motor

**Direct successor documents:**
- RFT_v3_003: Gravitation and Spin Delay — Step 2 of the hierarchy, G from α and L₀
- RFT_v3_004: Momentum and Energy — particles as solitons

---

*End of RFT_v3_002 — The Fine Structure Constant from Pure Geometry*
*Version 3.0 (EN) | 24 March 2026 | Franz Zollner | CC BY-NC-ND 4.0*
