# RFT_v3_011 PART 1: FOUNDATIONS
# Quantum Mechanics — Deterministic Interpretation of the Resonance Matrix

**Version:** EN 1.0 (Translation of DE v3.0)
**Date:** 01 April 2026
**Author:** Franz Zollner
**Translation:** AI Instance T11a
**Language:** EN
**DC Reference:** v10.10

**License:** Creative Commons BY-NC-ND 4.0

---

> **Translation note:** This is the English translation of RFT_v3_011 Teil 1 (DE v3.0,
> 06.03.2026). Confidence levels and canonical parameters updated to DC v10.10
> (28.03.2026). Mathematical formulas are identical to the German source.
> Standalone document — no file-path references. Designed for physicists
> without prior RFT knowledge.

---

## 📖 Abstract — Part 1

This first part lays the conceptual foundations of the deterministic
interpretation of quantum mechanics within Resonance Field Theory (RFT).

**Core questions:**
- What is the wave function Ψ physically?
- Why does |Ψ|² appear as probability?
- What happens during the measurement process?

**RFT answers:**
1. Ψ is a modulation of the resonance matrix (physically real!)
2. |Ψ|² is energy density → statistics emerge from dynamics
3. Measurement is coupling + decoherence (no collapse!)

**Historical context:**
- Louis de Broglie (1927): Pilot-wave idea
- David Bohm (1952): Formal elaboration
- RFT (2025): Mechanistic derivation from the resonance matrix

---

## 📚 Table of Contents — Part 1

### **Chapter 1: The Quantum Dilemma**
1.1 Three Unanswered Questions
    - Question 1: What is Ψ?
    - Question 2: Why |Ψ|²?
    - Question 3: What is collapse?
1.2 Summary of Chapter 1

### **Chapter 2: Pilot-Wave Theories**
2.1 Louis de Broglie (1927)
2.2 David Bohm (1952)
2.3 The RFT Improvement (2025)
2.4 Summary of Chapter 2

### **Chapter 3: Determinism and Hidden Variables**
3.1 What does "deterministic" mean?
3.2 Hidden variables in RFT
3.3 Practical unmeasurability vs. principled existence
3.4 Bell's theorem and non-local hidden variables
3.5 Summary of Chapter 3

---

# CHAPTER 1: THE QUANTUM DILEMMA

## 1.1 Three Unanswered Questions

### Introduction

**Quantum mechanics works perfectly** — smartphones, lasers, MRI scanners,
transistors, GPS. All of these technologies are based on quantum mechanical
principles. Mathematical predictions agree with experiment to a precision of
10⁻¹² — no other theory in physics achieves this level of accuracy.

And yet: **three fundamental questions have remained unanswered for 100 years.**

These questions are not purely academic. They touch the core of what we can
know about reality:
- What actually exists?
- What can we in principle know?
- How does observation relate to reality?

Resonance Field Theory (RFT) offers new answers to these old questions —
not through new mathematics, but through a new **physical interpretation**
of the existing equations, anchored in the resonance matrix as the
fundamental physical structure.

---

## QUESTION 1: What is Ψ?

### The Problem

Every physics textbook contains:

$$i\hbar\frac{\partial\Psi}{\partial t} = \hat{H}\Psi$$

Ψ (Psi) is the **wave function**. It determines all predictions of quantum
mechanics. But: **what IS it?**

This is not a trivial question. The answer determines what quantum mechanics
says about reality.

---

### Four Possible Answers

**Answer 1: Copenhagen — "Ψ is our knowledge"**

```
Bohr, Heisenberg (1927):

Ψ describes our state of knowledge about the system.
→ Not a physical object
→ "Collapses" when we measure (= when we know more)
→ Question "What is Ψ really?" is meaningless

Problem:
How can "our knowledge" interfere?
The electron double-slit shows an interference pattern.
If Ψ is only knowledge — what interferes physically?
```

**Answer 2: Many Worlds — "Ψ is everything"**

```
Everett (1957):

The universal Ψ is fully real.
→ At every measurement: all outcomes realized
→ In different "branches" of the wave function
→ No collapse needed

Problem:
Where do probabilities come from?
Why |Ψ|² and not |Ψ|³ or |Ψ|?
→ No satisfactory mechanism.
```

**Answer 3: Bohm — "Ψ is a guidance field"**

```
Bohm (1952):

Ψ is a physical field that guides particles.
→ Particles have definite positions
→ Ψ "navigates" the particle (pilot wave!)
→ Born rule: from "Quantum Equilibrium" (postulated)

Problem:
Where does Ψ come from? What is its medium?
The guidance field is postulated, not derived.
```

**Answer 4: RFT — "Ψ is a resonance matrix modulation"**

```
Resonance Field Theory (2025):

Ψ is the displacement of the resonance matrix — the fundamental
dynamic resonance medium from which space itself is constituted.

→ Ψ is physically real (has energy, can interfere)
→ The medium is known: the resonance matrix (DRM)
→ Born rule is DERIVED (not postulated!)
→ Mechanistically complete
```

---

### Detailed Explanation: Three Levels

**LEVEL 1 (General audience):**

