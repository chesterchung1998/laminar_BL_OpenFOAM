# laminar_BL_OpenFOAM
This is a laminar boundary layer using OpenFOAM's icoFoam solver.

The boundary conditions in the U file are ...

We have zeroGradient on the top and bottom of the entrance region.
We have constant velocity on left side of entrance region.
We have zeroGradient on top of the flat plate region and the right hand side.
We have noSlip condition on the bottom of flat plate region. 

For the future we want to include turbulence modelling... Let's see how we can do it (maybe we can do it in another repository).
