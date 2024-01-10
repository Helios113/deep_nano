---
title: " Quantum mechanical simulations of electronic devices "
date: 2024-01-10
authors: ["Vihar Georgiev"]
---

We are developing quantum mechanical simulator to model current flow in CMOS devices


<!--more-->

Our Quantum Transport Simulations  are based on self-consistent solution of Poisson's equation and non-equilibrium Green’s function (NEGF) approach. NEGF formalism is a generalization of the Landauer’s formalism to treat many body systems at room temperature in context of one particle. The electrostatic potential and the electron density, which serve as an initial condition for the Poisson-NEGF cycle, are obtained from a density gradient of Drift-Diffusion equations. The Hamiltonian used in the discretization of the NEGF equations is an effective-mass Hamiltonian that folds the full crystal interaction into the electron effective masses. 

We can perform calculations in ballistic and scattering regime where in the latter case sources of incoherent scattering such as phonon interaction, are currently included in NEGF module. The Poisson-NEGF cycle is iterated until density and current converges. We developed two methods based on either fully-3D or coupled mode space approach self-consistent methodology to solve electron transport equations. The NEGF module is included in the 'atomistic' simulator NESS.
