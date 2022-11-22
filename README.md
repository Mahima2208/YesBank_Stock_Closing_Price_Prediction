# YesBank Stock Closing Price Prediction
![start slide](https://akm-img-a-in.tosshub.com/businesstoday/images/story/202201/markets-1_10-sixteen_nine.jpg?size=1200:675)

# 📖PROBLEM STATEMENT

Yes Bank Limited is an Indian private sector bank headquartered in Mumbai, India and was founded by Rana Kapoor and Ashok Kapur in 2004. It offers wide range of differentiated products for corporate and retail customers through retail banking and asset management services. On 5 March 2020, in an attempt to avoid the collapse of the bank, which had an excessive amount of bad loans, the Reserve Bank of India (RBI) took control of it.

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

# 📖ALGORITHMS USED:

## i. 	  Linear Regression

## ii. 	  Lasso Regression

## iii. 	Ridge Regression

## iv. 	  KNN




# 📖CONCLUSION

•	In EDA part we observed that

1.	There is increase in trend of Yes Bank's stock's Close, Open, High, Low price till 2018 an then sudden decrease.

2.	We observed that open vs close price graph concluded that after 2018 yes bank's stock hitted drastically.
	
3.	We saw Linear relation between the dependent and independent values.
	
4.	There was alot of multicollinearity present in data.

•	Target variable(dependent variable) strongly dependent on independent variables

•	We get maximum accuracy of 99%

•	Linear regression and Ridge regression get almost same R squared value

•	Whereas Lasso model shows lowest R squared value and high MSE,RMSE,MAE,MAPE

•	Ridge regression shrunk the parameters to reduce complexity and multicollinearity but ended up affecting the evaluation metrics.

•	Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).

•	KNeighborsRegressor end up giving the highest R squared value. The predicted values are nearly equal to the actual values. We got 99% accuracy.

•	SVM and Elastic Net showed nearly equal accuracy.

# 📋 Execution Instruction
The given IPython Notebook can be either downloaded to be run on your local Jupyter Notebook or can be directly run on Google Colab.

# 📜 Credits
Mahima Phalkey | Data Scientist | Machine Learning Engineer | Data Science enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/mahima-phalkey/) [![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/Mahima2208) [![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@mahimaphalkey) [![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)](https://drive.google.com/file/d/1Xi9oBrCjMc3QPGAhFdfO5rnMUssLa7Hw/view?usp=sharing)


# 📚 References

https://trendlyne.com/research-reports/stock/1535/YESBANK/yes-bank-ltd/

https://www.ijraset.com/research-paper/stock-market-prediction-using-ml
