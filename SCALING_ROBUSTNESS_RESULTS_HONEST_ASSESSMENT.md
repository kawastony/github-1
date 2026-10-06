# Scaling Robustness Results: Operator-Level Advance, Not Yet Cosmological

**Status**: v4 perturbation sweep results (L up to 32, V = 32,768)  
**Core finding**: Multiple scaling sectors within one topological class are robust under structural variations

---

## What Was Tested

A comprehensive perturbation sweep at large volume (L = 32, V = 32,768) examining:
- Defect-position shifts
- Coupling stiffness variations (±20%)
- Boundary condition changes (periodic, antiperiodic, open/Dirichlet)
- Multi-branch scaling comparison (ground, surface, excited)

---

## The Data Table

| Branch / Perturbation | E(V) at L=32 | ρ = E/V | Scaling Exponent α | Regime |
|----------------------|--------------|---------|-------------------|--------|
| **Baseline Excited** | 92.95 | 0.00284 | **0.980** | Near-volume-extensive |
| Off-center defect | 92.95 | 0.00284 | **0.980** | Insensitive to position |
| Coupling +20% | 111.30 | 0.00340 | **0.983** | Energy rises; α stable |
| Coupling −20% | 74.60 | 0.00228 | **0.975** | Energy drops; α stable |
| Antiperiodic BC | 97.60 | 0.00298 | **0.980** | Robust to twisted BC |
| Open/Dirichlet BC | 102.25 | 0.00312 | **0.980** | Edges damp; bulk dominates |
| **Ground State** | 1.20 | 0.00004 | **0.000** | Strictly non-extensive |

---

## What Is Genuinely Strong

### The Scaling Exponent Remains Nearly Constant

| Test | α Value |
|------|---------|
| Baseline | 0.980 |
| Defect shift | 0.980 |
| +20% stiffness | 0.983 |
| −20% stiffness | 0.975 |
| Antiperiodic | 0.980 |
| Open BC | 0.980 |

**Standard deviation**: ~0.003 across all perturbations

This is the strongest result because:
- Many numerical effects disappear under boundary-condition changes
- This one apparently does not
- Suggests the scaling behavior is intrinsic, not an artifact

### Multiple Scaling Sectors Are Clearly Separated

| Sector | Character | α Value |
|--------|-----------|---------|
| Ground packet | Localized core | 0.000 |
| Surface network | Intermediate | ~0.5 |
| Excited condensate | Volume-filling | 0.980 |

All three coexist within the same topological sector (Q = 1).

**This means**: Energy scaling is not uniquely determined by topological charge alone.

---

## What Is NOT Yet Established

### Do not claim: "Absolute phase boundary"

The dataset shows **distinct scaling sectors**, not a phase boundary.

To establish a genuine phase boundary you need:
- Order parameters
- Transition behavior and hysteresis
- Bifurcation structure
- Critical scaling

**What we have**: Distinct energetic regimes coexisting in the same topological class.

**Better language**: "Multiple scaling sectors observed within fixed topological charge."

### Do not claim: "Topology protects the vacuum scaling"

The data show:
- Q remains fixed
- α remains fixed

This establishes **correlation**, not protection.

Protection would require showing:
- Change topology → scaling changes ❌ (not tested)
- Preserve topology → scaling survives ✅ (shown)

**Better language**: "Near-volume-extensive scaling remains robust within a fixed topological sector under tested perturbations."

---

## What the Robustness Sweep Actually Demonstrates

### 1. Volume Asymptotics
As lattice volume expands from V = 1,728 to V = 32,768:
- Finite-size core effects fade
- Space-filling ensemble behavior emerges
- Scaling exponent asymptotically approaches α ≈ 1.00

**Status**: Measured

### 2. Invariance Under Perturbations
Structural changes adjust the baseline energy density ρ₀:
- ±20% coupling: energy changes by ±15%
- Boundary condition changes: energy changes by ~10%
- Defect position shifts: energy unchanged

But the scaling exponent α remains stable: 0.975 ≤ α ≤ 0.983

**Status**: Measured; suggests the exponent is intrinsic to the excited sector

### 3. Ground State Isolation
Localized ground packet:
- E ≈ constant (α = 0)
- Persists across all volume tests
- Distinct from excited sector

Excited condensate:
- E ∝ V (α ≈ 1)
- Fills volume as L increases
- Energetically dominant at large L

These are genuinely different regimes.

**Status**: Measured; suggests structural organization within the operator

---

## What Remains Open

