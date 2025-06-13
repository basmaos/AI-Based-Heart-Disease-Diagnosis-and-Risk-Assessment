# AI-Based Heart Disease Diagnosis and Risk Assessment

##  Description

This project focuses on diagnosing and assessing the risk of heart disease using machine learning models, including XGBoost, Gradient Boosting, and MLP.  
The models are designed with a strong emphasis on accuracy, interpretability.

## Data Source

- Dataset information is provided in the Dataset.txt file, which contains the link to the UCI Machine Learning Repository - Heart Disease Dataset.  
- The dataset is stored in the project directory as heart_disease_data.csv.

##  Environment Setup

- The project was developed using:  
  - IDE: Jupyter Notebook and Visual Studio Code.  
  - Programming Language: Python 3.12.0.  
  - Libraries:  
    - numpy
    - pandas
    - matplotlib
    - seaborn
    - scikit-learn
    - xgboost
    - tensorflow
    - shap

##  File Descriptions

- code.ipynb:  
  This notebook includes all the code and results for:  
  - Binary classification models for XGBoost, Gradient Boosting, and MLP.  
  - Multi-class classification models (5 classes) for XGBoost, Gradient Boosting, and MLP.  
  - It contains visualizations such as ROC curves, AUC scores, classification reports, and model interpretability analysis using SHAP.  
  - All the outcomes are documented within the notebook, making it a comprehensive resource for understanding both the implementation and evaluation of the models.

- requirements.txt:  
  A list of all the required Python libraries for running the project.

- Dataset.txt:  
  Contains the link to the dataset source and additional metadata.

- heart_disease_data.csv:  
  The processed dataset used for training and testing the models.

## How to Run

1. Clone the repository
2. Navigate to the project directory
3.	Install the required libraries from requirements.txt
4.	Access the dataset:
	- 	The dataset file is named heart_disease_data.csv.
	- 	For additional details about the source, refer to the Dataset.txt file.
5.	Run the code:
 -   Open and execute the notebook code.ipynb using Jupyter Notebook.
 -   Review all implemented models, their performance, and visualized results within the notebook.
