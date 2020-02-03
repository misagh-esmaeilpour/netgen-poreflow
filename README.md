# semester-project2
this is the second ver of project 



***
### Title of Project:  V2
#### *Simulation of fluid flow through porous media using netgen/poreflow porenetwork modeling package*
***

**Background:**

Understanding petrophysical properties and their scale dependency in porous media have been active subjects of research over the past several decades in hydrology, soil physics and geosciences. 
Pore-network models (PNMs) represent the pore structure of soils and rocks by connecting pore bodies via pore throats of various sizes and geometries.

Per H. Valvatne back in 2004 developed a package for generating pore-network (Netgen) and simulating fluid flow (Poreflow) through the generated networks to come up with the petrophysical values of the disired networks such as permeability, porosity,etc. The package is a compiled code written in c++ and could be easily executed by termuinal.

For my masters thesis I am using this package and am running it in Matlab with often over 200 iterations and outputs are saved in the format of _.mat_ files. 


There are two main isues that I am facing while running this code on my machine:

* I am not able to use matlab anymore when the program is running and it could take several days for the program to foinish
* since I do not have Parallel Computing toolbox in Matlab it takes longer

---
**Objectives:**

By rewriting my matlab code in python I am aiming to achieve these two goals:

1. not making my Matlab busy for days
2. By using Numba or Pythran (or such modules) and running multi threads at a time, accelerating the computations.

---
**Sketch**

<img src="sketch.png" alt="sketch_image" width="900"/>




---
**References**

1. Valvatne, P. H. (2004). Predictive pore-scale modelling of multiphase flow (Doctoral dissertation, Department of Earth Science and Engineering, Imperial College London).
2. Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>




---






