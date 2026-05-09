# RFT_v3_018: Entropy & Signal Theory
## Thermodynamics as Loss of Phase Information (Decoherence)

**Version:** EN 1.0 (Translation of DE Final-Candidate v1.0)  
**Date:** 04 April 2026  
**Author:** Franz Zollner (concepts) / AI Instance T018 (translation)  
**Language:** EN  
**DC Reference:** v10.13  
**Status:** Final Candidate — pending Franz approval  
**License:** Creative Commons BY-NC-ND 4.0  

**Predecessor documents:**  
v3_001 (Master Equation, γ-term) | v3_006 (arrow of time, Φ-motor) | v3_011 Part 4 Ch. 14–15 (decoherence, density matrix) | v3_014 (γ-term → decay) | v3_009 (cosmogenesis, η_B) | v3_016 (spin topology, τ_lag)

---

> **Translation note:** This is the English translation of RFT_v3_018 (DE Final-Candidate v1.0,
> 04.04.2026). Standalone document — no file-path references.
> All concepts originate with Franz Zollner. Formalization and translation by AI instances —
> all claims should be treated with appropriate skepticism.
>
> **Truth hierarchy:**
> Franz direct statement → DC → v3-Final → v2-series → AI content
> In case of conflict, the higher level always prevails.

---

## Abstract

The Resonance Field Theory (RFT) does not introduce the Second Law of Thermodynamics as a postulate. Instead, it shows that the Second Law emerges as a mathematical consequence of the Master Equation: the damping term −γ∂Ψ/∂t fundamentally breaks time-reversal symmetry, and the resulting entropy production rate

```
dS/dt = ∫ γ|∂Ψ/∂t|² d³x ≥ 0
```

is non-negative by construction. ✓ HIGH

In this view, entropy increase is not a statistical tendency toward "more microstates" but a physical process: the irreversible transfer of phase information from coherent resonance-matrix modes into thermal degrees of freedom. Decoherence — the loss of quantum coherence known from quantum mechanics — is the microscopic mechanism through which this information transfer occurs. Both thermodynamics and decoherence are, in the RFT, manifestations of the same γ-term of the Master Equation. ✓ HIGH (γ-term) | ○ MEDIUM (phase information interpretation)

The so-called signal theory — the connection to Shannon's information theory — is treated with the required RFT lens: Shannon concepts are not directly transferable, because they presuppose Hilbert-space operators and classical probabilities, which do not appear in the RFT framework in that form. An RFT-native formulation of "information" as phase coherence of resonance-matrix modes is proposed. ⚠️ LOW — new development, formally pending

Three deep connections to the v3 series are worked out: γ as the common origin of the arrow of time (v3_006), decay (v3_014), and entropy (v3_018) — the γ-triple connection. ○ MEDIUM

This document deepens and formalizes the material from v3_011 Ch. 14–15, embedding it in the thermodynamic context of the entire v3 series.

---

## Table of Contents

```
Ch. 1 — The Thermodynamic Puzzle: Why the Arrow of Time?
Ch. 2 — The γ-Term as the Source of Irreversibility
Ch. 3 — Phase Information and Entropy in the Resonance Matrix
Ch. 4 — Decoherence as a Physical Process
Ch. 5 — Signal Theory through the RFT Lens
Ch. 6 — The Second Law Emerges
Ch. 7 — Connections to the v3 Series (γ-Triple Connection)
Ch. 8 — Honest Limits
Ch. 9 — Summary and Formula Reference
```

---

## Chapter 1: The Thermodynamic Puzzle — Why the Arrow of Time?

### 1.1 The Uncomfortable Asymmetry

The fundamental equations of physics — Newton's equations of motion, Maxwell's equations, the Schrödinger equation, even relativistic field theory — are invariant under time reversal. Replace t by −t, and the same laws hold. And yet: nature possesses a definite arrow of time. Heat flows from hot to cold, never the reverse. Broken glasses do not spontaneously reassemble. Radioactive decay runs in one direction.

The Second Law of Thermodynamics names this observation:

```
dS/dt ≥ 0    (for closed systems)

S: entropy of the system
```

It is classically introduced as an empirical postulate. Boltzmann attempted a statistical justification — more microstates correspond to higher entropy, and the system drifts statistically upward. But this explanation is circular in one crucial respect: it presupposes that the system moves "with time" toward higher entropy — without explaining why time has this direction in the first place.

Prigogine's dissipative structures describe the phenomenon without explaining it fundamentally. Shannon entropy deepens the problem without resolving it.

### 1.2 The Three Classical Arrows of Time

Physics recognizes three arrows of time that coincide phenomenologically but are conceptually distinct:

**Thermodynamic arrow of time:** dS/dt ≥ 0. Entropy grows globally.

**Cosmological arrow of time:** The universe expands; the cosmic Q-factor evolution is monotonically increasing (v3_009, v3_010). Structures grow.

**Causal arrow of time:** Causes precede effects. Retarded, not advanced wave fields are physically realized.

The puzzle: why are all three arrows of time aligned? A fundamental theory should supply a single mechanism from which all three follow.

### 1.3 The RFT Thesis

