
[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **VaRcorrfDGF2** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml

Name of QuantLet : VaRcorrfDGF2

Published in : Applied Quantitative Finance

Description : 'Computes the cumulative distribution function (CDF) of an approximated normal
distribution for the class of quadratic forms of Gaussian vectors.'

Keywords : Delta-Gamma-models, normal approximation, approximation, gaussian, cdf, normal

See also : VaRcdfDG, VaRcharfDGF2, VaRqDG, XFGqDGtest

Author : Awdesch Melzer

Submitted : Tue, June 04 2013 by Awdesch Melzer

Usage : r = VaRcorrfDGF2(x,l)

Input: 
- x: the argument to the CDF
- l: a list defining the distribution, contains at least theta, delta, lambda
- theta: the constant
- delta: the linear term
- lambda: the diagonal of the quadratic term

Output: 
- r: the value of the approximated normal CDF at x

```


### R Code:
```r
VaRcorrfDGF2 = function(x, l) {
    # cdf of normal approximation
    mu = l$theta + 0.5 * sum(l$lambda)
    s2 = sum(l$delta^2 + 0.5 * l$lambda^2)
    r = pnorm((x - mu)/sqrt(s2))
    return(r)
}

#################### TEST ######################

theta = 0
delta = c(1)
lambda = c(1)
par = list(theta = theta, delta = delta, lambda = lambda)
VaRcorrfDGF2(c(-1, 0, 1), par)

 

```
