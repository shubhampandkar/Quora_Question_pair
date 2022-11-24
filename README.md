# Quora Question Pairs
### Description  
  
Quora is a platform where people ask questions as well as connect with other people who contribute with their insights and quality solutions.  
As this is a great tool, people who ask questions, expect quick answers. Incase the questions have been repeated mulitple times on quora, then answers to these questions can be retrieved easily.  
For such a scenario, it is important to identify the duplicate questions.  
This project is to predict whether a question on quora has a similar existing question pair.

> Kaggle Project

#### Problem Statement
* Identify which questions asked on Quora are duplicates of questions that have already been asked.  
* This could be useful to instantly provide answers to questions that have already been answered.  
* We are tasked with predicting whether a pair of questions are duplicates or not. 

### Business Objectives and Constraints
1. Cost of misclassification is high  
2. Threshold of choice. 
3. NO strict latency concerns
4. Interpretability is partially important

## Machine Learning Problem
* Binary Classification problem - We need to predict if questions are duplicate or not
1. Performance Metric  
    * log loss  
    * Binary confusion matrix
2. Train-Test Construction
    * Train and test will be built from the dataset by splitting it in 80:20 ratio
