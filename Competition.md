---
layout: page
permalink: /Competition/index.html
title: Competitions
---
*I am honored that you would be interested in my experience with mathematical modeling and data mining competitions!*<br>
## Introduction
   During my college years, as a team leader, **I completed a total of 12 mathematical modeling and data mining competitions**, accumulated a rich programming foundation and cultivated the ability of mathematical modeling. In my sophomore year, I founded the first competition-based organization in our university - AI Second Class. In the coming year, I led the organization members to **win more than 80 National or Global Awards**, with more than 3 awards per organization members.<br>
***I have selected some of the results I have achieved from the competitions I have entered.***

## Selected Competitions

### Sailboat Price Prediction Model - XGBoost Based on SA Split Strategy.
***Competition**: Mathematical Contest In Modeling-2023*<br>
***Brief overview of competition problems***：<br>
Model sailboat price forecasts and analyze the impact of regional economic factors on sailboat price fluctuations.<br>
***problems-solving strategy***：<br>
First, I change the strategy of selecting features when constructing sub-models in XGBoost to the SA algorithm-based approach and compare the effects of XGBoost and the Improved SA-XGBoost.<br>
<img src="/images/FIG_MCM2-1.png">
Second, I compare our model with the rest of the integrated learning or deep learning models.<br>
<img src="/images/FIG_MCM2-2.png">
Ultimately I used SHAP values, PDP analysis, and ICE plots to explain the conclusions drawn from the Improved SA-XGBoost model. <br>
<img src="/images/FIG_MCM2-3.png">

### Bitcoin and Gold Price Prediction - EEMD Based Machine Learning Algorithm
***Competition**: Mathematical Contest In Modeling-2022*<br>
***Brief overview of competition problems***：<br>
Construct a price prediction model for Bitcoin and gold and propose a trading strategy model to maximize the gains.<br>
***problems-solving strategy***：<br>
First, To address the fact that the number of IMFs obtained from EEMD decomposition of time-series data is usually inconsistent, the problem leads to difficulties in extrapolating predictions from EEMD models. I propose to cluster the IMFs before prediction, as follows:<br>
<img src="/images/FIG_MCM1-flowchat&decomposition.png">

Second,The prediction effects we obtain on this basis are as follows，The prediction error of our model is 12% lower than LSTM and 7% lower than CNN.<br>
<img src="/images/FIG_MCM1-p1p2.png">
Ultimately my teammates built financial and mathematical trading models based on my predictions, which resulted in a staggering gain of over $1000w!<br>
<img src="/images/FIG_MCMC1-Opt_functions.png">

### Reflective Panel Adjustment Model of China's Sky Eye(FAST)
***Competition**: Contemporary Undergraduate Mathematical Contest in Modeling(CUMCM)-2021*<br>
***Brief overview of competition problems***：<br>
Constructing reflective panel conditioning model and signal reflection model to maximize the efficiency of receiving and reflecting signals from China's sky eye.<br>
***problems-solving strategy***：<br>
First,I take the minimum radial Manhattan distance sum as the optimization objective, and use the grid search method to determine the focal length parameter of the paraboloid.The optimal paraboloid is finally determined.<br>
<img src="/images/FIG_CUMCM-FIG1_Fumula.png">
Second，I take the maximization of the affinity between the reflective surface and the ideal paraboloid as the criterion, and the minimization of the standard deviation of the angle between the line of The standard deviation of the angle between the corresponding nodes and the origin is minimized as the optimization goal, and the improved simulated annealing algorithm is used to solve the optimization of the 665 nodes to be adjusted. <br>
<img src="/images/FIG_CUMCM-FIG2.png">
Ultimately we modeled the signal reflection.<br>
<img src="/images/FIG_CUMCM-FIG3.png">

### Edge detection for industrial devices<br>
***Competition**: 11th Asia Pacific University Mathematical Contest in Modeling(APMCM)-2021*<br>
***Brief overview of competition problems***：<br>
Constructing an industrial device for edge detection and labeling edges of different curvatures with different colors.<br>
***problems-solving strategy***：<br>
First, I denoised the industrial device images given by the competition, and at the same time constructed a camera calibration model using opencv to obtain the physical parameters of the camera.<br>
<img src="/images/FIG_APMCM-FIG1_denoise_biaoding.png">
Second, I constructed the edge detection model.<br>
<img src="/images/FIG_APMCM-FIG2.png">
Ultimately I used the cohesive hierarchical clustering algorithm and halcon to label the edges of different curvatures with different colors.<br>
<img src="/images/FIG_APMCM-FIG3.png">

---
**END**<br>
*If you have any questions please email me!*