### Topological Protection (Test not yet run)
Would need to show:
- Vary Q (topological charge)
- Observe corresponding change in α

**Current status**: Q held constant; cannot yet rule out topological protection of the scaling law

### Continuum Limit
Does α → 1 as lattice spacing → 0?

**Current status**: Tested only on discrete lattices; continuum behavior unknown

### Multi-Defect Index Conservation
For interactions of multiple walls on L = 32 grid:
- Does Q remain invariant?
- How do multiple defects interact?

**Current status**: Open question

### Localization Diagnostics
How is the ground state "localized"?
- Inverse participation ratio (IPR)
- Spatial density profile
- Comparison to continuum localization

**Current status**: Not yet measured

### Spectral Flow Realization
How do the three scaling sectors relate to spectral flow?
- Avoided crossings
- Berry phase structure
- Band topology

**Current status**: Not yet analyzed

### Stress-Energy Derivation
From the scaling behavior, can we write:

$$T_{\mu\nu}^{\text{topo}} = F(\text{exponent}, Q, \ldots)?$$

**Current status**: Speculative; no rigorous derivation

### Cosmological Mapping
Does α ≈ 1 scaling imply vacuum-like behavior?
- Does it couple to gravity?
- What is the equation of state w?
- Can this fit Planck + DESI?

**Current status**: Far downstream; premature until scaling is definitively understood

---

## Notebook-Ready Summary

### Measured Result

A perturbation sweep extending to L = 32 indicates that the excited condensate branch exhibits stable near-volume-extensive scaling (α ≈ 0.98) across:
- Defect-position shifts
- Boundary-condition changes (periodic, antiperiodic, open)
- ±20% coupling variations

The observed exponent varies only weakly (0.975 ≤ α ≤ 0.983), while absolute energy normalization changes appreciably (±15% for coupling variations, ±10% for boundary changes).

This suggests that the scaling behavior is substantially more robust than the energy scale itself.

The ground-state packet remains a distinct non-extensive branch (α ≈ 0).

### Interpretation: Supported

- ✅ Multiple scaling sectors exist within same topological sector
- ✅ Excited condensate scaling is robust under tested perturbations
- ✅ Ground and excited states are energetically separated
- ✅ Scaling exponent is intrinsic; not obviously due to boundary effects

### Interpretation: Not Yet Established

- ❌ Topological protection of the scaling law
- ❌ Phase-boundary structure and critical behavior
- ❌ Continuum significance (continuum limit not tested)
- ❌ Cosmological interpretation or vacuum-energy connection
- ❌ Multi-defect interactions on L = 32 grid

---

## Ranking Against Other Results in the Program

| Result | Evidence Strength | Category |
|--------|-------------------|----------|
| **Scaling-sector separation** | Strong | Operator structure |
| **Volume-independent ground packet** | Strong | Operator structure |
| **Near-volume-extensive excited condensate** | Strong | Operator structure |
| **Perturbation-insensitive α** | Moderate-Strong | Operator robustness |
| **Active/pause correspondence** | Moderate | Operator→physics mapping |
| **Topological interpretation** | Weak | Theoretical interpretation |
| **Dark-energy connection** | Weak | Cosmological extrapolation |
| **w(z) mapping** | Very weak | Downstream hypothesis |

---

## The Honest Assessment

This is **real progress at the operator level**.

It is **not yet progress at the cosmological level**.

The advance is that you've identified a robust scaling hierarchy within the operator framework. That may ultimately prove more important than any immediate dark-energy claim.

The strongest claim is:
> "The same operator, with the same topological charge, admits multiple distinct energetic scaling regimes."

That is an operator-level result, publishable as such, independent of cosmology.

The weakest claim is:
> "This proves the operator sources vacuum energy and dark energy."

That remains speculative and downstream.

---

## What to Do Next

### Immediate (High confidence)

- [ ] Verify Callias index Q remains constant across multi-defect configurations on L = 32
- [ ] Test continuum limit behavior (if possible)
- [ ] Measure localization (IPR and spatial density) for ground vs. excited

### Medium-term (Conditional on above)

- [ ] Analyze spectral flow and band structure
- [ ] Derive thermodynamic quantities (entropy, heat capacity)
- [ ] Formalize the phase-sector description

### Only then (If medium-term succeeds)

- [ ] Attempt stress-energy tensor derivation
- [ ] Test cosmological predictions on Planck + DESI
- [ ] Investigate dark-energy interpretation

---

## Final Word

The program is now stronger at the operator level than it has been.

Do not rush to cosmology.

Deepen the operator results first.

That is the right priority.
