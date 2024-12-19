<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRcharfDG

Published in: Applied Quantitative Finance

Description: 'Computes the characteristic function for the class of quadratic forms of Gaussian vectors.'

Keywords: Delta-Gamma-models, characteristic function, gaussian, characteristic, function

See also: VaRcdfDG, VaRcgfDG, VaRcharfDGF2, VaRqDG, XFGVaRcgfDGtest, XFGVaRcharfDGtest, XFGqDGtest

Author: Awdesch Melzer

Submitted: Sun, June 02 2013 by Awdesch Melzer

Usage: 'r = VaRcharfDG(t,par)'

Input: 

-t: the complex argument to the cgf

-par: a list defining the distribution# contains the components theta, delta, lambda

-theta: the constant term

-delta: the linear term

-lambda: the diagonal of the quadratic term

Output: 

- r: the value of the cgf at t

Example: 'Plots the real (blue line) and the imaginary part (red line) of the characteristic function for a distribution, which is close to a chi^2 distribution with one degree of freedom.'

```
