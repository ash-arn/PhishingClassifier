# PhishingClassifier
### Buisness Problem:
     Phishing is the fraudulent attempt to obtain sensitive data, such as usernames, passwords by disguising a fake website
     as a trustworthy website.It is important to identify Phishing websites.
### Target Variable: Result
    If Result = 0, Not a Phishing website
    If Result = 1, Phishing website.
Data is having 30 predictor attributes and one response variable with binary classes. 0 out of 2456 records is missing for all columns.1362 records are of trust-worthy websites(majority class) and  1094 records are Phishing websites(Minority class)
![Resultcount](https://user-images.githubusercontent.com/60782716/87672405-84799500-c790-11ea-95cf-270642efe661.PNG)
The datatype of predictors are taken as int64, Howerver the predictors are nominal. Therefore Quantitative analysis like correlation has no or less signficance.
### Exploratory Data analysis
Since predictors are categorical, they are plotted as Bivariate countplots  where class labels are represented as color of the bars.

![features1](https://user-images.githubusercontent.com/60782716/87689485-e2fd3e00-c7a5-11ea-8f8d-7c3705bb7c92.PNG)
![features2](https://user-images.githubusercontent.com/60782716/87690161-b564c480-c7a6-11ea-800d-b1f85ca293e3.PNG)


