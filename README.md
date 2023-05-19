# OpenFOAM_FlowPastCylinder
The water of Re=3e4 with velocity of 10 at inlet flowing past cylinder with Diameter=10mm
# Description
The water of Re=3e4 with velocity of 10 at inlet flowing past cylinder with Diameter=10mm
1 - the grid is created by ICEM and the source files is uploaded.
2 - The utility of fluentMeshtofoam is used which can be used for the transformation from Fluent to Openfoam grid. And the grid is named as INLET, OUTLET, WALL_UP, WALL_DOWN and WALL_CYLINDER.
3 - The turbulence model is k-Omega SST with pimpleFoam. In order to meet the requirement of CFL, the delta_T is set as 2e-5. And the 10m/s is set as the velocity of inlet.
4 – The contour of physical parameters is shown in below.
5 – To be clarified, the case is just used for DEMO, which means that the lift or drop force coefficient may not be correct. However, the parametric modeling is on the go corresponding to the meshing in ICEM, which can greatly improve the general purpose for solving the problems of flowing past cylinder.