```
Imagine space itself is not empty.

It consists of a vast "resonance matrix" — a network of resonance
nodes that can oscillate.

When an electron exists, it is a particular oscillation
(a "vortex") in this resonance matrix.

The wave function Ψ?
→ That is the oscillatory motion of the resonance matrix
   surrounding this vortex.
→ Like water waves around a stone in a pond.
→ Physically real — not an abstraction!

Why can Ψ interfere?
→ Because waves can superpose.
→ Two resonance-matrix oscillations can reinforce or cancel.
→ Exactly like water waves!
```

**LEVEL 2 (Engineers):**

```
The resonance matrix has a Master Equation (v3_001 — Mathematical Foundations):

∂²Ψ/∂t² = c²∇²Ψ − γ·∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η

Symbols:
κ = resonance rigidity of the resonance matrix [PRIMARY QUANTITY]
γ = damping term (arrow of time)
λ = nonlinearity coefficient
η = noise (stochastic excitation)

In the low-energy limit, this simplifies to:
iħ·∂Ψ/∂t = -ħ²/(2m)·∇²Ψ + V·Ψ
→ That is the Schrödinger equation!

So: the Schrödinger equation = low-field approximation of the
RFT Master Equation.

Ψ in the Schrödinger equation is therefore:
→ The displacement of the resonance matrix
→ A physical field, not an abstract object
```

**LEVEL 3 (Physicists):**

```
Ontological status of Ψ in RFT:

Ψ(x,t): real physical field
[Ψ] = m⁻³/² (for normalized QM wave function)

Energy density:
ρ_E(x,t) = ½κ²|Ψ(x,t)|²

Interpretation:
→ |Ψ|² is PRIMARY: an energy density distribution
→ |Ψ|² as probability is SECONDARY:
   emerges from the energy distribution (Born rule)

Complexity of Ψ:
Ψ is complex due to U(1) symmetry of the resonance matrix.
The phase of Ψ has physical significance
(interference, Aharonov-Bohm effect).

Connection to the Master Equation:
The Schrödinger equation is the linearized,
non-relativistic limit of the Master Equation.
Corrections at high energies: nonlinear (λ|Ψ|²Ψ term).

Lorentz invariance:
⚠️ Not yet formally proved for the discrete resonance matrix model.
Open research question (see Part 5, Chapter 21.3).
```

---

## QUESTION 2: Why |Ψ|²?

### The Problem: Born's Rule

Max Born established in 1926:

$$P(x) = |\Psi(x)|^2$$

The **probability** of finding a particle at position x is the squared
magnitude of the wave function.

**This works perfectly. But why the square?**

Why not |Ψ|? Why not |Ψ|³? Why not |Ψ|²·cos(φ)?

All previous interpretations could only **postulate** this — not explain it.
RFT derives it.

---

### Detailed Explanation: Three Levels

**LEVEL 1 (General audience):**

```
Imagine Ψ is a water wave.

The "height" of the wave is |Ψ|.
The "energy" of the wave is |Ψ|².
(Energy of a wave ∝ amplitude²)

Where the energy is large:
→ Resonance matrix oscillates strongly
→ Vortex object (particle) is strongly driven
→ Particle spends more time there
→ We find it there more often

So:
|Ψ|² = energy density = probability of presence

This is not coincidence!
This is physics: energy governs dynamics.
```

**LEVEL 2 (Engineers):**

```
The full causal chain in RFT:

Step 1: Energy density
ρ_E(x) = ½κ²|Ψ(x)|²
→ Resonance-matrix energy proportional to |Ψ|²

Step 2: Guidance potential
V_eff(x) = -½c²·α_K·|Ψ(x)|²
[α_K: coupling strength particle–resonance matrix
 Note: NOT the fine structure constant α ≈ 1/137!]

Step 3: Guidance force
F(x) = -∇V_eff(x) = +½c²·α_K·∇|Ψ(x)|²
→ Attracts particle toward high |Ψ|²

Step 4: Trajectories
m·d²x₀/dt² = F(x₀(t))
→ Deterministic, but initial position unknown

Step 5: Statistics
Unknown initial position x₀(0)
→ Ensemble of many trajectories
→ Thermalization (ergodic behavior)

Step 6: Born rule emerges
P(x) ∝ |Ψ(x)|²   ✓

This is not an assumption — it follows from the dynamics!
```

**LEVEL 3 (Physicists):**

```
Formal derivation (approach):

Given: guidance potential V_eff = -½c²·α_K·|Ψ|²

Liouville equation for ensemble density ρ(x,t):
∂ρ/∂t + ∇·(ρ·v) = 0

Equilibrium state (∂ρ/∂t = 0):
Stationary solution: ρ ∝ |Ψ|²

Thermal argument:
Under ergodic conditions, any arbitrary initial distribution
relaxes to ρ = |Ψ|².

This is the origin of Born's rule in RFT:
→ Not an assumption (as in Bohm)
→ Not a reinterpretation (as in Copenhagen)
→ Thermodynamic consequence of resonance-matrix dynamics

⚠️ Confidence: MEDIUM (○)
Direction of derivation clear and consistent.
Rigorous proof from the Master Equation:
not yet fully carried out (see Part 5, Chapter 21.2).
```

