# Airline Passenger Referral Prediction
![pexels-jerry-wang-3768654](https://github.com/yashtambee/Airline-Passenger-Referral-Prediction/assets/121399834/cd0a553c-0501-465b-9916-72125550507a)

This project focuses on predicting whether airline passengers will refer the airline to a friend or not, based on their past behavior and demographic information. The following models were used for the classification of airline recommendations as 'yes' or 'no':

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors
4. Support Vector Machine
5. XG Boost Classifier

To enhance the accuracy and prevent overfitting, hyperparameter tuning was performed using the GridSearchCV method for the Decision Tree, K-Nearest Neighbors, and Logistic Regression models.

The classification metrics of precision, recall, F1 score, and AUC value were given priority in evaluating the models. Among all the implemented ML models, SVM and XGBoost achieved an impressive F1 score of around 95% - 96%, making them the best performing ML models.

The most influential features for the XGBoost and SVM models were found to be 'overall' and 'airline_Royal Air Maroc'. These features carried more weight compared to other features in those specific ML models.

The classifier models created in this project can be utilized to forecast passenger referrals, enabling airlines to identify influential travelers who can contribute to higher revenue. Therefore, to grow and expand, it is crucial for our client to provide top-notch ratings in the following areas:

- Cabin
- Ground services
- Food and beverage
- Entertainment
- Seat comfort

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

In conclusion, this project successfully employed supervised ML techniques to predict airline passenger referrals. SVM and XGBoost emerged as the best performing models, achieving an impressive F1 score of around 95% - 96%. By utilizing these models, airlines can identify influential travelers and focus on providing exceptional experiences in areas such as cabin, ground services, food and beverage, entertainment, and seat comfort. This will lead to increased customer satisfaction and potentially higher revenue.

It is important to note that this project serves as a proof of concept and further refinement and testing may be required before deploying the models in a production environment. Additionally, as the airline industry is dynamic, regular updates and retraining of the models may be necessary to maintain their accuracy and effectiveness.
