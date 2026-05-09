# RFT_v3_017: ENTANGLEMENT
## Non-Locality through Common Resonance Modes

**DOCUMENT-ID:** RFT_v3_017_Entanglement_EN_v1.0
**Series:** v3-Series (Level IV: Particle Physics & Properties)
**Status:** Translation Final v1.0
**Date:** 04 April 2026
**Author:** Franz Zollner
**Revision:** AI Working Instance 017
**Language:** EN
**Based on:** RFT_v3_017_Verschraenkung_v1.0 (DE Final)

**Dependencies (required):**
- RFT_v3_001 (master equation, κ, L₀)
- RFT_v3_006 (arrow of time, guidance field Φ)
- RFT_v3_007 (space topology, 3D structure)
- RFT_v3_011 Part 5 Ch. 16–17 (primary source)
- RFT_v3_016 (AP topology, 720° periodicity)

**Created in parallel with:** RFT_v3_018 (Decoherence & Signal Theory)

---

> **Confidence notation:** This document uses explicit confidence markers:
> ✓ HIGH (multiply confirmed), ○ MEDIUM (conceptually clear, formally open),
> ⚠️ LOW (working hypothesis), 🚩 OPEN (Franz decision or DeepSeek task pending).
>
> Open questions are documented explicitly, not concealed.

---

## Table of Contents

1. The Puzzle of Entanglement — Spook or Structure?
2. Common Resonance Modes — The Physical Mechanism
3. Common Resonance Mode — Core Concept of the RFT
   3.1 Definition
   3.2 What Exactly is a "Common Resonance Mode"?
   3.3 Comparison with the Photon
   3.4 Object Hierarchy: Entanglement — Cooper Pair — Hadron
4. Bell's Theorem and the RFT
5. The EPR Paradox: Resolution in the RFT
6. Decoherence as the Limit of Entanglement
7. Experimental Consequences
8. Connection to the v3-Series
9. Honest Limits
10. Summary and Formula Overview

---

# CHAPTER 1: THE PUZZLE OF ENTANGLEMENT

## 1.1 The Observation

Two particles can be prepared in a joint quantum state that cannot be
written as the product of two independent states. When a measurement is
subsequently performed on one of the particles — whether in a laboratory
on Earth or, hypothetically, at the other end of the galaxy — the second
particle instantly delivers a correlated result. This correlation exceeds
anything that can be explained by local causes.

```
Experiment (schematic):
  Source produces entangled pair
       │
       ├─────── Particle 1 → Alice (measures spin)
       │
       └─────── Particle 2 → Bob (measures spin)

Alice measures: ↑
Bob measures immediately: ↓  (regardless of distance!)
Correlation: E(θ=0°) = -1  (perfect anti-correlation)
```

The standard formulation (Bell state, spin singlet):

```
|Ψ⟩ = (1/√2)(|↑↓⟩ - |↓↑⟩)

This superposition is NOT factorizable:
|Ψ⟩ ≠ |ψ₁⟩ ⊗ |ψ₂⟩  for any single-particle states |ψ₁⟩, |ψ₂⟩
```

The angle-dependent correlation is:

```
E(θ_A, θ_B) = -cos(θ_A - θ_B)

e.g. θ_A = θ_B = 0°: E = -1  (perfectly anti-correlated)
     θ_A - θ_B = 90°: E =  0  (uncorrelated)
```

## 1.2 The Problem: Locality or Non-Locality?

Einstein called this correlation "spooky action at a distance" and
rejected it as inconsistent with the theory of relativity. His argument
(Einstein, Podolsky, Rosen 1935): if quantum mechanics is complete and
yet implies such non-locality, it violates fundamental principles of
classical physics. If it respects those principles, it must be incomplete.

John Bell formalized this tension in 1964: he showed that no theory
with *local* hidden variables can reproduce the quantum mechanical
correlations. Nature is either non-local or non-realistic —
one of the two assumptions must fall.

```
Bell's Inequality (CHSH form):
  |E(a,b) − E(a,b') + E(a',b) + E(a',b')| ≤ 2   (local realism)

Quantum mechanical prediction:
  |S_QM| = 2√2 ≈ 2.828  (violates the inequality!)

Experiments (Aspect 1982; Zeilinger 1998 et al.):
  |S_exp| > 2  (QM confirmed, local hidden variables refuted)
```

## 1.3 The RFT Thesis

The RFT responds to this puzzle with a clear mechanistic picture:

> **Entanglement is no mystery and no "spook".**
>
> Entangled particles are not two separate objects with strange
> action at a distance. They are **topologically a single object** —
> a common vortex configuration of the resonance matrix, spatially extended.
>
> Non-locality = Common Resonance Mode of the resonance matrix.
> No signal is transmitted. No causality violation.
> The correlation was always encoded in the common guidance field.

This is not merely a new interpretation of the same mathematics. It is
a physically substantive statement about the structure of space itself:
the resonance matrix (DRM) is the medium that carries the "connection"
of entangled particles — not as an abstract mathematical object, but
as a real resonant field configuration.

---

# CHAPTER 2: COMMON RESONANCE MODES

## 2.1 The Guidance Field for Two Particles

