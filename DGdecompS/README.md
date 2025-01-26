<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: DGdecompS

Published in: Applied Quantitative Finance

Description: Computes the square root of a positive semi-definite matrix, using an eigenvalue decomposition. Notes: Square roots of matrices can also be computed by the Cholesky decomposition, which only works for positive definite matrices, but which is faster.

Keywords: Cholesky decomposition, eigenvalue-decomposition, square root matrix, decomposition, eigenvalues, eigenvectors

See also: VaRDGdecomp, VaRDGdecompG

Author: Awdesch Melzer

Submitted: 

Usage: B = DGdecompS(Sigma)

Input: 
- Sigma: 'positive semi-definite matrix (p x p) containing user-defined data

Output: 
- B: 'matrix (p x p) containing the square root of Sigma.

Note that the solution is non-unique. B solves the equation: 

Example: 

```