---

## QUESTION 3: What is "Collapse"?

### The Problem: The Mysterious Collapse

In the Copenhagen interpretation, the wave function "collapses" during
measurement:

```
BEFORE measurement:  Ψ = α|↑⟩ + β|↓⟩    (superposition)
AFTER measurement:   Ψ = |↑⟩              (collapsed)
```

This raises immediate questions:
- How quickly does it happen? (Instantaneous?)
- What counts as a "measurement"?
- Does it require an observer?
- Does collapse violate the Schrödinger equation?

These questions have occupied physics for 100 years.
RFT replaces "collapse" with physical mechanisms.

---

### Detailed Explanation: Three Levels

**LEVEL 1 (General audience):**

```
"Collapse" sounds mysterious — but it is simply
interaction + loss of information.

Analogy: a droplet in the ocean

A water droplet falls into the sea.
Before: the droplet has a definite shape.
After:  the waves have dispersed throughout the ocean.
        The droplet has "collapsed".

Was this a mystery? No — just physics!
Energy and momentum have redistributed.

The same applies to quantum measurement:

Before:  electron in superposition (resonance matrix oscillating
         in several modes simultaneously)
After:   interaction with measurement device transfers
         the mode structure → coherence is lost
         → we observe a definite result

This is not mysterious.
This is thermodynamics.
```

**LEVEL 2 (Engineers):**

```
The measurement process in RFT — 5 steps:

Step 1: Initial state
System S:        Ψ_S = α|0⟩ + β|1⟩  (superposition)
Measurement device M: Ψ_M = |ready⟩
Environment E:   Ψ_E = |ground state⟩

Step 2: Coupling system–device
Interaction Hamiltonian: H_int = g·Ô_S ⊗ Ô_M
Coupling for time τ_int ~ ħ/g ~ 10⁻¹⁵ s
→ Entanglement is created:
  Ψ_SM = α|0⟩|reads 0⟩ + β|1⟩|reads 1⟩

Step 3: Decoherence through environment
Device M has N_M ~ 10²³ degrees of freedom.
Environment couples to all N_M degrees of freedom.
Time: τ_D ~ ħ/(N_M·k_B·T) ~ 10⁻²¹ s

Step 4: Loss of coherence
Off-diagonal elements of the density matrix:
ρ_off(t) = ρ_off(0)·exp(-t/τ_D)
→ For t >> τ_D: ρ_off ≈ 0

Step 5: Classical result
Density matrix has only diagonal elements:
ρ = |α|²|0⟩⟨0| + |β|²|1⟩⟨1|
→ Classical probabilities!
→ "Collapse" fully explained.

Important timescales:
τ_D ≈ 10⁻²¹ s  ≪  τ_int ≈ 10⁻¹⁵ s  ≪  τ_obs ≈ 10⁻³ s
→ Collapse appears instantaneous, but is continuous.
```

**LEVEL 3 (Physicists):**

```
Decoherence in RFT:

Starting point: full quantum mechanics always applies.
Schrödinger equation for the total system S+M+E.

Reduced density matrix of system S (after partial trace):
ρ_S(t) = Tr_{M,E}[|Ψ_SME(t)⟩⟨Ψ_SME(t)|]

Pointer basis states {|n⟩} defined by H_int:
H_int |n⟩ = ε_n|n⟩

Timescale hierarchy:
τ_D = ħ/(N_M·k_B·T)      [decoherence time]
τ_R = exp(S/k_B)·τ_D     [Poincaré recurrence — astronomically long]

For t >> τ_D:
⟨m|ρ_S|n⟩ → δ_mn·|⟨n|Ψ_S⟩|²

This is the Born rule as diagonalization!

RFT specifics:
The resonance matrix provides the mechanism for H_int.
Coupling via anchor points (AP):
→ Particle couples to the resonance matrix via AP
→ Resonance matrix couples to environmental degrees of freedom
→ Decoherence channel fully defined

Observer:
In RFT no observer is required.
Decoherence occurs through physical interaction.
"Observer" in the Copenhagen interpretation =
"sufficiently large measurement device" in RFT.
```

---

## 1.2 Summary of Chapter 1

**The three great questions of quantum mechanics:**

### **Question 1: What IS Ψ?**

| Interpretation | Answer | Ontology | Explanatory power |
|----------------|--------|----------|-------------------|
| Copenhagen | Knowledge state | Epistemic | ⭐ (no derivation) |
| Many Worlds | Universal Ψ | Ontic | ⭐⭐ (many worlds!) |
| Bohm | Guidance field | Ontic | ⭐⭐⭐ (postulated) |
| **RFT** | **Resonance matrix modulation** | **Ontic** | **⭐⭐⭐⭐** (mechanistic!) |

**RFT answer:**
```
✅ Ψ is physically real (field configuration of the resonance matrix)
✅ Ψ describes displacement of the resonance matrix
✅ Ψ has energy: ρ_E = ½κ²|Ψ|²
✅ Ψ can interfere (because it is a field!)
✅ Ψ is complex (due to U(1) symmetry)
```

---