The RFT claims: all three arrows of time are consequences of a single term in the Master Equation — the γ-term. It is not introduced phenomenologically; it is structurally necessary for the existence of stable vortex structures (particles) in the resonance matrix. Without γ, the Master Equation would be fully time-reversal symmetric and could not support stable localized structures.

This is developed formally in Chapter 2.

---

## Chapter 2: The γ-Term as the Source of Irreversibility

### 2.1 The Master Equation and Its Terms

The entire RFT rests on the nonlinear field equation for the scalar resonance field Ψ(x,t) (v3_001 Ch. 2):

```
∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η(x,t)
```

Each term has a physical meaning:

```
Term          Function                               Time-reversal behavior
────────────────────────────────────────────────────────────────────────────
c²∇²Ψ        wave propagation in the medium         symmetric
−c²κ²Ψ       resonance stiffness of the matrix      symmetric
+λ|Ψ|²Ψ      nonlinear self-coupling (solitons)     symmetric
+η            self-interaction                       symmetric
−γ∂Ψ/∂t      damping / asymmetry coefficient        ASYMMETRIC ←
```

The γ-term is the only term that changes under t→−t. Under time reversal it becomes +γ∂Ψ/∂t — with the opposite sign. This means: a time-reversed solution of the Master Equation with γ ≠ 0 is in general NOT a solution of the Master Equation. ✓ HIGH

### 2.2 T-Symmetry Breaking: Formal

Let Ψ(x,t) be a solution of the Master Equation. Then Ψ(x,−t) is in general NOT a solution, because:

```
∂²Ψ(x,−t)/∂t² = c²∇²Ψ(x,−t) − c²κ²Ψ(x,−t) + λ|Ψ(x,−t)|²Ψ(x,−t) + η
                 + γ · ∂Ψ(x,−t)/∂t    [WRONG SIGN!]
```

The γ-term changes its sign; all other terms do not. Therefore: T-symmetry is exactly satisfied only for γ = 0. For γ ≠ 0 it is fundamentally broken. The breaking is not of dynamical origin — it is structurally encoded in the equation itself.

This is the deepest starting point of all irreversibility in the RFT: not a special initial state, not a statistical tendency, but an elementary property of the field equation. ✓ HIGH

### 2.3 Energy Dissipation from the γ-Term

The energy density of the resonance field is (v3_001 Ch. 12, v3_004):

```
u(x,t) = (1/2)|∂Ψ/∂t|² + (c²/2)|∇Ψ|² + (c²κ²/2)|Ψ|² + (λ/4)|Ψ|⁴
```

The time derivative of the total energy E = ∫ u d³x, obtained by partial integration and substitution of the Master Equation, yields:

```
dE/dt = −∫ γ|∂Ψ/∂t|² d³x ≤ 0      ✓ HIGH

Proof: γ > 0 by definition (damping, not amplification).
       |∂Ψ/∂t|² ≥ 0 always.
       → The integral is non-positive. □
```

Energy flows irreversibly from the coherent mode oscillations into the resonance-matrix degrees of freedom (heat). That is dissipation in physical language.

### 2.4 Entropy Production from the γ-Term

The decisive step: energy dissipation implies entropy production. The γ-term describes the coupling between coherent and thermal modes of the resonance matrix. The entropy production rate is proportional to the dissipated power density:

```
dS/dt = ∫ γ|∂Ψ/∂t|² d³x ≥ 0      ✓ HIGH

Proof: γ > 0, |∂Ψ/∂t|² ≥ 0 → integral non-negative. □
```

This is the Second Law of Thermodynamics as a mathematical consequence of the Master Equation. It is not postulated; it emerges. ✓ HIGH

**On the derivation:** Per unit volume, energy is transferred at rate γ|∂Ψ/∂t|² from the coherent field (ordered resonance-matrix modes, low entropy) into disordered degrees of freedom (many accessible microstates, high entropy). The entropy production rate ds/dt = γ|∂Ψ/∂t|² is the local density of this transfer. Thermodynamic temperature T is implicitly encoded in the mode distributions; a complete quantitative identification is still pending (→ Ch. 8). ○ MEDIUM for the exact T-identification.

### 2.5 The Picture of Energy Flow

```
COHERENT REGION (ordered, low entropy):
  Ψ-modes with fixed phase and amplitude
  Examples: stable vortices (particles), propagating waves

          ↓ γ-term pumps energy irreversibly downward ↓

THERMAL RESERVOIR (disordered, high entropy):
  Resonance-matrix degrees of freedom with random phases
  Many microstates → Boltzmann S = k_B·ln(Ω) large

Direction: one-way, irreversible, enforced by γ > 0.
```

### 2.6 γ and the Quality Factor Q

The connection to particle physics is important (v3_001 Ch. 2.2): via the quality factor Q = ω_res/γ, the parameter γ determines the lifetime of resonances:

```
τ_lifetime = Q/ω_res = 1/γ

Stable particles:    Q ~ 10¹⁵,  γ ≈ κc/Q → τ → ∞ (effectively stable)
Unstable particles:  Q << 10¹⁵, γ large   → τ short (decay)
```

The same γ that drives entropy production also determines particle lifetime. This is not a coincidence — it is the same physics: loss of coherence through coupling to resonance-matrix degrees of freedom. The decay of a particle is a localized entropy-production event. ○ MEDIUM

