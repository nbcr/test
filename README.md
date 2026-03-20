## 2. Mathematical Framework

### 2.1 Setup

Let $\{U_i\}_{i=1}^{N}$ be a finite collection of 4‑dimensional Lorentzian manifolds without boundary (or with boundaries only at membranes). Adjacent universes $U_i$ and $U_j$ share a 3‑dimensional membrane $\partial_{ij}$ with induced metric $h_{ab}$. The membrane carries constant tension $\sigma$ and a phase shift $\Delta\theta_{ij}$ (fixed for all adjacent pairs).

The total action is
$$
S = \sum_i \frac{1}{16\pi G} \int_{U_i} \sqrt{-g^{(i)}} R^{(i)} \, d^4x
   + \sum_{\langle i,j \rangle} \int_{\partial_{ij}} \sqrt{h} \left( \frac{1}{8\pi G} K^{(i)} + \frac{1}{8\pi G} K^{(j)} + \sigma \right) d^3x,
$$

where $K^{(i)}$ is the trace of the extrinsic curvature of $\partial_{ij}$ as embedded in $U_i$. The membrane term includes the tension $\sigma$ and the Gibbons–Hawking–York boundary terms. Variation with respect to the metric on each $U_i$ yields the Einstein equations in the bulk, and the Israel junction conditions at the membranes:
$$
K^{(i)}_{ab} - K^{(j)}_{ab} = -8\pi G \, \sigma \, h_{ab}.
$$

### 2.2 Averaged Effective Equations

Assume the multiverse packing is homogeneous and isotropic on large scales, with coordination number $z$ (number of neighbors per universe). The average effect of the junction conditions can be incorporated into an effective stress‑energy tensor for a single universe. The tension $\sigma$ contributes a constant energy density
$$
\rho_{\Lambda,\text{eff}} = \frac{1}{2} \sigma \frac{A_{\text{total}}}{V},
$$

where $A_{\text{total}}/V$ is the total membrane area per unit volume in the comoving packing. For a regular tiling of a compact space, this ratio is fixed and constant in time, so $\rho_{\Lambda,\text{eff}}$ is a constant—a cosmological constant.

The gravitational influence of matter in neighboring universes is not fully shielded. A linearized analysis shows that the matter density $\rho_b$ in a neighbor contributes an effective energy density in our universe proportional to $\rho_b$. Because the multiverse expands homogeneously, this contribution scales as $a^{-3}$, exactly like pressureless matter. Hence we write
$$
\rho_{\text{DM,eff}} = \alpha z \rho_b,
$$

where $\alpha$ is a dimensionless coupling constant determined by the membrane physics (e.g., by the phase‑shift magnitude and the details of the junction conditions). For a symmetric arrangement, $\alpha$ is expected to be of order unity.

### 2.3 Effective Friedmann Equation

Combining the above, the Friedmann equation for our universe (assuming spatial flatness for simplicity) becomes
$$
H^2 = \frac{8\pi G}{3} \left[ \rho_b + \alpha z \rho_b + \rho_{\Lambda,\text{eff}} \right] + \text{(possible small corrections)}.
$$

The total matter density parameter is $\Omega_m = (1+\alpha z)\Omega_b$. Observations give $\Omega_m \approx 0.32$ and $\Omega_b \approx 0.05$, so
$$
1 + \alpha z \approx \frac{0.32}{0.05} = 6.4 \quad\Rightarrow\quad \alpha z \approx 5.4.
$$

For $\alpha = 1$, we obtain $z \approx 5.4$. Since $z$ must be an integer, $z = 5$ or $6$ are natural candidates. If $\alpha$ differs slightly from 1, the integer could be 4 or 5, still a small number. This is consistent with a finite, closed packing (e.g., a tiling of the 3‑sphere or a 4‑dimensional analogue).

The constant $\rho_{\Lambda,\text{eff}}$ is then determined by the membrane tension and the packing geometry. It must match the observed dark energy density $\Omega_\Lambda \approx 0.68$. This gives a relation between $\sigma$ and the curvature scale of the packing.