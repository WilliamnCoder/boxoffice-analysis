### Data analysis of Box Office 

## How to start

# Code the following in the terminal 
- source .venv/bin/activate
- cd notebooks
- jupyter notebook

## Install requirements
Run:
```bash
pip install -r requirements.txt
```

# Imported libraries: 
### Data cleaning:
    **pandas** - for handling data frames
    **numpy** - for numerical calculations, logic and array handling. 
### For data visualization: 
    **matplotlib** - basis for data visualization, e.g. making diagram, plots, tables,
    **matplotlib.ticker** - fine tuning of axis and formatting,
    **seaborn** - builds on matplotlib, with advanced visualizations.
### For train-test split:
    **sklearn.model_selection import train_test_split** - divides data into training/test data, which is important for model validation.

### Machine Learning:
    **from sklearn.linear_model import LinearRegression** - linear model that is interpretable.
    **from sklearn.ensemble import RandomForestRegressor** - ensemble method for analyzing non-linear relationships.

### Evaluation metrics:
    **sklearn.metrics import mean_squared_error, r2_score** - for evaluation of the model performance