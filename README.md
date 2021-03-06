Hartree-Fock program
====================

A simple implementation of the Hartree-Fock algorithm. It uses a STO-6G basis set which is generated from each Slater exponent in the input file. The following calculations can be performed (in a rather rudimentary manner):
 - RHF
 - UHF
 - RMP2
 - geometry optimization (numerical, gradient descent)
 - optimization of Slater exponents (numerical, gradient descent)
 - charge density along z-axis
 - Mulliken charges
 - normalization check   

This program was written in the context of the [Quantum Chemistry II](https://github.com/grimme-lab/qc2-teaching) course taught in the summer term of 2021.  

The program was developed using the [Fortran Package Manager (fpm)](https://github.com/fortran-lang/fpm).  
Run with `fpm run -- molecules/h2.in`.



### License

[![CC-BY-SA](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
This project is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). 
  
This project contains a [minimal, redistributed version of LAPACK](http://www.netlib.org/lapack/), which is available under a BSD 3 clause license.  
Also check the [Quantum Chemistry II course page](https://github.com/grimme-lab/qc2-teaching) for further information.
