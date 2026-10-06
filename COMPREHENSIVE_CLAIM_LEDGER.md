# The v4 Claim Ledger: What Is Earned, Supported, Open, and Retired

**Status**: Complete inventory of research claims across all program phases  
**Core principle**: Every statement carries a status label; movement between categories requires named tests

---

## Overview

This ledger consolidates the complete research program from Phase 0 (Original TAFA/Cone Engine) through Phase 4 (Audit/v4 Discipline). It separates:

- **Earned**: Nonperturbative lattice ground truth and verified computations
- **Supported**: Robust patterns within the model, but not yet fully derived
- **Open**: Known gaps requiring resolution before further claims
- **Retired**: Hypotheses definitively abandoned or superseded
- **Not Claimed**: Explicit boundaries to prevent overstatement

---

## EARNED (Nonperturbative Lattice Ground Truth & Verified Computations)

### Micro-Topology Foundation

**8-Component Wilson-Dirac Operator**
- The 8-component matrix algebra on $T^3$ with mass-texture anti-alignment ($\chi_{\beta n} \approx -0.81$) supports Callias zero modes
- **Status**: Constructed and verified across multiple lattice sizes
- **Boundary**: Does not yet prove uniqueness; only that it works

**Topological Index Invariance**
- The index $Q = 1.0$ remains stable across volume expansion from $V = 216$ to $V = 32,768$
- Measured to machine precision: $Q(L=6) = Q(L=32)$
- **Status**: Measured across all lattice configurations
- **Boundary**: Does not prove topological protection of energy scaling; only that the index is stable

**Ground-State Non-Extensive Scaling ($\alpha \equiv 0$)**
- Ground-state packet energy remains effectively constant: $E(V) \approx 1.200$ across $V = 216 \to 1728$
- Scaling exponent: $\alpha = 0.0000 \pm 0.0001$ (to numerical precision)
- Energy density dilutes as matter: $\rho \propto V^{-1}$
- **Status**: Verified via spatial integral, spectral trace, and matrix norm; invariant across 5-point extraction audit
- **Robustness**: Insensitive to lattice discretization, boundary conditions, geometric aspect ratio

**Excited Condensate Volume Scaling ($\alpha \approx 0.98 \to 1.00$)**
- Space-filling excited branch exhibits near-volume-extensive scaling: $\alpha \approx 0.980$ at $L = 32$
- Asymptotic behavior (via finite-size correction model): $\alpha_{\text{asymptotic}} = 1.0000 \pm 0.0002$
- Exponent range across perturbations: $0.975 \le \alpha \le 0.983$ (variation ~0.3%)
- **Status**: Verified across 8× volume expansion, 3 energy definitions, 3 fit-family ansätze
- **Robustness**: Stable under:
  - Defect-position shifts
  - ±20% coupling stiffness changes
  - Periodic, antiperiodic, and open/Dirichlet boundary conditions
  - Lattice refinement toward continuum ($a \to 0$)
  - Non-cubic spatial geometries (slab, tri-axial)

**Spectral Degeneracy (Exact)**
- Lowest doublet splitting: $\Delta E \approx 10^{-16}$ (numerical noise)
- First and second eigenvalues indistinguishable: $\lambda_0 \approx \lambda_1$ to floating-point precision
- **Status**: Measured across all volume sizes
- **Interpretation**: No finite-size lifting of degeneracy observed

**Wall Density Geometric Dilution**
- Wall count remains fixed: $N_{\text{wall}} = 32$ across volume expansion
- Wall density follows exactly: $n_{\text{wall}} = 32/V$
- **Status**: Measured; not fitted
- **Implication**: Wall dilution is purely geometric, not dynamical

### Operator-Level Branching Structure

**Bimodal Branch Separation**
- Two sharply separated scaling regimes coexist within the same topological sector
- Separation measured via spatial variance ratio: $\text{VR} \gg 10$ (ground) vs. $\text{VR} \ll 0.02$ (condensate)
- Bimodality gap completely empty: no configurations between $0.05 < \text{VR} < 10.0$
- **Status**: Verified via 3 independent diagnostics (variance ratio, IPR, spatial entropy)
- **Cross-validation**: 100% concordance across all three metrics

**Multiple Scaling Sectors Within Fixed Topological Class**
- Ground packet: $\alpha = 0.000$ (non-extensive)
- Surface/intermediate regime: $\alpha \sim 0.5$ (geometric scaling)
- Excited condensate: $\alpha \approx 1.0$ (volume-extensive)
- All coexist with $Q = 1.0$ constant
- **Status**: Measured and reproducible
- **Implication**: Energy scaling is not uniquely determined by topological charge alone

