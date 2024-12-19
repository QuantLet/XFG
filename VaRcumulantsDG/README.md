<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRcumulantsDG

Published in: Applied Quantitative Finance

Description: 'Computes the first n cumulants for the class of quadratic forms of Gaussian vectors. Notes: This function does not need the initial diagonalization. If the diagonalization has been done already, use VaRcumulantDG, which is faster.'

Keywords: 'Delta-Gamma-models, cumulant, gaussian, diagonalization, function'

See also: VaRcumulantDG

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: r = VaRcumulantsDG(n,l)

Input: '-n: scalar, highest order of cumulants to be computed

-l: a list defining the distribution contains at least the following components:

- theta: the constant term

- Delta: the linear term (the first derivative)

- Gamma: the quadratic term (the Hessian matrix)

- Sigma: the covariance matrix'

Output: '- rn : (rn x 1) vector of the first n cumulants'

Example: 'theta = 0

Result: Contents of r

```