The starting point is the RFT master equation (v3_001):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ
```

For a single particle, Ψ(x, t) describes its wave function in the
resonance matrix. The particle itself is a stable vortex (soliton)
in this field; its position and motion are determined by the guidance
field Ψ.

For **two particles**, the picture extends to a
6-dimensional configuration space:

```
Ψ = Ψ(x₁, x₂, t)

where x₁ = position of particle 1
      x₂ = position of particle 2
```

This common guidance field is a single, non-separable field configuration
in the resonance matrix. It is *not* the sum or product of two independent
single-particle fields.

## 2.2 Non-Separability: What Exactly Does This Mean?

A two-particle state is called *separable* if the common guidance field
can be written as a product of two single-particle fields:

```
Separable:    Ψ(x₁, x₂, t) = Ψ₁(x₁, t) · Ψ₂(x₂, t)
Entangled:    Ψ(x₁, x₂, t) ≠ Ψ₁(x₁, t) · Ψ₂(x₂, t)  for any Ψ₁, Ψ₂
```

In the separable case, particle 1 moves independently of particle 2:
its guidance field has no knowledge of the other's position. In the
entangled case, the common guidance field is topologically connected:
the motion of each particle depends on the current configuration of
the entire two-particle field.

## 2.3 The Guidance Equations for Entangled Particles

From the common guidance field Ψ(x₁, x₂, t) follow the
guidance velocities of both particles (analogous to Bohm, but adapted
to the RFT guidance field — see v3_011 Ch. 11.3 and 16.3):

```
v₁(t) = f(∇₁Ψ(x₁(t), x₂(t), t), Ψ(x₁(t), x₂(t), t))
v₂(t) = f(∇₂Ψ(x₁(t), x₂(t), t), Ψ(x₁(t), x₂(t), t))
```

where ∇₁ denotes the gradient with respect to x₁ and ∇₂ accordingly.

**Decisive consequence:** The guidance velocity of particle 1 depends
on the position x₂ of particle 2 — and vice versa. This coupling is
non-local and *instantaneous* in the sense of the guidance field.
It does not, however, transmit information (Ch. 4.3).

⚠️ Note (RFT lens, J.16): The guidance equation above is formulated
in the language of Bohmian mechanics by analogy. The RFT guidance field
v ∝ −∇V_eff from the master equation satisfies the same continuity equation.
Both formulations are equivalent for the two-particle case
(v3_011 Ch. 16.3, note). ○ MEDIUM

## 2.4 Formation of Common Modes: The λ-Term

How do entangled pairs arise? In the resonance matrix picture, through
an interaction in which two vortices emerge from a common parent vortex —
or through the direct coupling of two vortices via the nonlinear term
of the master equation.

The λ-term in the master equation:

```
λ|Ψ|²Ψ

is the nonlinearity term. It is decisive:
  → Without λ: linear wave equation → no solitons, no stable particles
  → With λ: nonlinear self-coupling → stable vortices (particles), solitons
```

When two vortices interact through this term, their fields couple such
that the resulting two-particle field Ψ(x₁, x₂) can no longer be written
as a product. The nonlinearity mixes the degrees of freedom inseparably.

**Candidate argument (○ MEDIUM):** Consider whether a product ansatz
Ψ(x₁, x₂) = Ψ₁(x₁)·Ψ₂(x₂) is consistent in the two-particle master
equation once λ ≠ 0. The nonlinear term then becomes:

```
λ|Ψ|²Ψ = λ|Ψ₁|²|Ψ₂|² · Ψ₁ · Ψ₂
```

In general, the time evolution under this coupling generates terms that
can no longer be accommodated in the product form: the back-reaction of
|Ψ₂|² on Ψ₁ creates a dependence that makes Ψ₁ a function of x₂.
The product becomes a non-separable total wave function.

🚩 DS-017-A (Priority HIGH): Formal verification of this argument from
the master equation without Hilbert space prerequisites. Can it be shown
that after a λ-term interaction, Ψ(x₁, x₂) is generically non-separable?

## 2.5 Persistence of the Common Mode

After the entangled pair is created, the two particles separate spatially.
The common guidance field Ψ(x₁, x₂, t), however, persists. It is a
property of the resonance matrix — no additional "connection" that needs
to be established, but the original topological link of the common mode.

```
Formation:
  t < 0: parent vortex (e.g. photon), Ψ(x,t) simple
  t = 0: decay/interaction → λ-term couples particles
  t > 0: Ψ(x₁, x₂, t) — one field configuration, two vortices

Spatial separation:
  |x₁ - x₂| → large
  Ψ(x₁, x₂) remains non-separable!  (as long as no decoherence)
```

The persistence of this non-separable field configuration is the
RFT mechanism behind the long range of entanglement.
How far it reaches and under what conditions it breaks down
is discussed in Chapter 6 (Decoherence).

---

# CHAPTER 3: COMMON RESONANCE MODE — CORE CONCEPT OF THE RFT

## 3.1 Definition (✓ HIGH — Franz, 04.04.2026)

The core concept of this document: **"Common Resonance Mode"**

> **Definition — ✓ HIGH (Franz Zollner, 04.04.2026):**
>
> Two objects share a *Common Resonance Mode* if their
> joint wave function Ψ(x₁, x₂) is not factorizable as a product
> Ψ₁(x₁) · Ψ₂(x₂) —
> generated by the λ-term of the master equation.
>
> Mechanism: Two waves meet → λ-term acts →
> fields become "interwoven" → Common Resonance Mode arises
> and persists.
>
> In RFT language: The two vortices are not two separate objects
> with action at a distance, but two aspects of the same common
> resonance matrix pattern.

## 3.2 What Exactly is a "Common Resonance Mode"?

Three descriptive levels help make the concept tangible:

**Level 1 (intuitive):**
```
Two entangled particles = two "ends" of a single
three-dimensional resonance pattern in the resonance matrix.

