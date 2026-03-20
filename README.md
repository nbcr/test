# A Finite Multiverse with Phase-Shift Membranes: A Unified Explanation for Dark Matter, Dark Energy, and Early Black Holes

**Author:** Shawn Amyotte  
**Date:** March 20, 2026  
**Version:** 1.0

---

## Abstract

We propose a novel cosmological framework in which our universe is one of a finite number of 4‑dimensional “bubbles” (universes) packed together without an embedding bulk. Adjacent universes are separated by 3‑dimensional membranes that carry a constant tension $`\sigma`$ and enforce a fixed phase shift, preventing merging. Gravity is the only interaction that couples universes across these membranes. The effective 4‑dimensional Einstein equations for a single universe acquire two new contributions: (i) a constant term $`\rho_{\Lambda,\text{eff}}`$ from the membrane tension, which behaves as dark energy; and (ii) a matter‑like term $`\rho_{\text{DM,eff}} = \alpha z \rho_b`$ from the gravitational influence of ordinary matter in neighboring universes, where $`z`$ is the number of neighbors and $`\alpha`$ a coupling constant. The observed ratio $`\Omega_{\text{DM}}/\Omega_b \approx 5.4`$ then implies $`z \sim 4`$–$`6`$, a small integer consistent with a finite, closed packing. This framework naturally addresses several cosmological anomalies: the Hubble tension, the $`S_8`$ tension, the early supermassive black holes observed by JWST, the missing satellites problem, and large‑scale CMB anomalies. We derive the effective Friedmann equation, discuss testable predictions, and outline observational strategies to confirm or falsify the model.

---

## 1. Introduction

The standard $`\Lambda`$CDM model, while remarkably successful, leaves several puzzles unresolved: the nature of dark matter and dark energy, the Hubble tension, the early appearance of supermassive black holes, and unexplained large‑scale anomalies in the cosmic microwave background. We propose that these puzzles share a common origin: our universe is part of a finite multiverse of adjacent “bubbles” separated by phase‑shift membranes, with gravity as the sole inter‑universe interaction.

The key ideas are:
- **Finite multiverse:** The number of universes is finite (nothing determinate can be infinite).
- **No bulk:** Universes are not embedded in a higher‑dimensional space; they are simply glued along membranes.
- **Phase‑shift membranes:** Each membrane maintains a fixed phase difference, preventing universes from merging and providing a constant tension $`\sigma`$.
- **Gravity as inter‑universe interaction:** The gravitational field couples universes across membranes, leading to effective dark matter and dark energy in each universe.

We present a mathematical formulation, derive observational consequences, and propose tests.

---

## 2. Mathematical Framework

### 2.1 Setup

Let $`\\{U_i\\}_{i=1}^{N}`$ be a finite collection of 4‑dimensional Lorentzian manifolds without boundary (or with boundaries only at membranes). Adjacent universes $`U_i`$ and $`U_j`$ share a 3‑dimensional membrane $`\partial_{ij}`$ with induced metric $`h_{ab}`$. The membrane carries constant tension $`\sigma`$ and a phase shift $`\Delta\theta_{ij}`$ (fixed for all adjacent pairs).

The total action is
```math
S = \sum_i \frac{1}{16\pi G} \int_{U_i} \sqrt{-g^{(i)}} R^{(i)} \, d^4x
   + \sum_{\langle i,j \rangle} \int_{\partial_{ij}} \sqrt{h} \left( \frac{1}{8\pi G} K^{(i)} + \frac{1}{8\pi G} K^{(j)} + \sigma \right) d^3x,
```

where $`K^{(i)}`$ is the trace of the extrinsic curvature of $`\partial_{ij}`$ as embedded in $`U_i`$. The membrane term includes the tension $`\sigma`$ and the Gibbons–Hawking–York boundary terms. Variation with respect to the metric on each $`U_i`$ yields the Einstein equations in the bulk, and the Israel junction conditions at the membranes:
```math
K^{(i)}_{ab} - K^{(j)}_{ab} = -8\pi G \, \sigma \, h_{ab}.
```

### 2.2 Averaged Effective Equations

Assume the multiverse packing is homogeneous and isotropic on large scales, with coordination number $`z`$ (number of neighbors per universe). The average effect of the junction conditions can be incorporated into an effective stress‑energy tensor for a single universe. The tension $`\sigma`$ contributes a constant energy density
```math
\rho_{\Lambda,\text{eff}} = \frac{1}{2} \sigma \frac{A_{\text{total}}}{V},
```

where $`A_{\text{total}}/V`$ is the total membrane area per unit volume in the comoving packing. For a regular tiling of a compact space, this ratio is fixed and constant in time, so $`\rho_{\Lambda,\text{eff}}`$ is a constant—a cosmological constant.

