---
layout: page
permalink: /Competition/index.html
title: Competitions
---
# Introduction
*I am honored that you would be interested in my experience with mathematical modeling and data mining competitions!*
During my college years, as a team leader, **I completed a total of 12 mathematical modeling and data mining competitions**, accumulated a rich programming foundation and cultivated the ability of mathematical modeling. In my sophomore year, I founded the first competition-based organization in our university - AI Second Class. In the coming year, I led the organization members to **win more than 80 national or global awards**, with more than 3 awards per organization members.
I have selected some of the results of the competition to show you.

# Selected Competitions
## Sailboat Price Prediction Model - XGBoost Based on SA Split Strategy.
*Competition: Mathematical Contest In Modeling-2023*
*Brief overview of competition problems*：
Model sailboat price forecasts and analyze the impact of regional economic factors on sailboat price fluctuations.
*problems-solving strategy*：
First, we change the strategy of selecting features when constructing sub-models in XGBoost to the SA algorithm-based approach and compare the effects of XGBoost and the Improved SA-XGBoost.
**FIG_MCM2-1**
Second, we compare our model with the rest of the integrated learning or deep learning models.
**FIG_MCM2-2**
Ultimately I used SHAP values, PDP analysis, and ICE plots to explain the conclusions drawn from the Improved SA-XGBoost model. 
**FIG_MCM2-3**

## Bitcoin and Gold Price Prediction - EEMD Based Machine Learning Algorithm
*Competition: Mathematical Contest In Modeling-2022*
*Brief overview of competition problems*：
Construct a price prediction model for Bitcoin and gold and propose a trading strategy model to maximize the gains.
*problems-solving strategy*：
First, To address the fact that the number of IMFs obtained from EEMD decomposition of time-series data is usually inconsistent, the problem leads to difficulties in extrapolating predictions from EEMD models. I propose to cluster the IMFs before prediction, as follows:
**FIG_MCM1-flowchat&decomposition**
Second,The prediction effects we obtain on this basis are as follows，The prediction error of our model is 12% lower than LSTM and 7% lower than CNN
**FIG_MCM1-p1p2**
Ultimately my teammates built financial and mathematical trading models based on my predictions, which resulted in a staggering gain of over $1000w!
**FIG_MCMC1-Opt_functions**

## Reflective Panel Adjustment Model of China's Sky Eye(FAST)
*Competition: Contemporary Undergraduate Mathematical Contest in Modeling(CUMCM)-2021*
*Brief overview of competition problems*：
Constructing reflective panel conditioning model and signal reflection model to maximize the efficiency of receiving and reflecting signals from China's sky eye.
*problems-solving strategy*：
First,I take the minimum radial Manhattan distance sum as the optimization objective, and use the grid search method to determine the focal length parameter of the paraboloid.The optimal paraboloid is finally determined.
**FIG_CUMCM-FIG1_Fumula**
Second，I take the maximization of the affinity between the reflective surface and the ideal paraboloid as the criterion, and the minimization of the standard deviation of the angle between the line of The standard deviation of the angle between the corresponding nodes and the origin is minimized as the optimization goal, and the improved simulated annealing algorithm is used to solve the optimization of the 665 nodes to be adjusted. 
**FIG_CUMCM-FIG2**
Ultimately we modeled the signal reflection.
**FIG_CUMCM-FIG3**

## Edge detection for industrial devices
*Competition: 11th Asia Pacific University Mathematical Contest in Modeling(APMCM)-2021*
*Brief overview of competition problems*：
Constructing an industrial device for edge detection and labeling edges of different curvatures with different colors.
*problems-solving strategy*：
First, I denoised the industrial device images given by the competition, and at the same time constructed a camera calibration model using opencv to obtain the physical parameters of the camera.
**FIG_APMCM-FIG1_denoise_biaoding**
Second, I constructed the edge detection model.
**FIG_APMCM-FIG2**
ultimately I used the cohesive hierarchical clustering algorithm and halcon to label the edges of different curvatures with different colors.
**FIG_APMCM-FIG3**

---
**END**
*If you have any questions please email me!*


