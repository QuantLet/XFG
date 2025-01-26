<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: gFourierInversion

Published in: Applied Quantitative Finance

Description: Is a generic function that approximates the density of a distribution function by numerically inverting its characteristic function.

Keywords: FFT, Fourier inversion, characteristic function, approximation, density

See also: StandardNormalCharf, VaRcdfDG, VaRqDG, XFGqDGtest

Author: Awdesch Melzer

Submitted: Tue, June 04 2013 by Awdesch Melzer

Usage: 
- 'r = gFourierInversion(N,K,dt,t0,x0,charf,l)

Input: 
- N: 'scalar, the modulus of the Fast Fourier Transform (FFT) used; should be a power of 2.
- K: 'scalar, the number of evaluations of the characteristic function; K has to be smaller or equal to N; when K < N, the input vector is filled with zeros up to N.
- dt: 'scalar, the grid-size in t used for the approximation of the inversion integral
- t0: 'scalar, indicating whether the t-grid includes t = 0 (t0==0) or t = dt/2 (otherwise)
- x0: 'scalar, the starting point of the x-grid
- charf: 'string, the name of the characteristic function
- l: 'list, containing l$mu (the expectation) and l$sigma (the standard deviation) of the characteristic function (charf).

Output: 
- rn: '(rn x 1) - vector containing the density values on the x-grid. The grid is given by x_j = x_0 + j dx, dx = 2 pi/(N dt)

Example: Approximates the standard normal density and plots it.

z = cbind((-pi/0.1+(0: 511)*2*pi/(512*0.1)) , r)

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/gFourierInversion/plot.png" alt="Image" />
</div>