### **Question 2: Why |Ψ|²?**

**Born's rule — comparison of explanations:**

| Interpretation | Mechanism | Derived? | Explanatory power |
|----------------|-----------|----------|-------------------|
| Copenhagen | Postulate | ❌ No | ⭐ (inexplicable) |
| Many Worlds | Branch weight | ❌ No | ⭐⭐ (implicit) |
| Bohm | Quantum Equilibrium | ❌ No | ⭐⭐ (postulated) |
| **RFT** | **Energy density → statistics** | **✅ Approach!** | **⭐⭐⭐⭐** (direction clear) |

**RFT causal chain:**
```
|Ψ|² → Energy density (ρ_E = ½κ²|Ψ|²)
     → Guidance potential (V_eff = -½c²·α_K·|Ψ|²)
     → Guidance force (F = -∇V_eff)
     → Trajectories (m·d²x₀/dt² = F)
     → Statistics (unknown x₀(0) + ergodicity)
     → Thermal equilibrium
     → P(x) ∝ |Ψ(x)|² (Born's rule!) ✓

⚠️ Status: approach conceptually clear.
   Rigorous proof from Master Equation: open (Part 5, Chapter 21.2).
```

---

### **Question 3: What is collapse?**

**Measurement process — comparison:**

| Aspect | Copenhagen | RFT |
|--------|------------|-----|
| **Mechanism** | Mysterious collapse | Coupling + decoherence |
| **Timescale** | Instantaneous (Δt=0) | Continuous (τ_D ~ 10⁻²¹ s) |
| **Reversible?** | No (axiom) | No (thermodynamics) |
| **Energy conserved?** | Unclear | Yes (in the total system) |
| **Observer required?** | Yes (or unclear) | No (decoherence always) |
| **Physical mechanism** | ❌ None | ✅ H_int + H_env |

**RFT measurement process:**
```
1. System S + device M (separate)
2. Coupling: H_int = g·Ô_S ⊗ Ô_M
3. Entanglement: |Ψ⟩_SM after τ_int ~ 10⁻¹⁵ s
4. Decoherence: environment E destroys coherence in τ_D ~ 10⁻²¹ s
5. Result: definite outcome (irreversible)
```

**Important timescales:**
```
τ_D  ~ 10⁻²¹ s  (decoherence M-E)
τ_int ~ 10⁻¹⁵ s  (coupling S-M)
τ_obs ~ 10⁻³ s   (human perception)

Hierarchy: τ_D ≪ τ_int ≪ τ_obs
→ Appears instantaneous, but is continuous!
```

---

### **Core message of Chapter 1:**

```
RFT resolves ALL three puzzles of quantum mechanics:

✅ Ψ is physically real (resonance matrix modulation)
✅ |Ψ|² is energy density (Born's rule from dynamics)
✅ Collapse is decoherence (physical, not mysterious)

PLUS:
✅ Mechanistically derived (not postulated!)
✅ Consistent with QM predictions (100%)
✅ New testable predictions (weak measurements)

OPEN (honestly):
⚠️ Born derivation: direction clear, proof not yet rigorous
⚠️ Lorentz invariance: formally still open
```

**Next chapter:** Historical development of pilot-wave theories

---

# CHAPTER 2: PILOT-WAVE THEORIES

## 2.1 Louis de Broglie (1927)

### The Revolutionary Idea

**Solvay Conference 1927, Brussels**

Louis de Broglie presented a radical idea:

> "Perhaps the particle is real and is guided by a wave!"

**Context:**

After de Broglie's doctoral thesis (1924), it was clear:
- Particles have wavelength: λ = h/p
- Waves have particle character: E = hf

But: **what does this mean physically?**

Copenhagen (Bohr, Heisenberg):
```
"Wave-particle duality is complementary"
"Particle OR wave, depending on the experiment"
"Not simultaneously!"
```

De Broglie:
```
"No! Particle AND wave SIMULTANEOUSLY!"
"Particle is guided by wave"
"Pilot wave!"
```

---

### Mathematical Formulation (de Broglie 1927)

**Particle:**
- Position: x(t) (definite, always!)
- Velocity: v(t)

**Wave:**
- Wave function: ψ(x,t)
- Phase: S(x,t)

**Decomposition:**
$$\psi(x,t) = R(x,t) \cdot e^{iS(x,t)/\hbar}$$

> ¹ **Note on ħ (v3-series):** In RFT, ħ is an algebraic identity,
> not a fundamental input. The primary quantity is κ (resonance rigidity
> of the resonance matrix). The relation reads: ħ = mc/κ. In the context
> of this quantum mechanics presentation, ħ is retained as familiar
> notation; the causal direction is κ → ħ, not the reverse.
> See v3_004 (Impulse & Energy), Chapter 6.

**Symbols explained:**

```
R(x,t): amplitude (real-valued)
        [R] = 1/m^(3/2) (in 3D)
        R ≥ 0 (always non-negative)
        |ψ|² = R²

S(x,t): phase function (real-valued)
        [S] = J·s (action)
        S as in classical mechanics (Hamilton-Jacobi!)

e^(iS/ħ): complex phase
           |e^(iS/ħ)| = 1 (unit circle)
           arg(e^(iS/ħ)) = S/ħ (phase angle)
```