Analogy: A Möbius strip has two apparently separate boundary points
that are topologically connected — no cut between them can destroy
the topology of the strip without changing the strip itself.

Better (RFT-specific): The resonance matrix mode Ψ(x₁, x₂) is a
connected object in configuration space ℝ⁶.
```

**Level 2 (physical):**
```
Measuring particle 1 = locally "probing" a property
of the common configuration-space field.

The result is immediately known for particle 2, because:
→ There are no two separate realities for x₁ and x₂.
→ There is only one: Ψ(x₁, x₂, t) — and this is
  topologically connected with respect to x₁ and x₂.
```

**Level 3 (formal, ○ MEDIUM):**
```
Non-separability ↔ non-trivial entanglement entropy:

  ρ₁ = Tr₂(|Ψ⟩⟨Ψ|)  (reduced density matrix, particle 1)
  S₁ = −Tr(ρ₁ log ρ₁) > 0  ↔  Common Resonance Mode!

For Bell state |Ψ⟩ = (1/√2)(|↑↓⟩ − |↓↑⟩):
  S₁ = log(2) ≈ 0.693  (maximally entangled for 2-level system)
  → Maximum Common Resonance Mode! ✓

⚠️ RFT lens (J.16): These formulas use Hilbert space language.
In the discrete resonance matrix, S₁ is an effective description
of non-separability — not a fundamental axiom.
```

## 3.3 Comparison with the Photon: Similarity and Difference

An important comparison that must be made explicitly:

**Photon = 2 APs (e⁻ + e⁺) — canonical (Franz, 11.03.2026, ✓ HIGH):**

```
Photon:
  e⁻ (1 AP, left-circular) + e⁺ (1 AP, right-circular) = 2 APs
  → One bound, propagating object
  → Stable through vortex geometry
  → Not separable without annihilation (or pair production)

Entangled pair (e.g. e⁻e⁺ after photon decay):
  e⁻ (1 AP) + e⁺ (1 AP) = 2 separate particles
  → Spatially separable (no longer a bound vortex structure)
  → Connected through common guidance field Ψ(x₁, x₂)
    via Common Resonance Mode
  → Separable: decoherence breaks Common Resonance Mode
```

**The mechanism is similar, the situation different:**

```
In common:
  Both: Two APs share a common resonance matrix configuration.
  Both: The common object is non-separable as a product.

Difference:
  Photon: bound, compact, propagating — both APs at the same location
  Entanglement: separated, extended — APs far apart,
                but connected through Ψ(x₁, x₂) via Common Resonance Mode
```

In short: the photon is a *locally bound* two-AP object; entanglement
is a *spatially extended* common field configuration.
The basic mechanism (common resonance matrix mode) is the same —
but the boundary conditions differ substantially.

## 3.4 Object Hierarchy: Entanglement — Cooper Pair — Hadron

This is one of the deepest insights that the Common Resonance Mode concept
opens up: entanglement is not a special case, but the most general
representative of an entire **hierarchy of objects**, all defined by
sharing a common resonance matrix mode.

```
HIERARCHY OF COMMON RESONANCE MODES (✓ HIGH concept; ○ MEDIUM details):

┌─────────────────────────────────────────────────────────────────┐
│  ENTANGLEMENT               (Ch. 2–6 of this document)          │
│  Two vortices, λ-term interaction                               │
│  Ψ(x₁,x₂) non-separable                                        │
│  Coupling: weak (via guidance field)                            │
│  Range: arbitrary (until decoherence)                           │
│  Binding: none — particles separate freely                      │
│  Breakable: by decoherence (environmental coupling) ✓           │
│  Document: v3_017 (this)                                        │
├─────────────────────────────────────────────────────────────────┤
│  COOPER PAIR                (Superconductivity, v3_019)          │
│  Two electrons (1 AP each), bound via κ-mode of resonance matrix│
│  at T < T_c: common mode stable                                 │
│  Coupling: medium (phonon-equivalent resonance matrix vibration) │
│  Range: coherence length ξ (mesoscopic)                         │
│  Binding: weak — breaks at T > T_c                              │
│  Breakable: by thermal excitation of the resonance matrix       │
│  Document: v3_019 (Superconductivity)                           │
├─────────────────────────────────────────────────────────────────┤
│  HADRON (proton, neutron)   (v3_013)                            │
│  Three quarks (3 APs each = 9 APs total), sharing common        │
│  3D resonance matrix mode (color neutrality = mode closure)     │
│  Coupling: strong (κ_str >> κ_EM)                               │
│  Range: L₀ ~ l_P (sub-femtometer)                               │
│  Binding: strong — confinement = mode cannot be isolated        │
│  Breakable: not isolatable (topological instability 1–2 APs)   │
│  Document: v3_013 (Strong Interaction)                          │
└─────────────────────────────────────────────────────────────────┘
```

**Common denominator:** In all three cases the object is defined by a
Common Resonance Mode — a Ψ-configuration that cannot be written as a
product of independent single modes. What changes is the
**coupling strength** (λ, κ, κ_str) and the
**breaking condition** (decoherence / temperature / geometric impossibility):

```
Entanglement:  Common mode via λ-term         → breaks through decoherence
Cooper pair:   Common mode via κ-vibration    → breaks at T > T_c
Hadron:        Common mode via κ_str          → does not break (confinement)
```

**What this means:** The RFT, through the λ-term and the resonance mode
concept, provides a **unified mechanism** for phenomena that in standard
physics are described by entirely separate theories
(QM entanglement, BCS superconductivity, QCD confinement).
This is conceptually powerful — the formal elaboration of each branch
resides in the respective v3 documents.

⚠️ Confidence note: The hierarchy as a concept ✓ HIGH; the quantitative
transitions between levels (in particular Entanglement ↔ Cooper pair
via κ-scaling) are ○ MEDIUM and await v3_019.

🚩 DS-017-A (Priority HIGH — Franz confirmation 04.04.2026):

```
Task: Formal verification of the λ-term mechanism

