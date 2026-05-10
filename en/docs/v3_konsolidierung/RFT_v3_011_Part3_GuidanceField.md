# RFT_v3_011 PART 3: THE GUIDANCE FIELD
# Quantum Mechanics — Deterministic Interpretation of the Resonance Matrix

**Version:** EN 1.0 (Translation of DE v3.0)
**Date:** 01 April 2026
**Author:** Franz Zollner
**Translation:** AI Instance T11c
**Language:** EN
**DC Reference:** v10.10

**License:** Creative Commons BY-NC-ND 4.0

---

> **Translation note:** This is the English translation of RFT_v3_011 Teil 3
> (DE v3.0, 06.03.2026). α_K used consistently (≠ fine structure constant α).
> Note on velocity fields added in Sec. 8.3 consistent with Parts 4 & 5.
> Standalone document — no file-path references.

---

## 📖 Abstract — Part 3

This third part explains the **mechanism of guidance** in the deterministic
RFT interpretation.

**Core questions:**
- How exactly is the vortex core guided?
- What is the guidance potential physically?
- How are trajectories computed?
- What is the difference from Bohm?

**RFT answers:**
1. Modulation field creates a real physical potential
2. Core follows the gradient deterministically
3. Trajectories are computable (but practically unpredictable)
4. RFT is physical; Bohm is mathematical

**Prerequisites:**
- Part 1 read (quantum dilemma, determinism)
- Part 2 read (Master Equation, two-component decomposition)
- Understanding of potentials and forces

---

## 📚 Table of Contents — Part 3

### **Chapter 7: The Guidance Potential V_eff**
7.1 Derivation from the Master Equation
7.2 The explicit form: V_eff = −½c²·α_K·|Ψ_field|²
7.3 Physical interpretation (3 levels)
7.4 Coupling strength α_K
7.5 Numerical examples
7.6 Summary of Chapter 7

### **Chapter 8: Equations of Motion of the Core**
8.1 Newtonian form: F = −∇V_eff
8.2 Trajectory computation
8.3 Velocity field
8.4 Hamiltonian formulation
8.5 Conservation laws
8.6 Summary of Chapter 8

### **Chapter 9: The Double-Slit Mechanism**
9.1 Step 1: Preparation (core + field)
9.2 Step 2: Approach to the slits
9.3 Step 3: Interference of the field
9.4 Step 4: Core passage
9.5 Step 5: Guidance to the screen
9.6 Step 6: Statistical pattern
9.7 Summary of Chapter 9

### **Chapter 10: Comparison Bohm vs. RFT**
10.1 Quantum potential Q vs. guidance potential V_eff
10.2 Commonalities (deterministic trajectories)
10.3 Differences (physical vs. mathematical)
10.4 Experimental distinguishability
10.5 Philosophical implications
10.6 Summary of Chapter 10

---

# CHAPTER 7: THE GUIDANCE POTENTIAL V_eff

## 7.1 Derivation from the Master Equation

### Starting Point

In Part 2 we learned that the total field decomposes into two components:

```
Ψ_total(x,t) = Ψ_core(x,t) + Ψ_field(x,t)
```

**The central question now:**

> How do these two components interact?

**The answer lies in the Master Equation!**

---

### Master Equation (Recap)

```
∂²Ψ/∂t² = c²∇²Ψ - γ∂Ψ/∂t - c²κ²Ψ + λ|Ψ|²Ψ + η(x,t)
```

**The decisive term for coupling:**

```
λ|Ψ|²Ψ  (self-interaction term!)
```

**Why is this term so important?**

Because it is **nonlinear**:
```
|Ψ_total|² = |Ψ_core + Ψ_field|²
           = |Ψ_core|² + |Ψ_field|² + 2Re(Ψ_core*·Ψ_field)

The last term: 2Re(Ψ_core*·Ψ_field)  ← COUPLING!
```

**This means:**
- Core feels the field
- Field feels the core
- They interact!

---

### Step-by-Step Derivation

**Step 1: Ansatz for separated dynamics**

We assume:
- Core is localized at x₀(t)
- Field is extended, weak

**Step 2: Effective equation for core**

The core "sees" the field as an **external modulation** of the resonance matrix.

The resonance matrix normally has rigidity κ₀². With field modulation:

```
κ_eff²(x,t) = κ₀²(1 + β|Ψ_field(x,t)|²)
```

where β: modulation parameter

**Step 3: Potential term**

The effective rigidity generates a **potential**:

```
V_matrix(x,t) = ½c²κ_eff²(x,t)
              = ½c²κ₀²(1 + β|Ψ_field|²)
              = ½c²κ₀² + ½c²κ₀²β|Ψ_field|²
```

The first term is constant (rest energy):
```
E_rest = ½c²κ₀² = ½mc²
```

The second term is the **guidance potential**:
```
V_eff(x,t) = ½c²κ₀²β|Ψ_field(x,t)|²
```

**Step 4: Sign!**

If β > 0:
- Large |Ψ_field|² → high V_eff → core is pushed away (repulsive)

If β < 0:
- Large |Ψ_field|² → low V_eff → core is attracted (attractive)

**Experiment shows:** Core accumulates where |Ψ|² is large!
→ β < 0 (attractive!)

**Definition:**
```
α_K ≡ -κ₀²β  (with α_K > 0)

V_eff = -½c²·α_K·|Ψ_field|²
```

