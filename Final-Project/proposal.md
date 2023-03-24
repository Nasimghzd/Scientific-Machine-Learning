## Learning Multilevel Domain Decomposition Methods Using Graph Neural Networks

**Group Members:** Ali Taghibakhshi, Nasim Gholizadeh

### Problem Statement

Domain decomposition methods (DDMs) [1, 2, 3] are notable in solving the linear and nonlinear systems of equations that arise from the numerical approximation of solutions to partial differential equations (PDEs). Among DDM methods, Schwarz methods are particularly popular given their relative simplicity and ease of parallelization. Optimized Schwarz Methods (OSMs) are developed to improve the convergence of the Schwarz methods by using more general interface conditions between problem subdomains[4]. However, the OSM methods are only developed for very specific structured grids with a certain number of subdomains of certain shapes. 

Recently, Graph Neural Networks have been used to learn the optimal interface values for 1-level Optimal Restricted Additive Schwarz Methods (ORAS) [5]. The aim of this research is to extend the methods in [5] to multilevel ORAS methods. Particularly, we will investigate how we can learn interface values as well as the prolongation operator in the multilevel ORAS methods and will aim to obtain a method that can outperform conventional multilevel RAS solvers.


### References
[1] Andrea Toselli and Olof Widlund. Domain decomposition methods—algorithms and theory, volume 34 of Springer Series in Computational Mathematics Springer-Verlag, Berlin, 2005.

[2] Alfio Quarteroni and Alberto Valli. Domain decomposition methods for partial differential equations. Numerical Mathematics and Scientific Computation. The Clarendon Press, Oxford University Press, New York, 1999. Oxford Science Publications.

[3] Victorita Dolean, Pierre Jolivet, and Frédéric Nataf. An introduction to domain decomposition
methods. Society for Industrial and Applied Mathematics (SIAM), Philadelphia, PA, 2015.

[4] M.J. Gander, L. Halpern, and F. Nataf. Optimized Schwarz methods. In Proceedings of the 12th International Conference on Domain Decomposition, pages 15–27. ddm.org, 2000.

[5] Taghibakhshi, A., Nytko, N., Zaman, T., MacLachlan, S., Olson, L. and West, M., 2022. Learning Interface Conditions in Domain Decomposition Solvers. arXiv preprint arXiv:2205.09833.
