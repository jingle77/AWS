# Predict Housing Prices with Sagemaker Canvas

## Project
Sagemaker Canvas is an AWS service that allows the end user to build a machine-learning model with no code. It is a practical way for someone with little to no experience with machine learning to get started and/or experience Data Scientists and Machine Learning Engineers to quickly build a model. In this project, we will utilize one of the sample datasets in Sagemaker Canvas to build a model that predicts housing prices.

#### Create a new model
We will start by creating a new model and will give it a practical name.
![image](https://github.com/jingle77/AWS-Projects/blob/5575d6057e1333734df9533438aa9d80b64eac52/sagemaker-canvas-housing-price-prediction/Create%20New%20Model.PNG)

#### Select sample dataset
We will select the sample housing dataset from the below options. Note that you can also upload your own data. 
![image](https://github.com/jingle77/AWS-Projects/blob/5575d6057e1333734df9533438aa9d80b64eac52/sagemaker-canvas-housing-price-prediction/Select%20Dataset.PNG)

#### Build Model
Select your target column and build the model. In this case, our target is the median_house_value
![image](https://github.com/jingle77/AWS-Projects/blob/5575d6057e1333734df9533438aa9d80b64eac52/sagemaker-canvas-housing-price-prediction/Build%20Model.PNG)

#### Evaluate Performance
After a few minutes, the model has been trained and we can evaluate the performance.
![image](https://github.com/jingle77/AWS-Projects/blob/main/sagemaker-canvas-housing-price-prediction/model%20performance.PNG)

#### Predict on new data
After building a model, we can make predictions with new data. Note that you have the option to predict on a single value or do a batch prediction.
![image](https://github.com/jingle77/AWS-Projects/blob/main/sagemaker-canvas-housing-price-prediction/Single%20Prediction.PNG)

#### Create a new model recipe with log transformations
Canvas allows the end user to make multiple versions of a model. We will make a new version that include log transformations on the numerical features that show a skew.
![image](https://github.com/jingle77/AWS-Projects/blob/main/sagemaker-canvas-housing-price-prediction/Model%20Recipe.PNG)
