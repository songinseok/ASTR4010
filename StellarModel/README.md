# Fortran codes for simple stellar structure modeling

This directory conintas Fortran source files to simulate stellar interiors from a set of equations, constitutive relations, and boundary conditions. These source files form a pckage, called __StatStar__, in the textbook ("An Introduction to Modern Astrophysics" by Caroll & Ostlie).

_StatStar_ computes ZAMS models of stars using the physics presented in the textbook. Simplifying assumptions made in this code include using Kramers opacity laws, adiabatic convection, and unsophisticated surface boundary conditions. As such StatStar is not a research-grade stellar structure code, but is meant to introduce the student to the basic concepts of stellar model building.  

## Term project for ASTR 4010 students
Transform these fortran files into a Python package which can also create figures showing the structures of some important parameters such as enclosed luminosity (L_r), M_r, T, P, density, etc.
