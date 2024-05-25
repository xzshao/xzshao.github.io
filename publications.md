---
layout: page
permalink: /publications/index.html
title: Publications
---


## Papers & Publications 
**A Dynamic Cost-Adjusted Adacost Model for Credit Prediction of Smallholder Farmers	(Under Review)**
<br>JOURNAL: Energy,**IF:9**,**JCR Q1**
<br>**First author**
- In order to enhance the model’s ability to capture the information present in both the seasonal and trendcyclical part of the time series, we have implemented two modifications to the baseline model. 1. In order
to embed temporal information, the model presented in this paper employs the Time2Vec module, which replaces the rule-based temporal information embedding utilized in the baseline model. The sine/cosine-based
function of Time2Vec is capable of more effectively capturing periodic information, and a greater degree of
periodic information is extracted at the input stage of the model, which reduces the difficulty of the model in
capturing periodic features.2. We propose an embedding module for time series decomposition. This module
extracts the periodic and trend terms of the time series using the moving average method. Furthermore, each
step of the attention in the encoder and decoder computation is followed by seasonal term decomposition of
the output of the hidden layer. This is conducive to improving the model’s ability to recognize seasonal and
trend-cyclical part.
- To address the issue of inefficiency in processing long time series, we propose the probabilistic sparse selfattention mechanism as a replacement for the autocorrelation module of Autoformer. This modification
significantly reduces the computational time of the attention mechanism in the model, enabling it to more
effectively extract key information.
- A comprehensive comparison of multiple models and datasets was conducted to validate the efficacy of the
proposed model. Additionally, a detailed ablation study was performed to ascertain the significance of each
module in the model
  
**A Dynamic Cost-Adjusted Adacost Model for Credit Prediction of Smallholder Farmers	(Under Review, Revise)**
<br>JOURNAL: International Journal of Forecasting,**IF:7.9**,**JCR Q1**
<br>**Co-First author & Corresponding author**
- I proposed a **dynamically adjusted cost-sensitive matrix**, resulting in an exponential growth of misclassification costs for defaulting samples during the training process. As the model advances in its training, it acquires a more comprehensive understanding of the characteristics of defaulting samples, leading to a substantial reduction in the misclassification rate of defaulting samples.
- Through rigorous mathematical theory, I conducted a formal derivation and proof to establish the effectiveness of the exponentially growing cost-sensitive matrix during the training process. The model's training process is characterized by an exponential rate of error reduction. Error analysis unveiled that the misclassification rate of the proposed model is confined to a range asymptotically approaching zero.
- I modified the AdaBoost algorithm code in scikit-learn to develop the Adjust-Adacost algorithm for this study. Using a real dataset from a commercial bank in China involving loans to famer, I compared the Adjust-Adacost model with the Adacost and AdaBoost models. Additionally, I compared it with other cost-sensitive algorithms like Cost-Sensitive Random Forest (CS-RF), Cost-Sensitive XGBoost (CS-XGBoost), Cost-Sensitive Support Vector Machine (CS-SVM), and Cost-Sensitive Decision Trees (CS-DT). The results showed that the Adjust-Adacost model significantly outperformed the others, **with an AUC improvement of over 20% compared to Adacost and more than 10% compared to the other cost-sensitive algorithms**.
- I conducted extensive experiments on international public datasets such as UCI and KEEL, and the results consistently demonstrated that the proposed Cost-**Adjusted Adacost model outperformed other cost-sensitive machine learning models**.

**Based on Adaboost Algorithm for Loan Default Prediction Model 	(Published)**
<br>JOURNAL: Journal of China Emergency Management Science,May. 2023
<br>**First author**	
- I constructed an Adaboost model and conducted empirical analysis on a loan dataset from a commercial bank in China. The empirical analysis confirmed the superior performance of the Adaboost model in default prediction compared to other ensemble learning methods.
  
**Predicting China's Thermal Coal Price: Does Multivariate Decomposition-Integrated Forecasting Model with Window Rolling Work?	(Under review)**
<br>JOURNAL: Resources Policy, **IF:10.2**,**JCR Q1**
<br>Fourth author	
- I propose **rolling ICEEMDAN theory** for time series prediction of the average coal price index in China's Bohai Rim region, which decomposes the time series data into multimodal modes and trains the prediction by neural network model for the sub-modal modes respectively.
- I constructed LSTM,TCN,CNN time-series combination prediction model, and **the final error was reduced by more than 7% compared to the neural network model without time-series data decomposition**.
<br>



