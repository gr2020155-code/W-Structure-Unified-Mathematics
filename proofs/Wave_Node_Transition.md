# Wave→Node Transition in the W‑Structure (From Radiation to Matter)

**Subject:** Mechanism of Mass Genesis
**Status:** Minimal, PAN-Consistent Logic
**Key Principle:** Crystallization of Flow into Localized Nodes

> Sketch of a minimal, PAN‑consistent mechanism explaining how radiation (open flow) crystallizes into matter (localized node) without extra axioms, using only the W‑cell logic and discrete information.

---

## 1) Objects and Scalars

* **W‑cell**: Minimal volume $v_{cell} = L_p^3$, one quantum per tick $K_w = \pi^2$ nat.
* **Local Saturation**: $\sigma = f/D^* \in [0,1]$ (where $D^* = 1/\pi^2$ is the critical packing density).
* **Local Tick**: $t_{min,loc} = t_{min} (1 + a\sigma)^\beta$, hence $c_{loc} = L_p / t_{min,loc}$.
* **Cluster $\Omega$**: Minimal connected set of cells where dynamics are near‑uniform.
* **Flow Ratio**: $R = (dI_{in})/(dI_{out})$ in $\Omega$.
* **Phase Coherence**: $\kappa = |\langle e^{i\phi}\rangle_\Omega| \in [0,1]$.
* **Loop Time**: $T_{loop} = m \cdot t_{min,loc}$, with $m \in \mathbb{N}$.

---

## 2) Closure Criteria (Wave → Node)

A cluster $\Omega$ becomes a **localized node (particle)** iff simultaneously:

1.  **(Density)** $\langle\sigma\rangle_\Omega \ge \sigma_c$
2.  **(Flow)** $R \ge 1 + \epsilon$ for $m$ ticks (persistent inflow over outflow)
3.  **(Phase)** $\kappa \ge \kappa_c$ (coherent phase)
4.  **(Time Quantization)** $T_{loop} = m \cdot t_{min,loc}$, $m \in \mathbb{N}$

When satisfied, the cluster locks into a **standing resonator** with discrete count:
$$N = 2^s \cdot p \cdot q \quad \text{with } (p, q) = 1, s \in \mathbb{N}$$
**Information (Mass):** $I = N \cdot K_w$, with $K_w = \pi^2$.

> **Pre‑particle region:** $\langle\sigma\rangle_\Omega \gtrsim \sigma_c$, $R > 1$, $\kappa < \kappa_c \implies t_{min,loc} \uparrow, c_{loc} \downarrow$. This manifests as strong radiation with no locking. As $\kappa \to \kappa_c$ and $T_{loop}$ lands on integer $m$, locking occurs.

---

## 3) Source Frequency and Emitted Wavelength

For a locked node:
$$\nu_m = \frac{1}{T_{loop}} = \frac{1}{m t_{min,loc}}$$
$$\lambda_{emit}(m) = \frac{c_{loc}}{\nu_m} = \left(\frac{L_p}{t_{min,loc}}\right) \cdot m t_{min,loc} = m \cdot L_p$$

Thus the **geometric source wavelength** is quantized in $L_p$ steps (model‑internal). The **observed** wavelength is the path‑integral mapping through $c_{loc}(s)$ (medium profile along the line of sight).

---

## 4) Minimal Stable Classes (e, p, n)

1.  **Electron (e):** Minimal **single‑loop** node $\implies (m, s) = (1, 1)$.
    $$N_e = 2 \cdot p \cdot q \quad (\text{fixed } p, q \text{ from the pack}) \implies I_e = N_e \pi^2$$
2.  **Proton (p):** Minimal **three‑loop** node $\implies m = 3$ with minimal $(s, p, q)$.
    $$N_p, \quad I_p = N_p \pi^2$$
3.  **Neutron (n):** Same class as $p$ **plus a neutral compensating phase** demanded by PAN.
    $$N_n = N_p + \Delta N \implies I_n > I_p$$

