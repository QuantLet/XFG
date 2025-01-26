<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRcharfDGF2

Published in: Applied Quantitative Finance

Description: Computes the Fourier transform of an approximating Gaussian cumulative distribution function (CDF) for the class of quadratic forms of Gaussian vectors. Notes: This is an auxiliary function to VaRcdfDG.

Keywords: Delta-Gamma-models, Fourier transform, cdf, gaussian, function

See also: VaRcdfDG, VaRcharfDG, VaRcorrfDGF2, VaRqDG, XFGVaRcharfDGtest, XFGqDGtest

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: r = VaRcharfDGF2(t,l)

Input: 
- t: the complex argument of the transformed function
- l: a list defining the distribution contains at least the components theta, delta, labda
- theta: the constant term
- delta: the linear term
- lambda: the diagonal of the quadratic term

Output: 
-r: the (complex) value of the Fourier inversion at t

```
