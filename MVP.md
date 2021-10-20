## MVP

Analysis of the Amazon predicts the price of the laptop

The aim of this project is to scrape laptop data from the amazon website then build a regression model to predict an approximate price for the laptop.

We scrap around 500 pages from amazon.com then we marge it with the dataset in [https://www.kaggle.com/ionaskel/laptop-prices](https://www.kaggle.com/ionaskel/laptop-prices)

at the end the total become 1747 rows and 11 columns.

Our EDA steps :

- dropped all duplicated and unneeded rows and columns
- strip all spaces and unwanted characters
- remove outliers .
- Converted categorical data into numeric

After cleaning the data set the remain rows are 1469


![image](https://github.com/nisreenabdullah6/Amazone-project/blob/main/mvp1.png)

The figure above shows correlation between all numeric columns was calculated. As shown in the heatmap graph there are a lot of columns that are highly correlated with another.

![](RackMultipart20211020-4-1v5tnhe_html_8974e39aa1d46aad.png)

The figure above shows the relation between laptop brand and average price after the EDA

![](RackMultipart20211020-4-1v5tnhe_html_82b794df49af126f.png)

To start exploring this goal, as it showing the figure above we used linear regression to generate predictions on training data using fit model.

However, we built three different models, and Polynomial Regression Model shows the best result .

Our next step is to explore another models and see if it has batter result and improve the r square by feature engineering.