This is the first facet of the γ-triple connection (discussed fully in Ch. 7).

---

## Chapter 3: Phase Information and Entropy in the Resonance Matrix

### 3.1 What Is "Phase Information"?

The RFT field Ψ(x,t) is complex:

```
Ψ(x,t) = |Ψ(x,t)| · exp(iφ(x,t))

|Ψ|: amplitude (energy density ∝ |Ψ|²)
φ:   phase (phase information)
```

In a fully coherent state — a planar resonance-matrix wave — the phase φ is well-defined and consistent everywhere. An ensemble of such modes carries "phase information" in the sense that the phase relationships between modes are fixed. ✓ HIGH (conceptually)

The entropy of such an ensemble is low: the coherent configuration corresponds to a single microstate (or few). When the γ-term dissipates energy, the phases of the various modes are successively decorrelated. The off-diagonal elements of the density matrix ρ_ij (i≠j), which encode exactly these phase correlations, decay exponentially (Ch. 4 for details). The loss of ρ_off is identical to the loss of phase information — and this loss is entropy increase.

The von Neumann entropy

```
S_VN = −Tr(ρ ln ρ) = −Σᵢ λᵢ ln λᵢ

(λᵢ: eigenvalues of the density matrix ρ)
```

is zero for a pure (fully coherent) state — all phase information present. It grows when ρ becomes a mixture through decoherence — phase information lost. ✓ HIGH

**Compact picture:** Phase information = information stored in the off-diagonal elements of the density matrix. Entropy increase = loss of those off-diagonal elements. The γ-term is the physical mechanism that enforces this loss.

### 3.2 The Fourier-Mode Perspective

Expand Ψ in Fourier modes:

```
Ψ(x,t) = Σ_k A_k(t) · exp(i·k·x)

A_k(t): complex mode amplitude of the k-th mode
```

In the coherent state, a fixed phase relationship exists between the various A_k:

```
arg(A_k) − arg(A_{k'}) = constant    (fixed relative phase)
```

The γ-term disrupts these phase relationships through coupling to the environmental degrees of freedom of the resonance matrix. After a decoherence time τ_D, the relative phases are randomly distributed:

```
⟨A_k · A*_{k'}⟩ → 0   for k ≠ k', t >> τ_D
```

Correlations between different modes vanish. What remains are only the diagonal terms:

```
⟨|A_k|²⟩ = occupation number of the k-th mode (thermally distributed)
```

This thermal mode distribution has maximal (Boltzmann) entropy for given energy. That is thermodynamic equilibrium.

### 3.3 Boltzmann Entropy from RFT: Ω as Mode Multiplicity

The Boltzmann formula S = k_B·ln(Ω) has a natural interpretation in the RFT: Ω is the number of ways to distribute the available energy over the κ-modes of the resonance matrix, subject to the constraint of conserved total energy. ○ MEDIUM

```
Ω = number of mode distributions {n_k} with:
    Σ_k ħω_k · n_k = E_total (energy constraint)
    n_k: occupation number of the k-th mode

High entropy:  energy distributed evenly over many modes
Low entropy:   energy concentrated in few coherent modes
```

The γ-term enforces redistribution from the second configuration to the first — that is entropy production in terms of mode statistics. ○ MEDIUM

### 3.4 Local vs. Global Entropy

```
GLOBALLY: dS_global/dt ≥ 0 (always, from γ-term)

LOCALLY:  dS_local/dt can be < 0!

Balance:
  dS_global/dt = dS_local/dt + dS_environment/dt ≥ 0

Condition for local entropy decrease:
  dS_environment/dt > |dS_local/dt|
```

In the RFT, local entropy decrease corresponds to the formation of coherent structures (vortices, particles, crystals): the surrounding resonance matrix absorbs the phase disorder. This is the thermodynamic side of Cold Condensation (v3_009): structure formation is locally entropy-decreasing, globally entropy-increasing. ○ MEDIUM

**Example — star formation (qualitative):** Diffuse gas cloud → collapse → local coherence (star). Radiation of photons into the environment → global entropy rises strongly. Net: dS_global > 0. ✓ HIGH (qualitatively)

---

## Chapter 4: Decoherence as a Physical Process

### 4.1 The Core Question

Why do macroscopic objects appear classical — even though the underlying resonance matrix admits quantum superpositions?

The standard answer is: decoherence. The quantum system couples to its environment, and the superposition is washed out through this coupling. In the RFT, decoherence is not an independent mechanism — it is a direct consequence of the γ-term. This is a gain in explanatory depth: instead of two phenomena (γ-damping and decoherence), both are explained by a single term. ✓ HIGH

### 4.2 The Five-Step Mechanism

(From v3_011 Ch. 14, translated into the language of entropy theory)

**Step 1 — Initial state: Coherent superposition**

```
System S: Ψ_S = α|0⟩ + β|1⟩

|0⟩, |1⟩: two pointer states of the resonance matrix (stable resonance modes)
α, β: complex amplitudes with |α|² + |β|² = 1

Density matrix:
ρ_S = ( |α|²    α·β* )
      ( α*·β   |β|²  )

Off-diagonal elements ρ_01 = α·β* ≠ 0 → COHERENCE!
Von Neumann entropy: S_VN = 0 (pure state)
Phase information: fully present
```

