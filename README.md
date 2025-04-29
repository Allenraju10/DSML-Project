# DSML-Project

### Online News Popularity Project

### Project Topic

The transition of news from print, television, and radio to digital spaces has caused significant disruptions in the traditional news industry. Online platforms such as Buzzfeed, Mashable, and Medium publish a multitude of articles daily. To remain relevant, these platforms strive to publish articles that will attract more visitors and encourage widespread sharing.


In this study, I will analyze the Mashable dataset, which comprises data for nearly 40,000 articles. The project involves utilizing regression analysis to predict the number of times articles can be shared. This regression-based approach will prove invaluable to Mashable as it enables them to make informed decisions about which articles to publish, predicting those that are most likely to receive the maximum number of shares.


### Goals
1. Predict the number of shares an article is likely to receive
2. Understand which predictors affect the outcome (may reduce number of attributes if deemed unnecessary)
3. Assess the quality of predictions

### Models
I implemented a variety of different models and approaches to improve model accuracy.

* Simple linear regression
* Multilinear regression
* Ridge and Lasso regression
* Cross validation
* Random Forest
* Variance Inflation Factor
* Polynomial Regression

### Discussion and Conclusion
In this study, my goal was to explore article sharing behavior in the digital landscape. I went into this project with the hope that I could construct a model that could be used to accurately predict the number of shares an article was likely to get. Although I was not able to construct an accurate model, I did learn several new techniques that I hope to employ in future projects.

One key takeaway is the importance of careful predictor selection. Through rigorous analysis, it became evident that certain predictors have a significant impact on article shares. This emphasizes the need for a thoughtful approach to feature engineering, which ultimately enhances model performance.

One notable limitation is the relatively low R-squared values achieved across the different models. This suggests that there are factors influencing article shares that are not accounted for in the current predictor set. To address this, future analyses could explore additional predictors or consider more advanced techniques that capture more complex interactions. Furthermore, more complex models like neural net or deep learning methods could be useful to understand the structure of the data better.

#### By : Allen Daniel Raju
#### Batch : D53
