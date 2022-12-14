# Air Passengers 


## Project Intro
The purpose of this project is to use time series algorithms to find and predict patterns of the data.

### Methods Used
* Data Preparation
* Time Series Decomposition
* Visualization

### Technologies
* [Python](https://www.python.org/)
* [Matplotlib](https://matplotlib.org/)
* [Pandas](https://pandas.pydata.org/)
* [Statsmodels](https://www.statsmodels.org/stable/index.html)

## Project Description
The Airpassengers dataset contains the number of passengers each month throughout different years from 1949 untill 1960. Decomposition provides a useful abstract model for thinking about time series generally and for better understanding problems during time series analysis and forecasting.

As it is shown in the graph the number of passengers is increasing over time but there is a dramatic seasonal shift.

![here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/Air_Passengers/Dataset_plot.png)

With the use of seasonal decomposition the linear trend going up has been seperated from the seasonal variation.


Additive model on the left and Multiplicative model on the right:


![here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/Air_Passengers/Plot_additive.png)   ![here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/Air_Passengers/plot_multiplicative.png)


## Getting Started

1. Download and install python on your computer
2. Make sure to install libraries that have been mentioned before in the 'Technologies' section of the text, if you don't already have them
3. You can either directly download this repo or clone it (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)) 
4. Airpassengers dataset is stored [here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/Air_Passengers/AirPassengers.csv)
5. Data transformation script is being kept [here](https://github.com/Unisepp/Data_Mining_Exercises/blob/main/Air_Passengers/AirPassengers.py)
6. Run the code in python and see the results
