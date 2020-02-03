
### Project Proposal:
#### *Simulation of fluid flow through porous media using netgen/poreflow porenetwork modeling package*
***
**Name**: Misagh esmaeilpour<br/>
**Semester**: Spring 2020 <br/>
**Project area**: Flow and Transport in Porous Media

---
**Background:**

Per H. Valvatne back in 2004 [1] developed a package for generating pore-networks and simulating fluid flow (multi/single phase) through the generated networks to come up with the petrophysical values of the disired networks such as permeability, porosity,etc. The package is a compiled code written in c++ and could be easily executed by cmd, and is composed of two sub modules called NetGen( pore-network generator) and Poreflow (fluid flow simulator. 

Currently, I am using this package and am running it on Matlab with often over 200 iterations and outputs are saved in the format of _.mat_ files. This way I have two main isues:
* I am not able to use matlab anymore when the program is running and it could take several days for the program to foinish
* since I do not have Parallel Computing toolbox in Matlab it takes longer

---
**Objectives:**


By rewriting my matlab code in python I am aiming to achieve these two goals:

1. not making my Matlab busy for several days
2. accelerating the computations by using Numba or Pythran (or such modules) and running multi threads at a time.

---

**Outcome:**

Three separate plots showing the trend of changing in the values of permeability, porosity and formation factor while network size is increasing.

---
**Sketch**

In the following picture (Fig.1) various stages of this project is depicted:

<p>
    <img src="Presentation1.png" alt="Fig.1" width="900"/>
</p>
<p>
    <em>Fig.1: Workflow of the proposed project</em>
</p>

---
**References**

1. Valvatne, P. H. (2004). Predictive pore-scale modelling of multiphase flow (Doctoral dissertation, Department of Earth Science and Engineering, Imperial College London).
2. Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>




---

