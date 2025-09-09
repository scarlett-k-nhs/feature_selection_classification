# Diabetes & Prediabetes Feature Selection with XGBoost (Feature Selection Workshop)

## Overview
This repository contains code and analyses for building an XGBoost model to classify individuals with diabetes based on healthcare and lifestyle survey data. The primary focus is on **feature selection** using a variety of methods to reduce the number of features while **maximising f1**.

## Folder structure

It is important that your project structure looks like the below, otherwise you will struggle to run your code. 

```text
+---notebooks
|   +---Feature_Importance_Cheatsheet        <- This provides example code for feature importance for an XGBoost model.
|   +---Feature_Importance_Workshop          <- This trains and XGBoost model for Feature Selection.
|   +---load_diabetes_data                   <- This code was used to load the data from UCI and balance the classes. 
|
|   README.md                                <- Quick start guide
```

## Getting Started

The Feature_Importance_Workshop and the Feature_importance_cheatsheet runs in google collab notebooks. 

### Dataset Overview: CDC Diabetes Health Indicators
This dataset comprises healthcare statistics and lifestyle survey information about individuals in the United States. It was collected by the **Centers for Disease Control and Prevention (CDC)** and is publicly available through the **UCI Machine Learning Repository**.

**Citation:**
Markelle Kelly, Rachel Longjohn, Kolby Nottingham,
The [UCI Machine Learning Repository](https://archive.ics.uci.edu)

## Useful Resources
The work in this repository has been influenced by a number of helpful articles and tutorials:

- [Feature Importance and Feature Selection with XGBoost in Python](https://machinelearningmastery.com/feature-importance-and-feature-selection-with-xgboost-in-python/)  
- [Calculate Feature Importance with Python](https://machinelearningmastery.com/calculate-feature-importance-with-python/)  
- [Feature Selection with Real and Categorical Data](https://machinelearningmastery.com/feature-selection-with-real-and-categorical-data/)  
- [A Guide to 21 Feature Importance Methods and Packages in Machine Learning](https://medium.com/data-science/a-guide-to-21-feature-importance-methods-and-packages-in-machine-learning-with-code-85a841f8b319)  
- [Why You Should Stop Using Recursive Feature Elimination](https://blog.kxy.ai/why-you-should-stop-using-recursive-feature-elimination/index.html)  
- [Python Feature Importance Libraries](https://www.alooba.com/skills/machine-learning-libraries/python-16/feature-importance/)  
- [Best Practice to Calculate and Interpret Model Feature Importance](https://towardsdatascience.com/best-practice-to-calculate-and-interpret-model-feature-importance-14f0e11ee660/)  
- [XGBoost Feature Importance](https://medium.com/@emilykmarsh/xgboost-feature-importance-233ee27c33a4)  

## License