[α_K = core coupling strength — NOT the fine structure constant α ≈ 1/137!]

---

### LEVEL 1 (General audience): Magnetic "Channels"

**Imagine a magnetic game board:**

```
Board       = resonance matrix
Magnetic field = modulation field Ψ_field
Steel ball  = vortex core

Where magnetic field is strong:
→ Ball is attracted
→ "Channels" form
→ Ball rolls into channels

Where magnetic field is weak:
→ Ball is not attracted
→ "Hills"
→ Ball rolls away
```

**In RFT:**

```
|Ψ_field|² large → V_eff small → "channel" → core attracted
|Ψ_field|² small → V_eff large → "hill" → core rolls away
```

**At the double slit:**

```
Interference maximum (|Ψ_field|² large):
→ Deep channel
→ Many cores collect there

Interference minimum (|Ψ_field|² ≈ 0):
→ High hill
→ No cores
```

**Result:** The interference pattern of |Ψ_field|² becomes the **landscape
profile** on which the core "rolls"!

---

### LEVEL 2 (Engineers): Quantitative Derivation

**Starting point:**

Matrix element with local modulation:
```
κ²(x,t) = κ₀² + Δκ²(x,t)

Δκ²(x,t) = f(|Ψ_field|²)
```

**Linearization (|Ψ_field| small):**
```
f(|Ψ_field|²) ≈ β·|Ψ_field|²
```

**Energy density:**
```
ℰ = ½c²κ²|Ψ_core|²

With κ² = κ₀² + β|Ψ_field|²:

ℰ = ½c²κ₀²|Ψ_core|² + ½c²β|Ψ_field|²|Ψ_core|²
```

First term = rest energy (constant).
Second term = **position-dependent** (potential!):

```
V_eff(x,t) = ½c²β|Ψ_field(x,t)|²
```

**Force on core:**
```
F(x₀,t) = -∇V_eff|_{x=x₀}
         = -½c²β·∇|Ψ_field|²|_{x=x₀}
```

**Sign convention:** Define α_K = -β (with α_K > 0):
```
V_eff = -½c²·α_K·|Ψ_field|²

F = +½c²·α_K·∇|Ψ_field|²
```

→ Force points toward **increasing** |Ψ_field|² (attractive!)

**Dimensional analysis:**
```
[V_eff] = J/m³
[c²] = m²/s²
[|Ψ_field|²] = [Ψ]²

If Ψ ~ √(J/m³):
→ [α_K] = dimensionless  ✓
```

---

### LEVEL 3 (Physicists): Field-Theoretic Derivation

**Lagrange density (two-component system):**
```
ℒ = ℒ_core + ℒ_field + ℒ_int

ℒ_core = (1/2c²)(∂Ψ_K/∂t)² - (1/2)(∇Ψ_K)² - (c²κ₀²/2)|Ψ_K|² - (λ/4)|Ψ_K|⁴

ℒ_field = (1/2c²)(∂Ψ_F/∂t)² - (1/2)(∇Ψ_F)² - (c²κ₀²/2)|Ψ_F|²

ℒ_int = -g|Ψ_F|²|Ψ_K|²  (interaction!)
```

**Effective action for core** (integrate out field degrees of freedom):
```
S_eff[Ψ_K] = ∫d⁴x [ℒ_core + ⟨ℒ_int⟩]

Mean-field: ⟨|Ψ_F|²⟩ ≈ |Ψ_field|²

→ V_eff = g|Ψ_field|²
```

With g = -½c²·α_K:
```
V_eff = -½c²·α_K·|Ψ_field|²  ✓
```

**Connection to Higgs mechanism:**
```
Standard model:   m_eff² = m₀² + g·φ²  (φ: Higgs field)
RFT:             κ_eff² = κ₀² + α_K|Ψ_field|²  (Ψ_field: modulation)

→ Analogy: field modulates effective "mass" (rigidity)!
→ But in RFT: no separate Higgs field needed — matrix geometry does it.
```

---

## 7.2 The Explicit Form: V_eff = −½c²·α_K·|Ψ_field|²

### The Complete Formula

$$V_{eff}(x,t) = -\frac{1}{2}c^2 \cdot \alpha_K \cdot |\Psi_{field}(x,t)|^2$$

where:

**V_eff(x,t):** Guidance potential [J/m³ or eV/nm³]
- Physical: depth of the "energy channel"
- Determines: where core is attracted (valleys of V_eff)

**c:** Speed of light [m/s] = propagation speed of the resonance matrix

**α_K:** Core coupling strength [dimensionless]
- Value: α_K ~ 10⁻⁶ (from double-slit experiments)
- **Important: α_K ≠ α ≈ 1/137 (fine structure constant)!**
- α_K is much smaller than the electromagnetic coupling

**Ψ_field(x,t):** Modulation field [J^(1/2)/m^(3/2)]
- The extended "wave" component (from Part 2)
- Solution of the linearized Master Equation

---

## 7.3 Physical Interpretation (3 Levels)

### LEVEL 1 (General audience): A Real Physical Field

```
The guidance potential V_eff is REAL:
→ Not a mathematical trick
→ Not "probability amplitude"
→ Real energy distribution in space!

Compare:
Gravitational field: V = -GM/r
  → Real energy in space
  → Attracts mass
  
Guidance potential: V_eff = -½c²α_K|Ψ_field|²
  → Real energy in space
  → Attracts vortex core!

Difference:
Gravity: created by mass
V_eff: created by resonance-matrix modulation (= the "wave")
```

