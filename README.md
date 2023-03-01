# Football Players' Performance vs Transfer Fees
In the world of football, many star players are paid heavily to entertain audiences. However, many of these players also have ridiculous inflated transfer fees. For example, Neymar Junior, the Brazilian football player, was transferred from FC Barcelona to Paris Saint-Germain (PSG) for €222 million Euro, which was an extremely high fee. This project aims to investigate whether these transfer fees are actually related to player performance.

## Data Source
The data used in this project was collected from the following sources:

* Player’s Transfer fee dataset: https://www.kaggle.com/code/stmy456/football-transfer-analysis/data?select=top250-00-19.csv
* Player’s Overall Rating dataset: https://www.kaggle.com/code/oguzkhan/fifa-players-ratings-with-plotly/data?select=fifa_cleaned.csv

## Methodology
To investigate the relationship between transfer fees and player performance, we performed the following steps:

* Data collection and cleaning: We collected data on transfer fees and player performance from Transfermarkt and FBref websites, respectively. We then cleaned and merged the data to create a single dataset.
* Exploratory Data Analysis: We performed exploratory data analysis to understand the distributions and relationships between variables.
* Regression Analysis: We performed regression analysis to model the relationship between transfer fees and player performance. We used multiple regression models to account for confounding variables and to identify the most significant predictors of transfer fees.
* Data Cleaning:
  * Outlier Removal: We removed any outliers in the dataset to avoid skewing our analysis.
   * Problematic Data Removal: We removed any problematic data that would hinder model visualization.
* Linear Regression:
  * We used linear regression to determine the relationship between transfer fees and player performance.
  * Best-Fitted Line: We used linear regression to find the best-fitted line to visualize the trend of correlation.
* StatsModel:
  * Ordinary Least Square (OLS): We used OLS to evaluate the uncertainty of the best-fit line.
  * P-value and R-squared: We used OLS to calculate the p-value and R-squared of our analysis.

## Results
Our analysis showed that there is a positive correlation between transfer fees and player performance. However, the relationship is not as strong as one might expect, and there are several other factors that influence transfer fees, such as age, market demand, and contract duration. Our models also revealed some of the most significant predictors of transfer fees, such as goals scored, assists, and minutes played.

## Conclusion
In conclusion, our analysis suggests that there is a positive relationship between transfer fees and player performance, but it is not the only factor that determines transfer fees. Therefore, it is important to consider other factors when evaluating a player's market value. Our project provides a useful framework for further analysis and can help stakeholders make more informed decisions when it comes to player transfers.
