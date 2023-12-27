# LISP Program Problem 
Compute the Nth Fibonacci number using approximately N additions. This means that the 
running time of the program should be proportional to N. Formulate a recursive solution.

# FASTFIB Function
Write a top-level function called FASTFIB that takes in N, a single numeric argument, 
and returns the Nth fibonacci number. This function sets the base cases of the fibonacci
sequence: sets x to 0 and y to 1. 

# fib-helper Auxiliary Function
The helper function takes in three arguments: N, x, and y. If N=0, return x. If
N is greater than 0, then N is decremented, x=y, and y=x+y.

# Execution Time
In lisp you can use commands like (time(FASTFIB 100)) to see how many processor cycles
it takes to compute the fibonacci number. Using FASTFIB, which calls a function that uses
a recursive method to find the fibonacci number, takes less processor cycles than
if only using one function or even one function that uses the recursive method as well. 
