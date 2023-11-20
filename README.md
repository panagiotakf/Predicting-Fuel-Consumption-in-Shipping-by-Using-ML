# Predicting_Fuel_Consumption_Shipping_Using_ML

Given a dataset for a ship, we develop ML models that  predict current or future fuel consumption. We have five feautures (SOG-Speed Over Ground, STW-Speed Through Water, WD-Wind Direction, DWS-Discretized Wind Speed and Trim) and we predict the value of Main Engine Power (MEP), which is proportional of the fuel consumption. 

In Supervised_and_Ensemble_Learning, we use supervised and ensemble models, to predict the current value of MEP and we compare them to find the one with the best performance.

In LSTM_for_cape1_dataset we develop an LSTM model to predict future MEP values. We later tested our LSTM οn a simpler dataset to check its performance (LSTM_for_simpler_dataset).

Finally in Federated_Learning we develop a federated learning architecture to combine the infromations of two datasets and get better predictions.
