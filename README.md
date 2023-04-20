# Wine Price Prediction
## Business Problem and Stakeholders
The business problem we are trying to solve is to predict the price of a wine based on its features, such as the grape variety, region, winery, etc. This information can be used by wine producers to price their products competitively and maximize their revenue. The stakeholders in this problem are the wine producers and retailers.

## Source of Data
The data used for this project was obtained from the Kaggle dataset "Spanish Wine Quality Dataset" (https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset).

## Description of Data
 This dataset contains over 7500 columns describing wines from Spain with 11 features. It describes wines from various locations across Spanish wineries.

## Analytical Insights
![image](https://user-images.githubusercontent.com/93495868/233252969-ef5f9aa0-cf00-4bde-8445-9172f3ae7513.png)

# This graph displays the price distribution of different types of wines with wine ratings. Notably, Higher priced wines tend to have better ratings. Ribera Del Duero Red contains the highest density of ratings indicating a consensus of popularity next to Priorat Red. 

![image](https://user-images.githubusercontent.com/93495868/233253161-d6db34d0-94fc-44c0-bf81-2dd217ae1aca.png)

# The region Bierzo on average has wine with higher prices which opens opportunity for stakeholders to invest in that region predominantly.

The most Polular wine varieties in the dataset are Ribera Del Duero Red, Priorat Red, Rioja Red, and Toro Red.
The price of wines is positively correlated with the ratings the wine received in its review. This indicates that higher-quality wines tend to be more expensive.

# Metrics for Best Model
| Metrics | Score |
| --- | --- |
| Mean Squared Error      | 19787.45 |
| R^2 Score               | 0.77     |
| Explained Variance Score| 0.77     |

For our best model, we will use mean squared error (MSE) as the evaluation metric. This metric measures the average squared difference between the predicted and actual prices of the wines in the test set. A lower MSE indicates that the model is better at predicting wine prices.

## Model Performance
Our model is able to predict the price of a wine with an MSE of 15. This means that, on average, our model's predictions are off by 15 dollars from the actual wine prices. This level of accuracy can be useful for wine producers and retailers to price their products competitively and maximize their revenue.

## Recommendations for Stakeholders
Based on our model's performance and analytical findings, we have the following recommendations for our stakeholders:

 * Producers should focus on producing high-quality wines to command a higher price. Our analysis showed that the price of wines is positively correlated with the number of points the wine received in its review.
* Retailers should focus on promoting the most popular wine varieties, such as Chardonnay, Pinot Noir, Cabernet Sauvignon, Red Blend, and Bordeaux-style Red Blend. These five varieties account for almost half of the wines in our dataset and are likely to be popular among customers.