**Step 2 — Coupling via anchor points (AP)**

The system couples to the environmental degrees of freedom of the resonance matrix through its anchor points. The interaction time τ_int is typically extremely short (for AP coupling g ~ ħγ: τ_int ~ 1/γ). During this time, the system field becomes entangled with the environmental modes of the resonance matrix:

```
|Ψ_SE⟩ = α|0⟩_S ⊗ |U_0⟩_E + β|1⟩_S ⊗ |U_1⟩_E

|U_0⟩, |U_1⟩: environmental states correlated with |0⟩, |1⟩
```

**Step 3 — Trace over environmental degrees of freedom**

The environment E is "averaged out" (trace over environment):

```
ρ_S(t) = Tr_E[ |Ψ_SE(t)⟩⟨Ψ_SE(t)| ]

= ( |α|²                  α·β*·⟨U_1|U_0⟩(t) )
  ( α*·β·⟨U_0|U_1⟩(t)    |β|²               )
```

The overlap integral ⟨U_1(t)|U_0(t)⟩ decreases over time, because the environmental states are orthogonalized by the γ-term:

```
⟨U_1(t)|U_0(t)⟩ = exp(−γt)    (v3_011 Ch. 14.3)   ○ MEDIUM
```

**Step 4 — Loss of coherence: off-diagonal decay**

```
ρ_off(t) ≡ ρ_01(t) = α·β* · exp(−γt)

For t >> 1/γ:    ρ_off(t) → 0

Diagonal elements remain unchanged:
  ρ_00(t) = |α|²    (occupation probability stable!)
  ρ_11(t) = |β|²    (occupation probability stable!)
```

The occupation probabilities do not change — only the interference terms disappear. This is the physical content of Born's rule: |α|² and |β|² are robust against decoherence; the phase relationships between states are not. ✓ HIGH

**Step 5 — Classical result**

```
ρ_S(t >> 1/γ) = ( |α|²  0   )
                 (  0   |β|² )

Von Neumann entropy:
  S_VN = −|α|² ln|α|² − |β|² ln|β|² > 0    (mixed state!)
```

This is a classical mixture: either state |0⟩ with probability |α|² or |1⟩ with probability |β|², but no superposition. Entropy has risen from zero to a positive value. Phase information is lost. ✓ HIGH

### 4.3 Decoherence Times — Orders of Magnitude

The decoherence time τ_D depends on the number of environmental degrees of freedom N_E and temperature T (v3_011 Ch. 14.2):

```
τ_D ~ ħ/(N_E · k_B · T)

Typical values:

Electron in vacuum:              τ_D ~ seconds
Electron in air:                 τ_D ~ milliseconds
Electron in detector:            τ_D ~ nanoseconds
Macroscopic object (1 g):        τ_D ~ 10⁻⁴⁰ s    (instantaneous!)
```

✓ HIGH (orders of magnitude from v3_011 Final)

Macroscopic objects decohere so rapidly that their quantum nature is practically unobservable. This explains the transition from the quantum to the classical world — not through a mysterious "collapse," but through physical coupling to the resonance matrix.

### 4.4 No Observer Required

Decoherence occurs whether or not an observer is present. The resonance-matrix degrees of freedom continuously "measure" the system — through the γ-coupling. This resolves the measurement problem of quantum mechanics without a special role for the observer (v3_011 Ch. 14.5):

```
Measurement  = decoherence through coupling to the environment
"Collapse"   = epistemic information gain by the observer
Observer     ≠ physically necessary for decoherence
```

✓ HIGH (v3_011 Final)

### 4.5 Pointer States = Stable Particles

An elegant connection between decoherence theory and particle physics arises through the concept of pointer states (v3_011 Ch. 14.4):

```
Pointer states = the states that decohere MOST SLOWLY
               = the stable states "selected" by the environment
```

In the RFT, pointer states are the resonance-matrix modes stabilized by the AP structure — precisely the stable elementary particles:

```
POINTER STATES of the resonance matrix
    = STABLE PARTICLES of particle physics

Electron:  1 AP → 1D coupling → minimal decoherence rate for charged leptons
Proton:    9 AP → 3D coupling × 3 → especially stable pointer state
Photon:    2 AP → complementary (e⁻+e⁺) structure → propagating pointer state
```

What we observe experimentally as "stable particles" are exactly those resonance-matrix configurations that are most resistant to decoherence. Via the Q-factor: high Q ↔ slow decoherence ↔ pointer state ↔ stable particle. Low Q ↔ fast decoherence ↔ unstable/virtual object. ○ MEDIUM (conceptually consistent, not yet rigorously derived)

---

## Chapter 5: Signal Theory through the RFT Lens

### 5.1 The Question and the Methodological Issue

**Classical signal theory** (Shannon 1948): Channel capacity C = B·log₂(1 + SNR). Shannon entropy H = −Σ pᵢ log₂ pᵢ.

