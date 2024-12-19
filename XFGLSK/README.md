<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: XFGLSK

Published in: Applied Quantitative Finance

Description: 'Performes a Least Squares Kernel Smoothing technique for implied volatility smile estimation. To achieve good forecast of asset price volatility the Gaussian shaped vega function is used as weight. A quartic kernel is employed. Given global convexity, the Golden section search is implemented with estimation tolerance 10e-5. The data consists of January and February 2001 tick statistics of the DAX futures contracts and DAX index options. Since the data are transaction data containing potential misprints, a filter in deleting all observations whose implied volatility is bigger than 0.7 and less than 0.1 is applied. Plots of observed option price data are presented. From the lower left to upper right put prices are displayed, from upper left to lower right (normalized) call prices. Moreover, graphs of least squares kernel smoothed implied volatility smile for 17 days to expiry (January 02, 2001) with bandwidth = 0.025 and 95 percent confidence bands and 14 days to expiry (February 02, 2001) with bandwidth = 0.015 and 95 percent confidence bands are shown. Regression smoothing is made employing a Nadaraya Watson kernel regression estimate for quartic kernel'

Keywords: 'Golden section, LSKE, Nadaraya Watson, bandwidth, black-scholes, confidence-interval, forecast, gaussian, implied-volatility, kde, kernel smoothing, least-squares, nonparametric, nonparametric estimation, option, variance, vega, volatility smile'

See also: 'XFGIBT01, XFGIBT02, XFGIBT03, XFGiv00, XFGiv01, XFGiv02, XFGiv03, XFGiv04, XFGiv05, XFGiv06'

Author: Awdesch Melzer

Submitted: Fri, June 06 2014 by Awdesch Melzer

Usage: 'Please choose data source and bandwidth: January or February'

Datafiles: FebruaryData.dat, JanuaryData.dat

Example: 'DAX option prices from 20010102, 17 days to expiry.Plot of observed option price data are presented. From the lower left to upper right put prices are displayed, from upper left to lower right (normalized) call prices.'

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/XFGLSK/DAX%20option%20prices%20from%2020010102%2C%2014%20days%20to%20expiry.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/XFGLSK/DAX%20option%20prices%20from%2020010102%2C%2017%20days%20to%20expiry.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/XFGLSK/Implied%20Volatility%20Smile%2C%2020010102%2C%2014%20days%20to%20expiry.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/XFG/master/XFGLSK/Implied%20Volatility%20Smile%2C%2020010102%2C%2017%20days%20to%20expiry.png" alt="Image" />
</div>

