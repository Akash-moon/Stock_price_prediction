# Stock_price_prediction

## Problem Statement:
The problem is to develop a predictive model that combines numerical analysis of historical stock market data with textual analysis of relevant news articles and other textual sources to improve the accuracy of stock market predictions.

 **The model should address the following challenges:**
 * **Data Integration :**  *Integrating numerical data, such as historical stock prices and volumes, with textual data, such as news articles and social media sentiment, to create a comprehensive dataset.* 
 
 * **Feature Extraction :**  *Extracting meaningful features from the combined dataset using matplotlib and seaborn librarirs that capture the relevant patterns and correlations between numerical and textual data.*

 * **Model Development :** *Building a predictive model that effectively incorporates both numerical and textual features.* 
 
 * **Sentiment Analysis :** *This analysis should capture the market sentiment and its potential impact on stock prices.*

 * **Model Evaluation :** *Evaluating the performance of the developed model using appropriate evaluation metrics.*

## Stock Price Prediction(Goals) :

The project "Stock Market Prediction using Numerical and Textual Analysis" aims to develop a predictive model that utilizes both numerical data and textual analysis to forecast stock market trends.

Overall, this project aims to combine the power of numerical analysis and textual analysis to enhance stock market prediction accuracy. By considering both historical stock market data and relevant textual information, it seeks to provide investors, traders, and financial analysts with valuable insights and predictions for making informed investment decisions.

![stock_pic](https://github.com/Akash-moon/Stock_price_prediction/assets/83701120/6e8389f1-87ab-4c4a-b095-ac6b0551551e)


## Implementation :

**1.** Using Sckiit Learning (**Building Machine Learning model**).

**2.** Data Preprocessing using dataset (**Using Numpy, Pandas and NLTK**).

**3.** Visualization of Dataset (**Using Matplotlib and seaborn**).

**4.** Feature Scaling or Data Normalization (**Using Normalization and Standaridation**).

**5.** Preparing the Datasets for training (**Using sklearn**).

**6.** Reshaping the datasets (**Exculde unnecessary data**).

**7.** Model development (**Using different algorithms**).

**8.** Preprocessing the Data.

**9.** Predicting the Output.

## Conclusion :

* **RandomForest =** 0.05257968397499098

* **DecisionTree =** 0.10831900809236311

* **AdaBoost =** 0.05492347045438241

* **LightGBM =** 0.0583079056070462

* **XGBoost =** 0.05968830860645931

![Screenshot (16)](https://github.com/Akash-moon/Stock_price_prediction/assets/83701120/d2e647e9-c240-48c5-bfc3-faed23b73ec3)


**From here we can see that RandomForestRegressor shows a better performance than the others(Based on Mean Squared Error Parameter).**
