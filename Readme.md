#Poisson Equation Solver

* Jacobi solver 
* Gauss-Seidel with successive over relaxation



written in C with structures.

* Structures are used to store the field variables and for easy specification of boundary conditions.


Usage:

* To compile use: g++ poisson.c
* Type plot within an octave terminal to see the surface plot of the output.



Planning to extend this to run parallely on distributed memory system using MPI.

Finally scalability of the parallelization is to be tested.

