<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: VaRqDG

Published in: Applied Quantitative Finance

Description: 'Computes the a-quantile for the class of quadratic forms of Gaussian vectors uses Fourier inversion to approximate the cumulative distribution function (CDF).'

Keywords: 'Delta-Gamma-models, Fourier inversion, approximation, cdf, delta-gamma, quantile'

See also: 'VaR, VaR, VaRcdfDG, VaRcgfDG, VaRcharfDG, VaRcharfDGF2, VaRcorrfDGF2, XFGqDGtest, cdf2quant, gFourierInversion'

Author: Awdesch Melzer

Submitted: Tue, June 04 2013 by Awdesch Melzer

Usage: q = VaRqDG(a,par,N,K,dt)

Input: 'a- scalar, representing the probability level

par- a list defining the distribution# contains at least the components: 

Output: q- scalar, the alpha-quantile

Example: 'Please mind all necessary subroutines.

Result: 'Approximates a standard normal quantile and compares it with the built-in function:

```
