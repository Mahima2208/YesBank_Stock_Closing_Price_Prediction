# YesBank-Stock
![start slide](https://akm-img-a-in.tosshub.com/businesstoday/images/story/202201/markets-1_10-sixteen_nine.jpg?size=1200:675)

# PROBLEM STATEMENT

Yes Bank Limited is an Indian private sector bank headquartered in Mumbai, India and was founded by Rana Kapoor and Ashok Kapur in 2004. It offers wide range of differentiated products for corporate and retail customers through retail banking and asset management services. On 5 March 2020, in an attempt to avoid the collapse of the bank, which had an excessive amount of bad loans, the Reserve Bank of India (RBI) took control of it.

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

# ALGORITHMS USED:

## i. 	  Linear Regression

## ii. 	  Lasso Regression

## iii. 	Ridge Regression

## iv.   	Elastic Net Regression

## v. 	  KNN

## vi.   	SVM


# CONCLUSION

•	In EDA part we observed that

1.	There is increase in trend of Yes Bank's stock's Close, Open, High, Low price till 2018 an then sudden decrease.
2.	
3.	We observed that open vs close price graph concluded that after 2018 yes bank's stock hitted drastically.
4.	
5.	We saw Linear relation between the dependent and independent values.
6.	
7.	There was alot of multicollinearity present in data.

•	Target variable(dependent variable) strongly dependent on independent variables

•	We get maximum accuracy of 99%

•	Linear regression and Ridge regression get almost same R squared value

•	Whereas Lasso model shows lowest R squared value and high MSE,RMSE,MAE,MAPE

•	Ridge regression shrunk the parameters to reduce complexity and multicollinearity but ended up affecting the evaluation metrics.

•	Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).

•	KNeighborsRegressor end up giving the highest R squared value. The predicted values are nearly equal to the actual values. We got 99% accuracy.

•	SVM and Elastic Net showed nearly equal accuracy.
