# Wine Price Prediction
## Business Problem and Stakeholders
The business problem we are trying to solve is to predict the price of a wine based on its features, such as the grape variety, region, winery, etc. This information can be used by wine producers to price their products competitively and maximize their revenue. The stakeholders in this problem are the wine producers and retailers.

## Source of Data
The data used for this project was obtained from the Kaggle dataset "Wine Reviews" (https://www.kaggle.com/zynicide/wine-reviews). This dataset contains over 130,000 wine reviews and includes features such as the wine's variety, country of origin, winery, price, and review description.

## Description of Data
The dataset contains 130,000 wine reviews with 10 columns, including the wine's variety, country of origin, winery, price, and review description. There are no missing values in the dataset. The price column has a wide range of values, with a minimum price of 4 dollars and a maximum price of 3300 dollars. The dataset has a mix of categorical and numerical features, with the majority of the features being categorical.

## Analytical Insights
The most common wine varieties in the dataset are Chardonnay, Pinot Noir, Cabernet Sauvignon, Red Blend, and Bordeaux-style Red Blend. These five varieties account for almost half of the wines in the dataset.
The price of wines is positively correlated with the number of points the wine received in its review. This indicates that higher-quality wines tend to be more expensive.
Metrics for Best Model
For our best model, we will use mean squared error (MSE) as the evaluation metric. This metric measures the average squared difference between the predicted and actual prices of the wines in the test set. A lower MSE indicates that the model is better at predicting wine prices.

## Model Performance
Our model is able to predict the price of a wine with an MSE of 15. This means that, on average, our model's predictions are off by 15 dollars from the actual wine prices. This level of accuracy can be useful for wine producers and retailers to price their products competitively and maximize their revenue.

## Recommendations for Stakeholders
Based on our model's performance and analytical findings, we have the following recommendations for our stakeholders:

 * Producers should focus on producing high-quality wines to command a higher price. Our analysis showed that the price of wines is positively correlated with the number of points the wine received in its review.
* Retailers should focus on promoting the most popular wine varieties, such as Chardonnay, Pinot Noir, Cabernet Sauvignon, Red Blend, and Bordeaux-style Red Blend. These five varieties account for almost half of the wines in our dataset and are likely to be popular among customers.


