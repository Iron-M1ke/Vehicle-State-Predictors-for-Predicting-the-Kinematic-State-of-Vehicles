# Vehicle-State-Predictors-for-Predicting-the-Kinematic-State-of-Vehicles
Uses: Linear Regression, Random Forest (Regression), Neural Networks &amp; Places Predicted Vessel Positions on a Map.

Notebooks are used to predict vessel (ship) locations in terms of cartesian coordinates based on it's features and tuned based on the model's hyperparameters. The predicted coordinates are then imposed onto a map for visualisation purposes. 

Paper Abstract:
This thesis aims to address questions related to predicting the kinematic state of vehicles using satellite products. This study investigates the feasibility of predicting a vehicle’s kinematic trajectory from satellite products and satellite-enabled data then assessing the results of various models. The study of traditional statistical approaches compared to machine learning methods was conducted, comparing the performance of traditional methods such as linear regression and random forest regression to traditional neural networks. 

A preliminary study was also conducted comparing the usefulness of various GNSS constellations, accessing accuracy and precision of each GNSS constellation.

In order to fulfil the objectives of this thesis publicly available data was taken from reputable and official data sources including the European Commision and the French Naval Academy. The availability of maritime data meant that the implementation phase of this study focused on maritime vehicles. This data is then appropriately preprocessed ready for the implementation of three prediction models: linear regression, random forest regressor and a traditional neural network. 

Results were analysed based on various evaluation metrics, numerical analysis and residual graph interpretations. Findings indicated that there was varied performance and quality from each model. The random forest approach yielded results implying it was the most effective predictor model for maritime data based on analysis of evaluation metrics and the interpretation of residual graphs. By contrast, the neural network produced results showing it struggled to fit the data, particularly with the production of a negative R2-score.

The conclusion of this thesis demonstrates the usefulness of satellite products in conjunction with other data sources in order to demonstrate the validity and feasibility of performing trajectory predictions for the kinematic state of a vehicle. Providing insight into which models may be best appropriate as well as producing interpretations regarding how good a model may fit data.
