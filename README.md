# Suet Wah CHU's Portfolio
Welcome to my Github Portfolio! I am Suet Wah CHU (Sarah), a graduate student at Toulouse Business School, France, studying Artificial Intelligence and Business Analytics with some amazing and pratical projects. Any comments or guidance would be much appreciated!  

## Natural Language Processing
### [Project 1 : Social Media - Hate Speech Detection](https://github.com/Sarah-chu/AI-and-Big-Data-Project-Hate-Speech--1)
- ~34k posts/tweets with 3 categories(hate speech, offensive language, neither) were classified
- Achieved recall score of **92%** for hate speech and **89%** for offensive language using **SVM** with ***Python***
- **Unbalanced dataset** problem was handled by adding 2 extra datasets (more content and more topics of hate speech)
- A [Web App](https://hate-speech-detection-tbs.herokuapp.com/) was built on ***Streamlit*** and ***Heroku*** for users to test if they are posting hate speech or offensive language  
![SVM confusion matrix](/images/svm_model.png)

### [Project 2 : Social Media & PySpark - Donald Trump's Tweets from 2009 to 2020](https://github.com/Sarah-chu/NLP-PySpark-Donald-Trumps-Tweets)
- Explored the **sentiment** of **58681 Donald Trump tweets** by looking at the occurrence of both positive and negative words using ***PySpark***
- More **negative words** related to **impeachment** are used for retweets. About **positive words**, Donald Trump shows more frequent **appreciation** to other in retweets than in his original tweets.
- The hot topics were broken down in 2 aspects: by original tweets and retweets, by years.
- He had had more diversified topics, from personal life to politics, between 2012 and 2015 whereas he shifted his focus on political topics after 2015  

<img src="/images/DT_tweet_sentiment_word.png" width="700">

### [Project 3 : Twitter API -  

## Deep Learning
### [Project 4 : CNN & Image Recognition - Metallic Surface Anomaly Detection](https://github.com/Sarah-chu/CNN-Metallic-Surface-Anomaly-Detection)
- 1,800 grayscale images of **6 different types** of typical surface defects of the hot-rolled steel strip
- Achived **95% accuracy** of detection by using a convolutional neural network with ***PyTorch***
- The convolutional neural network consists of 3 convolutional layers and 3 dense layers, and applies rectified linear on each convolutional layers with max pooling over 3x3 pixels
- Can further develop into an application to detect defects on the surface of a metal part during the quality control process in the production lin

## Classification
### [Project 5 : Human Resources - IBM HR Analytics Employee Attrition Performance](https://github.com/Sarah-chu/Classification-IBM-HR-Analytics-Employee-Attrition-Performance-)
- Predicted if an employee is likely to quit the company based on the dataset consisited of 1233 employees with 16.1% attrition rate 
- Gaussian Naive Bayes was selected as the best model from Logistic Regression, KNN, Decision Tree and Random Forest, based on sensitivity(recall) in ***R***
- Achieved **68% recall** without any sampling method, will update the model using some sampling method in the future
- **8 influential factors of attrition** were identified and **6 recommendations** were made based on the key findings and data analysis  
![HR_model_comparison](/images/HR_model_comparison.png)

### [Project 6 : Finance/Banking - Default Payments of Credit Card Clients in Taiwan from 2005](https://github.com/Sarah-chu/Classification-Credit-Card-Default-Payment)
- Predicted if a client is going to default next month by using 3000 records of credit card clients in Taiwan from April 2005 to September 2005 
- Cleaned the data with the understanding of the dataset: the payment status were mislabled
- Applied three sampling methods to encounter the unbalanced dataset (Random Oversampling, Random Undersampling, SMOTE) with ***Python***
- **89% recall** score was achieved using Gaussian Naive Bayes model with SMOTE  
<img src="/images/credit_card_conf_matrix.png" width="700">

## Time Series
### [Project 7 : Hospitality & Tourism - CDG Airport Traffic Prediction](https://github.com/Sarah-chu/Time-Series-CDG-Airport-Traffic-Prediction)
- Forecasted the next three years of traffic per month of Charles de Gaulle Airport(CDG) despite the effect of COVID-19 using Box-Jenkins methodology
- Dummy variables were created to replace the largest outliers in the residual data to try to improve the model but the model was not improved
- ARIMA (0,1,3)(0,1,1)[12] with no dummy variables was used with **88.24%** of points in the confidence bound(over 80% of the sample can be predicted within the confidence bound) for in-sample test  
![time series prediction](/images/insample_prediction.png)

## Data Visualization
### [Project 8 : R Shiny App - COVID-19-Death by Country](https://github.com/Sarah-chu/Shiny-App---COVID-19-Death)
-  [Interactive website](https://suet-wah-chu.shinyapps.io/testui/?_ga=2.238267977.83272496.1606164025-724514677.1602514887) created with **Shiny App** in ***R*** showing the dealth rate and death rate per capita of each country from January 2020 to September 2020
-  2 types of data, 2 scales (linear and logarithmic) and multiple countries can be chosen and 2 Axes can be adjusted

<img src="/images/Rshiny_web_interface.png" width="700">
