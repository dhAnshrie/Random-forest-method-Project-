# Random Forest Regression in Python
Random Forest Regression is a versatile machine-learning technique for predicting numerical values. It combines the predictions of
multiple decision trees to reduce overfitting and improve accuracy. Python’s machine-learning libraries make it easy to implement and optimize this approach.

# Random Forest
A random forest is an ensemble learning method that combines the predictions from multiple decision trees to produce a more accurate and stable prediction. It is a type of supervised learning algorithm that can be used for both classification and regression tasks.

Every decision tree has high variance, but when we combine all of them in parallel then the resultant variance is low as each decision tree gets perfectly trained on that particular sample data, and hence the output doesn’t depend on one decision tree but on multiple decision trees. In the case of a classification problem, the final output is taken by using the majority voting classifier. In the case of a regression problem, the final output is the mean of all the outputs. This part is called Aggregation. 

![Capture482](https://github.com/user-attachments/assets/54801e5e-384d-4737-89c6-d8c25f6a9d7f)
# Walmart Weekly Revenue Prediction
## Data Description

* Store: Store number
* Date: Sales week start date
* Weekly_Sales: Store week sales
* Holiday_Flag: Mark on the presence or absence of a holiday
* Temperature: Air temperature in the region
* Fuel_Price: Fuel cost in the region
* CPI: Consumer price index
* Unemployment: Unemployment rate

## STEPS: 
1. Data preparation and research.
2. Visualizations.
3. Dividing the data into training and test sets.
4. Feature scaling.
5. Application of the random forest method.
6. Model evaluation.
7. Conclusion.

## Conclusion
After the work done, the following conclusions can be drawn:

We created and trained a model capable of predicting the weekly revenue of the famous chain retailer Walmart.

Removing outliers from the data resulted in improved model performance. The mean absolute error (MAE) and root mean square error (RMSE) decreased after data cleaning, indicating a better fit of the predicted values to the actual data.

The trained RandomForestRegressor model showed good results on the cleaned data. Evaluation of the model on the test set showed low error values, indicating its ability to make accurate predictions.
