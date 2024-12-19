<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of Quantlet: VaRestMC

Published in: Applied Quantitative Finance

Description: 'Partial Monte-Carlo method to calculate the Value at Risk (VaR) based on Delta-Gamma Approximation.'

Keywords: Importance Sampling, VaR, delta-gamma, monte-carlo, simulation

See also: VaR, VaR, XFGVaRestMC

Author: Awdesch Melzer

Submitted: Wed, June 05 2013 by Awdesch Melzer

Usage: 'VaRMC = VaRestMC(VaRdelta,VaRgamma,VaRcovmatrix, smethod, alpha, days, nsimu)'

Input: 

-VaRdelta: m x 1- vector of first derivatives, aggregated delta matrix

-VaRgamma: m x m- Hessian matrix, aggregated gamma matrix

-smethod: Monte-Carlo sampling method for VaR.

-Options for smethod: 'Default set at "IS".

"PS": Plain vanilla sampling method

"MS": Moment matching sampling method

"SS": Stratified Latin Hypercube sampling method

"IS": Importance sampling method'

-alpha: 'Significance level for VaR estimation. (Default = 0.01)'

-days: 'Estimation time horizon. (Default = 1 day)'

-nsimu: 'Number of Monte-Carlo simulations. (Default = 1000)'

Output: 

- VaRMC: Estimated VaR

```