### Galactic / Observational Anchors

**SPARC Rotation Curve Normalization**
- Standard normalization $a_0 = 1.2 \times 10^{-10}$ m/s² gives residuals: mean = -0.161 dex, MAE = 0.142 dex
- Cone-derived normalization $R_{\text{cone}} = \sqrt{6}/\varphi \approx 1.51387$ shifts residuals to: mean = +0.019 dex, MAE = 0.051 dex
- **Status**: Empirical fit result; measured on 175-galaxy SPARC sample
- **Boundary**: Does not prove the operator sources dark matter; only that a specific normalization improves fit

**Geometric Dark Energy Point** (w₀, wₐ) 
- Locked point: $(w_0, w_a) = (-\varphi/2, -1/\varphi) \approx (-0.809, -0.618)$
- Phantom crossing: $z_{\text{cross}} = 1/\sqrt{5} \approx 0.447$
- DESI DR1 BAO constraint: $\Delta\chi^2 = -0.96$ relative to $\Lambda$CDM
- **Status**: Geometric prediction, measured against DESI data
- **Boundary**: Consistency with one observable does not validate the full cosmological model

---

## SUPPORTED (Robust Within-Model Patterns)

**Energetic Multiplicity of Topological Classes**
- A single topological sector ($Q = 1.0$) supports at least two distinct energetic organizations
- **Evidence**: Multiple scaling sectors with different $\alpha$ values all carry $Q = 1$
- **Status**: Strongly supported; requires further investigation into the mechanism
- **Uncertainty**: Why multiple regimes coexist; what determines transitions

**Scaling Invariance Over Normalization**
- The scaling exponent $\alpha$ is substantially more robust against structural perturbations than absolute energy scale $\rho_0$
- When couplings change by ±20%, energy changes by ±15%, but $\alpha$ remains fixed to ~0.3%
- **Evidence**: Perturbation sweep table showing stable $\alpha$ across boundary/coupling/position variations
- **Status**: Strongly supported
- **Interpretation**: Suggests $\alpha$ is intrinsic; $\rho_0$ is more phenomenological

**Forman-Based State Classification**
- Relative Forman depth ($F^{\text{rel}}$) predicts early bridge-feeding rate ($\Delta W_8$) better than raw control couplings
- Mediating role of geometric curvature in state transitions
- **Evidence**: Correlation analysis in Phase 2 notes
- **Status**: Supported within the active/pause framework
- **Limitation**: Mechanism not yet formally derived

**Active/Pause Phase Correspondence**
- Three distinct energy organizations plausibly map to active (high-energy bulk), pause-1 (intermediate surface), and pause-2 (confined, low-energy) regimes
- **Evidence**: Scaling exponents align with phase structure descriptions
- **Status**: Plausible correspondence; requires formal phase-transition derivation
- **Work needed**: Show that transitions are thermodynamically necessary, not just phenomenologically convenient

---

## OPEN (Known Gaps Requiring Resolution)

### Critical Mathematical Bridges

**Stress-Energy Tensor Derivation: $T_{\mu\nu}^{\text{topo}} = F(Q)$**
- The central unresolved question: Does the index $Q$ determine an effective stress-energy tensor?
- **What is known**: $Q$ is conserved; $E(V) \propto V$ for excited branch
- **What is unknown**: 
  - Formal derivation connecting $Q$ to $T_{\mu\nu}$
  - Why (if true) $T_{\mu\nu}$ should couple to gravity
  - Pressure components $P_x, P_y, P_z$ and whether $P \approx -\rho$
- **Test**: Measure directional pressures via anisotropic box deformations (Note 49 protocol)
- **Status**: Foundational question; not yet addressed

**Equation of State from Operator Scaling**
- Hypothesis: $E(V) \propto V^\alpha$ implies $w = \alpha - 1$
- **Problem**: This is not automatic; requires formal derivation from thermodynamics
- **What would establish it**: 
  1. Measure pressure $P_i$ from deformations
  2. Compute $w_i = P_i / \rho$
  3. Show consistency with scaling law
- **Current status**: Untested

**Isotropy of Effective Stress-Energy**
- Does $P_x \approx P_y \approx P_z$ hold?
- **Critical for cosmology**: Isotropic stress is required for FRW metric
- **Test**: Measure pressures in three orthogonal directions (Note 49)
- **Current status**: Untested

### Scale Transfer & Cosmological Coupling

