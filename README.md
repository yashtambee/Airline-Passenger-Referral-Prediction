# Airline Passenger Referral Prediction
![pexels-jerry-wang-3768654](https://github.com/yashtambee/Airline-Passenger-Referral-Prediction/assets/121399834/cd0a553c-0501-465b-9916-72125550507a)
## Introduction

This project aims to predict whether airline passengers will refer the airline to a friend or not, based on their past behavior and demographic information. The ability to forecast passenger referrals is valuable for airlines as it helps them identify influential travelers who can contribute to higher revenue. By understanding the factors that influence passenger recommendations, airlines can focus on providing exceptional experiences and targeted marketing efforts to maximize customer satisfaction and loyalty.

To achieve this prediction, several supervised machine learning models were employed for the classification task. The models used in this project are:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors
4. Support Vector Machine
5. XG Boost Classifier

Hyperparameter tuning using the GridSearchCV method was performed for the Decision Tree, K-Nearest Neighbors, and Logistic Regression models to improve their accuracy and prevent overfitting. The models were evaluated based on classification metrics such as precision, recall, F1 score, and AUC value.


## Dependencies

This project requires the following libraries:

- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib
- seaborn

## Usage

To reproduce the results and analyze the models, follow these steps:

1. Ensure that the required dependencies are installed.

2. Clone this repository to your local machine.

3. Open the Jupyter Notebook file named "Airline_Passenger_Referral_Prediction.ipynb" using Jupyter Notebook or any compatible environment.

4. Run the notebook cells sequentially to execute the code and generate the results.

5. Analyze the classification metrics, model performance, and feature importance.

6. Make any necessary modifications or improvements based on your specific requirements.

## Conclusion

Among the implemented ML models, SVM and XGBoost exhibited the highest performance, achieving an F1 score of around 95% - 96%. These models can be effectively utilized to forecast passenger referrals and identify influential travelers. To enhance customer satisfaction and attract more referrals, airlines should focus on providing top-notch ratings in key areas such as cabin, ground services, food and beverage, entertainment, and seat comfort.

It is important to note that this project serves as a proof of concept, and further refinement and testing may be necessary before deploying the models in a production environment. The dynamic nature of the airline industry may require regular updates and retraining of the models to maintain their accuracy and relevance.
