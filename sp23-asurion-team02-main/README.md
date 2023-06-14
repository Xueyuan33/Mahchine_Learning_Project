# sp23-asurion-team02

## Business Problem
Asurion offers insurance for almost all the phone types available in the US.
Their phone insurance covers cracked phone screens, mechanical failures, loss & theft protection, water damage, local repairs and same day replacement.
We want to look specifically at the same day replacement service. Clients will first file a claim, then a new phone will be delivered the same day with every content in the old phone backed up. The new phone is shipped from the Asurion inventory warehouse and they want to be able to forecast the amount of
claims for the next few weeks to determine the optimum inventory levels and replenishment policy.This will help Asurion by reducing the inventory management cost.

## Goal
Develop forecasting models to accurately predict the iphone 14 claim volume for March, 2023.

## Data
Accre path to team folder: /data/p_dsi/teams2023/team2/asurion_data/

## Project Logisits
Project Board: https://github.com/orgs/dsi-teams-course/projects/10

In Person Meeting Location: 19th and Grand 

Sprint Meetings: Every Wednesday during class period (11:30am - 12:45pm)

Team Meetings: As needed via Zoom

Issues/Tasks: Due every Sunday 11:59PM 

Issue Reviews: Due every Tuesday 5PM 

Meeting Notes (Live Doc): https://docs.google.com/document/d/1BuBKqQZVtN2uryNC_wzu6WHyvZKds-HAoInFxsiwP50/edit 

Shared Drive:
https://drive.google.com/drive/folders/1QqAeMNBOSpnsRK_lYtIahX2-I8UrSOqu 

Communication: Slack Group ds5380_team02 (Expectation is to reply within half a day and proactively communicate) 

## Anticipated Timeline
Pre-Sprint: Generate questions for Client 

Sprint 1: Data Investigation + Cleaning + Data Augmentation (potentially?) 

Sprint 2: EDA  

Sprint 3: EDA done

Sprint 4: Feature Engineering + Model Selection 

Sprint 5: Modeling 

Sprint 6: Modeling done

Sprint 7: Hyperparameter tuning

Sprint 8: Presitation done and practiced

## Repository Breakdown
01_EDA: 
Initial exploratory data analysis of the data. This included a deeper dive at the trends of each iPhone models, non apple phone claims, seasonal trends, and feature exploration.

02_Data_Preprocessing_Feature_Eng: 
The features we needed for various models. We broke down the feature selection into two groups: one group of features for time series models and one group of features for tree based models. 

03_Modeling: 
Notebooks of which we tested various models within three main categories. These categories of models were: regressor models (Linear Regression), time series models (ARIMA and LSTM), and tree models (XGBoost and Random Forest).

