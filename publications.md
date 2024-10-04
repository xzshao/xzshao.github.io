---
layout: page
permalink: /publications/index.html
title: Publications
---


## Papers & Publications 
**ISFormer:Improved Seasonal Transformer for Power Load Forecasting(Under Review)**
<br>JOURNAL: Energy,**IF:9**,**JCR Q1**
<br>**First author**
**Abstract:** There is an urgent need for intelligent systems to drive the development of global power systems. We
propose a high-precision and high-efficiency time-series prediction model, ISFormer, for short-term
high-granularity prediction of power systems based on the state-of-the-art Transformer architecture.
Previous models are based on the auto-correlation sequence-attention mechanism, however, is inef-
ficient and heavily reliant on the sample size at the sequence level. In this paper, we incorporate
the highly efficient distillation-attention mechanism and the time-sequence decomposition module
as our Transformer model kernel. The Time2Vec module is employed as the temporal information
embedding module of the model, which enhances the predictive performance and seasonal capture
ability of the model. The predictive efficacy of four distinct prediction granularities was evaluated
on four public datasets. On average, ISFormer exhibited a reduction in MSE and MAE of over 10%
compared to the existing SOTA model. The efficacy and significance of each module proposed in
this paper were assessed through comprehensive ablation experiments. In terms of time efficiency,
ISFormer demonstrated a reduction in MSE and MAE of over 30% compared to the SOTA model in
each prediction task.
Keywords: Transformer · Power Forecasting · Autoformer · Time2Vec · Distillation Attention Mechanism  

**A Dynamic Cost-Adjusted Adacost Model for Credit Prediction of Smallholder Farmers	(Under Review, Revise)**
<br>JOURNAL: Journal of Forecasting,**JCR Q1**
<br>**Co-First author & Corresponding author**
- I proposed a **dynamically adjusted cost-sensitive matrix**, resulting in an exponential growth of misclassification costs for defaulting samples during the training process. As the model advances in its training, it acquires a more comprehensive understanding of the characteristics of defaulting samples, leading to a substantial reduction in the misclassification rate of defaulting samples.
- Through rigorous mathematical theory, I conducted a formal derivation and proof to establish the effectiveness of the exponentially growing cost-sensitive matrix during the training process. The model's training process is characterized by an exponential rate of error reduction. Error analysis unveiled that the misclassification rate of the proposed model is confined to a range asymptotically approaching zero.
- I modified the AdaBoost algorithm code in scikit-learn to develop the Adjust-Adacost algorithm for this study. Using a real dataset from a commercial bank in China involving loans to famer, I compared the Adjust-Adacost model with the Adacost and AdaBoost models. Additionally, I compared it with other cost-sensitive algorithms like Cost-Sensitive Random Forest (CS-RF), Cost-Sensitive XGBoost (CS-XGBoost), Cost-Sensitive Support Vector Machine (CS-SVM), and Cost-Sensitive Decision Trees (CS-DT). The results showed that the Adjust-Adacost model significantly outperformed the others, **with an AUC improvement of over 20% compared to Adacost and more than 10% compared to the other cost-sensitive algorithms**.
- I conducted extensive experiments on international public datasets such as UCI and KEEL, and the results consistently demonstrated that the proposed Cost-ML Model，**Adjusted Adacost model outperformed other cost-sensitive machine learning models.**

**Based on Adaboost Algorithm for Loan Default Prediction Model (Published)**
<br>JOURNAL: Journal of China Emergency Management Science,May. 2023
<br>**First author**	
- I constructed an Adaboost model and conducted empirical analysis on a loan dataset from a commercial bank in China. The empirical analysis confirmed the superior performance of the Adaboost model in default prediction compared to other ensemble learning methods.
  
**Predicting China's Thermal Coal Price: Does Multivariate Decomposition-Integrated Forecasting Model with Window Rolling Work?	(Minor revise)**
<br>JOURNAL: Resources Policy, **IF:10.2**,**JCR Q1**
<br>Fourth author	
- I propose **rolling ICEEMDAN theory** for time series prediction of the average coal price index in China's Bohai Rim region, which decomposes the time series data into multimodal modes and trains the prediction by neural network model for the sub-modal modes respectively.
- I constructed LSTM,TCN,CNN time-series combination prediction model, and **the final error was reduced by more than 7% compared to the neural network model without time-series data decomposition**.
<br>



