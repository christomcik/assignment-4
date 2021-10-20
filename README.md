# Assignment 4 Reproducibility Challenge

# Rayleigh Bernard Convection

Thermal gradient driven natural convection is simulated in a 2D domain.

## Description

Natural convection due to thermal gradients are simulated in a 2D rectangular domain. The Navier-Stokes equations are solved by the pressure projection method on a staggered grid. The hyperbolic flux terms are discretized explicitly (CD, MacCormack and Richtmyer) while the diffusive terms are dealt with both explicitly and implicitly. The energy transport equation is explicitly discretized (CD) for the advective fluxes along with an option for implicit or explicit method for the conduction terms. The Pressure Poisson equation is solved implicitly. The top and bottom surfaces are isothermal while the sides are adiabatic. No-slip is enforced for velocity on all sides and homogenous boundary conditions are employed for pressure. Both velocity and temperature field are used for visualization purposes. For specific (critical) values of Pe,Gr and Re, Rayleigh Benard convective rolls are observed.

## Getting Started

### Dependencies

* MATLAB
* An operating system: Windows, Linux, MacOS, ...

### Installing

* All required files can be downloaded from the assignment-4 repository: https://github.com/christomcik/assignment-4/
* No modifications are needed to install the program

### Executing program

* Open the RayleighBernardConvection.m file with your MATLAB software
* Run the program

## Authors

Suraj Shankar

## Version History

version 1.0.0.0

## License

See the license.txt file for details.

## Acknowledgments

Suraj Shankar (2021). Rayleigh Benard Convection (https://www.mathworks.com/matlabcentral/fileexchange/38093-rayleigh-benard-convection), MATLAB Central File Exchange. Retrieved October 20, 2021. 
