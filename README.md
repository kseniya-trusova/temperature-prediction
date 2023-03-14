# Description
This repository is the contribution to the Xtreme Weather Forecasting challenge organized by Omdena AI Silicon Valley Chapter.  

General project link: https://github.com/OmdenaAI/silicon-valley-chapter-extreme-weather

Corresponding Kaggle competition: https://www.kaggle.com/competitions/widsdatathon2023 

The final presentation: https://youtu.be/JeeT20i2diI 

The repository contains the literature review of models applying for the temperature prediction problem and the notebook including EDA and LSTM model.
# Challenge details
In this 4-week project, the team modeled data to predict the arithmetic mean of the maximum and minimum temperature over the next 14 days for each location and start date for longer-term weather forecasting to help communities adapt to extreme weather events caused by climate change.

The team used a pre-prepared dataset consisting of weather and climate information for several US locations, for many start dates for the two-week observation, as well as the forecasted temperature and precipitation from several weather forecast models. Each row in the data corresponds to a single location and a single start date for the two weeks.

RMSE was given as a model evaluation metric.
# Literature review
The literature review was accomplished to learn what models are used by other researchers solving the temperature prediction problem. The most popular model was LSTM. Therefore, this model was considered to solve the problem. Some LSTM tutorials were found to start the modeling step. 

The review contains articles, tutorials and LSTM models configurations from the articles.
# Model development and evaluation
The file includes the following steps:
1. Some EDA based on the team findings. The domain expert of the team (meteorologist) provided recommendations about features value. Then the team continued to work with remaining features.
2. The modeling stage based on the literature review findings. 

The different configurations of LSTM architecture were considered. Nevertheless, the validation loss function was higher than the training loss for any combination that means the model was underfitting. At the same time, the model did not give an absolute error less than 4 Celsius degrees.

Returning to the feature selection step and working on the locations and dataset size can be considered as possible improvements.