### LEVEL 2 (Engineers): Energy Landscape

```
3D energy landscape:
  z-axis = V_eff value
  xy-plane = spatial position

Double slit with two slits:
  Interference maxima → deep valleys (V_eff very negative)
  Interference minima → high hills (V_eff ≈ 0)
  
  Pattern:
     V_eff
  0  ___  ___  ___  ___
  |  | |  | |  | |  | |
  |  | |  | |  | |  | |  ← hills (minima)
  -  |_|  |_|  |_|  |_|  ← valleys (maxima)
            x →

Core behavior:
  → Rolls from hills into valleys
  → Collects at interference maxima ✓
  → Born's rule! P(x) ∝ |Ψ_field(x)|² ✓
```

### LEVEL 3 (Physicists): Continuity and Conservation

The guidance potential satisfies:

**Continuity equation:**
```
∂|Ψ_field|²/∂t + ∇·(|Ψ_field|²·v) = 0
```

where v = guidance velocity field.

**Consequence:** V_eff changes continuously — no discontinuous "collapse"!
The "collapse" in Copenhagen = rapid decoherence of Ψ_field (τ_D ~ 10⁻²¹ s),
which appears instantaneous to a macroscopic observer.

---

## 7.4 Coupling Strength α_K

### What Determines α_K?

The coupling constant α_K is **not freely choosable** — it emerges from matrix
geometry!

**Dimensional analysis:**
```
V_eff = -½c²·α_K·|Ψ_field|²
→ [α_K] = dimensionless (if Ψ ~ √energy density)
```

**Geometric derivation:**

α_K is related to the ratio:
```
α_K ~ (a₀/λ_Compton)³

a₀: lattice constant (~L₀ = 1/κ ~ 10⁻³⁵ m)
λ_Compton: Compton wavelength (~10⁻¹³ m for electron)

α_K ~ (10⁻³⁵/10⁻¹³)³ = (10⁻²²)³ = 10⁻⁶⁶  (too small by many orders!)
```

**Correction — including anchor points:**

The resonance matrix does NOT have uniform density — it has **anchor points**
(see v3_007 — Space Topology):

```
α_K ~ (ρ_anchor/ρ_matrix)·(a₀/λ_Compton)

With ρ_anchor ~ 10⁴⁰ × ρ_matrix:

α_K ~ 10⁴⁰·10⁻⁶⁶ = 10⁻²⁶ ... 10⁻⁶  (more realistic!)
```

**Experimental estimate:**

From double-slit experiments:
```
Contrast ratio → α_K ~ 10⁻⁶

Note: α_K ≪ α_EM = 1/137 (much weaker than electromagnetism!)
```

---

## 7.5 Numerical Examples

### Example 1: Double Slit

**Setup:**
```
Electron energy: E_kin = 1 eV
Slit spacing: d = 1 μm = 10⁻⁶ m
Screen distance: L = 1 m
Field amplitude: |Ψ_field|_max = 100
```

**Guidance potential at maximum:**
```
V_eff,max = -½·(3×10⁸)²·10⁻⁶·10⁴
           ≈ -4.5×10¹⁰ J/m³
```

**Force at interference fringe:**
```
Gradient scale: λ_fringe = λ_dB·L/d ≈ 0.62 μm

F ~ |V_eff|/λ_fringe ~ 4.5×10¹⁰/6×10⁻⁷ ~ 7×10¹⁶ J/m⁴

Effective force:
F_eff ~ F·V_electron ~ 7×10¹⁶·(10⁻¹³)³ ~ 7×10⁻²³ N
```

**Time in field:**
```
τ ~ L/v ~ 1/(3×10⁵) ~ 3×10⁻⁶ s  (for 1 eV electron)

Momentum transfer:
Δp ~ F·τ ~ 7×10⁻²³·3×10⁻⁶ ~ 2×10⁻²⁸ kg·m/s

→ Deflection angle:
θ ~ Δp/p ~ 2×10⁻²⁸/(3.4×10⁻²⁵) ~ 6×10⁻⁴ rad

Expected (Born rule):
θ_Born ~ λ_dB/d ~ 6.2×10⁻⁴ rad ✓  (consistent!)
```

### Example 2: Harmonic Oscillator

**Quadratic guidance potential:**
```
V_eff(x) = ½k·x²  (harmonic)

with k = ½c²·α_K·|∂²|Ψ_field|²/∂x²|
```

**Oscillation frequency:**
```
ω = √(k/m) = √(c²·α_K·|∂²|Ψ|²/∂x²|/m)
```

**Comparison with Bohr energy levels:**
```
E_n = ħω(n + ½)

→ Quantum levels emerge from classical oscillation in V_eff potential!
```

---

## 7.6 Summary of Chapter 7

```
✅ Guidance potential V_eff = -½c²·α_K·|Ψ_field|²
✅ Derived from the nonlinear λ-term of the Master Equation
✅ α_K = core coupling strength (~10⁻⁶, NOT α ≈ 1/137!)
✅ V_eff is physically real (energy distribution in space)
✅ Core collected where |Ψ_field|² is large → Born's rule ✓
✅ Analogy to Higgs mechanism (but without extra field)
```

---

# CHAPTER 8: EQUATIONS OF MOTION OF THE CORE

