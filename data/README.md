The data used is from UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/datasets/heart+disease

# Goal of the project:
## Building a machine learning model that would be able to classify if a patient has a heart disease given his medical parameters.

## Steps:
1. Explore the data (EDA)
2. Compare a few ML models in terms of accuracy
3. Choose the best performing ML (tune if necessary)


### The data is normally distributed according to age. There are twice as many males in the dataset. However, from EDA we can infer that females are more prone to heart disease


### The Logistic Regression showed better accuracy performance than KNN or Random Forest. The accuracy is 88.5 %. However, it is not enough for medical problem.
### Tuned the model with GridSearchCV. However, it showed the same performance as untuned Logistic Regression.


### Next steps:
- Evaluating the model
- Finding the most important features and tuning the model further