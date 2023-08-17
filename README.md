# Predicting-CO2-emission

Data Dictionary
Make → Company of the vehicle
Model → Car model
Vehicle_Class → Class of vehicle depending on their utility, capacity and weight
Engine_Size → Size of engine in terms of Litre
Cylinders → Number of cylinders
Transmission → Transmission type with number of gears
Fuel_Type → Type of Fuel used
Fuel_Consumption_City → Fuel consumption in city roads (L/100 km)
Fuel_Consumption_Hwy → Fuel consumption in Hwy roads (L/100 km)
Fuel_Consumption_Comb → The combined fuel consumption (55% city, 45% highway) is shown in L/100 km
Fuel_Consumption_Comb1 → The combined fuel consumption in both city and highway is shown in mile per gallon(mpg)
CO2_Emissions → The tailpipe emissions of carbon dioxide (in grams per kilometre) for combined city and highway driving (Target/dependent variable)

Objective: Leverage Machine Learning algorithms to effectively predict CO2 emission from vehicles
• Reduced dimension of data by Principal Component Analysis & t-distributed Stochastic Neighbor Embedding
• Trained Linear Regression with early stopping criteria and Elastic Net regularization
• Evaluated performance of models using Adjusted R2, Akaike Information and Bayesian Information Criteria
