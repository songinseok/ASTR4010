# Fortran codes for simple stellar structure modeling

This directory conintas Fortran codes, called StatStar, from the textbook.
StatStar computes ZAMS models of stars using the physics presented in the text.  
Simplifying assumptions made in this code include using Kramers opacity laws, 
adiabatic convection, and unsophisticated surface boundary conditions.  
As such StatStar is not a research-grade stellar structure code, 
but is meant to introduce the student to the basic concepts of stellar model building.  
StatStar is composed of a number of Fortran 95 modules, 
each containing one or more subroutines or functions.  
StatStar also requires Constants.F90 in order to be compiled.