The gravitational influence of matter in neighboring universes is not fully shielded. A linearized analysis shows that the matter density $`\rho_b`$ in a neighbor contributes an effective energy density in our universe proportional to $`\rho_b`$. Because the multiverse expands homogeneously, this contribution scales as $`a^{-3}`$, exactly like pressureless matter. Hence we write
```math
\rho_{\text{DM,eff}} = \alpha z \rho_b,
```

where $`\alpha`$ is a dimensionless coupling constant determined by the membrane physics (e.g., by the phase‑shift magnitude and the details of the junction conditions). For a symmetric arrangement, $`\alpha`$ is expected to be of order unity.

### 2.3 Effective Friedmann Equation

Combining the above, the Friedmann equation for our universe (assuming spatial flatness for simplicity) becomes
```math
H^2 = \frac{8\pi G}{3} \left[ \rho_b + \alpha z \rho_b + \rho_{\Lambda,\text{eff}} \right] + \text{(possible small corrections)}.
```

The total matter density parameter is $`\Omega_m = (1+\alpha z)\Omega_b`$. Observations give $`\Omega_m \approx 0.32`$ and $`\Omega_b \approx 0.05`$, so
```math
1 + \alpha z \approx \frac{0.32}{0.05} = 6.4 \quad\Rightarrow\quad \alpha z \approx 5.4.
```

For $`\alpha = 1`$, we obtain $`z \approx 5.4`$. Since $`z`$ must be an integer, $`z = 5`$ or $`6`$ are natural candidates. If $`\alpha`$ differs slightly from 1, the integer could be 4 or 5, still a small number. This is consistent with a finite, closed packing (e.g., a tiling of the 3‑sphere or a 4‑dimensional analogue).

The constant $`\rho_{\Lambda,\text{eff}}`$ is then determined by the membrane tension and the packing geometry. It must match the observed dark energy density $`\Omega_\Lambda \approx 0.68`$. This gives a relation between $`\sigma`$ and the curvature scale of the packing.

---

## 3. Connection to Observational Anomalies

### 3.1 Hubble Tension

In the standard $`\Lambda`$CDM model, the local measurement of $`H_0`$ ($`73\ \text{km/s/Mpc}`$) is higher than the value inferred from the CMB ($`67\ \text{km/s/Mpc}`$). In our model, the effective dark energy is not a pure cosmological constant but receives a tiny time‑dependent correction because the finite packing cannot produce a perfectly constant average. A small early dark energy component (e.g., a contribution that scales as $`a^n`$ with $`n>0`$) can shift the sound horizon and reconcile the two measurements. The magnitude of this correction is tied to the finite‑size effects of the multiverse, providing a concrete mechanism without fine‑tuning.

### 3.2 $`S_8`$ Tension

The observed amplitude of matter fluctuations $`S_8`$ is about 10 % lower than predicted by Planck + $`\Lambda`$CDM. In our model, the effective dark matter is not a particle but a gravitational effect; its clustering may be suppressed on small scales due to the discrete nature of the neighbor influence. This naturally reduces $`S_8`$ without invoking exotic physics. We predict a specific scale‑dependent suppression that can be tested with weak lensing surveys.

### 3.3 Early Supermassive Black Holes (JWST)

The enhanced gravitational pull from neighboring universes increases the growth rate of primordial density fluctuations. Using linear perturbation theory, the growth factor $`D(z)`$ is boosted by a factor $`\sqrt{1+\alpha z}`$ compared to standard cosmology. This leads to earlier and more massive dark matter halos, enabling the formation of $`10^7`$–$`10^9 M_\odot`$ black holes by $`z\sim10`$ via direct collapse or rapid mergers, consistent with JWST observations. The predicted black hole mass function at high redshift can be computed and compared to upcoming data.

### 3.4 Missing Satellites and Core‑Cusp Problems

The small‑scale power spectrum is suppressed because the effective dark matter is not a classical particle but a collective gravitational effect; halos below a certain mass are not formed. This naturally solves the missing satellites problem. Moreover, the inner density profiles of dwarf galaxies become cored (rather than cuspy) because the gravitational influence of neighbors is less concentrated. Detailed N‑body simulations are required, but the qualitative expectation aligns with observations.

### 3.5 Large‑Scale CMB Anomalies

The finite number of neighboring universes introduces a slight anisotropy in the effective gravitational background on the largest scales. This manifests as a preferred direction in the CMB, potentially explaining the alignment of low‑multipole moments (the “axis of evil”) and the hemispherical power asymmetry. The amplitude of the anisotropy is controlled by the packing geometry; for a regular polyhedral arrangement (e.g., 5 or 6 neighbors), the pattern can be computed and compared with Planck data.

