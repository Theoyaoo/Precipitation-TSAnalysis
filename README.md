# Precipitation-TSAnalysis
This repository contains the code and data used to conduct a time series analysis of monthly precipitation data from 1948 to 2022 Dec collected from Pittsburgh, New York, and Boston. The analysis includes conducting EDA, model identification, model fitting (ARIMA, vector ARMA, time series regression, GARCH), model validation, making inferences and/or forecasts using the fitted model.

## Data
The data used in this analysis is located in the data folder, and includes three separate files: pittsburgh.csv, new_york.csv, and boston.csv. Each file contains monthly precipitation data from its respective city, with columns for year and month, as well as the precipitation amount in inches.

## Code
All code used in this analysis is located in the code folder, with subfolders for each step in the analysis process (EDA, model identification, model fitting, etc.). The code is written in R, and each file is named according to its purpose.

## Results
The results of this analysis are located in the results folder, and include visualizations of the data, summary statistics, fitted model results, and forecasts.

## How to Use
To reproduce this analysis, clone this repository to your local machine and run the code in R. The data files are already included in the repository, so there is no need to download them separately.

## Dependencies
This analysis was conducted using R version 4.1.2, and the following packages were used:

+ _'ggplot2'_
+ _'forecast'_
+ _'tseries'_
+ _'astsa'_
+ _'vars'_
+ _'fGarch'_
These packages can be installed using the install.packages() function in R.

## Authors


## License
The code in this repository is licensed under the MIT License. See the LICENSE file for more information.
This project is licensed under the MIT License - see the LICENSE file for details.
