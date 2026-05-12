Project Overview

This project builds a custom Linear Regression model entirely from scratch using Python. It includes Lasso (L1) and Ridge (L2) regularization to improve predictions and prevent overfitting.


The Data

We used the California Housing dataset. Before training, the data was scaled (standardized) so that all features—like house age, rooms, and population—are treated equally by the model.

Results

Ridge (L2) performed slightly better, getting a lower Mean Squared Error (0.58) compared to Lasso (0.61) on the test data.

The training graphs show a steep, quick drop in loss, meaning our custom model successfully learned and minimized errors rapidly.

How the Regularization Worked
The final weights show exactly how L1 and L2 differ:

Lasso (L1) acts like a filter: It shrank the weights of less important features (like Population and AveRooms) all the way to zero, keeping only the strongest predictors.

Ridge (L2) shrinks everything: It kept all the features in the equation but shrank their sizes to prevent any single feature from overpowering the model.
