
.. image:: https://img.shields.io/badge/python-3.4%2C%203.5%2C%203.6-brightgreen.svg

# Optimizing Tensor Contraction
Evaluating tensor product and finding the optimized solution for its contraction. This will
reduce the memory usage and speed up the calculation. 

## Symmetric Tensor
Applications - Machine learning and Neural Networks

## Anti-symmetric Tensor
Application - Quantum Chemistry 


### Steps to be followed
1. Find permutation symmetries in the expression
2. Compute all intermediates small tensor product and their cost
3. Find the least cost combination.
4. Reduce it further if same intermediate is used more than once. 
5. Test it with dummy case
5. Print the C++, FORTRAN and Python script for the final expression. 
6. Develop GUI for the software using tkinter

### Useful libraries 
1. SymPy (https://docs.sympy.org/latest/install.html)


### References 
1. Performance Optimization of Tensor Contraction Expressions for Many-Body Methods in Quantum Chemistry (https://pubs.acs.org/doi/abs/10.1021/jp9051215)
2. Optimizing tensor contraction expressions for hybrid CPU-GPU execution (https://link.springer.com/article/10.1007/s10586-011-0179-2)
3. Faster identification of optimal contraction sequences for tensor networks (https://arxiv.org/pdf/1304.6112.pdf)