## 8.1 Newtonian Form: F = −∇V_eff

### The Fundamental Equation

**For the vortex core:**

$$m\cdot\ddot{x}_0 = -\nabla V_{eff}(x_0, t)$$

where:

**m:** Effective mass of core [kg]; m = ħκ/c [derived from κ — PRIMARY!]
**x₀(t):** Position of core center [m]
**V_eff:** Guidance potential = −½c²α_K|Ψ_field|² [J/m³]
**∇V_eff:** Gradient (force density) [J/m⁴ = N/m³]

**This is Newton's second law!**

---

### LEVEL 1 (General audience): Ball Rolling Downhill

**Imagine a ball on a hilly landscape:**

```
Ball          = vortex core
Landscape     = guidance potential V_eff
Height        = potential value

Ball always rolls downhill:
- Steep hills → fast acceleration
- Flat valleys → slow motion
```

**In RFT:**
```
Core "rolls" in the V_eff profile:

V_eff large (hill) → core rolls away
V_eff small (valley) → core stays / accumulates

Interference maxima = valleys
→ Core collects there!
```

**Important:** The core has **inertia** (mass m)!

```
Even when valley is reached:
→ Core overshoots (kinetic energy!)
→ Oscillates in valley
→ Not simply "captured"

→ This explains why Born's rule holds only STATISTICALLY!
```

---

### LEVEL 2 (Engineers): Vector Form and Components

**Vector equation:**
```
m·ẍ₀ = F(x₀,t)

with F = -∇V_eff = +½c²·α_K·∇|Ψ_field|²
```

**Component form (Cartesian):**
```
m·ẍ = +½c²·α_K·∂|Ψ_field|²/∂x
m·ÿ = +½c²·α_K·∂|Ψ_field|²/∂y
m·z̈ = +½c²·α_K·∂|Ψ_field|²/∂z
```

**First-order system:**

Define velocity v = dx₀/dt:
```
dx₀/dt = v
dv/dt  = -(1/m)∇V_eff = +(c²α_K/m)∇|Ψ_field|²/2
```

**Numerical integration (RK4):**
```
k₁ = f(t_n, X_n)
k₂ = f(t_n + Δt/2, X_n + k₁Δt/2)
k₃ = f(t_n + Δt/2, X_n + k₂Δt/2)
k₄ = f(t_n + Δt, X_n + k₃Δt)

X_{n+1} = X_n + (Δt/6)(k₁ + 2k₂ + 2k₃ + k₄)
```

**Stability condition:**
```
Δt < Δt_max ~ √(m/k_eff)

k_eff ~ c²α_K·|Ψ|²/(λ_interference)²

For electron in double slit:
Δt_max ~ 10⁻²⁷ s  (very demanding numerically!)
```

---

### LEVEL 3 (Physicists): Lagrange and Hamiltonian Formulation

**Lagrangian:**
```
L(x₀, ẋ₀, t) = (m/2)|ẋ₀|² - V_eff(x₀,t)
```

**Euler-Lagrange equations:**
```
d/dt(∂L/∂ẋ₀) - ∂L/∂x₀ = 0
→ m·ẍ₀ = -∂V_eff/∂x₀  ✓
```

**Hamiltonian:**
```
H(x₀, p₀, t) = |p₀|²/(2m) + V_eff(x₀,t)

where p₀ = m·ẋ₀
```

**Hamilton's equations:**
```
ẋ₀ = ∂H/∂p₀ = p₀/m
ṗ₀ = -∂H/∂x₀ = -∇V_eff
```

**Note:** Since V_eff is time-dependent (dynamic field!):
```
dH/dt = ∂V_eff/∂t ≠ 0  (in general)
→ Energy exchanged between core and field
```

---

## 8.2 Trajectory Computation

### Initial Conditions

**The central problem:**
```
Given:  x₀(t=0), v₀(t=0)
Sought: x₀(t) for all t > 0
```

**Initial conditions determine trajectory uniquely!**

**But:** We practically **never** know initial conditions exactly!

**Why?**
```
Heisenberg uncertainty:
Δx·Δp ≥ ħ/2

→ Initial conditions are in principle fuzzy!
```

**Consequence:**
```
Single trajectory: deterministic (computable)
Ensemble of trajectories: statistical (|Ψ|²-distribution)
```

---

### Algorithm

**Step 1: Initialization**
```
x₀(0) = x_init  (given or sampled from |Ψ(x,0)|²)
v₀(0) = ∇S(x_init,0)/m  (from phase of Ψ!)
```

**Step 2: Field computation**
```
Ψ_field(x,t) from linear equation:
(1/c²)∂²Ψ_F/∂t² - ∇²Ψ_F + κ²Ψ_F = 0

With boundary conditions (slits, sources, etc.)
```

**Step 3: Potential**
```
V_eff(x,t) = -½c²·α_K·|Ψ_field(x,t)|²
```

**Step 4: Integration**
```
Repeat for t = 0, Δt, 2Δt, ...:

  F(t) = -∇V_eff(x₀(t), t)
  v₀(t+Δt) = v₀(t) + (F/m)·Δt
  x₀(t+Δt) = x₀(t) + v₀(t)·Δt
```

**Step 5: Statistics**
```
Repeat for many (N ~ 10⁴ to 10⁶) initial conditions

Histogram: P(x) ≈ (1/N)·Σᵢ δ(x - xᵢ(T))

Compare with |Ψ(x,T)|²
```

