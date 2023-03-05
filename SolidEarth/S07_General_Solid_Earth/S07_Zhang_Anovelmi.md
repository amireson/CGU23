---
layout: home
title: "A novel mixed-flux-based nodal discontinuous Galerkin method for 3D dynamic rupture modeling and applications to complex tectonic earthquakes"
---


**Abstract ID**: S07_Zhang_Anovelmi

Session ID: [S07](.)

Corresponding author: Wenqiang Zhang <a href="mailto:wenqiang.zhang@mcgill.ca">wenqiang.zhang@mcgill.ca</a>

Coauthors: Co-authors: Yajing Liu, Department of Earth and Planetary Sciences, McGill University, Montreal, Canada, H3A 0E8, yajing.liu@mcgill.ca; Xiaofei Chen, Department of Earth and Space Sciences, Southern University of Science and Technology, Shenzhen, Guangdong, China, 518055, chenxf@sustech.edu.cn 

Numerical simulation of rupture dynamics provides critical insights for understanding earthquake physics, while the complex geometry of natural faults makes numerical method development challenging. The discontinuous Galerkin (DG) method is suitable for handling complex fault geometries. In the DG method, the fault boundary conditions can be conveniently imposed through the upwind flux by solving a Riemann problem based on a velocity-strain elastodynamic equation. However, the universal adoption of upwind flux can cause spatial oscillations in cases where elements on adjacent sides of the fault surface are not nearly symmetric. Here we propose a nodal DG method with an upwind/central mixed-flux scheme to solve the spatial oscillation problem, and thus reduce the numerical dependence on mesh quality. We verify our new method by comparing results with published solutions to benchmark problems with complex fault geometries, heterogeneous materials, off-fault plasticity, roughness, thermal pressurization, and various versions of fault friction laws. Our method can also achieve high scalability in parallel computing under different orders of accuracy, suitable for adaptation to simulations on 100s-km scale natural tectonic faults. Finally, we demonstrate that our method can be applied to simulate the dynamic rupture processes of recent complex tectonic earthquakes, including the 2008 Mw 7.9 Wenchuan earthquake, the 2019 Mw 7.1/6.4 Ridgecrest earthquakes and the recent 2023 Mw7.8/7.6 Turkey–Syria earthquakes, where coseismic ruptures propagate across multiple fault branches, step-overs and involve heterogeneous rock properties.

Preferred format: Oral presentation