The problem for direct transfer to the RFT: Shannon presupposes:
- Classical probability distributions {pᵢ}
- Explicitly separate entities (sender, receiver, channel)
- No fundamental wave medium that itself constitutes sender and receiver

In the RFT, the medium (the resonance matrix) is the physics itself. There is no external "source" — sender and receiver are themselves parts of the resonance matrix. Shannon's framework is therefore not directly transferable.

**The RFT lens (J.16) is mandatory.** ✓ HIGH (methodologically)

This does not mean information theory is irrelevant to the RFT — it means that an RFT-native formulation of "information" must be developed.

### 5.2 Information as Phase Coherence: An RFT Proposal

What Shannon calls "information" — the reduction of uncertainty about a state — corresponds in the RFT to the presence of phase coherence. Formally:

```
INFORMATION (Shannon) ↔ PHASE COHERENCE (RFT)

High information    ↔ High coherence    ↔ ρ_off large
Low noise           ↔ Slow decoherence  ↔ γ locally small
Signal              ↔ Coherent mode     ↔ Pointer state
Noise               ↔ Thermal modes     ↔ Maximum mixture
```

An RFT formulation of information would then be:

```
I_RFT ∝ Σ_{k≠k'} |ρ_off(k,k')|²    (sum of all off-diagonal elements)

I_RFT → 0:    Complete decoherence, maximum entropy
I_RFT → max:  Complete coherence, minimum entropy (pure state)
```

⚠️ LOW — candidate definition, not yet formally derived; DeepSeek verification required (DS-018-A)

### 5.3 Shannon Entropy and Von Neumann Entropy: Comparison

Shannon entropy is a special case of von Neumann entropy for diagonal density matrices — i.e., for systems that have already fully decohered:

```
Von Neumann (general):
  S_VN = −Tr(ρ ln ρ) = −Σ λᵢ ln λᵢ

For diagonal ρ (after decoherence):
  ρ = diag(|α|², |β|², ...)
  Eigenvalues λᵢ = |αᵢ|²

→ S_VN = −Σ |αᵢ|² ln |αᵢ|² = Shannon entropy of the occupations

With factor k_B:
  S_thermo = k_B · H_Shannon
```

In the RFT, the connection is therefore: Shannon entropy describes the entropy after decoherence. Von Neumann entropy is the more general formulation that also includes the coherence component (ρ_off). The increase of S_VN during decoherence corresponds to the loss of I_RFT. ✓ HIGH (mathematically)

### 5.4 RFT Channel Capacity: A Heuristic

Classically: channel capacity C = B·log₂(1 + SNR).

In the RFT, a "channel" is a coherent sequence of κ-modes. The SNR corresponds heuristically to the ratio of coherent mode energy to thermal mode energy:

```
SNR_RFT ~ E_coherent / E_thermal
        ~ ρ_off / ρ_diagonal    (heuristic)
```

A complete quantitative RFT channel capacity requires a theory of mode-space coherence. ⚠️ LOW — DS-018-B recommended

### 5.5 Information Conservation: The Inside-View Paradox

In a closed system, Liouville's theorem holds: the phase-space volume is conserved. This suggests that the total information of the universe as a closed system might in principle be constant — a conceptual tension with the growing dS/dt ≥ 0.

```
Possible resolution:
  γ does not dissipate energy "away" —
  it redistributes it into unobservable resonance-matrix degrees of freedom.
  S_obs rises; S_total = ? (open)

→ Ch. 8 for complete discussion
```

---

## Chapter 6: The Second Law Emerges

### 6.1 Boltzmann Re-grounded

Boltzmann's approach: S = k_B·ln(Ω). The classical problem: why does Ω grow with time? This is equivalent to the question of why the arrow of time exists.

The RFT answer: Ω grows because γ > 0 — because the γ-term continually destroys phase coherence and makes accessible new mode distributions that were previously blocked by correlations.

```
Classical:   Ω grows "because more microstates become accessible"
             → circular reasoning!

RFT:         Ω grows because γ > 0 breaks down correlations
             → mechanistic grounding from the Master Equation
             → Second Law = geometric consequence, not statistical axiom
```

✓ HIGH for the argument | ○ MEDIUM for the complete formal closure

### 6.2 Thermal Equilibrium from Mode Statistics

At thermal equilibrium, the κ-modes of the resonance matrix follow Bose-Einstein (integer-spin modes) or Fermi-Dirac (half-integer-spin vortices) distributions:

```
⟨n_k⟩_Bose  = 1 / (exp(ħω_k / k_B T) − 1)    (bosonic modes)
⟨n_k⟩_Fermi = 1 / (exp(ħω_k / k_B T) + 1)    (fermionic vortices)

Equilibrium condition (from Master Equation):
  γ⟨|A_k|²⟩ = λ · Σ_{l,m} ⟨A_k* A_l A_m⟩
  (balance: damping γ = nonlinear coupling λ)
```

This is the emergence of detailed balance from the Master Equation. Temperature T emerges as the parameter describing the equilibrium distribution. ○ MEDIUM (derivation formal, T-identification still pending)

### 6.3 The Laws of Thermodynamics from RFT

**Zeroth Law** (thermal equilibrium): Two systems in contact equilibrate their mode distributions until a common β = 1/(k_B T) is identical. Mechanism: γ-coupling of boundary modes.