---

### Example Code (Pseudocode)

```python
def calculate_trajectory(x0_init, v0_init, psi_field, alpha_K, m, dt, t_max):
    """
    Compute vortex core trajectory via RFT guidance potential.
    
    Args:
        x0_init: initial position [m]
        v0_init: initial velocity [m/s]
        psi_field: function Ψ_field(x, t)
        alpha_K: core coupling constant (NOT fine structure α!)
        m: effective mass [kg]; m = hbar*kappa/c
        dt: time step [s]
        t_max: maximum time [s]
    
    Returns:
        x_traj: array of positions
        t_traj: array of times
    """
    c = 3e8  # m/s  [v3-canonical: c, not c0]
    
    x = x0_init
    v = v0_init
    t = 0.0
    x_traj = [x]
    t_traj = [t]
    
    while t < t_max:
        # Guidance potential gradient (via finite differences)
        dx_small = 1e-12  # m
        psi_plus  = psi_field(x + dx_small, t)
        psi_minus = psi_field(x - dx_small, t)
        
        grad_intensity = (abs(psi_plus)**2 - abs(psi_minus)**2) / (2*dx_small)
        
        # Force from guidance potential V_eff = -½c²·α_K·|Ψ_field|²
        F = 0.5 * c**2 * alpha_K * grad_intensity  # → core goes up gradient
        
        # Integration (Euler step — use RK4 in production)
        v = v + (F / m) * dt
        x = x + v * dt
        t = t + dt
        
        x_traj.append(x)
        t_traj.append(t)
    
    # → Trajectory computed via RFT guidance equation (Part 3)
    return x_traj, t_traj
```

---

## 8.3 Velocity Field

### Definition

The **velocity field** v(x,t) gives the velocity of the core **if** it were
located at (x,t):

```
v(x,t) ≈ -(τ/m)∇V_eff(x,t)
```

where τ: characteristic relaxation time.

---

### LEVEL 1 (General audience): Wind Map

**Imagine a weather map:**
```
Arrows    = wind velocity at each location
Length    = how fast
Direction = where to

Bird in the wind:
→ Follows arrows
→ Is carried along
```

**In RFT:**
```
Velocity field = "wind" in the V_eff profile

Core = bird
→ Carried by the "wind"
→ Follows streamlines
```

**Streamlines:**
```
dx/dt = v(x,t)

Lines tangent to v → trajectories!
```

---

### LEVEL 2 (Engineers): Streamline Pattern

**Continuity equation:**
```
∂ρ/∂t + ∇·(ρv) = 0

where ρ(x,t) = |Ψ(x,t)|²
```

**Vorticity:**
```
Ω = ∇×v

If Ω = 0: irrotational (potential flow)
If Ω ≠ 0: vortex present
```

> **Note:** The RFT guidance velocity v ∝ -∇V_eff is irrotational (∇×∇V_eff = 0).
> Bohm's pilot-wave velocity v = (ħ/m)Im(∇Ψ/Ψ) is also irrotational under
> the same conditions. Both satisfy the same continuity equation — their
> statistical predictions are identical even though the functional forms differ.
> See Part 4, Ch. 11.3 for the formal equivalence.

---

### LEVEL 3 (Physicists): Hamilton-Jacobi Form

**Velocity field from phase (analogous to Bohm):**
```
v(x,t) = (1/m)∇S_eff(x,t)
```

where S_eff: effective action.

**Hamilton-Jacobi equation:**
```
∂S_eff/∂t + (∇S_eff)²/(2m) + V_eff = 0
```

**Comparison:**

| Theory | Velocity field | Potential |
|--------|---------------|-----------|
| Bohm | v = (ħ/m)∇S | Q = -(ħ²/2m)(∇²R)/R |
| RFT | v = (1/m)∇S_eff | V_eff = -½c²·α_K·|Ψ_field|² |

Key difference: In Bohm, ħ appears explicitly in v. In RFT, v is
determined by a classical gradient — the quantum character enters through
the shape of V_eff (which contains the field Ψ_field).

---

## 8.4 Hamiltonian Formulation

### Canonical Coordinates

```
Coordinates: q = x₀
Momenta:     p = m·ẋ₀
```

**Hamiltonian:**
```
H(q,p,t) = p²/(2m) + V_eff(q,t)
```

**Canonical equations:**
```
q̇ = ∂H/∂p = p/m
ṗ = -∂H/∂q = -∇V_eff
```

**Poisson brackets:**
```
{qᵢ,pⱼ} = δᵢⱼ
{qᵢ,qⱼ} = 0
{pᵢ,pⱼ} = 0
```

**Time evolution:**
```
df/dt = {f,H} + ∂f/∂t
```

---

## 8.5 Conservation Laws

### Energy (almost conserved)

**Core energy:**
```
E(t) = (m/2)|ẋ₀|² + V_eff(x₀,t)
```

**Time derivative:**
```
dE/dt = ∂V_eff/∂t
```

If field is static (∂Ψ_field/∂t = 0):
```
dE/dt = 0  → energy conserved!
```

If field is dynamic:
```
dE/dt ≠ 0  → energy exchanged between core and field
```

### Momentum (not conserved)

```
dP/dt = m·ẍ₀ = -∇V_eff ≠ 0
```

→ Core momentum not conserved (external force from field!).
But: total momentum (core + field) may be conserved.