**Volume Scaling → Cosmological w(z)**
- Hypothesis: Operator volume-scaling exponent $\alpha$ maps to cosmological equation-of-state trajectory
- **Problem**: This is a cross-scale hypothesis with many intermediate steps:
  - Micro-operator $\to$ effective field theory
  - Effective field theory $\to$ stress-energy tensor
  - Stress-energy tensor $\to$ Einstein equations
  - Einstein equations $\to$ Hubble expansion $H(z)$
  - Hubble expansion $\to$ equation of state $w(z)$
- **Current status**: Not yet proven; each step requires separate validation

**Micro→Macro Inheritance Mechanism**
- How do microscopic operator properties transmit to macroscopic cosmology?
- **Candidates**:
  - Vacuum expectation values averaged over large volumes
  - Collective long-range field modes
  - Emergent topological protection at cosmological scales
- **Current status**: Speculative; no clear mechanism identified

**Continuum Limit Realization**
- Does the lattice operator have a well-defined continuum limit?
- **Evidence so far**: Exponent improves with lattice refinement ($a \to 0$)
- **What's open**: 
  - Full continuum operator and its properties
  - Relationship to continuum QFT or string theory
  - Existence of correlation functions in continuum limit
- **Current status**: Partially tested; needs formal definition

### Multi-Scale Consistency

**Callias Index Proof on the Lattice**
- Is the discrete index rigorously connected to the continuum Callias theorem?
- **Current status**: Numerically observed; not yet mathematically proven

**Defect-Defect Interactions at Large Volume**
- How do multiple walls interact on $L = 32$ grids?
- **Current status**: Not yet measured

**Early-Universe Compatibility**
- If the operator sector exists at high redshift, does it affect BBN abundances?
- At what temperature does the excited condensate appear?
- **Current status**: Not addressed

**Large-Scale Structure Predictions**
- What does the operator predict for galaxy cluster counts, weak lensing, or baryon acoustic oscillations?
- **Current status**: Only the BAO constraint $(w_0, w_a)$ has been tested

---

## RETIRED (Hypotheses Abandoned or Superseded)

### Explicitly Rejected Approaches

**String/Flux Dictionary for $R$ and 11/72**
- **Original claim**: 10D string flux configurations uniquely determine $R \approx 1.5156$ and eigenvalue 11/72
- **Status**: **Formally retired**
- **Reason**: No evidence for 10D embedding; 5D cone accounting provides exact identities without flux
- **Current foundation**: 
  - $R_{\text{cone}} = \sqrt{6}/\varphi$ (cone geometry)
  - $(11/72)_{\text{cone}} = \Delta y / \varphi$ (cone dimensional reduction)

**Bessel Roots ≡ Lattice Soft Eigenvalues**
- **Original claim**: Conical Bessel root eigenvalues exactly match lattice soft-mode spectrum
- **Status**: **Dropped** (Milestone 3)
- **Reason**: Numerics show approximate correspondence only; not exact equivalence
- **Current status**: Bessel and lattice structures are distinct; may both contribute to physics

**Fuzzy Dark Matter Soliton Core Equivalence**
- **Original claim**: 1-kpc isolated FDM soliton core is equivalent to lattice operator ground packet
- **Status**: **Dropped** (Milestone 3)
- **Reason**: Scale and structure mismatch; different physical mechanisms
- **Current status**: Ground packet is operator-specific; does not inherit FDM phenomenology

**Pure-Geometry SI Units**
- **Original claim**: Deriving meters, seconds, or eV from pure geometric shapes alone
- **Status**: **Forbidden** by the One-Input No-Go Theorem (Phase 0 foundational principle)
- **Current position**: Exactly one external scale must be imported; all other quantities derive from it

**"Absolute Phase Boundary" Between Branches**
- **Original phrasing**: "Distinct phases with phase boundary"
- **Status**: **Downgraded** to "distinct scaling sectors"
- **Reason**: Phase boundary requires order parameters, critical behavior, hysteresis—not yet demonstrated
- **Current status**: Different regimes observed; phase-transition structure still open

---

## NOT CLAIMED (Explicit Boundaries)

### Statements Explicitly Forbidden from the Notebook

**Cosmological Claims Without Derivation**
- ❌ "The operator explains dark energy"
- ❌ "This is a dark-energy model"
- ❌ "The excited condensate is vacuum energy"
- **Replacement**: "The operator supports a volume-extensive energy configuration that may merit investigation as a candidate stress-energy source"

**Topological Causation Without Evidence**
- ❌ "Topology causes the volume scaling"
- ❌ "Topological protection of vacuum energy"
- **Replacement**: "The scaling exponent remains stable within a fixed topological sector under tested perturbations"

**Oversimplified Scale Transfer**
- ❌ "$E(V) \propto V$ automatically means $w = -1$"
- ❌ "$\alpha = 1$ is equivalent to dark energy"
- **Replacement**: "Volume-extensive scaling is consistent with vacuum-like behavior if pressure response confirms $P \approx -\rho$"

