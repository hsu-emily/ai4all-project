# (UPDATE IN README.md) Project Title

Predicting Adverse Effects of Drug Interactions


## Problem Statement <!--- do not change this line -->

Adverse drug interactions (ADIs) are a leading cause of preventable harm in healthcare. According to the FDA, in 2022, there were over 1.25 million serious adverse events reported and nearly 175,000 deaths. Manually identifying unsafe drug combinations is impractical due to the vast number of possible interactions and hidden risk patterns. Hence, to address this problem, our team leverages machine learning to accurately predict unsafe drug combinations and thus improve prescription safety.

## Key Results <!--- do not change this line -->

Achieved at least 98% ROC AUC accuracy on predicting over 222,000 unique drug interactions.
Deployed the model onto an interactive web application for more convenient drug interaction prediction, with features
searching for and selecting drugs easily from a dropdown list
providing binary prediction with a confidence score from 0-100


## Methodologies <!--- do not change this line -->

To accomplish this, we cleaned the dataset, trained a stacking ensemble model with Logistic Regression, Random Forest, and CatBoost, and applied 5-fold cross-validation to avoid overfitting. We then developed a web application using Gradio by passing in the dataset and making live predictions using the pre-trained model.

## Data Sources <!--- do not change this line -->

FDA FAERS dataset spanning 2014Q3-2024Q3: [High-Order Drug-Drug Interaction Dataset (HODDI)](https://github.com/TIML-Group/HODDI)

## Technologies Used <!--- do not change this line -->

- *Python*
- *Git*
- *pandas*
- *gradio*

## Authors <!--- do not change this line -->

This project was completed in collaboration with:

- *Jiyuan Ji [cji28@amherst.edu](mailto:cji28@amherst.edu)*
- *Emily Hsu [eh119@wellesley.edu](mailto:eh119@wellesley.edu)*
- *Anusri Nagarajan [anusri.nagarajan@sjsu.edu](mailto:anusri.nagarajan@sjsu.edu)*
- *Ahmed Mohammed [ahmed.mohammed@bison.howard.edu](mailto:ahmed.mohammed@bison.howard.edu)*