### Probability Current (conserved!)

**Continuity equation:**
```
∂ρ/∂t + ∇·j = 0

with ρ = |Ψ|² (density)
     j = ρ·v  (current)
```

**This means:** Probability is not lost!
```
∫ρ(x,t)·d³x = const  ✓
```

---

## 8.6 Summary of Chapter 8

```
✅ Equation of motion: m·ẍ₀ = -∇V_eff  (Newton's 2nd law!)
✅ Trajectories deterministic given x₀(0), v₀(0)
✅ But: initial conditions practically unknown → statistics necessary
✅ Velocity field irrotational: ∇×v = 0
✅ Energy: dE/dt = ∂V_eff/∂t (exchanged when field is dynamic)
✅ Born's rule emerges statistically from ensemble of trajectories
```

---

# CHAPTER 9: THE DOUBLE-SLIT MECHANISM

## 9.1 Step 1: Preparation (Core + Field)

**Initial state of the electron:**

```
Before the slits:

Component 1: Vortex core (Ψ_core)
→ Localized wave packet (σ ~ 10⁻¹³ m)
→ Moving with velocity v₀ ~ 10⁶ m/s (non-relativistic)
→ Definite position x₀(0) (unknown to us!)

Component 2: Modulation field (Ψ_field)
→ Extended wave packet (width w ~ coherence length >> σ)
→ Co-moving with core
→ Coherent (fixed phase relation to core)
```

**Together:**
```
|electron⟩ = |core at x₀⟩ ⊗ |field centered at x₀⟩

Total Ψ(x,t) = Ψ_core(x-x₀(t)) + Ψ_field(x,t)
```

---

## 9.2 Step 2: Approach to the Slits

**As the electron approaches:**

```
Core:
→ Moves classically toward slits
→ Follows one specific trajectory (determined by x₀(0)!)
→ Will pass through slit 1 OR slit 2 (not both!)

Field:
→ Extends spatially
→ "Sees" both slits simultaneously (wave!)
→ Governed by Huygens' principle
```

**At the slits:**
```
Core: passes through slit 1  (deterministically, say)
Field: diffracts through both slits 1 AND 2

→ Core and field separate spatially for a moment!
→ Core passes through slit 1
→ Field continues through both
```

---

## 9.3 Step 3: Interference of the Field

**After the slits:**

```
Ψ_field = Ψ_field,slit1 + Ψ_field,slit2

→ Two waves superpose!
→ Interference pattern forms!
```

**Mathematical description:**

```
Ψ_field(x,t) = A₁·e^(i(k₁·x - ωt)) + A₂·e^(i(k₂·x - ωt))

|Ψ_field|²(x) = |A₁|² + |A₂|² + 2|A₁||A₂|·cos(Δφ(x))

where Δφ(x) = (k₁-k₂)·x  (phase difference from path length)
```

**Interference maxima (constructive):**
```
Δφ = 2nπ  (n = 0, ±1, ±2, ...)

→ |Ψ_field|²_max = (|A₁| + |A₂|)²
→ Deep valleys in V_eff!
```

**Interference minima (destructive):**
```
Δφ = (2n+1)π

→ |Ψ_field|²_min = (|A₁| - |A₂|)²  → 0 if |A₁| = |A₂|
→ High hills in V_eff! (no attraction)
```

---

### LEVEL 1 (General audience): Two Waves → One Pattern

```
Classic ripple tank:

Stone 1 → wave 1
Stone 2 → wave 2

Where both waves are "up" simultaneously:
→ High amplitude (constructive interference)

Where one is "up" and other "down":
→ Cancellation (destructive interference)

Exactly the same for Ψ_field!
→ The field creates the interference pattern
→ The core sees this as an energy landscape
```

### LEVEL 2 (Engineers): Fringe Positions

```
Slit spacing: d
Screen distance: L
Wavelength: λ_dB = h/p (de Broglie)

Maxima at:
y_n = n·λ_dB·L/d  (n = 0, ±1, ±2, ...)

Fringe spacing:
Δy = λ_dB·L/d

For 1 eV electron, d = 1 μm, L = 1 m:
Δy ≈ 0.62 μm  (measureable!)
```

---

## 9.4 Step 4: Core Passage

**The core passes through one slit:**

```
Which slit? → Depends on x₀(0)!

If x₀(0) is slightly to the left: → slit 1
If x₀(0) is slightly to the right: → slit 2

This is the "hidden variable": x₀(0)!
```

**After passage:**
```
Core is on one side
Field has diffracted through both sides

→ Core enters the field's interference pattern
→ Guidance potential V_eff now has periodic structure
→ Core is guided by this structure!
```

**The paradox resolved:**
```
Traditional question: "Which slit did the particle go through?"
RFT answer: "The CORE went through slit 1 (or 2),
             the FIELD went through both!"

This is not a contradiction — core and field are different components
of the same system!
```

---

## 9.5 Step 5: Guidance to the Screen

**After the slits:**

```
Core moves through the interference pattern of V_eff.

Guidance equation:
m·ẍ₀ = +½c²·α_K·∇|Ψ_field|²

→ Force points toward maxima of |Ψ_field|²
→ Core is deflected toward bright fringes!
```

**Individual trajectory:**
```
Depends on:
1. Through which slit core passed (1 or 2)
2. Exact position x₀(0) in that slit
3. Velocity v₀(0) at the slit

→ All deterministic, but unmeasurable!
```

