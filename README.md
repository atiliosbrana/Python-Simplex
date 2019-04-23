# Python-Simplex
Implementations of the Simplex Method for the Diet Problem as part of the Linear Optimization class of the MS Computer Science program of UFSCAR - Sorocaba.

1) First I implement it using Scipy's linprog optimization. It is important to use the negative of the matrix in this case, since all the constraints are of the "greater than or equal to" type.

2) In the second implementation, I use the library PulP. To download it, use !pip install pulp in your compiler.

![alt text](https://github.com/atiliosbrana/Python-Simplex/blob/master/problem.png)