**Absolute Uniqueness Claims**
- ❌ "The 8-component operator is the only solution"
- ❌ "The 11/72 eigenvalue is uniquely forced"
- **Replacement**: "The tested framework admits these properties; uniqueness remains open"

**Claimed Completeness**
- ❌ "The program is now a closed theory"
- ❌ "All bridges are established"
- **Replacement**: "The operator foundation is robust; multiple bridges remain under construction"

### Explicit No-Claim Zones

**Dark Matter as Direct Operator Consequence**
- Ground packet is non-extensive; cannot source cosmological dark matter
- No formal connection to SPARC dynamics established
- $R_{\text{cone}}$ improvement is empirical fit, not derivation

**Uniqueness of Dark Energy Source**
- Even if excited condensate has $w \approx -1$, it is not proven to be the *only* source of cosmic acceleration
- Other mechanisms could coexist

**Modified Gravity Equivalence**
- The cone geometry is not claimed equivalent to MOND, TeVeS, or other modified gravity
- Phenomenological agreement with SPARC does not imply theoretical equivalence

---

## Movement Between Categories: Required Tests

### Conditions for "$\text{Open} \to \text{Supported}$"

1. **Stress-Energy Derivation**
   - Test: Measure $P_i$ via anisotropic box deformations (Note 49)
   - Success criterion: $w_i = P_i / \rho$ stable and isotropic
   - Next step: "Supported"

2. **Phase Transition Structure**
   - Test: Measure order parameters and bifurcation behavior
   - Success criterion: Hysteresis or critical scaling observed
   - Next step: "Supported"

3. **Continuum Limit**
   - Test: Refine lattice ($a \to 0$) and demonstrate smooth convergence
   - Success criterion: Continuum operator exists with same properties
   - Next step: "Supported"

### Conditions for "$\text{Supported} \to \text{Earned}$"

1. **Forman-Phase Connection**
   - Test: Formally derive active/pause transitions from Forman curvature
   - Success criterion: Transitions are thermodynamic necessities, not just observed patterns
   - Next step: "Earned"

2. **Multi-Defect Index Conservation**
   - Test: Run $L = 32$ grids with multiple walls and verify $Q_{\text{total}} = \sum Q_i$
   - Success criterion: Index additivity holds across all configurations
   - Next step: "Earned"

### Conditions for "$\text{Open} \to \text{Retired}$" (Falsification)

1. **Pressure Response Fails**
   - If: $P_i$ unmeasurable or highly anisotropic ($|w_x - w_y| > 0.1$)
   - Then: Vacuum-energy interpretation retired

2. **Scaling Collapses Under Perturbation**
   - If: $\alpha$ changes dramatically under small parameter changes
   - Then: Robustness claim retired

3. **Continuum Limit Diverges**
   - If: Properties do not improve with $a \to 0$
   - Then: Lattice result interpreted as discretization artifact

---

## Current Position Summary

| Category | Count | Status |
|----------|-------|--------|
| **Earned** | 12 claims | Solid foundation |
| **Supported** | 4 patterns | Robust within model |
| **Open** | 9 questions | Critical tests in progress |
| **Retired** | 5 hypotheses | Explicitly abandoned |
| **Not Claimed** | 12 statements | Boundaries explicit |

---

## The Discipline This Ledger Enforces

1. **Every claim has a status**, preventing vague assertions
2. **Movement between categories requires tests**, preventing drift
3. **Falsification paths are explicit**, making the program testable
4. **Boundaries are clear**, preventing overstatement
5. **Retired ideas are recorded**, preventing recycling of failed approaches

This is the structure of a research program that can survive peer review.

---

## Next Actions

### Immediate (High Confidence)
- [ ] Execute Note 49 anisotropic deformation experiment
- [ ] Measure directional pressures and equation of state
- [ ] Test isotropy under varied defect placements

### Medium-term (If above succeeds)
- [ ] Formalize stress-energy tensor derivation
- [ ] Solve Friedmann equations with operator-derived $(\rho, p)$
- [ ] Compare $w(z)$ predictions to Planck + DESI

### Long-term (Only if earlier steps succeed)
- [ ] Investigate dark matter sector connection
- [ ] Search for additional observational signatures
- [ ] Explore early-universe implications

---

## Final Note

This ledger is not a theory; it is a research program.

It does not claim final answers; it documents what is known and what remains to be discovered.

It is designed to survive rigorous external scrutiny because every statement is grounded in evidence or explicitly flagged as open.

That is the standard this program must maintain.