Question: Can it be shown from the master equation
  ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ
that two vortices Ψ₁(x₁) and Ψ₂(x₂), after interacting
through the λ-term, form a common Ψ(x₁, x₂, t) that
CANNOT be written as a product Ψ₁(x₁, t) · Ψ₂(x₂, t)?

RFT lens (J.16): no Hilbert space, no tensor product!
J.23: Filter out NLS (nonlinear Schrödinger eq.) and
      continuum QFT — seek RFT-internal justification.

Expected result:
  Insert product ansatz Ψ = Ψ₁·Ψ₂ into two-particle master eq.
  → λ|Ψ|²Ψ = λ|Ψ₁|²|Ψ₂|²·Ψ₁·Ψ₂
  → Time evolution generates terms ∝ |Ψ₂(x₂)|² in the equation for Ψ₁
  → Ψ₁ becomes dependent on x₂ → product form breaks down ✓
```

---

# CHAPTER 4: BELL'S THEOREM AND THE RFT

## 4.1 What Bell's Theorem Proves

Bell (1964) proved: no theory that assumes the following can reproduce
quantum mechanical correlations:

```
Bell assumptions (classical):
  (L) Locality:     A(a, λ) independent of b or λ_B
  (R) Realism:      λ exists before measurement (hidden variable)
  (D) Determinism:  outcomes A, B ∈ {-1, +1} uniquely determined

Consequence (Bell-CHSH inequality):
  |S| = |E(a,b) − E(a,b') + E(a',b) + E(a',b')| ≤ 2

Experiment: |S| ≈ 2.828 > 2  →  Bell assumptions violated!
```

## 4.2 Why Bell's Theorem Does Not Exclude the RFT (RFT Lens, J.16)

Bell's proof excludes *local* hidden variables. The RFT has
hidden variables — namely the precise state of the common guidance field
Ψ(x₁, x₂) — but these are explicitly **non-local**.

⚠️ RFT lens (J.16): Bell's proof operates in the language of
continuous quantum field theory (Hilbert space, operators,
density matrix). In the discrete resonance matrix these structures
are not given a priori. The RFT mechanism must therefore be
formulated in its own language:

```
Bell locality requires:
  A(a, λ_A) independent of b and λ_B

RFT guidance field:
  v₁(t) depends on x₂(t)!  (via Ψ(x₁, x₂))
  → Bell locality is NOT satisfied in the RFT!
  → Bell's theorem DOES NOT EXCLUDE RFT! ✓

The RFT is therefore a theory with non-local hidden variables.
The hidden variable = guidance field configuration Ψ(x₁, x₂).
```

**Why the RFT reproduces Bell correlations:**

The common guidance field Ψ(x₁, x₂) is constructed such that it
produces exactly the same correlations as the standard formulation:

```
E_RFT(θ_A, θ_B) = -cos(θ_A - θ_B)

→ CHSH parameter: S_RFT = 2√2 ≈ 2.828 ✓
→ Identical to QM prediction!
→ Consistent with all Bell tests! ✓
```

## 4.3 The Hidden Variable in the RFT

In Bell's standard formulation, a "hidden variable" λ is a quantity
that uniquely determines the measurement outcome but is not directly
accessible to the observer. In the RFT this hidden variable is:

```
λ_RFT = complete configuration of Ψ(x₁, x₂, t)

Contains:
  - Vortex configuration at x₁: strength, phase, orientation
  - Vortex configuration at x₂: strength, phase, orientation
  - Common mode structure: topological connection

Non-local:
  → λ_RFT cannot be split into "λ_A at x₁" and "λ_B at x₂"
  → It is a single, indivisible field configuration in ℝ⁶!
```

Deterministic: given the complete configuration Ψ(x₁, x₂, t₀) at
time t₀, all subsequent measurement outcomes are in principle determined.
The apparent randomness follows from ignorance of the precise initial
conditions of the guidance field.

## 4.4 Terminology: "Non-Locality" in the RFT

To avoid misunderstandings:

```
NOT meant: "non-local action" (suggests signal transmission)
MEANT:      "Common Resonance Mode (common resonance matrix mode)"