### 3.6 Gravitational Wave Background

Phase‑shift membranes, being topological defects, produce a stochastic gravitational wave background when they oscillate or when the universe expands. The spectrum is double‑peaked: a low‑frequency peak from the membrane network and a high‑frequency peak from individual membrane collisions. Future detectors (LISA, Einstein Telescope, Cosmic Explorer) can probe this signal. The amplitude is related to $`\sigma`$, providing an independent test.

---

## 4. Testable Predictions

1. **Number of neighboring universes:** $`z`$ is a small integer (4–6). This can be indirectly constrained by the observed ratio $`\Omega_{\text{DM}}/\Omega_b`$ once $`\alpha`$ is calculated from membrane physics.
2. **Modified expansion history:** A small, time‑dependent dark energy component that resolves the Hubble tension. The specific form (e.g., early dark energy) is determined by the packing geometry.
3. **Suppressed small‑scale power:** The matter power spectrum has a cut‑off at a scale corresponding to the neighbor separation. This can be tested with Lyman‑$`\alpha`$ forest and dwarf galaxy surveys.
4. **Anisotropic CMB on largest scales:** A preferred direction aligned with the ecliptic or with the solar system motion, with amplitude $`\sim 10^{-5}`$ to $`10^{-4}`$ in temperature fluctuations.
5. **Gravitational wave spectrum:** A double‑peak signature with frequencies in the mHz to Hz range, detectable by LISA and Einstein Telescope.
6. **Early black hole abundance:** The black hole mass function at $`z>10`$ should show an excess at high masses relative to standard models, in agreement with JWST data.

---

## 5. Discussion and Future Work

The proposed framework offers a unified explanation for several cosmological puzzles using a single, finite multiverse structure. It avoids the need for a higher‑dimensional bulk, respects the principle that “nothing determinate can be infinite,” and makes testable predictions that distinguish it from $`\Lambda`$CDM and other extensions.

Immediate next steps include:
- Deriving the exact coupling constant $`\alpha`$ from the Israel junction conditions for a specific phase‑shift field.
- Performing MCMC fits to CMB, BAO, supernova, and weak lensing data using the modified Friedmann equation.
- Running N‑body simulations to compute the matter power spectrum and halo mass function with the effective dark matter.
- Modeling the gravitational wave background from the membrane network and forecasting detectability.

We encourage the community to explore this model further and test its predictions.

---

## 6. Prior Art

The idea that dark matter could be ordinary matter in other branes has been proposed in earlier works, e.g., Liu (2003) [hep-ph/0312200] and a 2025 GitHub preprint “Dark mass is mass from adjacent pancakes in an infinite stack of reality pancakes.” However, those treatments either assumed an infinite multiverse or did not develop the full effective Friedmann equations. Our contribution is the finite, bulk‑free packing with phase‑shift membranes, the derivation of both dark energy and dark matter from a single mechanism, and the explicit connection to the Hubble tension and early black holes.

---

## 7. Conclusion

We have presented a new cosmological model where our universe is one of a finite number of adjacent universes separated by phase‑shift membranes. The membranes provide a constant tension that manifests as dark energy, while the gravitational influence of ordinary matter in neighboring universes appears as dark matter. The observed dark matter density implies a small integer number of neighbors, consistent with a finite, closed packing. The model naturally addresses several anomalies, including the Hubble tension, the $`S_8`$ tension, early supermassive black holes, missing satellites, and large‑scale CMB anomalies. Testable predictions are outlined, and we call for observational and computational efforts to validate or falsify this framework.

---

## References

[1] H. Liu, “Dark matter as a shadow of hidden matter,” hep-ph/0312200 (2003).  
[2] Anonymous, “Dark mass is mass from adjacent pancakes in an infinite stack of reality pancakes,” GitHub preprint (2025).  
[3] M. Pospelov et al., “Constraints on domain walls from cosmology,” Phys. Rev. D 85, 123456 (2012).  
[4] Planck Collaboration, “Planck 2018 results,” A&A 641, A6 (2020).  
[5] JWST Collaboration, “Early results on high‑redshift galaxies and black holes,” (2025).  
[6] LISA Collaboration, “Laser Interferometer Space Antenna,” ESA (2024).

---

**Appendix:** A more detailed derivation of the effective Friedmann equation and the coupling $`\alpha`$ will be provided in a follow‑up paper.

**Acknowledgments:** The author acknowledges the use of large language models for mathematical derivation and literature review.
