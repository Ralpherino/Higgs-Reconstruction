## Abstract

This project simulates proton-proton collisions at $\sqrt{s} = 14~\mathrm{TeV}$ using **PYTHIA8**, reconstructs Higgs candidates via $H \to ZZ \to 2\ell^+ 2\ell^-$, and analyzes the resulting data with **ROOT** and Python libraries (`NumPy`, `Matplotlib`, `SciPy`).

We expect the invariant mass distribution of reconstructed four-lepton candidates to peak around $125~\mathrm{GeV}$. Challenges include mastering PYTHIA event generation and handling combinatorics in four-lepton reconstruction.

---

## Introduction & Background

What gives particles mass? Before 1964, physicists had three fundamental field theories:

- **Electromagnetism:** Describes the behavior of electric and magnetic fields and their interaction with charged particles.  
- **Weak Nuclear Force:** Mediated by massive $W^\pm$ and $Z^0$ bosons, responsible for processes like beta decay.  
- **Strong Nuclear Force (QCD):** Binds quarks together via gluons to form atomic nuclei.  

The electroweak theory unifies the weak and electromagnetic interactions via a gauge theory based on gauge symmetry. Gauge invariance forbids explicit mass terms for $W$ and $Z$ bosons. Enter the Higgs mechanism: a scalar field $\Phi$ permeates space, giving mass to particles via spontaneous symmetry breaking. The Higgs field Lagrangian is:

$$
\mathcal{L}_{\text{Higgs}} = (D_\mu \Phi)^\dagger (D^\mu \Phi) - V(\Phi), 
\quad V(\Phi) = \mu^2 \Phi^\dagger \Phi + \lambda (\Phi^\dagger \Phi)^2
$$

After spontaneous symmetry breaking, $\Phi$ acquires a vacuum expectation value $v$ and the physical Higgs boson $H(x)$ emerges as its quantum excitation. In short, the Higgs boson is to the Higgs field what the photon is to the electromagnetic field — it also comes with a Nobel Prize. 🏆


