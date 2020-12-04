## NN-Schrödinger

This repository contains some of the experiments and additional materials for Entropy research paper *Deep neural network model for approximating eigenmodes localized by a 
confining potential*

Authors: Luka Grubišić, Marko Hajba, Domagoj Lacmanović
_________________________________________________________________
We study eigenmode localization for a class of elliptic diffusion-reaction operators. As the prototype model problem we use a family of Schrödinger Hamiltonians parametrized
 by random potentials and study the associated effective confining potential. 

You can expect to find code, data and some of the results inside folders.

*   **Ground_state_VPINN_1D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating the ground state of the Schrödinger equation in 1 dimension using a Deep Ritz method.

$$-\Delta \psi + V\psi = \varepsilon \psi.$$
Loss function used
\begin{equation}
    L(u;\beta)=\dfrac{\int_{\Omega}|\nabla u|^2+\int_{\Omega}V_{\omega}u^2}{\int_{\Omega}u}+\beta\left(\int_{\Omega}u^2-1\right).
\end{equation}
We also monitor few other important metrics like relative error in ground-state energy using a Rayleigh Quotient in weak and strong sense and we also monitor equation residual in each epoch.
*   **Landscape_function_VPINN_2D** folder contains jupyter notebook, data and some of the additional results for the problem of calculating landscape function
$$-\Delta \psi + V\psi = \textbf{1}.$$
FEniCS package was used in this 2D experiments. Effective potential is calculated from this landscape function and its minimums give a good approximation of the lowest eigenvalues and a localization of the corresponding eigenmodes.

\
### Some of the important packages used:


> Tensorflow 2\
FEniCS\
NumPy\
SciPy\
Matplotlib

