# N2O-PESs
Potential energy surfaces for the triplet states of N2O

**Requirements**

(1) RKHS toolkit : Download from https://github.com/MeuwlyGroup/RKHS

**Compile a particular PES**

A test program file (pes_test.f90) is given and it can be compiled for the 3A' PES as

`gfortran RKHS.f90 N2O-3AP-PES.f90 pes_test.f90`

**Running the executable**

Before running the executable make sure that the asymp.dat, .csv and/or .kernel files for that PES present in the current directory (or change the file path in the fortran program).

**Cite as**
Debasish Koner, Juan Carlos San Vicente Veliz, Raymond J. Bemish and Markus Meuwly,  	arXiv:2002.02310 [physics.chem-ph]