**Guidance equation (de Broglie):**

$$v(t) = \frac{1}{m}\nabla S\Big|_{x=x(t)}$$

**What does this mean?**

**LEVEL 1 (General audience):**

```
The wave ψ has a "phase" S(x,t):
→ Like the phase of a water wave

The particle follows the gradient of the phase:
→ Like a surfer riding the wave!

∇S points in the direction of "steepest ascent" of S
→ The particle moves in this direction

Velocity proportional to ∇S:
→ Larger gradient = faster motion
```

**LEVEL 2 (Engineers):**

```
Gradient: ∇S = (∂S/∂x, ∂S/∂y, ∂S/∂z)
          [∇S] = [S]/m = (J·s)/m = kg·m/s
          → That is a momentum!

Connection:
p = ∇S (de Broglie relation in position representation)

Velocity:
v = p/m = (∇S)/m

This is EXACTLY like classical mechanics:
Hamilton-Jacobi: p_i = ∂S/∂x_i
```

**LEVEL 3 (Physicists):**

```
Hamilton-Jacobi theory (classical mechanics):
H(x, ∇S, t) + ∂S/∂t = 0

For a free particle:
H = p²/(2m) = (∇S)²/(2m)

So:
(∇S)²/(2m) + ∂S/∂t = 0

This is the classical limit!

De Broglie proposed:
→ Also in QM: v = (∇S)/m
→ But S comes from ψ = R·e^(iS/ħ)
→ Schrödinger equation determines S!
```

---

### Example — Free Particle

**Plane wave:**

$$\psi(x,t) = A \cdot e^{i(kx - \omega t)}$$

**Symbols:**

```
A: amplitude (constant)
   [A] = 1/m^(3/2)

k: wave number [1/m]
   Connection: p = ħk (de Broglie)

ω: angular frequency [1/s]
   Connection: E = ħω (Planck-Einstein)
```

**Phase:**

$$S(x,t) = \hbar(kx - \omega t)$$

```
Gradient:
∇S = ħk

Velocity (de Broglie):
v = (∇S)/m = ħk/m = p/m  ✓

This is the classical particle velocity!
```

---

### Why Was de Broglie's Theory Rejected?

**Pauli's critique (Solvay 1927):**

Wolfgang Pauli asked a devastating question:

> "What happens at a node of a standing wave?"

**The problem:**

Standing wave: $\psi(x,t) = A \sin(kx) \cdot e^{-i\omega t}$

At nodes: $\sin(kx_n) = 0$
```
→ ψ(x_n, t) = 0
→ R(x_n, t) = 0

Gradient:
∇S = ?  →  at R = 0, S is undefined!
→ ψ = 0 · e^(iS/ħ)
→ S can be arbitrary!
```

**De Broglie had no good answer.** He gave up.
The pilot-wave idea was dormant for 25 years.

---

### What de Broglie Got Right

```
✅ Particles have definite positions x(t)
✅ Wave ψ is physically real
✅ Wave guides particle (pilot!)
✅ Deterministic trajectories
✅ Compatible with QM predictions

❌ Mechanism at nodes (R=0)
❌ Treatment of spinors
❌ Generalization to many particles
❌ Physical interpretation of phase S
```

**Bohm would close these gaps 25 years later.**

---

## 2.2 David Bohm (1952)

### The Rediscovery

**Princeton, 1951**

David Bohm, a young professor of theoretical physics, was dissatisfied:
- Had written a textbook on QM (following Copenhagen)
- Einstein encouraged him: *"Perhaps there are hidden variables after all!"*

**Result:** Two landmark papers (Physical Review, 1952)

---

### Bohm's Approach

**Step 1: Polar decomposition** — exactly like de Broglie:

$$\Psi(x,t) = R(x,t) \cdot e^{iS(x,t)/\hbar}$$

**Step 2: Insert into Schrödinger equation**

$$i\hbar\frac{\partial\Psi}{\partial t} = -\frac{\hbar^2}{2m}\nabla^2\Psi + V\Psi$$

**Step 3: Two coupled real equations**

After separating real and imaginary parts:

**Equation 1 (real part) — Modified Hamilton-Jacobi:**

$$\frac{\partial S}{\partial t} + \frac{(\nabla S)^2}{2m} + V + Q = 0$$

where the **quantum potential:**

$$Q(x,t) = -\frac{\hbar^2}{2m}\frac{\nabla^2 R}{R}$$

**Equation 2 (imaginary part) — Continuity equation:**

$$\frac{\partial R^2}{\partial t} + \nabla \cdot \left(R^2 \frac{\nabla S}{m}\right) = 0$$

With ρ = R² = |Ψ|² and v = (∇S)/m → this is probability conservation!

**Step 4: Guidance equation**

$$v(t) = \frac{1}{m}\nabla S\Big|_{x=x(t)}$$

**Step 5: Newtonian equation of motion**

$$m\frac{dv}{dt} = -\nabla(V + Q)\Big|_{x=x(t)}$$

---

### The Quantum Potential Q

