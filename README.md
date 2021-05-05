# DAV_project 
## Project Proposal

### Analyze E-commerce Customer Dataset using Linear Regression. 
An E-commerce company sells clothes online, but they have a physical store where they can come to receive advice on styles. They try to identify if a company should focus on improving mobile app experience or on website experience for their customers.This analysis can provide the information about whether the company owner should invest more money on the online app or website for their customers. 


### Objective:-  
Using Linear Regression technique we will analyze the effects of different parameters(as per our current dataset) like Avg. Session Length, Time on App, Time spent on Website, Length of Membership (Premium card), Yearly Amount Spent  effects on customers. Also, we will analyze how these parameters affect each other.


### Dataset:- 
We found this dataset on ‘Kaggle’. Our dataset provides the information of how the customer spent their time on an Ecommerce product and many other details. Our dataset contains 500 entries and 8 different features. Different features like Email, Address, Avatar, Avg. Session Length, Time on App, Time on Website, Length of Membership, Yearly Amount Spent.

### Contents:-
- [1. Analyze E-commerce Customer Dataset using Linear Regression]
  * [1.1 Exploratory Data Analysis (EDA)]
    + [1.1.1 correlations in the data]  
    + [1.1.2 Scatter plot of Yearly amount spent vs Time on Website]  
    + [1.1.3 Scatter plot of Yearly amount spent vs Time on App]  
    + [1.1.4 Pair Plot]  
  * [1.2 Linear Regression of Yearly amount spent and Length of Membership]
  * [1.3 Multiple Linear Regression Model] 
    + [1.3.1 Training the Model]  
    + [1.3.2 Predicting Test Data]  
    + [1.3.3 Evaluating the Model]  
- [2. Conclusion]


### Conclusion:-
From the above table we can see different coefficient value for different feature. From this table company can decide what should they do to increase their customers. Here we can see that an increase in the Length of Membership (in years) would affect more on the value of our customers for Yearly Amount Spent ($). Next parameter which affects on yearly amount spent is Time on the App. 

**Time spent on App has more impact than Time spent on Website so, here we can say that company should focus on invest money on App because the app provides greater profitability for one more minute increase compared to the time on the website** but it also depends on what the costs of developing the app vs. the website are. It's clear that the website needs more work compared to the time on the app, but it may be more cost effective to continue working on the App instead of bringing the website up to speed. 

Different economic factors would determine which course of action to take, but at least we now have knowledge of the state of our website and our app in terms of yearly spend per customer.

With addition to this, however, Length of Membership was the greatest impact in the amount a customer spent yearly, meaning that the longer the customers stay with the company, the more money the company will make in the long run. So, length of Membership should be included as the economic factors to decide between focusing on their app experience or their website.
