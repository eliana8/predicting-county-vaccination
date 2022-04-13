# Predicting COVID-19 Vaccination Rates by U.S. County

## Github pages: https://eliana8.github.io/predicting-county-vaccination/

### Overview:
The COVID-19 vaccine offers the best protection against severe illness and prevention of future outbreaks, however the efficacy depends on a widespread uptake of the vaccine. Currently, the national vaccination rate approaches the ‘guide’ for herd immunity, but 45.8% of the population has yet to be fully vaccinated. Beyond the interests in public health, individuals resistant to the idea of getting the vaccine could benefit from policies that encourage its uptake. Utilizing a predictive machine learning model, we uncover which factors appear to influence vaccine uptake the most by predicting vaccination rates by county. Understanding the sociological background of those unwilling to obtain the vaccine can aid policymakers in designing incentive programs for those groups, as well as offer information for future pandemics.

### Methods: 
We decided to use regression based methods of varying complexity to predict vaccination rate. We selected Ordinary Least Squares (OLS), Elastic Net, K-Nearest Neighbor, and Random Forest models. For tuning hyperparameters, we utilized a 5-fold cross validation and tuned the following hyperparameters: penalty, mixture, neighbors, mtry and min_n. The cross-validated RMSE selected the following values (ordered as above): 0.01, 1, 30, 8, and 6. In most cases, the MAE or 𝑅2 selected the same hyperparameter values.
