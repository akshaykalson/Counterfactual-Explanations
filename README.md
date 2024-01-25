Explainable ML Assignment
This repository contains a Jupyter notebook (Explainable ML_Assignment 7.ipynb) that explores and interprets a machine learning model for predicting recidivism risk. The notebook is created using Colaboratory and can be accessed here.

Overview
The notebook covers the following key aspects:

Data Loading: The dataset (recidivism-risk.csv) is loaded using Pandas, and a brief overview of the data is printed.
Data Preprocessing: The notebook handles preprocessing steps such as dropping unnecessary columns, creating a copy of the data, and generating confusion matrices.
Model Training: CatBoost classifier is used for training the model, and various metrics like accuracy and ROC curve are calculated.
Interpretability: The notebook employs interpretable methods, such as confusion matrices and ROC curves, to understand model performance.
Anchors: AnchorTabular is utilized to generate interpretable "anchors" explaining model predictions for specific instances.
Counterfactual Prototypes: CounterfactualProto is employed to generate counterfactual instances explaining changes in model predictions.
Prerequisites
To run the notebook, ensure the following dependencies are installed:

Python 3.x
Jupyter Notebook
Required Python packages (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, CatBoost, Alibi)
Usage
Clone the repository to your local machine.
Open the Jupyter notebook (Explainable ML_Assignment 7.ipynb) using a Jupyter Notebook environment.
Execute the cells in the notebook sequentially.
Additional Resources
The dataset (recidivism-risk.csv) used in the notebook is included in the repository.
External libraries like CatBoost and Alibi are used for machine learning and interpretability.
Feel free to explore and experiment with the notebook to gain insights into the interpretable aspects of the recidivism prediction model.
