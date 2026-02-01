---
title: " Quantum mechanical simulations of electronic devices "
date: 2024-01-10
authors: ["Vihar Georgiev"]
---

We are developing a quantum mechanical simulator to model current flow in CMOS devices.


<!--more-->

Our Quantum Transport Simulations  are based on self-consistent solution of the Poisson's equation and non-equilibrium Green’s function (NEGF) approach. NEGF formalism is a generalisation of the Landauer’s formalism to treat many body systems at room temperature in context of one particle. The electrostatic potential and the electron density, which serve as an initial condition for the Poisson-NEGF cycle, are obtained from a density gradient of the Drift-Diffusion equations. The Hamiltonian used in the discretisation of the NEGF equations is an effective-mass Hamiltonian that folds the full crystal interaction into the electron effective masses. 

We can perform calculations in ballistic and scattering regime where in the latter case sources of incoherent scattering, such as phonon interaction, are currently included in the simulations. The Poisson-NEGF cycle is iterated until density and current converges. We developed two methods based on either fully-3D or coupled mode space approach self-consistent methodology to solve electron transport equations. 

Selected publications:
- Gao, Y. P., Kumar, N., Williams, R., Shvarts, A., Kaczmarczyk, L. and Georgiev, V. (2025) [Mixed finite element method for device simulations](https://doi.org/10.1016/j.sse.2026.109346). Solid-State Electronics, In press, 2026. 


- Acharya, P., Kumar, N., Dixit, A. and Georgiev, V. (2025) [Sensitivity of resonant tunneling diodes to barrier variation and quantum well variation: a NEGF study](https://eprints.gla.ac.uk/360486/). Micro and Nanostructures, 207, 208264. [doi: 10.1016/j.micrna.2025.208264](https://www.sciencedirect.com/science/article/pii/S2773012325001931?via%3Dihub)

- Acharya, P., and Georgiev, V. (2025) [Interface roughness in Resonant Tunnelling Diodes for physically unclonable functions](https://eprints.gla.ac.uk/354950/). Solid-State Electronics, 228, 109131. [doi: 10.1016/j.sse.2025.109131](https://www.sciencedirect.com/science/article/pii/S0038110125000760?via%3Dihub)

- Acharya, P. , Rezaei, A. , Sengupta, A. , Dutta, T. , Kumar, N. , Maciazek, P., Asenov, A.  and Georgiev, V.  (2024) [Analysis of random discrete dopants embedded nanowire resonant tunnelling diodes for generation of physically unclonable functions](https://eprints.gla.ac.uk/342047/). IEEE Transactions on Nanotechnology, vol. 23, pp. 815-821.[doi:10.1109/TNANO.2024.3504963](doi:10.1109/TNANO.2024.3504963)

- Medina Bailon, C., Nedjalkov, M., Georgiev, V. , Selberherr, S. and Asenov, A.  (2023) [Comprehensive mobility study of silicon nanowire transistors using multi-subband models](https://eprints.gla.ac.uk/300245/). Nano Express, 4, 025005. [doi: 10.1088/2632-959X/acdb8a](https://eprints.gla.ac.uk/300245/)

- Berrada, S., Carrillo-Nunez, H., Lee, J., Medina Bailon, C., Dutta, T. , Badami, O., Adamu-Lema, F., Thirunavukkarasu, V., Georgiev, V. and Asenov, A. (2020) [Nano-electronic Simulation Software (NESS): a flexible nano-device simulation platform](https://eprints.gla.ac.uk/215701/). Journal of Computational Electronics, 19, pp. 1031-1046. [doi: 10.1007/s10825-020-01519-0](https://eprints.gla.ac.uk/215701/)

- Carrillo-Nuñez, H., Medina-Bailón, C., Georgiev, V. P.  and Asenov, A.  (2020) [Full-band quantum transport simulation in presence of hole-phonon interactions using a mode-space k·p approach](https://eprints.gla.ac.uk/226668/) Nanotechnology, 32(2), 020001. [doi: 10.1088/1361-6528/abacf3](https://eprints.gla.ac.uk/226668/) (PMID:32759487)


