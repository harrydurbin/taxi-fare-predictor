## taxi-fare-predictor

A regression model to predict ride fares based on past ride data.

The inputs used to predict fares were: <br/>
•	Origin coordinates – latitude and longitude at the start <br/>
•	Destination coordinates – latitude and longitude at the end <br/>
•	Departure time – the hour and minutes after midnight <br/>
•	Passengers – how many people are in the taxi <br/>
•	TAZ origin – transportation analysis zone at the start <br/>
•	TAZ destination -- transportation analysis zone at the end <br/>

The optimum model had a RSME of $2.36. 
Random Forests were found to be more accurate with n-estimators = 80 and max_depth = 20.