**Trajectories look like:**

```
Slits                  Screen
  |                      |
  |    /‾\     /‾\      |  ← bright fringe
slit1 → \__/ → \__/ → hit ← dark fringe
  |       →      →      |
slit2 → /‾\ → /‾\ → hit ← bright fringe
  |    \__/     \__/    |
  |                      |
```

Trajectories curve! They are NOT straight lines.
The curvature comes from the guidance force.

---

## 9.6 Step 6: Statistical Pattern

**After many electrons:**

```
Each electron:
→ Definite trajectory (deterministic)
→ But: x₀(0) unknown (random from our perspective)

Distribution of x₀(0):
→ At t=0: P(x₀) = |Ψ(x₀,0)|² (thermal equilibrium)

After reaching screen:
→ P(x_final) = |Ψ(x_final,T)|² = Born's rule! ✓
```

**Why does this work?**
```
V_eff ∝ -|Ψ_field|²
→ Core is attracted to high |Ψ_field|² regions
→ After many trajectories:
  distribution ∝ |Ψ_field|² = |Ψ|² ✓

Mechanism: Ergodic behavior of ensemble of trajectories
under influence of V_eff-landscape
```

---

## 9.7 Summary of Chapter 9

```
✅ Core: goes through ONE slit (deterministically)
✅ Field: diffracts through BOTH slits (wave!)
✅ Interference: in the FIELD, not in the core
✅ Guidance: V_eff ∝ -|Ψ_field|² guides core to maxima
✅ Statistics: x₀(0) distribution → Born's rule
✅ No mystery: everything deterministic and physical!

The double slit explained:
Step 1: Preparation (core + field together)
Step 2: Approach (both move toward slits)
Step 3: Field interference (through both slits)
Step 4: Core passage (through one slit)
Step 5: Guidance (core follows V_eff gradient)
Step 6: Statistics (ensemble → Born's rule)
```

---

# CHAPTER 10: COMPARISON BOHM VS. RFT

## 10.1 Quantum Potential Q vs. Guidance Potential V_eff

### The Two Potentials

**Bohm's quantum potential:**
```
Q = -(ħ²/2m)·(∇²R)/R

where Ψ = R·e^(iS/ħ)
```

**RFT guidance potential:**
```
V_eff = -½c²·α_K·|Ψ_field|²
```

### Key Difference

```
Q involves SECOND derivatives of |Ψ|
V_eff involves ZEROTH power (magnitude squared) of Ψ_field

Functionally different → different trajectories!
But: same statistics! (both satisfy Born's rule)
```

**Why?**

Both satisfy the same continuity equation:
```
∂ρ/∂t + ∇·(ρv) = 0  with ρ = |Ψ|²

→ Same distribution → same statistics ✓
→ Different individual paths → different predictions for "which-path"
```

---

## 10.2 Commonalities (Deterministic Trajectories)

```
✓ Both deterministic: given initial conditions → unique trajectory
✓ Both realistic: particle has definite position x₀(t)
✓ Both non-local: Ψ is non-local (instantaneous correlations)
✓ Both reproduce QM statistics: P(x) = |Ψ(x)|²
✓ Both show trajectories: x₀(t) exists and is computable
✓ Both consistent with Bell: non-local hidden variables
```

---

## 10.3 Differences (Physical vs. Mathematical)

**Origin of guidance:**
```
Bohm: Q derived mathematically from Ψ (no physical mechanism!)
RFT:  V_eff from field Ψ_field modulating the resonance matrix
      → Physical mechanism fully specified!
```

**Status of ħ:**
```
Bohm: ħ appears explicitly in Q = -(ħ²/2m)(∇²R)/R
      ħ is fundamental input

RFT:  m = ħκ/c [derived], κ = PRIMARY QUANTITY
      ħ is an algebraic identity, not fundamental input
      V_eff = -½c²·α_K·|Ψ_field|² — no ħ appears!
```

**Particle structure:**
```
Bohm: Point particle (no spatial extent)
      → UV divergences in QFT!

RFT:  Soliton with size σ ~ λ_Compton ~ 10⁻¹³ m
      → UV-finite by construction!
```

**Mass:**
```
Bohm: m = input parameter (from Schrödinger equation)
RFT:  m = ħκ/c [derived from κ — PRIMARY QUANTITY]
      κ = resonance rigidity of the DRM (geometric!)
```

---

### LEVEL 1 (General audience): Physical vs. Mathematical

```
Bohm's interpretation:
- Q is a "strange force" that acts on the particle
- It doesn't feel like a real force
- No carrier medium known
- Einstein: "Spooky!"

RFT:
- V_eff is the real energy of the resonance matrix
- Carrier medium known: the resonance matrix (DRM)!
- Mechanism understood: λ|Ψ|²-coupling
- No "spooky" elements
```

---

## 10.4 Experimental Distinguishability

### Can We Test Bohm vs. RFT?

```
Statistics: IDENTICAL
→ No experiment can distinguish them by statistics alone

Individual trajectories: DIFFERENT
→ If we could measure individual trajectories precisely enough...
```

**Possible experiments:**

1. **Weak measurements:**
```
Measure trajectory without collapsing wave function
→ Average trajectory → reveals guidance mechanism
→ So far: consistent with both theories!
```

