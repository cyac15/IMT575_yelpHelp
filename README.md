##  Yelp Help

**Introduction**</br>
The Yelp platform published crowd-sourced reviews about businesses. It provides pages devoted to information about restaurants and stores, allowing users to use a one-to-five-star rating system to evaluate products and services and to provide meaningful and detailed reviews about their experience (Chafkin, 2010). On one hand, users can make their decisions between similar restaurants or services based on the ratings and reviews shown on the Yelp pages. On the other hand, business owners can get an overall assessment of their restaurant's performance based on the reviews and ratings on Yelp and they can also further leverage the same massive dataset to analyze users to generate business insights for wiser decisions. Our project goal is to predict the popularity of restaurants. We deployed several machine learning methods including logistic regression, Naive Bayes, xGBoost, CNN, and LSTM to make predictions of popularity. We found that text and non-text features can both impact on the performance of predictions. Our best model is the CNN model with RMSE = 0.9807, using features from reviews, restaurants and users.

**Data Cleaning**
1.  [`preparation_importData.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/preparation_importData.ipynb)
2.  [`preparation_filterData.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/preparation_filterData.ipynb)

**Exploratory Data Analysis**
1.  [`EDA_restaurant.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/EDA_restaurant.ipynb)
2.  [`EDA_review.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/EDA_review.ipynb)
3.  [`EDA_user.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/EDA_user.ipynb)

**Feature Engineering**
1.  [`featureEngineering_review.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/featureEngineering_review.ipynb)
2.  [`featureEngineering_user.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/featureEngineering_review.ipynb)


**TrainValidationTest Split**
1.  [`trainValidationTest_split.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/trainValidationTest_split.ipynb)

**Data Modeling**
1.  [`analysis_CNN.ipynb.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/featureEngineering_review.ipynb)
2.  [`analysis_GaussianNB.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/analysis_GaussianNB.ipynb)
3.  [`analysis_LSTM.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/analysis_LSTM.ipynb)
4.  [`analysis_baseline.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/analysis_baseline.ipynb)
5.  [`analysis_xGBoost.ipynb`](https://github.com/cyac15/IMT575_yelpHelp/blob/master/analysis_xGBoost.ipynb)
