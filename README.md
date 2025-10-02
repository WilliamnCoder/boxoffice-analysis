### Data analysis of Box Office 

## How to start

# Code the following in the terminal 
- source .venv/bin/activate
- cd notebooks
- jupyter notebook

# Imported libraries (Prel.): 
- Data management:
    import pandas as pd  (for handling data frames)
    import numpy as np (for numerical calculations, logic and array handling)

- Data visualization:
    import matplotlib.pyplot as plt (basis for data visualization, e.g. making diagram, plots, tables)
    import matplotlib.ticker as mtick (used for delimiting number, e.g making 10000 to 10,000)
    import seaborn as sns (based on matplotlib, and makes it easer and nicer to make graphs)

- Machine Learning:
    from sklearn.model_selection import train_test_split (divides data into training/test, important for model validation)
    from sklearn.linear_model import LogisticRegression (classification model that is interpretable )
    from sklearn.ensemble import RandomForestClassifier (powerful ensemble model for classification)
    from sklearn.metrics import classification_report (how good is the model, shows precision, recall and f1-score ) 

- Advanced modelling:
    import xgboost as xgb (gradient boosting, powerful and especially effective for tabular data)
    import shap (explainable AI, that explains how every feature affects the models decision)