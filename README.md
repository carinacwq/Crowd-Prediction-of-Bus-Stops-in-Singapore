# Crowd Prediction of Bus Stops in Singapore

## Project Motivation
Public transportation systems, such as buses, are integral to urban mobility, particularly in densely populated countries like Singapore. Understanding and predicting the usage trends and patterns at bus stops can aid in the optimisation of bus schedules, improve service reliability and enhance the overall commuter experience.

## Project Description
This project aims to create a machine learning-based system that accurately predicts the expected passengers waiting at a bus stop at a particular time in Singapore, enabling authorities and planners to make informed data-driven decisions on bus stop crowd control. This includes leveraging historical data of different bus stops, including information such as tap-in-tap-out passenger volume, day of the week, public holidays.

## Proposed Solution
Data Collection: Data is collected from the Singapore Land Transport Authority’s (LTA) API, which includes passenger counts, bus stop locations and other relevant factors.  
Feature Engineering: Extract meaningful features such as the day of the week, and time of the day from the collected data  
Model Selection and Training: Explore and select appropriate machine learning models and algorithms such as Random Forest, Gradient Boosting and Long Short-term Memory (LSTM) for crowd prediction by training the data on the models. Benchmark using the linear regression model.   
Evaluation Metrics: Access model performance using suitable metrics like Mean Square Error, F1 score, AUC-ROC.  
Prediction and Visualisation: Deploy the trained models to make predictions of passenger volume at bus stops on new data. Visualise the crowd levels on a map interface.

## Project Milestones 
Milestone 1 - Data Processing:
Data collection from the web using LTA  API. Exploratory data analysis and visualisation to gain insights. Pre-processing of data to prepare clean data.  
Milestone 2 - Data Analysis of passenger volume using model development and training:
Develop ML models. Split data into training and testing sets. Train models.  
Milestone 3 - Model Testing:
Evaluate model performance against testing data. Fine-tune hyperparameters such as batch size, tree depth, specific to chosen model. Compare different model performance.  
Milestone 4 - Model Deployment:
Deploy trained models to make real-time predictions of passenger volume.  
Milestone 5 - Present results:
Analysis of results. Presentation of project end-to-end. Propose potential improvements. 
