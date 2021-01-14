## NN-Schrödinger

This repository contains some of the experiments and additional materials for a research paper 
*Deep neural network model for approximating eigenmodes localized by a confining potential* which is accepted to the open-access journal Entropy.
Authors: Luka Grubišić, Marko Hajba, Domagoj Lacmanović

The research paper is accepted as a part of the special issue "Human-Centric AI: The Symbiosis of Human and Artificial Intelligence" and it is freely available at:
https://www.mdpi.com/journal/entropy/special_issues/Human-Centric_AI

Direct link to the paper: https://www.mdpi.com/1099-4300/23/1/95 

If you find this codes or paper usefull in your research, please cite (the are other styles available on the links above):

MDPI and ACS Style

Grubišić, L.; Hajba, M.; Lacmanović, D. Deep Neural Network Model for Approximating Eigenmodes Localized by a Confining Potential. Entropy 2021, 23, 95.

AMA Style

Grubišić L, Hajba M, Lacmanović D. Deep Neural Network Model for Approximating Eigenmodes Localized by a Confining Potential. Entropy. 2021; 23(1):95.
____________________________________________________________________________________________________
We study eigenmode localization for a class of elliptic reaction-diffusion operators. As the prototype model problem we use a family of Schrödinger Hamiltonians parametrized
 by random potentials and study the associated effective confining potential. 

You can expect to find code, data and some of the results inside folders. There are more details inside corresponding .ipynb files.

*   **Ground_state_VPINN_1D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating the ground state of the Schrödinger equation in 1 dimension using a Certified Deep Ritz method.

*   **Landscape_function_VPINN_2D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating landscape function as a solution of the equation
<a href="https://www.codecogs.com/eqnedit.php?latex=-&space;\Delta&space;\psi&space;&plus;&space;V\psi&space;=&space;\textbf{1}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?-&space;\Delta&space;\psi&space;&plus;&space;V\psi&space;=&space;\textbf{1}" title="- \Delta \psi + V\psi = \textbf{1}" /></a>


### Some of the important packages used:


> Tensorflow 2\
Keras\
FEniCS\
NumPy\
SciPy\
Matplotlib
