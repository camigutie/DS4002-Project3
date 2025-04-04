# DS4002-Project3: Medical vs. Headline CPI Time Series Analysis
### Group Leader: Ethan Banerjee
### Group 20: Camila Gutierrez, Will Mayer

## (1) Software and Platform
Software type: Python 

Packages: 
* Pandas Package
* Matplotlib Package
* Numpy Package
* Seaborn Package
* SARIMAX Statistical Model
* Pmdarima Package 

Platform: Mac/Windows
## (2) A Map of Documentation
This repository contains the contents necessary to implement our sentiment analysis which consists of 3 main folders:

DATA FOLDER: 
* **[DATA/DS4002P2_RawData.xlsx](DATA/DS4002P2_RawData.xlsx)**: Our raw dataset with two sheets. The first sheet contains our monthly Consumer Price Index and Medical Consumer Price Index values. This sheet runs from 2000-12-01 to 2025-01-01. The second sheet contains our annual Health Expenditure Index values. This sheet runs from 2001-01-31 to 2021-01-31.
* **[DATA/established.csv](DATA/established.csv)**: Our established dataset with columns CPI, MCPI, and HEI. The index is the observation date, forward filled to annually at the end of the month. This set runs from 2000-12-31 to 2025-01-31. HEI values were not available from 2021 onwards and are marked as missing.
* **[SCRIPTS/analysis.ipynb](SCRIPTS/analysis.ipynb)**: This script uses the established dataset train a linear regression model to predit Medical Care CPI based on the Health Expenditures Price Index. The script then uses SARIMAX (Seasonal Autoregressive Integrated Moving Average with eXogenous regressors) Model for time series forecasting. It generates scatterplot visualizations for our output folder.

OUTPUT FOLDER: 
* **[OUTPUT/eda1.png](OUTPUT/eda1.png)**
* **[OUTPUT/eda2.png](OUTPUT/eda2.png)**
* **[OUTPUT/eda3.png](OUTPUT/eda3.png)**
* **[OUTPUT/eda4.png](OUTPUT/eda4.png)**


SCRIPTS FOLDER:
* **[SCRIPTS/eda.ipynb](SCRIPTS/eda.ipynb)**: This script uses raw data to perform exploratory data analysis and generate visualizations.
* **[SCRIPTS/make_data.ipynb](SCRIPTS/make_data.ipynb)**: This script uses raw data to create the established dataset found at [DATA/established.csv](DATA/established.csv).
* **[SCRIPTS/analysis.ipynb](SCRIPTS/analysis.ipynb)**: This script uses [DATA/established.csv](DATA/established.csv) to perform analysis and generate visualizations.

## (3) Result Replication

### In order to replicate the results of our study, you must follow these steps:
If you want to fully recreate our dataset, you can run [SCRIPTS/make_data.ipynb](SCRIPTS/make_data.ipynb). You can also use the set we've established at [DATA/established.csv](DATA/established.csv)

Recreating our dataset requires the following dependencies:
- matplotlib
- pandas
- seaborn
- SARIMAX

To recreate our analysis, run analysis.ipynb.

## (4) References
[1] 
