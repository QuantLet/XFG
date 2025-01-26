<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRcdfDG

Published in: Applied Quantitative Finance

Description: Approximates the cumulative distribution function (CDF) for the class of quadratic forms of Gaussian vectors.

Keywords: FFT, cdf, Fourier transform, approximation, frequency

See also: VaRcgfDG, VaRcharfDG, VaRcharfDGF2, VaRcorrfDGF2, VaRqDG, XFGqDGtest, gFourierInversion

Author: Awdesch Melzer

Submitted: Tue, June 04 2013 by Awdesch Melzer

Usage: r = VaRcdfDG(l,N,K,dt)

Input: 
- l: a list containing (at least) the components theta, delta, lambda
- theta: the constant
- delta: the linear term
- lambda: the diagonal of the quadratic terms
- N: scalar, modulus of the FFT, should have a power of 2
- K: 'scalar, number of characteristic function evaluations; K<=N
- dt: scalar, grid-length in t to use for the approximation

Output: 
- r: a list containing the two components x and y
- x: the grid (vector) in x
- y: the values of the CDF on the grid x

Example: Please mind the necessary subroutines.

Result: Plots the CDF of a distribution, which is close to the chi^2 distribution with one degree of freedom.

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/VaRcdfDG/Plots%20the%20CDF%20of%20a%20distribution.png" alt="Image" />
</div>

