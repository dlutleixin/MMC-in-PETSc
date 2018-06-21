# MMC_in_PETSc
## A new 3D large-scale topology optimization numerical framework baced on Moving Morphble Component methed using PETSc

![Presentation in our lab](https://github.com/dlutleixin/MMC_in_PETSc/blob/master/presentation.png)
### Presentation in DUT,China

![Torsion Example](https://github.com/dlutleixin/MMC_in_PETSc/blob/master/torsion_exaple.png)
### Visulization using Paraview ( We are developing visulization using UG based on one of the most important advantages of MMC:Explicit Boundary Description )


Besides the main program file, the code contains the following building  blocks for topology optimization:

  1. TopOpt class containing mesh and optimization parameters.
  2. Physics class containing a 3D linear elasticity solver and objective, constraint and sensitivity computations.
  3. MMA class with a simple, serial implementation the method of moving asymptotes based on Eigen3.
  4. IO class and Python script converters. 
