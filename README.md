# FEA_SoC
This repo contains the code file for FEA evalation of a bar subjected to axial traction and point load P.
The user is required to input the problem data like length of the bar, Area of cross section, Young's Modulus etc along with number of elements in which the bar has to be discretised.
The stiffness matrices form is acquired in hand using the weak form through the variational method.
Then the program creates the element level stiffness matrices and ultimately generating the global matrix.
Matrix computations have been done using numpy.
