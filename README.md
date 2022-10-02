# Job-a-Thon-September-2021

## Problem Statement
Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs.

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities.

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc. 
Your task is to predict the store sales for each store in the test set for the next two months. 

## Objective
The main objective of the problem is to develop the machine learning approach to predict the store sales for each store in the test set for the next two months.

## ML Approach
After applying basic data preprocessing, I have tried few algorithms like Random forest algorithm and Gradient boosting algorithm etc. For final modeling I have used XGB Regressor algorithm.
The evaluation metric was 'MSLE * 1000'. This model gave a public leaderboard score of 228.56 and a private leaderboard score of 226.93.

## Final Result
Private Leaderboard Rank - 152

Public Leaderboard Rank - 317