The correlation does not arise because, upon measuring x₁,
a signal is sent to x₂. It is already encoded in the common
guidance field Ψ(x₁, x₂) — measurement merely reveals it.

Analogy (illustrative only):
  Two "endpoints" of a single resonance matrix configuration.
  Measuring one endpoint reveals something about the entire
  configuration — including the other endpoint.
  No signal flows: the information was always there.
```

---

# CHAPTER 5: THE EPR PARADOX — RESOLUTION IN THE RFT

## 5.1 The EPR Argument (1935)

Einstein, Podolsky, and Rosen formulated their paradox as follows:
if quantum mechanics is complete, it implies non-local actions that
contradict the theory of relativity. If it respects relativity,
it must be incomplete (lacking "elements of reality").

```
EPR dilemma:
  EITHER QM complete → non-local action (Einstein: unacceptable!)
  OR     QM incomplete → hidden variables needed

EPR preference: incompleteness + hidden variables
```

## 5.2 The RFT Response

The RFT agrees with Einstein on one essential point:

```
Einstein was right:
  There is indeed a non-local structure (guidance field Ψ(x₁,x₂)).
  The correlation is real and physically grounded.

But Einstein was wrong on one point:
  Non-locality ≠ non-local action.
  A correlation is not a causation.
```

**The RFT resolution in three steps:**

```
Step 1: Both particles arise from a common interaction (λ-term)
        → common guidance field Ψ(x₁, x₂) is created
          (Common Resonance Mode — Ψ(x₁,x₂) non-separable).

Step 2: The particles separate spatially, but the common guidance
        field Ψ(x₁, x₂, t) persists.
        → The correlation is already fully encoded in the field.

Step 3: Alice "measures" = her detector couples locally to particle 1.
        The measurement outcome reveals which aspect the common
        field Ψ has — and therefore what result Bob will obtain.
        → No signal sent. Correlation was always there. ✓
```

## 5.3 No Contradiction with Special Relativity

Special relativity forbids the transmission of information faster than
light. The RFT respects this:

```
What does NOT happen (RFT):
  ✗ Alice sends a signal to Bob
  ✗ Energy or information flows from x_A to x_B
  ✗ Change of the resonance matrix at x_A influences causal structure at x_B

What DOES happen (RFT):
  ✓ Measurement at x_A = local interaction with global object Ψ(x₁,x₂)
  ✓ The global object always has a defined correlation structure
  ✓ Bob "reads" this structure at his measurement (also locally)
  ✓ Only through classical communication (≤ c) can they identify
    the correlation as such

No-Signaling Theorem:
  P(Bob's outcome b | Alice measures) = P(Bob's outcome b | Alice does not measure)
  → Without Alice's message (via classical channel), Bob cannot
    determine whether Alice has measured or not! ✓
```

## 5.4 "Reality" in the RFT: A Physical Position

The EPR discussion revolves essentially around whether particles have
"definite properties" before measurement. The RFT takes a clear
physical position here:

```
RFT position:
  Yes, particles have definite properties before measurement!

  But: These properties are not classical properties
  (position, momentum as independent quantities), but aspects of
  the common guidance field Ψ(x₁, x₂).

  "Property of particle 1" does not exist independently of
  particle 2 — because there is no independent field Ψ₁(x₁).
  There is only the common field Ψ(x₁, x₂).

  This is realism — but not local classical realism.
  It is topological realism:
  → The common field configuration is real and determines outcomes.
  → It cannot be split into two local realities.
```

---

# CHAPTER 6: DECOHERENCE AS THE LIMIT OF ENTANGLEMENT

## 6.1 Why Entanglement Does Not Last Forever

The common guidance field Ψ(x₁, x₂, t) is determined not only by the
dynamics of the two entangled particles. It is in interaction with the
entire resonance matrix environment: other vortices, thermal fluctuations,
the κ-field of the resonance matrix itself.

This coupling to the environment causes **decoherence**: the Common
Resonance Mode of the common mode is progressively "measured" by
environmental couplings and thereby dissolved.

```
RFT picture of decoherence:
  t = 0:  Ψ(x₁, x₂) — non-separable (Common Resonance Mode)
  t > 0:  interaction with environmental vortices at x₁ and x₂
  t = τ_D: Ψ ≈ Ψ₁(x₁) · Ψ₂(x₂) — effectively separable
           → Common Resonance Mode broken! ✗
```

## 6.2 Decoherence as Environmental Entanglement

The decoherence mechanism is, in the language of the RFT, not a
special case but the same physics in a different direction: the entangled
particles become entangled with the environment. Thereby the Common
Resonance Mode distributes over an ever-larger system, until the pairwise
correlation between particles 1 and 2 vanishes for practical purposes.

```
Formal picture (RFT lens for Lindblad formalism! J.16):

  ∂ρ/∂t = −(i/ħ)[H, ρ] + Σ_k γ_k (L_k ρ L_k† − ½{L_k†L_k, ρ})

⚠️ Lindblad equation: QFT formalism (Hilbert space, operators).
   In the RFT: L_k corresponds to coupling of vortices to
   environmental κ-modes. The structural statement is transferable;
   formal derivation from the master equation pending (→ v3_018, DS-018).

