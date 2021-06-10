# Case Study: Energy Consumption in London Households
*STAT 471 Final Project*

*May 2, 2021*

In this project, we aim to predict energy consumption behaviors in London households based on a combination of different demographic, temporal, and weather-based predictors. We analyze 3.5 million observations across different consumers and days. 

## File List

Our submission consists of the following files:
- ```data_cleaning.ipynb``` - Jupyter Notebook where we clean and merge data from four different tables in order to prepare it for our analysis and modeling

- ```FinalProject.Rmd``` - R Markdown file where we perform Exploratory Data Analysis, Modeling and Evaluation on the cleaned data
- ```daily_dataset.csv``` -  This dataset consists of data related to energy consumption for each day and each
household from December 2011 to January 2014
- ```informations_households.csv``` - This dataset links each household to their ACORN group.
- ```uk_bank_holidays.csv``` - This dataset lists the days which are bank holidays in the United Kingdom
from December 2011 to January 2014
- ```weather_daily_darksky.csv``` - This dataset details the weather metrics for each day in London from
December 2011 to January 2014
- ```mse-results.png``` - A table showing the mean squared error obtained on the test dataset using each of our trained models

**Data pulled from:** [https://www.kaggle.com/jeanmidev/smart-meters-in-london](https://www.kaggle.com/jeanmidev/smart-meters-in-london)