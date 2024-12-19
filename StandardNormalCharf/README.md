<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: StandardNormalCharf

Published in: Applied Quantitative Finance

Description: 'Computes the characteristic function of a one-dimensional normally distributed random variable.'

Keywords: characteristic function, normal, normal-distribution, characteristic, standard-normal

See also: XFGqDGtest, gFourierInversion

Author: Awdesch Melzer

Submitted: Tue, June 04 2013 by Awdesch Melzer

Input: 

- t: 'scalar, complex number indicating the point at which the characteristic function should be calculated. l: list, containing l$mu (the expectation) and l$sigma (the standard deviation) of the Standard Normal Distribution.'

Output: 

- r: scalar, complex number representing the value of the characteristic function at t'

Example: 'Please mind the necessary subroutines. mu = 0 sigma = 1 l = list(mu=mu,sigma=sigma) t = compl(1,1) r= StandardNormalCharf(t,l).

Result: Contents of r$re [1,] 0.5403. Contents of r$im [1,] -0.84147.'

```
