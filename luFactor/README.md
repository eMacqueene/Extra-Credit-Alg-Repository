# LU Factorization

This algorithm uses the Naive Gauss elimination with partial pivoting to get a matrix into an upper triangular matrix and a lower triangular matrix. It also outputs the pivoting matrix. The matrix must be a square matrix, and the program will output an error if the matrix is not. Note that [P][A] = [U][L].

The inputs are:
1. A = square coefficient matrix that the user wants to use LU factorization on

The ouputs are:
1. L = the lower triangular matrix of A
2. U = the upper triangular matrix of A
3. P = the pivoting matrix demonstrating the row switches
