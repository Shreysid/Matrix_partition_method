# Matrix_partition_method
Matrix partition method to solve a system of linear equations numerically

This matrix currently works for only 3x3 matrix
Further changes neeeded
The initial systme of equation when given to matrix A is broken down to four seperate matrices B, C, D and E but not used in further calculations. The formulas are to be implemented to get the inverse of a matrix A and calculate the roots for the system of linear equations.

to find matrix P = inv(B)-[inv(B)xCxR]
matrix Q = -[inv(B)xCxS]
matrix R = -[SxDxinv(B)]
matrix S = inv{[E-[Dxinv(B)xC]]}

need to implement P, Q, R and S

