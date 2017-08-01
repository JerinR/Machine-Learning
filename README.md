# New-York-taxi-ride
EDA of the New York yellow cab drive dataset of 2016 from kaggle. It has train and test data sets with the following data fields

| Data fields |	Explanation |
| ----------- | ----------- |
| id	| a unique identifier for each trip |
| vendor_id	| a code indicating the provider associated with the trip record |
| pickup_datetime	| date and time when the meter was engaged |
| dropoff_datetime	| date and time when the meter was disengaged |
| passenger_count	| the number of passengers in the vehicle (driver entered value) |
| pickup_longitude | the longitude where the meter was engaged |
| pickup_latitude	| the latitude where the meter was engaged |
| dropoff_longitude	| the longitude where the meter was disengaged |
| dropoff_latitude | the latitude where the meter was disengaged |
| store_and_fwd_flag | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip |
| trip_duration | duration of the trip in seconds |

## How to install gmaps for jupyter notebook?
You can install using [pip] or [conda]

## Installing XGBoost
You can install using [conda install]

[pip]:https://pypi.python.org/pypi/gmaps/0.1.6
[conda]:https://anaconda.org/conda-forge/gmaps
[conda install]: https://anaconda.org/conda-forge/xgboost 

## Animation of pick up and drop off data
y-axis -> Longitude,
x-axis -> Latitude
![](https://github.com/JerinR/New-York-taxi-ride/blob/master/Animation/im.gif)
