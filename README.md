# BOSS-V
Bayesian Optimization of Big Data Applications via SFFS

Experiments obtained by the application of BOSS-V algorithm to TPC-DS benchmark (Query 26) and Sparkbench (K-means).

We ran each experiment with all 4 variants of the BOSS-V algorithm for each threshold Tau_max for 2304 experiments total.
We set Tau_max = max(T)/2, Tau_max = 400000, Tau_max = 500000 and Tau_max = 600000.

BOSSV_extrapolation folder has subfolders whose name end with a number.
That number represents the initial digit of the threshold Tau_max.
The only exception is 0, which represents the results obtained with Tau_max = max(T)/2.


Optimization analyses:
These experiments consist in 36 scenarios for Query 26 and 56 for K-means with both black and gray box models for every case and datasize.

Extrapolation analyses:
These experiments consist in 24 scenarios for Query 26 and 28 for K-means with both black and gray box models, for every case with highest datasize, with and without additional data.
