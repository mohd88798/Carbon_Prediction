# Carbon_Prediction 

## Introduction
This project proposes the development of a CO2 Emission Pattern Detection system that utilizes 
machine learning and deep learning algorithms to predict and analyze carbon levels based on historical data of 
global CO2 emissions, country-wise CO2 emissions, and sector-wise CO2 emissions. The 
system is designed to predict carbon levels and current carbon levels using RNN, LSTM and Regression 
algorithm, which is known for its ability to predict data. The predicted carbon levels 
are displayed through graphical representations, allowing users to easily visualize and 
understand the data.

## ibrary used
1. Pandas
2. Numpy
3. Plotly_Express
4. Sklearn
5. Keras

## Flow Chart
![image](https://user-images.githubusercontent.com/73273004/231633065-fd133398-da56-4328-b872-4df7c4e9773d.png)

## Data Set Specification:
Historical data of world CO2 emissions from 1750-2021.
Country-specific data of CO2 emissions from 1950-2021
Country Names data for Filtering 

## Algorithm 
LSTM
1. Import the necessary libraries for data manipulation and LSTM modeling
2. Load the historical CO2 emissions data into a pandas dataframe
3. Split the data into training and testing sets
4. Normalize the training and testing data
5. Reshape the training and testing data to be compatible with the LSTM model
6. Build the LSTM model with the following layers:
7. a. LSTM layer with a specified number of units
8. b. Dense layer with one output unit
9. Compile the model with the following parameters:
10. a. Loss function - mean squared error
11. b. Optimizer - adam
12. Fit the model on the training data
13. Predict CO2 emissions on the testing data
14. De-normalize the predicted CO2 emissions
15. Show the graph of Actual and Predicted data

## Result
### World CO2 Emission Pattern
![image](https://user-images.githubusercontent.com/73273004/231635122-db57ce5b-98d6-4923-8f44-dd81f871ce05.png)

### Top 10 Country CO2 Emission Pattern
![image](https://user-images.githubusercontent.com/73273004/231635595-88970d52-f36e-4ef3-b4c7-ecd4fec1eaa1.png)

### World CO2 Map 
![image](https://user-images.githubusercontent.com/73273004/231635712-7937ccad-1b76-4231-bf60-448800eea14a.png)

### Actual vs Predicted CO2 Emission for India using LSTM
![image](https://user-images.githubusercontent.com/73273004/231636016-ebc5d065-32a1-4e51-9ba8-022031d05efa.png)
