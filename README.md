# StaticStressTriggering

Interactive 3D plots for the aftershock sequences with associated Coulomb Failure Stress change are available [here](https://observablehq.com/@cehanagan/aftershock_stress).

This repository contains files for Hanagan et al. (2022). The input and results for each aftershock sequence (Umbria-Marche UM, L'Aquila LA, Ridgecrest RC) are available in the Relax directory. In each earthquake subdirectory, there are three further subdirectories with files described below:
- run/: coseismic input files for the earthquake sequence with aftershock points and fault plane slip distributions. These are for Relax 1.0.7 (Barbot and Fialko, 2010 [a,b]; Barbot, 2014).
- synthetic_points/: three point files with randomized 3D locations and assigned strike-constrained plane parameters following the methodology described in the main text.
- results/: the stress tensor outputs for each point (i.e. aftershock) provided at the model run time for the synthetic and non-synthetic results. The non-synthetic result files also provide the original parameters, timing, and locations for the aftershocks analyzed in this study.

All x1 (N), x2 (E), x3 (D) positions within files for each earthquake sequence are referenced to the largest mainshock epicentral location:
- Umbria-Marche: 43.0305 N, 12.8622 E
- L'Aquila: 42.339 N, 13.381 E
- Ridgecrest: 35.771 N, -117.599 E

Interactive 3D plots for the aftershock sequences with associated Coulomb Failure Stress change are available [here](https://observablehq.com/@cehanagan/aftershock_stress).


