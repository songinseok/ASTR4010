# Fortran codes for simple stellar structure modeling

This directory conintas Fortran source files to simulate stellar interiors from a set of equations, constitutive relations, and boundary conditions. These source files are the content of the package, called __StatStar__, from the textbook ("An Introduction to Modern Astrophysics" by Caroll & Ostlie).

_StatStar_ computes ZAMS models of stars using the physics presented in the textbook. Simplifying assumptions made in this code include using Kramers opacity laws, adiabatic convection, and unsophisticated surface boundary conditions. As such _StatStar_ is not a research-grade stellar structure code, but is meant to introduce the student to the basic concepts of stellar model building.  

## Term project for ASTR 4010 students
Transform these fortran files into a Python package which can calculate the internal structure of a star with given parameters (e.g., mass, radius, luminosity, composition). The Python code/package will also create figures showing the structures of some important parameters such as $L_r, M_r, T, P, \rho$, etc.
