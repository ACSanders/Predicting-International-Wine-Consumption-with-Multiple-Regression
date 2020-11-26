# Predicting International Wine Consumption with Multiple Regression
This project aims at constructing a machine learning model that predicts international wine drinking behavior based on certain economic and social factors.

## Author
Adam Sanders, Ph.D.

## Dependencies
This project uses Python 3. There are several libraries and modules that must be installed. These libraries and modules are:
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. LinearRegression from sklearn
6. train_test_split from sklearn
7. PolynomialFeatures from sklearn
8. sklearn.metrics

## Acknowledgements
Special thanks to Fivethirtyeight, the Heritage Foundation, and the Sustainable Development Solutions Network for producing the datasets used in this project. All datasets were accessed November 13, 2020. Specific citation and download information is as follows:

The 2020 Index of Exonomic Freedom was retrieved from the Heritage Foundation at this link: https://www.heritage.org/index/download
The dataset concerning global alcohol consumption was published by Fivethirtyeight, and was referenced in the article, "Dear Mona Followup: Where Do People Drink The Most Beer, Wine And Spirits?" (Chalabi 2014). It can be retrieved here: https://fivethirtyeight.datasettes.com/fivethirtyeight/alcohol-consumption%2Fdrinks
The 2020 World Happiness Report was published by the Sustainable Development Solutions Network, and was retrieved at this site: https://worldhappiness.report/ed/2020/

## Business Case
A winery wants to expand into new international markets. The winery wants to determine which markets have a good amount of wine drinkers. This knowledge will help direct its distribution efforts. Moreover, it will enable them to develop effective advertising campaigns. Consequently, the winery wants to know if we can build a model that predicts international wine consumption given a select number of economic and social factors.

## The Project Aim
This project aims at answering the buisness questions to promote the overall business aim. In order to answer the business questions, I will collect and clean several disparate datasets. I will then analyze the data and attempt to build an accurate machine learning model that predicts wine drinking behavior based on certain social and economic factors.

## Strategy and Methodology
1. Identify and import data.
2. Clean, process, standardize, normalize, and merge the data into a single, cleansed dataframe.
3. Conduct exploratory data anlysis and visualizations.
4. Using scatter plots, Pearson correlation, and P-values, identify possible features for analysis.
5. Develop the model(s) and evaluate them using R-squared scores and Mean Squared Error values.
6. Select and test the best model.
7. Discuss the results.