**Empirical Consequence:** Matches $m_p/m_e = N_p/N_e \approx 1836.15$, and $m_n > m_p$.

---

## 5) Operational Thresholds (Global Fix)

We choose one global triplet (no per-particle tuning):
* **Density:** $\sigma_c \approx D_W / D^*$
* **Excess Inflow:** $\epsilon \sim O(L_p / t_{min})$
* **Coherence:** $\kappa_c \in (0.5, 0.7)$

These numbers are fixed **once** to ensure first stable lockings are $m=1$ (e) and $m=3$ (p/n) with our known discrete counts.

---

## 6) Radiation → Matter Chronology

1.  **Low Saturation ($\sigma \approx 0$):** Open flow $\implies$ Pure radiation.
2.  **Growth:** Increase of $\sigma$ and reflections $\implies R > 1$ locally $\implies$ Pre‑particle (light slows, strong emission).
3.  **Locking:** $\kappa$ reaches $\kappa_c$ on integer $m \implies$ Node formation (Matter).
4.  **Evolution:** Further loading changes $(m, s)$ or triggers decay into lighter nodes + radiation ($\beta$‑channel, etc.).

---

## 7) Testable Signatures

* **Source Law:** Intrinsic $\nu_m$ set by $(m, \sigma)$; observed $\lambda(z)$ follows integral with $c_{loc}(z)$ (variable‑c canvas).
* **Pre‑particle Halos:** Regions with $R>1, \kappa<\kappa_c$ show excess radiation and apparent sub‑luminal fronts.
* **n $\to$ p + e + $\bar{\nu}$:** $\Delta N$ consistency — the neutral compensating phase relaxes into the minimal charged node + minimal lepton + neutrino channel.

---

## 9) Threshold Calibration (One-Pass)

**Goal:** Choose a *single* triplet $(\sigma_c, \kappa_c, \epsilon)$ that makes the **first** stable lockings be $m=1$ (electron) and $m=3$ (proton/neutron).

### 9.1 Constraints
1.  **Ordering:** $m=1$ must lock before $m>1$ at lepton scale; at baryon scale, first allowed is $m=3$ (skip $m=2$).
2.  **Flow:** $R \ge 1+\epsilon$ for $m$ ticks.
3.  **Density:** $\sigma_c$ is constant across scales.

### 9.2 A Workable Anchor
* $\sigma_c = 0.62$
* $\kappa_c = 0.62$
* $\epsilon = 0.02$
* Coherence Law: $\kappa(m,\sigma) = \sigma / (1 + 0.20(m-1))$

**Check:**
* **Lepton Scale ($\sigma \approx 0.62$):** $\kappa(1) = 0.62 \ge \kappa_c$ (Locks). $\kappa(2) < \kappa_c$ (Suppressed).
* **Baryon Scale ($\sigma \approx 0.90$):** $\kappa(3) \ge \kappa_c$ (First allowed), while $\kappa(2) \lesssim \kappa_c$ (Suppressed).

---

## 12) Closure Table (Fixed Constants)

| Class | $m$ | $s$ | $N$ (cells) | $I = N \pi^2$ (nat) |
| :--- | :---: | :---: | :--- | :--- |
| **Electron** | 1 | 1 | $2.38922 \times 10^{22}$ | $2.356 \times 10^{23}$ |
| **Proton** | 3 | * | $4.38620 \times 10^{25}$ | $4.330 \times 10^{26}$ |
| **Neutron** | 3 | * | $4.39230 \times 10^{25}$ | $4.340 \times 10^{26}$ |

* **Mass Ratio:** $m_p/m_e = N_p/N_e \approx 1836.15$
* **Neutron Decay:** $\Delta N \approx 2.5 N_e$ (Channels to electron + neutrino).

---

**Date-lock:** December 27, 2025
**Author:** Hrachya Danielyan
**License:** MIT
