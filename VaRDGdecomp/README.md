<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRDGdecomp

Published in: Applied Quantitative Finance

Description: VaRDGdecomp uses a generalized eigenvalue decomposition to do a suitable coordinate change. The new risk factors are independently standard normal distributed and the new Hessian matrix (Gamma) is diagonal.

Keywords: diagonalization, eigenvalue-decomposition, eigenvalues, risk, standard-normal

See also: DGdecompS, VaR, VaR, VaRDGdecompG

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: r = VaRDGdecomp(l)

Input: 
- l: a list with components Delta, Gamma, Sigma
- Delta: '(m x 1) vector of first derivatives 
- Gamma: '(m x m) Hessian matrix 
- Sigma: '(m x m) covariance matrix

Output: 
- r: a list with the additional components B, delta, lambda
- B: (m x m) transpose(BB) = Sigma
- delta: (m x 1) first derivatives w.r.t. new coordinates
- lambda:  (m x 1) diagonal of the Hessian matrix w.r.t. new coordinates

Example: 

Result: $Delta

```
