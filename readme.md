ShipmentValuePrediction

Predicted Shipment Value in Logistics based on 5 different models and selected the best one.

In this project I predicted shipment value prediction in the logistics by cleaning and modelling Kaggle dataset (US Supply Chain Information for COVID19). I build 5 different models and select the best of all.

Models Build:
Random Forest
Linear Regression
Artificial Neural Network
Decision Trees
Gradient Boosting
For predicting the shipment value I decided to keep the cut off value for R-square as 80%. It was noticed that Random Forest and Neural Network shows training accuracy as 93% and 83% respectively and test accuracy as 84% and 83%. This confirms that Random Forest Regressor is overfitting the training set, so I selected Neural Network as the best of the 5 models.

Business Impact:
This model can be implemented in estimating the shipment cost in the logistics department. By implementing this model, value of the shipment can be identified beforehand, which in turn helps one to avoid possible deviation of around $5000 - $7000. It will help retailers and buyers to know the amount being spend for the shipment. Also, this model can be further developed to decide shipment cost based on the route taken.
