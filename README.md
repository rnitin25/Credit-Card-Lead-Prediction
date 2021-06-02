### Credit-Card-Lead-Prediction

The dataset provided more than a million customer data to train the model & predict whether a customer can become a potential lead to buy credit card.

#### Modelling Steps:
1. Pipeline created to preprocess data.
2. As target variable is imbalanced, I have performed undersampling from imblearn package.
3. Various algorithms and Hyperparameter tuning was performed to choose the Gradient Boosting algorithm as the final model which gave ~78% score on the test data.
