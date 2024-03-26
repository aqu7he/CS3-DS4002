# DS-4002-Group-5-Project-2

## Section 1: Software and Platform

Software: Python (Colab or Jupyter)

Packages: numpy, pandas, scikit.learn, statsmodels.api, matplotlib, statsmodels.tsa.api

Platform: Charlie and Cato used Windows, Andrea on Mac

## Section 2: A map of documentation

LICENSE.md: markdown file containing licensing information

OUTPUT: folder containing all graphs and figures relevant to our final presentation

> output_graphs.pdf

> output_figures.pdf

DATA: folder containing both original data and cleaned data

> N_seaice_extent_daily_v3.0.csv: original NOAA data for northern polar region sea ice

> S_seaice_extent_daily_v3.0.csv: original NOAA data for southern polar region sea ice

> seaice_data.csv: data cleaned and combined during EDA, joined on datetime

SCRIPTS: folder containing all relevant scripts used in the project

> seaice_eda.ipynb: notebook containing code for data cleaning and exploratory data analysis

> tripleexpsmoothing.ipynb: notebook containing code for the triple exponential smoothing portion of our analysis

## Section 3: Instructions for reproducing your results

To replicate our results, first download the files in the DATA folder.

Prepare Python - Import the necessary libraries and add-on packages.  For python you will need to install pandas, statsmodels.api, numpy, matplotlib.pyplot, and import Exponential Smoothing, SimpleExpSmoothing, and Holt from statsmodels.tsa.api.

Run master script file - In the SCRIPTS folder, download and run the tripleexpsmoothing.ipynb script in python.

For additional graphs/analysis, run tripleexpsmoothing_additional.ipynb.

Analyze the results - After running the master script, there should have resulted in some graphs and figures. Cross reference these with the graphs and figures uploaded in the OUTPUT folder.

Resources:
[1] IEEE. (2022). Performance Analysis of the Triple Exponential Smoothing Method During the Covid19 Pandemic on Tourist Visit Data. https://ieeexplore.ieee.org/document/9872863 
[2] LinkedIn community. (2024, January 2). How do you evaluate the accuracy of exponential smoothing forecasts?. Types of Exponential Smoothing and How to Evaluate Them. https://www.linkedin.com/advice/0/how-do-you-evaluate-accuracy-exponential-smoothing#:~:text=To%20evaluate%20the%20accuracy%20and,absolute%20percentage%20error%20(MAPE) 
[3] SARIMA (Seasonal Autoregressive Integrated Moving Average). (2023). https://www.geeksforgeeks.org/sarima-seasonal-autoregressive-integrated-moving-average/ 
[4]B. Etienne, “Time Series in Python — Part 2: Dealing with seasonal data,” Medium, Feb. 15, 2019. https://towardsdatascience.com/time-series-in-python-part-2-dealing-with-seasonal-data-397a65b74051
[5]“Exponential smoothing — statsmodels,” www.statsmodels.org. https://www.statsmodels.org/dev/examples/notebooks/generated/exponential_smoothing.html
