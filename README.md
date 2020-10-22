# Predicting-number-of-Shares

Predicting the number of shares based on how popular the article is.

## Business Challenge

[Mashable](www.mashable.com) is a global, multi-platform media and entertainment company. Powered by its own proprietary technology, Mashable is the go-to source for tech, digital culture and entertainment content for its dedicated and influential audience around the globe. Just like any other media company its success depends on the popularity of articles.
One of the key metrics to measure popularity is to find how many times the article is shared.

## Business benifits

Mashable’s entire business is dependent on popularity of articles. With accurate prediction of shares, company can choose which articles to publish hence driving higher user engagement and profits.  Rough estimate is 1% increase in engagement time (minutes) increases profit by up to 5%

---

### Additional information

- Technology used - Machine Learning
- Dataset - [OnlineNewsPopularity](https://github.com/JVedant/Predicting-number-of-Shares/blob/master/dataset/OnlineNewsPopularity.csv)
- Models used :
  - LinearRegression
  - RandomForestRegressor
  - DecisionTreeRegressor
  
- Stats on test data :

  - raw data
    - r2-score for Linear Regression:  -0.2944
    - r2-score for Decision tree :  -0.3957
    - r2-score for Random Forest :  -0.1088

  - Preprocessed data
    - r2-score for Linear Regression:  -3813840325600752.5
    - r2-score for Decision Tree :  -0.5309
    - r2-score for Random Forest :  0.0158
  
---
