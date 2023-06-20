# Introduction to Bias and Variance
All ML models have a tradeoff between minimizing bias and variance factors, both prediction errors. To build an accurate model, we must first understand the meanings of these terms
### Bias
Models with lots of bias pay little attention to the training data causing them to output errors on both the test and training data. Underfitting usually occurs in these scenarios where the model can't understand the pattern between the data. 
### Variance
Variance is the variability of data and predictions. Models with high variance overfit, get trained so much that the model can't learn independently(Testing data), causing them to do poorly on just the testing data.
## The Tradeoff
A model can either have high bias and low variance or vice versa. This results in a tradeoff between the two factors. Finding the perfect mix between the two factors, results in a highly accurate model and prevents overfitting/underfitting. A trade-off is necessary for a model to be successful and there are many other such tradeoffs like this.
![image](https://github.com/MrCarry123/intro-to-data-science/assets/116237341/36a4932d-9211-45be-a534-96645115a5b3)
