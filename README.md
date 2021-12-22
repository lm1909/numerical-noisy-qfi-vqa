# Numerical Analysis of Variational Quantum Optimisation Using the Natural Gradient/QFI Technique

<p align="center">Dissertation for MSc Mathematical and Theoretical Physics at Oxford University</p>

----

This repo contains the code for my masters' dissertation. The Mathematica notebook `notebook.nb` grew during the project and was not originally intended to be published; the quality is therefore not en par with coding standards in the Wolfram language.
However it might still be useful, so I wanted to make the code available.
The quantum simulation software used was [QuESTlink](https://github.com/QTechTheory/QuESTlink)/[QuEST](https://quest.qtechtheory.org/).

----

#### Abstract

Noisy intermediate-scale quantum (NISQ) computing provides the exciting opportunity of near-term quantum advantage on non-artificial computational problems.
Particularly important for the NISQ era are variational quantum algorithms (VQAs), which, for example, allow to approximate the ground state of a quantum Hamiltonian. As noise is a significant cause of concern, realistic noise models are crucial for evaluating such algorithms. A recent and important development in this field is the introduction of Riemannian algorithms with natural gradient [32] and quantum Fisher information (QFI) optimisation [17], which unify and improve upon the performance of previous techniques. I briefly review general aspects of modelling noise in quantum circuits and summarise the relevant theory of VQAs from basic concepts to the recent development of the QFI algorithm. I then present the results of numerical simulations analysing different aspects of the behaviour of this algorithm under noise. In particular, I discuss the influence of hyperparameter choice in situations with noise, a possible performance difference of depolarising and damping noise, the effectiveness of a commonly used initialisation procedure with the optimal computational basis state, the influ-
ence of an improved approximation of the continuous time gate/noise dynamics and aspects of a regularisation subprocedure in the algorithm.
(_citations refer to the references in `dissertation.pdf`_)
