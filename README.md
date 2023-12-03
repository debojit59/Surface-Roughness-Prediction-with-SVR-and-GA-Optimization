# Surface-Roughness-Prediction-with-SVR-and-GA-Optimization
Predicting Mg Sic surface roughness using SVR and optimizing parameters with GA. Enhance accuracy, improve machining outcomes. Code and dataset available for exploration on GitHub.
Objective:
This project aims to predict the surface roughness of Mg Sic using Support Vector Regression (SVR) and optimize the SVR parameters using Genetic Algorithm (GA). The goal is to enhance the accuracy of surface roughness predictions and improve the model's performance through parameter tuning.

Description:
The project involves the following key steps:

Data Loading and Preprocessing:

The dataset (svr-exp-new.csv) is loaded, containing experimental data for Mg Sic surface roughness.
Data is split into features (X) and target variable (y).
A train-test split is performed for model evaluation.
Support Vector Regression (SVR):

Initial SVR model is trained using default parameters.
Predictions are made on the test set, and the model's R2 accuracy is evaluated.
Genetic Algorithm Optimization:

A GA is employed to optimize SVR parameters (C, epsilon, gamma) for better performance.
The objective function for GA is mean squared error between actual and predicted surface roughness.
Optimized SVR Model:

The SVR model is retrained with the optimized parameters obtained from GA.
Predictions are made with both the original and optimized SVR models.
Performance Evaluation and Visualization:

R2 accuracy is calculated for the original SVR model.
Optimized SVR parameters and their performance are printed.
Surface roughness predictions are visualized using a plot with original and optimized parameter predictions.
Conclusion:
The project demonstrates the effectiveness of SVR and the improvement achieved through GA optimization. The optimized model provides more accurate predictions of Mg Sic surface roughness, contributing to better machining outcomes.
