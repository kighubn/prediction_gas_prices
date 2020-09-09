# prediction_gas_prices
I used a logit regression moodel to calculate the probability of rising oil price. The model is simplified, if the price goes up, the label is 1 else the label is 0. 
The data I used contains the historical prices of oil(Gasoil) in France and the historical prices of crude(Brent). After Data processing，each vector in the training data contans 10-day oil prices and 10-day crude prices, thus a vector of dimension (1,20). Its label is 0 or 1.
Gibbs sampler is used to find the parameters of logit regression.  
