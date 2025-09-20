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

After spontaneous symmetry breaking, $\Phi$ acquires a vacuum expectation value $v$ and the physical Higgs boson $H(x)$ emerges as its quantum excitation. In short, the Higgs boson is to the Higgs field what the photon is to the electromagnetic field, it also comes with a Nobel Prize. 

## Motivation  

During my undergraduate studies under the supervision of Dr. Walid Malaeb, I explored the historical and theoretical background with a bit of computation to detect the Higgs boson, for my Bachelor’s thesis. Curiosity about how colliders produce these particles has stayed with me though sadly, I do not have a 14 TeV proton-proton collider in my backyard.  

Fortunately, **PYTHIA8**, a Monte Carlo event generator, allows me to simulate high-energy collisions and “produce” Higgs bosons on my laptop. This project gives me a hands-on chance to generate events, reconstruct the Higgs via $H \to ZZ \to 2\ell^+ 2\ell^-$, and analyze the resulting data.  

After several hours of talking with some friends on installing Linux operating systems they still haven't been convinced, so I decided to create a **Dockerfile** that creates a virtual environment that contains the exact Distro, libraries, packages that will be needed for this project. So all you could do is pull the image, hop on in, clone the repo, sit back and relax. Jokes! 

You still have a few commands to run which I will be documenting throughout this repository. You should have basic knowledge in bash commands right? RIGHT? Ughh fine I will introduce two paths and hold your hand through it:

## Docker Method

What is docker? Well actually we will be using Podman the open-source alternative! Feel free to check out the amazing workshop provided by the HSF community [Introduction to Docker and Podman](https://hsf-training.github.io/hsf-training-docker/)! 



## Manual (for the masochists out there)