$$Q(x,t) = -\frac{\hbar^2}{2m}\frac{\nabla^2 R}{R}$$

**LEVEL 1 (General audience):**

```
Imagine a hilly landscape (this is R):

∇²R measures the "curvature" of the landscape:
→ Concave (∩): ∇²R < 0 (mountain peak)
→ Convex (∪):  ∇²R > 0 (valley)

Q = -(ħ²/2m)·(∇²R/R)

Strong curvature → large |Q| → large quantum effect
Weak curvature → small |Q| → nearly classical
```

**LEVEL 2 (Engineers):**

```
The quantum potential has unusual properties:

1. Independent of amplitude R:
   Q ∝ (∇²R)/R → even at small R, Q can be large!

2. Non-local:
   Q(x) depends on R(x') for ALL x'
   (Schrödinger is non-local)

3. Energy conservation:
   ∫Q|Ψ|²d³x = 0 (vanishes on average!)
   → Redistributes energy, does not create it

4. Vanishes classically:
   ħ → 0: Q → 0 → only important at small scales!
```

**LEVEL 3 (Physicists):**

```
RFT reinterpretation of the quantum potential:

In RFT, Q is not an independent postulate.
Q emerges from the resonance-matrix dynamics:

Q(x,t) = effect of the guidance field of the resonance matrix
        = expression of the non-locality of the resonance matrix

The resonance matrix is the physical medium that generates
Bohm's "quantum potential".
→ No more "mysterious" Q — it has a carrier!
```

---

### Bohm's Main Results (1952)

**1. Particles have definite trajectories x(t)**
```
Given:
- Initial position: x(0)
- Initial velocity: v(0) = (∇S(x(0),0))/m
- Wave function: Ψ(x,t) (from Schrödinger equation)

→ Trajectory x(t) uniquely determined
→ Equation of motion: m·dv/dt = -∇(V+Q)|_{x(t)}
→ Deterministic!
```

**2. Born's rule as statistical consequence**
```
If initial distribution P(x,0) = |Ψ(x,0)|²
Then (continuity equation!):
P(x,t) = |Ψ(x,t)|² for all t   [Quantum Equilibrium]
```

**3. Full equivalence with QM**
```
All QM predictions reproduced:
→ Interference ✓  → Tunneling ✓
→ Entanglement ✓  → Bell inequalities ✓
```

---

### Why Was Bohm Criticized?

**Main criticisms:**

