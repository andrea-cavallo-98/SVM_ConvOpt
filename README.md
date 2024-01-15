# SVM_ConvOpt

This repository contains the code for the project on Linear Support Vector Machines for the course Applied Convex Optimization. The project consists in the formulation of linear SVM as an optimization problem and the solution of the problem using off-the-shelf solvers and a self-implemented subgradient descent algorithm. The code is organized as follows.

- `svm_primal` contains the code to solve the primal SVM problem with the off-the-shelf solver from the CVXOPT library
- `svm_dual` contains the code to solve the dual SVM problem with the off-the-shelf solver from the CVXOPT library 
- `svm_gd` contains the implementation of the subgradient descent algorithm for the primal problem