Qualitative RFT statement (○ MEDIUM):
  Decoherence time τ_D ~ 1/(n_E · σ_int · v_E)

  n_E   = density of environmental vortices (thermal excitations)
  σ_int = effective interaction cross section (from κ and L₀)
  v_E   = typical velocity of environmental vortices
```

## 6.3 When Does the Common Resonance Mode Break?

The qualitative boundary: the Common Resonance Mode is broken as soon
as the environment contains "enough information" about the state of the
individual particles to distinguish between the two components of
the guidance field.

```
Limiting cases:
  Isolated, T → 0:  τ_D → ∞   (entanglement long-lived)
  Many environmental vortices, high T: τ_D short (fast decoherence)

RFT candidate (⚠️ LOW — not quantitatively derived from canonical parameters):
  τ_D ~ τ_int / (Q_system/Q_environment)

  τ_int = typical interaction time of resonance matrix modes
  Q = quality factor (from κ, γ, L₀)

🚩 Quantitative derivation of τ_D from master equation and
   canonical parameters (κ, γ, L₀, c): open → v3_018
```

## 6.4 Connection to v3_018

Decoherence is the central topic of the parallel document v3_018
(Entropy & Signal Theory). The present section is limited to the
statement relevant for entanglement: decoherence breaks the Common
Resonance Mode by distributing the common mode over multiple,
effectively separate modes through interaction with the environment.

The question of "when" is a quantitative question that v3_018 addresses.

---

# CHAPTER 7: EXPERIMENTAL CONSEQUENCES

## 7.1 Comparison: RFT and Standard Quantum Mechanics

In most experimentally accessible situations, the RFT makes the same
predictions as standard quantum mechanics:

```
RFT predictions identical to QM:
  ✓ E(θ_A, θ_B) = -cos(θ_A - θ_B)
  ✓ CHSH: S = 2√2 ≈ 2.828 (Bell violation)
  ✓ No FTL communication
  ✓ Born rule (mechanism: guidance field statistics)

Reason: Identical predictions because the common guidance field
Ψ(x₁, x₂) carries the same mathematics as the QM wave function —
but with physical interpretation instead of abstract description.
```

Stated honestly: in the domain of entanglement experiments (Bell tests,
EPR correlations, quantum cryptography, quantum teleportation), the RFT
does *not* differ experimentally from standard quantum mechanics.
Here the RFT is an alternative interpretation, not an alternative theory.

## 7.2 Possible Differences: Open Questions

In the longer term, differences might appear in regimes where the
nonlinear structure of the master equation (λ-term) or the discrete
resonance matrix structure (L₀ ~ l_P) becomes relevant:

```
Candidates for differences (⚠️ LOW — speculative):

1. High-energy precision tests:
   At energies near the Planck scale, the discrete L₀-structure
   of the resonance matrix could lead to deviations from the
   continuum-QM picture. Status: far beyond current experimental reach.

2. GHZ states (three-particle entanglement):
   |GHZ⟩ = (1/√2)(|↑↑↑⟩ + |↓↓↓⟩)
   In the RFT: three vortices with a common resonance matrix mode.
   Prediction: identical to QM, but RFT mechanism: common mode
   in ℝ⁹ (configuration space for 3 × ℝ³).
   Open: stability of the common mode as the number of APs grows.
   🚩 Not elaborated.

3. Entanglement in curved resonance matrix:
   Near strong gravity (near BH, v3_008):
   How does the common mode behave if the resonance matrix itself
   transitions to Mode 2? Speculative, no formalism.
```

## 7.3 Quantum Cryptography in the RFT Picture

Quantum key distribution (QKD) exploits the non-locality of entanglement
for secure key exchange. In the RFT picture:

```
BB84 / E91 in the RFT:
  Security rests on: Common Resonance Mode of the joint state
  → Any eavesdropping measurement by Eve = partial decoherence
    of the Common Resonance Mode
  → Error rate detectable by Alice and Bob ✓

Mechanism:
  Eve's detector couples to the common guidance field Ψ(x₁,x₂).
  → The field is modified by Eve's detector (partial decoherence)
  → Alice and Bob can statistically detect that Ψ was disturbed
  ✓ Consistent with standard QKD security statements
```

---

# CHAPTER 8: CONNECTION TO THE v3-SERIES

## 8.1 v3_001: Master Equation

The λ-term of the master equation is the origin of entanglement (Ch. 2.4).
Without λ = 0 the theory would be linear: superposition would be possible,
but genuine non-separable two-particle modes could not be generated
from single modes. The nonlinear λ-term is the mechanism that generates
Common Resonance Modes.

## 8.2 v3_006: Arrow of Time and Guidance Field

The arrow of time in the RFT arises from a slight mode asymmetry
(Φ = 2α/(1+α²) ≈ 0.01460). The guidance field Φ is the motor of the
arrow of time. The guidance field Ψ(x₁, x₂) in the entanglement context
is the same field — it also determines the temporal evolution of the
entangled configuration.

The question of Lorentz invariance of the simultaneous update of the
Common Resonance Mode upon measurement is directly connected to the
discussion in v3_006 and v3_011 Ch. 21.3: the measurement statistics are
Lorentz invariant, even if the guidance field itself does not avoid a
preferred reference frame.

## 8.3 v3_007: Space Topology — Why 3D is Decisive

The 3D structure of the resonance matrix (v3_007) is the framework in
which Common Resonance Modes can be defined at all. In 1D no vortex
is possible; in 2D stable soliton structures are absent; only in 3D
does the geometric foundation exist for stable anchor points
and thus for the carriers of common resonance matrix modes.

## 8.4 v3_011 Ch. 16–17: Starting Point

This document deepens and formalizes Chapters 16 and 17 of v3_011
Part 5. The core statements remain:

```
From v3_011 Ch. 16.3 (✓ HIGH, adopted):
  Entanglement = common guidance field Ψ(x₁, x₂, t)
  → Non-separable: Ψ(x₁,x₂) ≠ Ψ₁(x₁)·Ψ₂(x₂)
  → v₁ depends on x₂ (and vice versa) → instantaneous coupling