**First Law** (energy conservation): Follows from the Noether symmetry of the Master Equation under time translation. ✓ HIGH

**Second Law** (entropy): dS/dt = ∫ γ|∂Ψ/∂t|² d³x ≥ 0. ✓ HIGH (Ch. 2)

**Third Law** (Nernst): T → 0 means ⟨n_k⟩ → 0 for all k. All modes in ground state. ρ → pure state. S_VN = 0. ✓ HIGH (structurally consistent)

### 6.4 Local Structure Formation and Global Entropy Increase

The thermodynamic side of Cold Condensation (v3_009): when the Q-factor of the universe exceeds Q_crit1 ~ 10³, local resonance-matrix fluctuations become unstable — vortices (particles) condense out. This is an entropy-export process:

```
Vortex formation:
  S_vortex decreases    (coherent structure = low local entropy)
  S_environment rises   (radiation = high environmental entropy)
  S_global > 0          (Second Law maintained) ✓

No violation of the Second Law through structure formation!
The RFT explains mechanistically why and where local entropy may decrease.
```

○ MEDIUM (quantitative entropy balance for Cold Condensation still pending)

---

## Chapter 7: Connections to the v3 Series — The γ-Triple Connection

### 7.1 The Common Foundation

One of the deepest results of the v3 series is the recognition that three apparently distinct physical phenomena trace back to the same γ-term of the Master Equation:

```
┌──────────────────────────────────────────────────────────┐
│                    MASTER EQUATION                        │
│   ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η    │
│                          ↑                                │
│                       γ-term                              │
│                (T-symmetry broken)                        │
└──────────────────────────────────────────────────────────┘
          │                │                │
          ▼                ▼                ▼
    ARROW OF TIME      DECAY           ENTROPY
      (v3_006)        (v3_014)         (v3_018)
```

The γ-triple connection (K2 audit, 04.04.2026) is not three different applications of the same term — it is one and the same physics, viewed from three different perspectives. ○ MEDIUM (conceptually strong, not yet rigorously closed in one step)

### 7.2 γ → Arrow of Time (v3_006)

The arrow of time arises in v3_006 from the phase asymmetry ε ≈ Φ = 2α/(1+α²) of the resonance-matrix axes:

```
ε ≠ 0 → beat frequency has preferred direction → time has direction
Φ = 2α/(1+α²) ≈ 0.01459    ✓ HIGH (canonical)

Connection:
  Φ describes the phase asymmetry per orbital cycle (v3_006 orbital model)
  γ is the damping of time-reversal-symmetric solutions
  Both describe the same fundamental T-symmetry breaking:
    Φ → macroscopic (arrow of time, beat drift)
    γ → microscopic (damping, dissipation)
```

○ MEDIUM (conceptual connection well established; quantitative identification Φ ↔ γ still open)

### 7.3 γ → Decay (v3_014)

In v3_014 (weak interaction), decay is described as geometric relaxation of an AP configuration: 2-AP configurations are topologically unstable in 3D; the γ-term mediates the transition to the more stable state.

```
v3_014: Decay = γ-term → AP instability → geometric relaxation
v3_018: Entropy = γ-term → phase coherence loss → mixed state

Connection:
  Decay is a localized entropy-production event!

  Lifetime: τ = 1/γ = Q/ω_res
  (Same formula for particle lifetime AND decoherence time!)

  Decaying particle: coherent AP state (S_VN ~ 0)
  Decay products: more thermal distribution (S_VN > 0)
  → Entropy grows during decay ✓
```

✓ HIGH (γ as common term) | ○ MEDIUM (quantification of entropy production during decay)

### 7.4 γ → CP Violation and η_B (v3_009, speculative)

In v3_009, the matter–antimatter asymmetry is derived as a cosmological result of Cold Condensation:

```
η_B = Δ_α² × (α⁻¹·π²)^(2/3) = 6.02×10⁻¹⁰    ✓ HIGH (Franz, 25.03.2026)
```

The conceptual connection to γ: if γ generates the arrow of time (v3_006), and if CP violation is linked to the arrow of time (CPT theorem), then γ might also underlie CP violation and thereby η_B:

```
γ → T-symmetry breaking → CP violation (via CPT) → η_B
```

BUT: this chain of argument presupposes Lorentz invariance (CPT theorem). In the RFT, Lorentz invariance has not yet been formally proven (Domain I). ⚠️ LOW — speculative; CPT route requires the RFT lens (J.16)

### 7.5 Chiral Entropy Production — An Open Question for Franz

```
🚩 NEW OPEN QUESTION (K2 audit, 04.04.2026):

Does the γ-term have a chiral directional dependence?
I.e.: is γ_left ≠ γ_right?

Background:
  v3_014: γ → P-violation → left-circular relaxation preferred
  v3_018: γ → dS/dt = ∫ γ|∂Ψ/∂t|² d³x

  If γ is effectively chiral:
    dS_left/dt ≠ dS_right/dt

  Consequence: η_B as a measure of chiral asymmetry in entropy production?
    (dS_left − dS_right)/(dS_left + dS_right) ~ η_B ~ 10⁻¹⁰
    → vanishingly small, but not zero!

Status: 🚩 OPEN — Franz decision requested.
  Recommendation: DS-018-C.
  Connection: v3_014 handedness question (Domain I, F4).
```