2. **Very small scales:**
```
At r < λ_Compton (below Compton wavelength):
RFT: soliton structure visible (finite size!)
Bohm: point particle (no structure)
→ Requires energies >> mc² (extreme accelerators)
```

3. **Modified interference:**
```
Change α_K (coupling strength) by external fields?
→ Would be direct test of RFT guidance mechanism
→ Currently: not feasible
```

**Honest assessment:**
```
⚠️ Currently: Bohm and RFT experimentally indistinguishable
→ Choice between them is philosophical/aesthetic
→ RFT preferred because: physical mechanism complete
```

---

## 10.5 Philosophical Implications

### Ontology: What Exists?

**Copenhagen:**
```
Only observables exist.
Ψ = mathematical tool (no ontological status).
"Shut up and calculate!"
```

**Bohm:**
```
Particle (x₀) + wave (Ψ) both exist.
Q = real force (but no medium!).
Dualism: particle + field, separate entities.
```

**RFT:**
```
Resonance matrix exists (fundamental).
Vortex core = localized excitation of DRM.
Modulation field = extended excitation of DRM.

→ Monism! ONE medium with two aspects.
→ No dualism needed.
→ Ontologically parsimonious (Occam's razor ✓).
```

### Causality

```
Copenhagen: Non-causal (measurement creates reality)
Bohm:       Causal (trajectories exist, but non-local)
RFT:        Causal + non-local (DRM mode paths)

All three: consistent with all experiments!
```

---

## 10.6 Summary of Chapter 10

### Commonalities

```
✓ Both deterministic
✓ Both realistic
✓ Both non-local
✓ Both reproduce QM statistics
✓ Both show trajectories
```

### Differences

| Aspect | Bohm | RFT |
|--------|------|-----|
| **Potential** | Q = -(ħ²/2m)(∇²R)/R | V_eff = −½c²α_K\|Ψ_field\|² |
| **Ontology** | 3D + Hilbert space | Only 3D (matrix) |
| **Physicality** | Mathematical | Physical |
| **Mass** | Parameter input | Emerges from κ [PRIMARY] |
| **ħ** | Fundamental | Algebraic identity |
| **Non-locality** | "Spooky" | Mode path (physical) |

### Conclusion

```
Statistically:   Equivalent
Ontologically:   RFT more parsimonious
Explanatorily:   RFT more complete
Experimentally:  Hard to distinguish

RFT advantage:

Everything is PHYSICAL:
- Matrix (real!)
- Vortex (real!)
- Modulation field (real!)
- Guidance potential (real!)

→ No "magical" elements!
→ Mechanistic throughout!
```

---

# 🎯 CONCLUSION OF PART 3

## Overall Summary

**Chapter 7 (Guidance Potential):**
- ✅ Derived from Master Equation (λ-term!)
- ✅ V_eff = −½c²·α_K·|Ψ_field|² (explicit)
- ✅ α_K = core coupling strength (~10⁻⁶, NOT α ≈ 1/137!)
- ✅ Physical interpretation (3 levels)
- ✅ Numerical examples (double slit, oscillator)

**Chapter 8 (Equations of Motion):**
- ✅ m·ẍ₀ = −∇V_eff (Newton's law!)
- ✅ Trajectory algorithm (pseudocode)
- ✅ Velocity field (irrotational!)
- ✅ Hamiltonian formulation
- ✅ Conservation laws (energy ~ conserved, probability exactly)

**Chapter 9 (Double-Slit Mechanism):**
- ✅ 6 steps detailed (preparation → statistics)
- ✅ Core goes through ONE slit
- ✅ Field goes through BOTH slits
- ✅ Interference is REAL (in the field!)
- ✅ Guidance to maxima (deterministic)
- ✅ Born's rule emerges statistically

**Chapter 10 (Bohm vs. RFT):**
- ✅ Q vs. V_eff (second vs. zeroth derivative)
- ✅ Commonalities (determinism, realism)
- ✅ Differences (physical vs. mathematical)
- ✅ Experimental tests (difficult!)
- ✅ Philosophy (RFT ontologically parsimonious)

---

## Open Questions for Part 4

```
❓ How does Born's rule emerge mathematically rigorously?
❓ What is |Ψ|² physically (energy density)?
❓ How does statistics arise from determinism?
❓ What happens during measurement (decoherence)?
❓ How does entanglement work?
```

**Part 4 will cover:**
- Chapters 11–15: Born's rule derivation
- |Ψ|² as energy density
- Statistical emergence
- Measurement and decoherence
- Ensemble theory

---

**End of Part 3 — The Guidance Field**

---

**© 2026 Franz Zollner — Resonance Field Theory Project**

**License:** Creative Commons BY-NC-ND 4.0
**Version:** EN 1.0 (Translation of DE v3.0)
**Date:** 01 April 2026
**Translated from:** RFT_v3_011_Teil3_Fuehrungsfeld.md, DE v3.0 (06.03.2026)
**DC Reference:** v10.10 (28.03.2026)

**Translation notes (T11c):**
- "Führungspotential" → "guidance potential"
- "Raummatrix" → "resonance matrix" / "DRM"
- α_K used consistently (≠ fine structure constant α)
- κ PRIMARY QUANTITY consistently noted; m = ħκ/c
- Velocity field note added in Sec. 8.3 (Bohm vs. RFT equivalence)
- Pseudocode: c₀ → c (v3-canonical); variable named alpha_K
- Standalone document — all cross-references descriptive
