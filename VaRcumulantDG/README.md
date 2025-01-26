<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRcumulantDG

Published in: Applied Quantitative Finance

Description: Computes the n-th cumulant for the class of quadratic forms of Gaussian vectors. Notes: This function requires the eigenvalue decomposition that diagonalizes the quadratic term. VaRcumulantsDG computes the first n cumulants without need for the initial diagonalization.

Keywords: Delta-Gamma-models, cumulant, gaussian, eigenvalues, decomposition

See also: VaRcumulantsDG

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: c = VaRcumulantDG(n,l)

Input: 
- n: scalar, order of the required cumulant# n=1 is the mean
- l: a list defining the distribution contains at least the components theta, delta, lamda
- theta: the constant term
- delta: the linear term
- lambda: the diagonal of the quadratic term

Output: 
- c: scalar, the n-th cumulant

Example: theta = 0

Result: Contents of c

```
