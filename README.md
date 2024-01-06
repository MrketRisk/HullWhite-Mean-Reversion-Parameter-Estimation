# HullWhite-Mean-Reversion-Parameter-Estimation.
Introduction to Hull White Model.

The Hull–White (One-Factor) Model: It is an arbitrage free model of Short Rates.

The formula for Short Rate as per HW Model is given as: dr = (Theta(t) - k * r) * dt + Sigma * dz

where k and Sigma are constants.

k is the rate of mean reversion

Sigma is the long run volatility of short rate.

Theta(t) is long term mean rate.

k is determined using log likelihood

For more info, check wikipedia and John C. Hull's book on Derivatives.

The purpose here is to determine the k (mean reversion rate) given a historical 1 month MIBOR rate for 5 years. Assuming 1 month MIBOR as the proxy for short rate.

1 month MIBOR can be downloaded from FBIL website.
