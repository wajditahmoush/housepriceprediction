# House Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual value and flip them at a higher price. For the same purpose, the company has collected a data set from house sales in Australia. 

# General Information
The company is looking analayize the collected data to select prospective properties to buy and enter the market.

### The company wants to know:
- Whether to invest in them or not.
- Which variables are significant in predicting the price of a house.
- How well the different variable relate and describe the price.

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2


## Conclusion
This Linear progression model provides good prediction for houses pricing with accuracy of more than 84% and max average error around 50K.
The most significanyt variable with most effects on price are: GrLivArea, OverallQual, OverallCond, GarageScore and the neighborhood area: NridgHt, StoneBr, Veenker, and NoRidge.
The method used to handle categorical variables (business and da-values analysis) enabled building a powerful model using linear regression. The model doesn't suffer overfitting problem and thus was used without the need for any regularization through Ridge or Lasso.
Prices were all changed to current value using an inflation rate of 4% annual from the sales date.
