# Inverse-Matrix-in-R
library(matlib)


#Find the value of inverse of a matrix, determinant of a matrix by using the following values:
  
  A <- matrix(1:100, nrow=10)
  
  B <- matrix(1:1000, nrow=10)

#The function to find the inverse is solve() 
  
  solve(A)
  
  solve(B)

#The determinant is found with the det() function
  
  det(A)
  
  det(B)
  

library(matlib)
>   A <- matrix(1:100, nrow=10)
>   B <- matrix(1:1000, nrow=10)
>   solve(A)
Error in solve.default(A) : 
  Lapack routine dgesv: system is exactly singular: U[6,6] = 0
>   solve(B)
Error in solve.default(B) : 'a' (10 x 100) must be square
>   det(A)
[1] 0
>   det(B)
Error in determinant.matrix(x, logarithm = TRUE, ...) : 
  'x' must be a square matrix


#First I Installed the package "matlib" inorder to use the function solve() to calculate the inverse of the matrix
#when I run the first inverse matrix A, it showed error saying that A is singular.
#The second inverse matrix showed error that said B is not square 
#The determinant can be found with the function of det()
#The determinant of A returned 0
#The determinant of B gives error that 'x' must be a square matrix
