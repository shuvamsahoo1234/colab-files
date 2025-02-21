CO₂ Emission Prediction System
using Machine Learning
1. Introduction
1.1 Purpose
The CO₂ Emission Prediction System aims to estimate carbon dioxide 
emissions based on various factors such as fuel consumption, vehicle 
type, industrial activities, and other relevant parameters. The system 
utilizes machine learning techniques to provide accurate and efficient 
predictions to help stakeholders make informed environmental 
decisions.
1.2 Scope
The system will:
• Collect and preprocess relevant datasets for CO₂ emissions.
• Train and evaluate machine learning models to predict CO₂ 
emissions.
• Provide a user-friendly interface for inputting data and obtaining 
predictions.
• Generate reports and visualizations for analysis.
• Offer API support for integration with other applications.
Business Objective
• The fundamental goal here is to model the CO2 emissions as a 
function of several car engines features.
Data Set Details
The file contains the data for this example. Here the number of variables 
(columns) is 12, and the number of instances (rows) is 7385. In that way, this 
problem has the 12 following variables:
▪ make, car brand under study.
▪ model, the specific model of the car.
▪ vehicle_class, car body type of the car.
▪ engine_size, size of the car engine, in Litres.
▪ cylinders, number of cylinders.
▪ transmission, "A" for 'Automatic', "AM" for 'Automated manual', "AS" for 
'Automatic with select shift', "AV" for 'Continuously variable', "M" for 
'Manual'.
▪ fuel_type, "X" for 'Regular gasoline', "Z" for 'Premium gasoline', "D" for 
'Diesel', "E" for 'Ethanol (E85)', "N" for 'Natural gas'.
▪ fuel_consumption_city, City fuel consumption ratings, in litres per 100 
kilometres.
▪ fuel_consumption_hwy, Highway fuel consumption ratings, in litres per 100 
kilometres.
▪ fuel_consumption_comb(l/100km), the combined fuel consumption rating 
(55% city, 45% highway), in L/100 km.
▪ fuel_consumption_comb(mpg), the combined fuel consumption rating (55% 
city, 45% highway), in miles per gallon (mpg).
▪ co2_emissions, the tailpipe emissions of carbon dioxide for combined city 
and highway driving, in grams per kilometer
