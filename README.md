# COVID-19 Datasets

This repository contains aggregated datasets generated from the *covid19-projections.com* [infection estimates model](https://covid19-projections.com/about/#infection-estimates-model).

## Datasets

* `us_counties_infection_estimates_time_series.csv.gz` - 34MB (111MB unzipped) - Data up until 2021-03-07 - Time series of infection estimates and reported cases & deaths for 3,000+ US counties (need to unzip first). Aggregated from https://github.com/youyanggu/covid19-infection-estimates-latest/tree/main/counties for your convenience.
* `us_states_infection_estimates_time_series.csv` - 1.8MB - Data up until 2021-03-07 - Time series of infection estimates and reported cases & deaths for all US states and territories. Filtered from https://github.com/youyanggu/covid19-infection-estimates-latest/blob/main/latest_all_estimates_states.csv for your convenience.
* `us_infection_estimates_time_series.csv` - 36KB - Data up until 2021-03-07 - Time series of infection estimates and reported cases & deaths for the US nationally. Filtered from https://github.com/youyanggu/covid19-infection-estimates-latest/blob/main/latest_all_estimates_us.csv for your convenience.
* `us_states_misc_stats.csv` - 5KB - Data updated 2021-06-22 - Contains various statistics about all 50 states + DC, such as COVID-19 deaths per 100k, change in unemployment rates, population density, median age, etc. (*2021-06-22 Update*: We also recommend [this dataset by Joseph Sill](https://github.com/jsill/usstatecovidanalysis/blob/main/us_states_covid_death_potential_covariates.csv), which was inspired by this project and contains many more variables).

## Other Repositories

- [Main COVID-19 Repository](https://github.com/youyanggu/covid19_projections)
- [Infections Estimates](https://github.com/youyanggu/covid19-infection-estimates-latest)
- [Historical CDC Vaccination Data](https://github.com/youyanggu/covid19-cdc-vaccination-data)
- [SEIR Simulator](https://github.com/youyanggu/yyg-seir-simulator)
- [Model Evaluations](https://github.com/youyanggu/covid19-forecast-hub-evaluation)