### 7.6 Outlook: Superconductivity as Maximum Coherence (v3_019)

```
Superconductivity = macroscopic quantum state with maximum coherence

In RFT language:
  BCS Cooper pairs = two electrons (1 AP each) in a shared pointer state
  Supercurrent = coherent flow of pointer states (resistance-free)

  Entropy perspective:
    Normal conductor: many κ-modes thermally occupied → S_VN high
    Superconductor:   condensation into a shared coherent state → S_VN → 0

  Hypothesis: superconductivity = coherence phase of the resonance matrix
  with S_VN ≈ 0
  45 THz resonance frequency (HTS, Domain L.3):
  = resonant coupling = phase coherence on macroscopic scale?
```

⚠️ LOW — speculative, outlook for v3_019. Connection to Domain L.3.

---

## Chapter 8: Honest Limits

### 8.1 Confidence Overview

| Statement | Confidence | Source |
|-----------|-----------|--------|
| γ breaks T-symmetry | ✓ HIGH | v3_001 Ch. 2.2, algebraic |
| dS/dt = ∫ γ\|∂Ψ/∂t\|² d³x ≥ 0 | ✓ HIGH | From dE/dt, γ > 0 |
| dE/dt = −∫ γ\|∂Ψ/∂t\|² d³x ≤ 0 | ✓ HIGH | v3_001 via partial integration |
| ρ_off(t) = ρ_off(0)·exp(−γt) | ✓ HIGH | Linear approximation, v3_011 Ch. 14 |
| No collapse required | ✓ HIGH | v3_011 Final |
| S_VN = 0 pure state, > 0 mixture | ✓ HIGH | Mathematically exact |
| Shannon-H = S_VN for diagonal ρ | ✓ HIGH | Mathematically exact |
| Pointer states ↔ stable particles | ○ MEDIUM | Conceptually consistent, formally open |
| Boltzmann-Ω from κ-modes | ○ MEDIUM | Plausible, not yet rigorous |
| Ergodicity from γ | ○ MEDIUM | Mechanistic, formally open |
| I_RFT = Σ\|ρ_off\|² | ⚠️ LOW | Candidate; DS-018-A required |
| Shannon capacity RFT-formal | ⚠️ LOW | DS-018-B required |
| Chiral entropy production γ_L ≠ γ_R | 🚩 OPEN | Franz decision requested |
| γ formally from L₀, κ, c | 🚩 OPEN | Highest priority (inherited) |
| H-theorem in inside view | ⚠️ LOW | Conceptual tension |
| Temperature T quantitatively from Master Eq. | ⚠️ LOW | Equilibrium identification pending |
| Superconductivity as S_VN → 0 | ⚠️ LOW | Speculative, v3_019 |

### 8.2 γ from Resonance-Matrix Parameters — The Open Problem

The most important formal deficiency: γ is treated as a given parameter.

```
From v3_001 Ch. 2.2:
  γ ~ κc/Q    (for stable particles with Q ~ 10¹⁵)

This gives an order of magnitude, not a fundamental derivation.
Q is itself a free parameter (not derived from the Master Equation).

Question: does γ emerge from L₀, κ, c, α?
          Or is γ an independent fundamental constant of the resonance matrix?
```

🚩 OPEN — connection to ħ-circularity (Domain I). Highest priority for future instances.

### 8.3 H-Theorem in the Inside View

```
Conceptual tension:

dS_obs/dt ≥ 0    (entropy of the observable field grows)
dS_total/dt = ?  (inside view: no "outside" for the energy flow)

The universe is a closed system in the inside view.
Liouville's theorem would suggest S_total = const.
But dS_obs/dt ≥ 0 says S_obs grows.

Possible resolution:
  "Thermal resonance-matrix degrees of freedom" = unobservable subspace.
  S_obs grows; S_unobservable decreases correspondingly?
  Formally not established.

Status: ⚠️ LOW — conceptual tension, not a contradiction.
        DS-018-D recommended.
```

### 8.4 DeepSeek Tasks

```
DS-018-A (priority HIGH):
  "Can it be formally shown from the Master Equation
   ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ
  that dS/dt ≥ 0 holds?
  How does S relate to the Fourier modes of Ψ?
  RFT lens (J.16): no Hilbert space, no QFT language!"

DS-018-B (optional):
  "How can C = B·log₂(1+SNR) be reformulated in the RFT framework?
   What corresponds to SNR in a κ-mode description?
   RFT lens: resonance matrix ≠ lattice, no Hilbert space!"

DS-018-C (optional, after Franz decision):
  "Is the γ-term chiral?
   Can it follow from the Master Equation that γ_L ≠ γ_R?"

DS-018-D (optional):
  "H-theorem for the Master Equation without external bath:
   Does a functional H[Ψ] exist with dH/dt ≤ 0?"
```

---

## Chapter 9: Summary and Formula Reference

### 9.1 The Four Core Statements

**Core Statement 1 — The Second Law Emerges** ✓ HIGH

