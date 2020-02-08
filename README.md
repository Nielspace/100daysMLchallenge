# 100daysMLchallenge Notes

Learning something new with ML each day. The motive behind this repo is to spend 30 mins or more in an ML problem and learn something new. 

# Day 1
## 6 January 
> Dataset : Medical cost personal dataset

> **Note:  Logs**
> - Using Logarithms: Logarithms helps us have a normal distribution which could help us in a number of different ways such as outlier detection, implementation of statistical concepts based on the central limit theorem and for our predictive modell in the foreseen future. 

# Day 2
## 7 January 
> Dataset : Medical cost personal dataset

> **Note:  OLS and Hyppthesis Testing**
> - OLS is also known as the Ordinary Least Squares. It is a method to find a linear relation between the independent variable and dependent variable. 
> - In stats module ols is can be used to find the p value between the two. The p-value or the probability value is used to test the hypothesis against the alternative hypothesis which stands against the ruling hypothesis or the null hypothesis. 
> - The alternative hypothesis is the one you would believe if the null hypothesis is concluded to be untrue. The evidence in the trial is your data and the statistics that go along with it. All hypothesis tests ultimately use a p-value to weigh the strength of the evidence (what the data are telling you about the population). The p-value is a number between 0 and 1 and interpreted in the following way:

>> 1. A small p-value (typically ≤ 0.05) indicates strong evidence against the null hypothesis, so you reject the null hypothesis.
>> 2. A large p-value (> 0.05) indicates weak evidence against the null hypothesis, so you fail to reject the null hypothesis.
>> 3. p-values very close to the cutoff (0.05) are considered to be marginal (could go either way). Always report the p-value so your readers can draw their own conclusions.

# Day 3
## 8 January 
> Dataset : Medical cost personal dataset

> **Note: Learning Data Exploration**
> - Learning to explore correlation and colinearity and also reason out the plausible conclusion as how and why a particular feature is important. 

# Day 4
## 13 January 
> Dataset : Medical cost personal dataset

> **Note: Intro to Unsupervised Learning**
> - Using clusterring to understand the distribution of data and make sense of it. 
> - The next two days will learning and understanding:
>>  - K-means clusterring 
>>  - Hierarchical clusterring


# Day 5
## 14 January 
> Dataset : Medical cost personal dataset

> **Note: Intro to Unsupervised Learning -- KMeans**
> - In the quick half an hour session that I got to learn something about K-means clusterring is that it find groups or cluster based upon the centroid which is quite un-reliable which I though in the beginning but later on as I started to look more into the centroid patterns started to emerge. For example in manual clusterring there was no distinct geography on which the data is being seperated it is just based upon the fact that some data share a particular property where as others do not. In case of KMeans we see a distinct geography seperating the two region or the clusters. KMeans serves as opportunity to segregate the based upon the gravity of the center also known as the centroid. An emerging cluster finds its way by creating different centriods and then reducing the error to reach the center of the cluster. 

# Day 6
## 15 January 
> Dataset : Medical cost personal dataset

> **Note: Feature Engineering and Modeling**
> - Explored various methods to drop features and transform feature to make a reliable machine learning model. Used techniques from Jeremy Howard's fast.ai lessons. 
> - In the end, I used Linear Regression and Random Forest Regression to complete the first project of 100daysML challenge. 
> - I closed with an accuracy of 82% in both training and testting dataset, which far eliminates the question of overfitting and underfitting. 

> - Link to the notebook is <a href ='https://www.kaggle.com/nielspace/patient-charge-sheet/edit/run/26511306'>here</a>

> - You can download the project from<a href='https://github.com/Nielspace/100daysMLchallenge/blob/master/100daysMachineLearningChallenge/Project%2001%20-%20Patient%20Charge%20sheet.ipynb'> here</a>

# Day 7
## 3 Febuary 
> Dataset : Pulsar star

> **Note: Data Visualisation**
> - Different kind of distribution is helpful in modelling a good machine model.


# Day 8
## 4 Febuary 
> Dataset : Pulsar star

> **Note: Studying Outliers**
> - Working on outliers
> - Outliers seems to be problematic. Removing outliers eventually affects the loss of data or reduction of observations. With less observations we have limited source to forecast or even find patterns. 
> - Instead of removing outliers we can transform them or even use different machine learning modelling to build a good classifier
> - Today in my approach I looked upon removing outlier from an imbalanced dataset. Although the data had enough observations but while removing outliers I was certain that the number of observations will reduce drastically, because almost all the features had outliers. 
> - In order to solve the above problem I used the scaling method. More specifically Robust scaler because it reduces the effect of outliers in the dataset. 

# Day 9
## 5 Febuary 
> Dataset : Pulsar star

> **Note: Studying Outliers**
> - Read a paper called "Robust Decision Tree Removing Outliers".
> - Key points from the paper were, outliers are best removed from the non-parametric model. 