From v3_011 Ch. 17.4 (✓ HIGH, adopted):
  RFT: non-local (guidance field!) + deterministic
  → Bell's theorem does not exclude RFT
  → S_RFT = 2√2 ✓ (identical to QM)

New in v3_017:
  → "Common Resonance Mode" defined (✓ HIGH, Franz 04.04.2026)
  → λ-term as formation mechanism elaborated
  → Photon comparison clarified
  → Decoherence as limit elaborated (→ v3_018)
  → RFT lens for Bell explicit (J.16)
  → Object hierarchy: Entanglement → Cooper pair → Hadron
```

## 8.5 v3_016: AP Topology

v3_016 addresses the 720° periodicity of vortex structure and APs as
dimensional couplings. This is relevant for the further formalization
of the Common Resonance Mode: the mode structure in configuration space
could be characterized more precisely through winding numbers of vortices.

🚩 Connection v3_016 → v3_017: Can the Common Resonance Mode be formally
characterized through winding numbers of vortices in ℝ⁶?
(DS-017-B, optional)

---

# CHAPTER 9: HONEST LIMITS

## 9.1 Confidence Table

| Statement | Confidence | Source |
|---|---|---|
| Entanglement = common guidance field Ψ(x₁,x₂) | ✓ HIGH | v3_011 Ch. 16.3 |
| v₁ depends on x₂ (non-local coupling) | ✓ HIGH | v3_011 Ch. 16.3 |
| E_RFT(θ) = -cos(θ), S = 2√2 | ✓ HIGH | v3_011 Ch. 17.4 |
| RFT is non-local → Bell not applicable | ✓ HIGH | v3_011 Ch. 17.4 |
| No FTL signal transmission (no-signaling) | ✓ HIGH | v3_011 Ch. 16.4 |
| λ-term generates non-separability | ○ MEDIUM | Ch. 2.4; DS-017-A open |
| Common Resonance Mode (definition) | ✓ HIGH | Ch. 3.1; Franz 04.04.2026 |
| Persistence of common mode over large distances | ○ MEDIUM | Ch. 2.5 |
| Decoherence breaks Common Resonance Mode | ○ MEDIUM | Ch. 6; formal → v3_018 |
| τ_D quantitatively from canonical parameters | ⚠️ LOW | Ch. 6.3; → v3_018 |
| GHZ states in RFT | 🚩 OPEN | Ch. 7.2 |
| Lorentz invariance of guidance field | 🚩 OPEN | v3_011 Ch. 21.3 |
| Formal characterization via winding number in ℝ⁶ | 🚩 OPEN | Ch. 8.5 |

## 9.2 Open Questions in Detail

**✅ "Common Resonance Mode" — Franz-confirmed (04.04.2026):**

The term and definition (Ch. 3.1) are canonically confirmed.
Open remains the formal characterization through winding numbers in ℝ⁶
(DS-017-B, optional — not a blocker for Final v1.0).

**🚩 λ-term and non-separability (DS-017-A — intuition confirmed):**

Franz confirmed the intuition: two waves meet → λ-term acts → thereafter
they are "interwoven" (04.04.2026). The formal derivation from the master
equation without Hilbert space prerequisites remains open.

**🚩 Range of entanglement:**

Why does the Common Resonance Mode persist over light-years (in the
absence of decoherence)? The resonance matrix mode Ψ(x₁, x₂) is a
global object — there is no mechanism that spatially "attenuates" it
as long as no environmental coupling is present. This statement is
physically plausible but not formally proven from the master equation.

**⚠️ Lorentz invariance of the simultaneous update:**

Upon measurement at x₁, the common guidance field updates instantaneously.
In which reference frame is this update "simultaneous"? The measurement
statistics are Lorentz invariant (no signal), but the guidance field
itself apparently selects a preferred reference frame. This is a known
tension in all Bohmian theories and likewise open in the RFT
(v3_011 Ch. 21.3). Document as an open question, do not gloss over.

**⚠️ Decoherence time quantitatively:**

Deriving τ_D from canonical parameters (κ, γ, L₀, c) is an open task
for v3_018. The qualitative statement (environmental coupling breaks the
Common Resonance Mode) is robust; the number is open.

## 9.3 What These Limits Mean

```
These open questions do not weaken the core thesis:

Established (✓ HIGH):
  → Entanglement = common guidance field
  → RFT is non-local, Bell not applicable
  → No FTL communication
  → Identical Bell predictions to QM

