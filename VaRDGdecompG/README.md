<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRDGdecompG

Published in: Applied Quantitative Finance

Description: Computes the first and second derivatives with respect to the new risk factors.

Keywords: diagonalization, eigenvalue-decomposition, eigenvalues, risk, derivative

See also: DGdecompS, VaRDGdecomp

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: r = VaRDGdecompG(l)

Input: 

- l: a list with (at least) the components Delta, Gamma, B

- Delta: (m x 1) 'old' first derivatives

- Gamma: (m x m) 'old' second derivatives

- B: (m x m) square root of the covariance matrix, BB' = Sigma

Output: 

- r: a list containing the additional components delta and lambda

- delta: '(m x 1) new first derivatives'

- lambda: '(m x m) diagonal of the new second derivatives'

Example: 

```
