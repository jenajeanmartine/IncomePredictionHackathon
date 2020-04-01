# Income Prediction Hackathon
### Team: Jena Brentano, Ingrid Wang
## Summary:
Our team had a 6hr work day to create a Random Forest model to predict whether a person's income was above or below 50,000 dollars based on data provided <a href="https://archive.ics.uci.edu/ml/datasets/adult">here</a> and originally from the census. Our dataset contained ~16,000 rows

## Conclusions:
Categorical data was dummied and some features were simplified or combined. My teammate and I focused on narrowing down the feature set and tuning hyperparameters to reduce overfitting and to create a model that prioritized sensible features like level of education and age. This was a successful approach, our model performed best on unseen data out of the four groups who participated! 

Our model was still a little overfit and due to imbalanced classes, had 94% Specifictiy and only 61% Sensitivity. By chosing to balance the class_weights parameter of the model, Sensitivity and Specificity can be balanced at around 80% each, but accuracy loses a few points. We optimized for accuracy.

