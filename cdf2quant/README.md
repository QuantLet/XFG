<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: cdf2quant

Published in: Applied Quantitative Finance

Description: Approximates the quantile from a cumulative distribution function (CDF) that is given on a grid.

Keywords: quantile, density, approximation, cdf, distribution

See also: VaRqDG, XFGqDGtest

Author: Awdesch Melzer

Submitted: Tue, June 04 2013 by Awdesch Melzer

Usage: q = cdf2quant(a,l)

Input: 
- a:  scalar, representing the probability level
- l: a list containing x and y (see below)
- x: the grid in x
- y: the values of the CDF on the grid x

Output: 
- q: scalar, the approximated quantile

Example: Please mind the necessary subroutines. theta = 0 delta = c(1) lambda = c(0) par = list(theta=theta,delta=delta,lambda=lambda) r = VaRcdfDG(par,512,512,0.1) cdf2quant(0.95,r) qnorm(0.95)

Result: Contents of q [1] 1.647865 Contents of qnorm [1] 1.644854'

```
