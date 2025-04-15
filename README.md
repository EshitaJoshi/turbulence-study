# turbulence-study
Example code for running LAMMPS simulations associated with the paper [Particle-resolved study of the onset of turbulence](https://doi.org/10.1103/PhysRevResearch.6.L012013).

The input file ```initialising_3dfluid.in``` is used to generate ```3d_obstacle.restart```, which can be used to restart simulations.
This restart file is then used in ```obstacle.in``` to simulate the flow of complex plasma past an obstacle.

The input file ```obstacle.in``` is an example template that needs to be configured to run simulations.
Parameters such as the charge of the obstacle, the electric field, and gas pressure need to be given to the input file before it will run.
