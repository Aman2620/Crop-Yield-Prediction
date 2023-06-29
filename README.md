
# Crop Yield Prediction

This repository contains the code and models for predicting crop yield. The goal is to develop accurate models that can estimate crop yield based on given input features.


## Dataset

The dataset used for this project contains information about crop yield, as well as various features that can potentially influence yield outcomes. The dataset is split into a training set and a test set.


## Models

The following models were evaluated for crop yield prediction:

    1. RandomForestRegressor
        Mean Squared Error: 191,858,309.45
        R2 Score: 0.9735
    
    2. GradientBoostingRegressor
        Mean Squared Error: 989,654,013.38
        R2 Score: 0.8636

    3. SVR (Support Vector Regressor)
        Mean Squared Error: 8,665,721,562.27
        R2 Score: -0.1947

    4. DecisionTreeRegressor
        Mean Squared Error: 289,307,922.38
        R2 Score: 0.9601


## Best Model

Based on the evaluation metrics, the RandomForestRegressor model performed the best among the models tested. It achieved a low mean squared error and a high R2 score, indicating a strong fit to the data and good predictive performance for crop yield estimation.

## Usage

To use the code and models in this repository, follow these steps:
```
1. Clone the repository: git clone <repository_url>
2. Install the required dependencies: pip install -r requirements.txt
3. Preprocess the data, if necessary, to match the expected format.
4. Split the dataset into train and test sets.
5. Run the provided code to train and evaluate the models on the data.
6. Use the trained RandomForestRegressor model for crop yield prediction on new data.
```
Feel free to customize and adapt the code to suit your specific needs.


## Conclusion

Crop yield prediction is an important task in agriculture. The RandomForestRegressor model showed promising results in accurately estimating crop yield based on the provided features. Further improvements and optimizations can be made to enhance the performance of the models.

If you have any questions or suggestions, please feel free to reach out.

Happy crop yield prediction!
    