| Criticism | Source | RFT answer |
|-----------|--------|------------|
| Quantum Equilibrium postulated | Pauli, Heisenberg | Born's rule is derived |
| Guidance field: no medium | Many | Resonance matrix = the medium |
| Non-relativistic | Correct | v3_004 + extension open |
| "Superfluous" (Occam's razor) | Copenhagen | Explains what Copenhagen cannot |

---

## 2.3 The RFT Improvement (2025)

### What RFT Goes Beyond Bohm

```
BOHM (1952):                      RFT (2025):
─────────────────────────         ─────────────────────────
Guidance field: postulated    →   Guidance field: from resonance matrix
Born's rule:    postulated    →   Born's rule:    derived (approach)
Medium of Ψ:   unknown        →   Medium of Ψ:   resonance matrix
Quantum potential Q: mystical →   Q: resonance-matrix dynamics
Particle structure: point-like →  Anchor points (AP): topological
```

### Anchor Points — The New Element

RFT introduces anchor points (AP) as topological coupling sites between
vortex objects (particles) and the resonance matrix:

```
FUNDAMENTAL STRUCTURE:
  Vortex object ←→ Anchor point ←→ Resonance matrix

AP = interface between particle and resonance matrix
AP = point at which vortex rotation couples to the resonance matrix

PARTICLE STRUCTURE (canonical, per DC v10.10):

  Electron (e⁻):  1 AP  [cyclonic vortex, left]   ✓ HIGH
  Positron (e⁺):  1 AP  [cyclonic vortex, right]  ✓ HIGH
  Photon  (γ):    2 AP  [bound e⁻/e⁺ vortex pair] ✓ HIGH (Franz, 11.03.2026)
  Quark:          3 AP  [individually, not shared]  ✓ HIGH
  Proton:         9 AP  [3 quarks × 3 AP]           ✓ HIGH

  Neutrino (ν):   0 AP  [not a vortex — longitudinal
                          pressure wave in the DRM]  ○ MEDIUM

RESONANCE CONDITION for stable bound states:
  n_AP ≥ n_dim = 3

PHOTON — two complementary descriptions (consistent, not contradictory):
  "2 AP" = particle structure (e⁻/e⁺ vortex pair)
  "n=0"  = field mode description (wave perspective, v3_001)
  → Analogous to wave-particle complementarity ✓ HIGH (Franz, 11.03.2026)

NEUTRINO (○ MEDIUM, longitudinal wave hypothesis):
  → 0 AP, no vortex, directed propagation
  → Couples via matrix tension (analogous to gravitational waves)
  → RFT prediction: propagates at c — consistent with SN 1987A
     simultaneous arrival ○ MEDIUM
  → Open: neutrino oscillations reconciled via κ > 0 (small)
```

### The RFT Guidance Equation (Basic Form)

From the Master Equation of the resonance matrix:

$$m\frac{d^2x_0}{dt^2} = -\nabla V_{eff}\Big|_{x_0(t)}$$

with:

$$V_{eff}(x,t) = V(x) + Q_{RFT}(x,t)$$

where:

$$Q_{RFT} = -\frac{c^2 \cdot \alpha_K}{2}\frac{\nabla^2|\Psi|}{|\Psi|}$$

[α_K = core coupling strength (particle–resonance matrix).
 Not to be confused with the fine structure constant α ≈ 1/137.036!]

---

## 2.4 Summary of Chapter 2

**Historical development:**

```
1927  de Broglie:  Pilot-wave idea (pilot wave without medium)
1927  Pauli:       Node problem → idea rejected
1952  Bohm:        Full formalization (Quantum Equilibrium)
1952  Critics:     "Superfluous", "no explanation for Born"
2025  RFT:         Resonance matrix as medium → mechanistically complete
```

**Comparison:**

| Theory | Medium | Born's rule | Particle structure |
|--------|--------|-------------|-------------------|
| de Broglie | Unknown | Not treated | Point particle |
| Bohm | Postulated | Quantum Equilibrium | Point particle |
| **RFT** | **Resonance matrix** | **From dynamics** | **Anchor points (AP)** |

---

# CHAPTER 3: DETERMINISM AND HIDDEN VARIABLES

## 3.1 What Does "Deterministic" Mean?

### Definition

**Deterministic** = the present fully determines the future.

Formally:
```
State Z(t₀) known
+ Equations of motion known
→ Z(t) for all t > t₀ uniquely determined
```

**Is RFT deterministic?**

```
YES — fully!

Equations of motion:
1. m·d²x₀/dt² = -∇V_eff|_{x₀(t)}      [particle trajectory]
2. iħ·∂Ψ/∂t = ĤΨ                       [guidance field evolution]

Given:
- Initial position: x₀(0)
- Initial wave function: Ψ(x,0)

→ x₀(t) and Ψ(x,t) for all t > 0 uniquely determined.
→ 100% deterministic!
```

**Why does QM then appear statistical?**

```
Because x₀(0) is in principle unknown (Heisenberg uncertainty).

This is not fundamental randomness —
it is fundamental ignorance of initial conditions.

Exactly like a classical coin toss:
→ Deterministic (Newton's laws)
→ Appears random (initial conditions unknown)
```

---

## 3.2 Hidden Variables in RFT

**The four relevant variables:**

### **Variable 1: x₀(t) — Particle position**

```
LEVEL 1 (General audience):
The particle ALWAYS has a definite position.
Before measurement, during measurement, after measurement.
We simply do not know it.
```

```
LEVEL 2 (Engineers):
x₀(t): 3D vector field, continuously differentiable
Initial value x₀(0): the actual "hidden variable"
Heisenberg Δx·Δp ≥ ħ/2: measurement limit, not existence limit!
```

```
LEVEL 3 (Physicists):
In RFT, x₀(t) is ontologically real.
Heisenberg uncertainty is an epistemic limit,
not an ontological non-existence.

Precision of x₀(0): limited by the Planck scale
(~L₀ = 1/κ = (π/6)·l_P  [primary definition, ħ-free])
```

---

### **Variable 2: v(t) — Particle velocity**

```
v(t) = (∇S)/m |_{x=x₀(t)}

NOT independent:
→ Follows deterministically from x₀(t) and Ψ(x,t)
→ Not an independent hidden variable
```

---

### **Variable 3: φ(t) — Phase of the guidance field**

```
Decomposition: Ψ = R·e^(iφ/ħ)

φ(t): global phase at the particle's location
→ Influences trajectory via ∇S = ħ∇(arg Ψ)
→ Appears indirectly in interference experiments
→ Measurement cost: would destroy coherence
```

---

### **Variable 4: Ψ_field(x,t)**

```
LEVEL 1 (General audience):
The guidance field spreads out and creates interference.
It guides the core. Partially measurable (weak measurements).

LEVEL 2 (Engineers):
Ψ_field: solution of the Schrödinger equation (deterministic!)
Not independent — follows from initial value Ψ(x,0)
Like electromagnetic field: physically real, indirectly measurable.

LEVEL 3 (Physicists):
Time evolution: iħ∂Ψ/∂t = ĤΨ  (well-posed initial value problem)
Weak measurements: allow reconstruction of Re(Ψ), Im(Ψ)
Ontological status in RFT: displacement of the resonance matrix (ontic)
```

---

### Summary: Hidden Variables

| Variable | Independent? | Hidden? | Why hidden? |
|----------|-------------|---------|-------------|
| **x₀(t)** | ✅ Yes (initial value) | ✅ Yes | Δx·Δp ≥ ħ/2 |
| **v(t)** | ❌ No (from x₀ + ψ) | ❌ No | Follows from ψ |
| **φ(t)** | ✅ Yes (initial value) | ✅ Yes | Interference |
| **Ψ_field** | ❌ No (Schrödinger) | ⚠️ Partially | Decoherence |

**The essential hidden variable: x₀(0)**

All others follow from it + the Schrödinger equation!

---

## 3.3 Practical Unmeasurability vs. Principled Existence

### The Philosophical Question

> "If x₀(t) is in principle unmeasurable, does it make sense to say it exists?"

**Two positions:**

```
Instrumentalism (Copenhagen):
"Only what is measurable exists"
→ x₀(t) not measurable → x₀(t) does not exist

Realism (RFT):
"Reality exists independently of measurement"
→ x₀(t) exists objectively
→ It is merely: practically unmeasurable
```

**LEVEL 1 (General audience):**

```
Analogy — distant galaxy:
There is a galaxy 10 billion light-years away.
→ No human will ever visit it
→ Does it exist? — Of course!

Instrumentalist: "If we can never measure it,
                  the question is meaningless"
Realist (RFT):  "Our inability to measure
                  does not change its existence"

Exactly the same holds for x₀(t).
```

**LEVEL 2 (Engineers):**

```
Practical limit vs. fundamental limit:

PRACTICAL: moon crater to 1mm accuracy
→ Impossible today → technology will solve it

FUNDAMENTAL: x₀ and p simultaneously exact
→ Heisenberg: Δx·Δp ≥ ħ/2
→ Never possible (in principle)

x₀(t) in RFT:
→ Fundamental measurement limit (Heisenberg)
→ But: exists nonetheless!
```

**LEVEL 3 (Physicists):**

```
Ontology vs. epistemology:

Copenhagen (epistemic):
→ Ψ describes our knowledge
→ No ontology "beneath"

RFT (ontic):
→ Ψ_field describes a real resonance-matrix field
→ x₀(t) exists objectively
→ Epistemic limits ≠ ontological non-existence

Bell-type argument:
Bell (1964): local hidden variables ≠ QM
BUT: non-local hidden variables = QM ✓

RFT has non-local hidden variables:
→ Entanglement via resonance-matrix mode paths
→ ψ is non-local (resonance matrix couples everything)
→ Consistent with Bell!
```

---

## 3.4 Bell's Theorem and Non-Local Hidden Variables

### Bell's Theorem (1964)

**Bell showed:**

If a theory satisfies:
1. Locality: measurement at A does not influence B (for space-like separated events)
2. Realism: measurable quantities have definite values before measurement

→ Then: Bell inequalities must hold.

**Experimentally (Aspect 1982, many successors):**

The Bell inequalities are **violated**!
→ Either no locality OR no realism (or both).

---

### The RFT Response

```
RFT abandons locality — retains realism.

NON-LOCAL VARIABLES:
→ Ψ_field is non-local (instantaneous phase correlations)
→ Entangled particles: Ψ_SM(x_S, x_M, t)
   — shared field in 6D configuration space!
→ Resonance matrix couples both locations

NO SIGNAL TRANSMISSION:
→ Non-locality cannot be used for FTL communication
→ Measurement statistics follow QM (Born's rule)
→ No causality violation

CONSISTENCY WITH BELL:
→ Bell: local hidden variables ≠ QM ✓
→ RFT: non-local hidden variables = QM ✓
→ No contradiction!
```

---

## 3.5 Summary of Chapter 3

**Determinism:**

```
✅ RFT is fully deterministic
✅ Future states determined by present state
✅ Equation of motion: m·d²x₀/dt² = F(x₀, Ψ_field)
✅ Unique trajectories x₀(t)
```

**Hidden variables:**

| Variable | Status | Hidden because |
|----------|--------|----------------|
| x₀(t) | Essential | Heisenberg uncertainty |
| φ(t) | Important | Would destroy interference |
| Ψ_field(x,t) | Follows from Schrödinger | Partially measurable |

**Philosophy:**

```
Instrumentalism (Copenhagen):
→ "Only measurables exist"
→ No trajectories

Realism (RFT):
→ "Reality independent of measurement"
→ Trajectories exist objectively
→ Practically unmeasurable ≠ non-existent
```

**Next part:** Mathematical foundations (Master Equation,
limiting cases, two-component description)

---

**End of Part 1**

---

**© 2026 Franz Zollner — Resonance Field Theory Project**

**License:** Creative Commons BY-NC-ND 4.0
**Version:** EN 1.0 (Translation of DE v3.0)
**Date:** 01 April 2026
**Translated from:** RFT_v3_011_Teil1_Grundlagen.md, DE v3.0 (06.03.2026)
**DC Reference:** v10.10 (28.03.2026)

**Translation notes (T11a):**
- "Raummatrix" → "resonance matrix" / "DRM"
- "Führungsfeld" → "guidance field" (NOT "pilot wave" — avoids Bohmian connotation)
- "Ankerpunkt" → "anchor point (AP)"
- α_K used consistently throughout (≠ fine structure constant α)
- Photon status: upgraded to ✓ HIGH per DC v10.10 (Franz, 11.03.2026)
- Neutrino status: upgraded to ○ MEDIUM per DC v10.10 (Franz, 15.03.2026)
- L₀ = 1/κ added as primary definition (ħ-free) in Sec. 3.2
- Standalone document — all cross-references descriptive (no file paths)
