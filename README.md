# SDM
R function for calculating the standard deviation from the mode

The Standard Deviation from the Mode (SDM) is a dispersion measure proposed by Tarald O. Kvalseth in his paper "Measuring variation for nominal data" (Bulletin of the Psychonomic Society, 1988, 26 (5), 433-436). 
It solves the problem of other measurements for variation in nominal data like the mean deviation from the mode, that are unaffected by anything else but the modal frequency. SDM also takes into account the number of categories (I).
Other properties stated by Kvalseth are:
1. SDM is 0 only when all observations belong to a single category
2. SDM is 1 only when the distribution over all categories is uniform

The R code provided here generates a function, that calculates SDM for a vector or dataframe column.
