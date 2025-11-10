# DA5401 A8 — Ensemble Learning on Bike Share Data

##  Overview
This assignment explores the use of **Ensemble Learning** techniques to improve regression performance on the **Bike Sharing Demand** dataset from the UCI Machine Learning Repository.  

The goal is to predict the total count of hourly bike rentals (`cnt`) using environmental and temporal features.  
Three ensemble strategies are implemented and compared against simple baseline models to analyze how they reduce **bias** and **variance**.

## Learning Objectives
1. Understand the bias–variance trade-off in ensemble models.  
2. Implement three major ensemble methods using scikit-learn:
   - **Bagging** – reduces variance through bootstrap aggregation.
   - **Boosting** – reduces bias via sequential residual learning.
   - **Stacking** – combines diverse models through a meta-learner.
3. Evaluate models using **Root Mean Squared Error (RMSE)**.