Open (but no contradiction):
  → Formal characterization "Common Resonance Mode"
  → λ-term proof (DS-017-A)
  → Lorentz invariance of the guidance field

Stated honestly:
  v3_017 provides a mechanistic framework.
  Formal precision at the level of a rigorously
  derived theorem is still outstanding.
```

---

# CHAPTER 10: SUMMARY AND FORMULA OVERVIEW

## 10.1 Main Statements

**1. Entanglement is Common Resonance Mode (✓ HIGH — Franz 04.04.2026)**

Entangled particles are not two objects with strange action at a distance.
They are two aspects of *one* common, non-separable resonance mode
Ψ(x₁, x₂, t) of the resonance matrix. This non-separable field
configuration is what "Common Resonance Mode" means.

**2. Common guidance field as physical substrate (✓ HIGH)**

The guidance field Ψ(x₁, x₂, t) exists really in the configuration
space of the resonance matrix. It couples the motions of both particles
non-locally and instantaneously — without any signal being transmitted.

**3. Bell's theorem does not exclude the RFT (✓ HIGH)**

Bell excludes *local* hidden variables. The RFT has non-local hidden
variables (the guidance field Ψ(x₁, x₂)). No contradiction.
The RFT reproduces E(θ) = -cos(θ) and S = 2√2 exactly.

**4. EPR paradox resolved (✓ HIGH)**

Einstein was right: there is a real, non-local structure.
But: non-locality ≠ signal transmission. The correlation was always
encoded in the common guidance field. No causality violation.

**5. Decoherence breaks Common Resonance Mode (○ MEDIUM)**

Environmental coupling leads to effective separability of the field.
Quantitative limit: v3_018.

**6. Unified mechanism: Entanglement — Cooper pair — Hadron (✓ HIGH concept)**

All three phenomena are instances of the Common Resonance Mode
at different coupling strengths. The RFT provides a single mechanistic
framework where standard physics requires three separate theories.

## 10.2 Formula Overview

```
Master equation (v3_001):
  ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ

  λ-term = source of non-separability (entanglement)

Two-particle guidance field:
  Ψ(x₁, x₂, t) — non-separable in the entangled case:
  Ψ(x₁, x₂, t) ≠ Ψ₁(x₁, t) · Ψ₂(x₂, t)

Guidance field coupling:
  v₁ = f(∇₁Ψ(x₁, x₂, t) / Ψ(x₁, x₂, t))  [depends on x₂!]
  v₂ = f(∇₂Ψ(x₁, x₂, t) / Ψ(x₁, x₂, t))  [depends on x₁!]

Correlation (✓ HIGH):
  E_RFT(θ_A, θ_B) = -cos(θ_A - θ_B)

Bell-CHSH parameter (✓ HIGH):
  S_RFT = 2√2 ≈ 2.828  (> 2, Bell violation)

Entanglement entropy (confidence indicator, ○ MEDIUM):
  S₁ = −Tr(ρ₁ log ρ₁) > 0  ↔  Common Resonance Mode

Object hierarchy (✓ HIGH concept):
  Entanglement  via λ-term   → breaks through decoherence
  Cooper pair   via κ-mode   → breaks at T > T_c
  Hadron        via κ_str    → does not break (confinement)

Canonical parameters (✓ HIGH):
  α⁻¹ = 4π³ + π² + π = 137.036 304  [2.22 ppm from CODATA]
  L₀ = 1/κ  [primary definition, ħ-free!]
  Φ = 2α/(1+α²) ≈ 0.014 596
```

## 10.3 DeepSeek Tasks

```
DS-017-A (Priority HIGH):
  Show from the master equation without Hilbert space prerequisites:
  when two vortices interact through the λ-term, the resulting
  Ψ(x₁, x₂) cannot be written as a product Ψ₁(x₁)·Ψ₂(x₂).
  → J.16: apply RFT lens!
  → J.23: filter out mainstream QFT arguments (tensor product,
    Hilbert space) — seek RFT-internal justification.

DS-017-B (optional):
  Which RFT-internal quantity formally characterizes the
  "Common Resonance Mode"?
  Winding number of vortices in ℝ⁶-configuration space?
  κ-mode structure? Guidance field topology?
```

---

## Glossary: New Terms in v3_017

| German | English | Definition |
|---|---|---|
| Gemeinsame Resonanz-Mode | Common Resonance Mode | Ψ(x₁,x₂) not factorizable as Ψ₁·Ψ₂; generated by λ-term (✓ HIGH) |
| Führungsfeld (Zwei-Teilchen) | guidance field (two-particle) | Ψ(x₁,x₂,t) in 6D configuration space |
| Nicht-Separierbarkeit | non-separability | property: Ψ ≠ Ψ₁⊗Ψ₂ |
| Brechbedingung | breaking condition | condition under which Common Resonance Mode dissolves |
| Objekt-Hierarchie | object hierarchy | Entanglement → Cooper pair → Hadron as unified concept |

---

*RFT_v3_017_Entanglement_EN.md | Translation Final v1.0*
*Based on: RFT_v3_017_Verschraenkung_v1.0 (DE Final)*
*04 April 2026 | Working Instance 017*
*Key term: "Common Resonance Mode" = "Gemeinsame Resonanz-Mode" (Franz, 04.04.2026)*
