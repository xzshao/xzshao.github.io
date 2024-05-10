---
layout: page
permalink: /research/index.html
title: research
---

*I appreciate your interest in my research so far and look forward to doing more valuable research with you in the future!!*

## Introduction


## All research projects
### Loan Default Prediction: Adjust-Adacost Model Based on Imbalance Data
**Cost-sensitive learning** is a class of models that biases losses by assigning different misclassification costs (defaults classified as nondefaults and nondefaults classified as defaults) to different misclassification categories. This makes the model correct for unbalanced data.<br>
Cost-sensitive learning can significantly improve the performance of machine learning models on **imbalanced data**. I introduced cost-sensitive learning in the adaboost model, construct a cost-sensitive function that is continuously adjusted as the model is trained, and mathematically derive the optimal solution of the model's sample weights for this training process, the form of the analytical solution of the optimal solution of the model's weights. Furthermore, demonstrate that the upper bound of the proposed model's error is controlled near 0 (almost equal to 0) through error ana.

<img src="/images/p1.png" > 

**I propose that the adjust-adacost model outperforms all baseline models and compares favorably to cost-sensitive machine learning models**


### Time Series Prediction: Machine Learning Models Based on Rolling-ICEEMDAN Methods
The usual EMD,EEMD,ICEEMDAN etc. methods of prediction after temporal decomposition (One-Dimensional->Higher-Dimensional) are almost always wrong because of serious data leakage problems, so the predictions obtained are very good. My research group and I proposed **Rolling-ICEEMDAN Methods**, which is an adaptive **decomposition-prediction-fusion** scheme that solves the data leakage problem well and also shows good performance.
<img src="/images/p2.png" > 


### Solid-state Diffusion Coefficient Correction for Lithium Batteries: a High-Performance Parallel Simulated Annealing Algorithm
Simulated annealing algorithm (SA) has a strong global optimization ability, but SA is serialized algorithm, it cannot converge quickly in a short time on engineering problems with long single-step computation time, it is easy to fall into the local optimum, I greatly improve the optimization ability of SA by adding the techniques of **rewarming**, **adaptive annealing**, **randomly selecting the sampler**, **Lévy flight sampling**, and **exponentially distributing the samples** in simulated annealing algorithm, and I finally **parallelize** SA.

<img src="/images/HIGH_SA.png" > 


### SOH Prediction for Lithium Batteries: An Improved LSTM model Based on Seq2Seq
SOH prediction of lithium batteries is a very hot topic in recent years, and has an important position in the BMS system, but 90% of the existing research is to predict only one point in the future through historical data, and the error is higher, I have been working on the algorithm development for about two months for this problem, and finally constructed a high-performance SOH prediction model, which can predict 80% of the future SOH changes by inputting 20% of the data, and can also flexibly input n SOH data points to predict the future m SOH data points(*the prediction accuracy is shown in the CV or Publication*).
<img src="/images/SOH_LSTM2.png" > 

### Exploration of High-Performance Large Sparse Matrix Solvers
Solving large sparse matrices is a performance bottleneck often encountered in the field of computational fluid dynamics (of course, it is also very common in the field of AI Algorithm). For example, COMSOL uses pardiso is a high-performance sparse matrix solver, the direct solver has a very high accuracy, but often in the process of large sparse matrices is very slow or can not be calculated, the iterative solver is to lose accuracy through the loss of make large sparse matrices to be solved.
I spent about a month exploring almost all high-performance solver frameworks, and also accumulated more development experience, including ***PARDISO, CUPY, JAX, TAICHI, PETSc, AMGX***, etc.. Finally, I improved the computational performance of a process algorithm by nearly two orders of magnitude.

---
*Due to some technical terms, I can't provide project details for the last three projects, so if you're interested, please contact me at my email and maybe we can set up a meeting to talk about it together!*
<br>

---
**END**
