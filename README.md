# Bitcoin-LineUp
A linear transformation for price support modeling

Introduction
When beginners want to start on bitcoin, always they want to know when to buy. This article proposes a linear transformation of bitcoin price to evaluate prices support and to find the best entries on bitcoin for an interesting hold strategy.
In a previous article, I proposed a new method based on Bitcoin Waves to model the price of bitcoin, pointing buy and sell zones. For this propose, Bitcoin Waves model intented to predict the next waves by approximating the future waves as linear combinations of prior waves.
Hence, the present study was designed to investigate the potential of differentiation (Fundamental Theorem of Calculus) and derivative test for finding critical points, in other words, when you can buy and hold without suffering.

Bitcoin LineUp data treatment
Prices from Coinmetrics were used, 2010 to 2021. The four halving waves were investigated (2010 > 2012, 2012 > 2016, 2016 > 2020 and 2020 >2021). Next, the waves were submitted to derivative test by calculating 1st and 2nd derivatives.
Data import, pre-processing and multivariate procedures were carried out using R software with Signal Processing (signal) package [4]. All data processing was performed using the free R software from the R Foundation for Statistical Computing.