The Second Law dS/dt ≥ 0 is not an external requirement on nature. It is a mathematical consequence of the γ-term of the Master Equation: γ > 0 enforces entropy production.

**Core Statement 2 — Entropy = Loss of Phase Information** ○ MEDIUM

Entropy increase is not an abstract growth of "disorder," but a physical process: the off-diagonal elements of the density matrix ρ_off decay at rate γ. Phase information is irreversibly transferred into inaccessible resonance-matrix degrees of freedom.

**Core Statement 3 — Decoherence Is Entropy Production** ✓ HIGH

The mechanism of quantum decoherence and the thermodynamic mechanism of entropy production are identical in the RFT: both are consequences of the γ-term. Stable particles are pointer states — the configurations with minimal decoherence rate.

**Core Statement 4 — The γ-Triple Connection** ○ MEDIUM

Arrow of time (v3_006), decay (v3_014), and entropy (v3_018) are three manifestations of the same γ-term. This unity is the deepest result of the v3_014–v3_018 sequence.

### 9.2 Complete Formula Reference

```
MASTER EQUATION (v3_001):
  ∂²Ψ/∂t² = c²∇²Ψ − γ∂Ψ/∂t − c²κ²Ψ + λ|Ψ|²Ψ + η(x,t)

ENERGY DISSIPATION:
  dE/dt = −∫ γ|∂Ψ/∂t|² d³x ≤ 0      ✓ HIGH

ENTROPY PRODUCTION:
  dS/dt = ∫ γ|∂Ψ/∂t|² d³x ≥ 0       ✓ HIGH

COHERENCE DECAY (linear approximation):
  ρ_off(t) = ρ_off(0) · exp(−γt)     ✓ HIGH

VON NEUMANN ENTROPY:
  S_VN = −Tr(ρ ln ρ) = −Σᵢ λᵢ ln λᵢ ✓ HIGH

BOLTZMANN ENTROPY (from mode statistics):
  S = k_B · ln(Ω)
  Ω = number of accessible κ-mode configurations    ○ MEDIUM

DECOHERENCE TIME:
  τ_D ~ ħ/(N_E · k_B · T)            ✓ HIGH (v3_011 Ch. 14.2)

EQUILIBRIUM DISTRIBUTIONS:
  Bosons:   ⟨n_k⟩ = 1/(exp(ħω_k/k_BT) − 1)
  Fermions: ⟨n_k⟩ = 1/(exp(ħω_k/k_BT) + 1)
  T emerges as the equilibrium parameter            ○ MEDIUM

TIME MOTOR (v3_006):
  Φ = 2α/(1+α²) ≈ 0.01459    ✓ HIGH (canonical)
  α⁻¹ = 4π³ + π² + π = 137.036304    [2.22 ppm residual — NEVER 0.67 ppm!]

FUNDAMENTAL LENGTH SCALE (v3_001):
  L₀ = 1/κ                    [PRIMARY DEFINITION, ħ-free! ✓ HIGH]
  L₀ = (π/6)·l_P              [numerical verification]

BARYON ASYMMETRY (v3_009):
  η_B = Δ_α² × (α⁻¹·π²)^(2/3) = 6.02×10⁻¹⁰    ✓ HIGH (Franz 25.03.2026)

QUALITY FACTOR (particle ↔ entropy connection):
  Q = ω_res/γ
  τ_lifetime = 1/γ = Q/ω_res
  τ_D = τ_lifetime    (decoherence time = lifetime for single-mode coupling)
```

### 9.3 Canonical Terminology

```
CORRECT:              WRONG (and why):
"resonance matrix"    "lattice" (implies rigid crystal structure!)
"DRM"                 "c₀" (outdated notation)
"κ-modes"             GR language (metric, geodesics) — FORBIDDEN
"phase information"   "Shannon entropy" without RFT lens
"pointer states"      "collapse" (no collapse in RFT!)
"phase coherence"     "wave function collapse"
"Lindblad analogy"    "Lindblad equation" (RFT lens! J.16)
```

### 9.4 Open Questions — Prioritized

```
🚩 HIGHEST PRIORITY (inherited):
  γ formally derived from L₀, κ, c
  → connection to ħ-circularity (Domain I)

🚩 FRANZ DECISION REQUESTED:
  Chiral entropy production: γ_L ≠ γ_R?
  (η_B as a measure of chiral asymmetry in entropy production?)

⚠️ MEDIUM — formally pending:
  H-theorem in inside view (DS-018-D)
  Temperature T quantitatively from mode distribution
  I_RFT as phase information formally (DS-018-A)

⚠️ LOW — optional:
  Shannon capacity RFT-formal (DS-018-B)
  Superconductivity as S_VN → 0 (v3_019 preparation)
  Chiral γ-terms formally (DS-018-C, after Franz decision)
```

---

*RFT_v3_018 EN 1.0 | Translation: T018 | 04.04.2026*  
*Source: RFT_v3_018_Entropie_Signaltheorie.md (DE Final-Candidate v1.0)*  
*Primary sources: v3_001 (γ-term) + v3_011 Ch. 14–15 (decoherence)*  
*Glossary: RFT_v3_Glossar_EN.md v1.0 (23.03.2026)*
