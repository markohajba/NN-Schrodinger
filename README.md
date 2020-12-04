## NN-Schrödinger

This repository contains some of the experiments and additional materials for Entropy research paper *Deep neural network model for approximating eigenmodes localized by a 
confining potential*

Authors: Luka Grubišić, Marko Hajba, Domagoj Lacmanović
_________________________________________________________________
We study eigenmode localization for a class of elliptic diffusion-reaction operators. As the prototype model problem we use a family of Schrödinger Hamiltonians parametrized
 by random potentials and study the associated effective confining potential. 

You can expect to find code, data and some of the results inside folders. There are more details inside readme.ipynb

*   **Ground_state_VPINN_1D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating the ground state of the Schrödinger equation in 1 dimension using a Deep Ritz method.

*   **Landscape_function_VPINN_2D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating landscape function as a solution of the equation
<a href="https://www.codecogs.com/eqnedit.php?latex=-&space;\Delta&space;\psi&space;&plus;&space;V\psi&space;=&space;\textbf{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-&space;\Delta&space;\psi&space;&plus;&space;V\psi&space;=&space;\textbf{1}" title="- \Delta \psi + V\psi = \textbf{1}" /></a>


### Some of the important packages used:


> Tensorflow 2\
FEniCS\
NumPy\
SciPy\
Matplotlib
