# Ethical_Issues_for_AI
Fairness-Aware Credit Risk Prediction: An Analysis of Disparate Impact, Disparate Treatment, and Disparate Mistreatment Using the Credit Card Clients Dataset

This repository have a machine learning fairness analysis conduct on a credit risk prediction task. This project assess bias and ethical problem in predictive model using build fairness metrics like disparate impact, disparate treatment, and disparate mistreatment
the work is more designed for academic assessment and illustrate the responsible AI practices in financial decision making sysytem

## Project Overview
Machine learning models used in credit scoring can unintentionally discriminate against protected groups (e.g., gender, education, marital status).
this project investigates whether such biases exist and execute this model behavior across different demographics groups  

### Key objectives:
   * Build credit risk prediction models
   * Identify and quantify algorithmic bias
   * Compare fairness across multiple models
   * Support ethical AI decision-making

### Dataset
  * Dataset: Credit Card Clients Dataset
  * Target Variable: DEFAULT (credit default)
  * Protected Attributes:
     * Gender
     * Education Level
     * Marital Status
This dataset is widely used in fairness and bias research, making it suitable for ethical AI analysis.

## Models Used
The following machine learning models are implemented and compared:
  * Logistic Regression
  * Decision Tree
  * Random Forest
Each model is evaluated using both performance and fairness metrics.

## Fairness Metrics
The notebook evaluates fairness using three key concepts:
  * Disparate Impact (DI):
    Measures outcome imbalance between protected and unprotected groups.
  * Disparate Treatment:
    Assesses whether protected attributes directly influence predictions.
  * Disparate Mistreatment:
    * Compares error rates such as:
         * False Positive Rate (FPR)
         * False Negative Rate (FNR)
Fairness is analyzed separately for gender, education, and marital status.

## Exploratory Data Analysis (EDA)
EDA is used to:
    * Visualize demographic distributions
    * Analyze default rates across protected groups
    * Connect data imbalance with fairness metric outcomes
This strengthens the interpretation of bias results.

## Evaluation Criteria
Models are compared based on:
* Accuracy
* Disparate Impact values
* Group-wise FPR and FNR
* Ethical trade-offs between fairness and performance

## Key Takeaways
* High accuracy does not guarantee fairness
* Some models show clear disparities across demographic groups
* Fairness-aware evaluation is essential in financial ML systems

## Author
Nikhil Sojitra
