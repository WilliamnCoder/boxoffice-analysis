# BoxOffice-analysis Readme

## How to start
### 1. Clone the repository
Run:
```
git clone https://github.com/WilliamnCoder/boxoffice-analysis.git 
```

## 2. Create and start the environment
Run:
```
source .venv/bin/activate
cd boxoffice-analysis
```

## 3. Install dependencies
Run:
```
pip install -r requirements.txt
```

## 4. Start Jupyter Notebook
Run:
```
cd notebooks
jupyter notebook
```


## 5. Imported libraries 

### 5.1. Data cleaning
- **pandas** - for handling data frames
- **numpy** - for numerical calculations, logic and array handling. 
### 5.2. For data visualization: 
- **matplotlib** - basis for data visualization, e.g. making diagram, plots, tables,
- **matplotlib.ticker** - fine-tuning of axis and formatting.
- **seaborn** - builds on matplotlib, with advanced visualizations.
### 5.2. For train-test split:
- **sklearn.model_selection import train_test_split** - divides data into training/test data, which is important for model validation.

### 5.3. Machine Learning:
- **from sklearn.linear_model import LinearRegression** - linear model that is interpretable.
- **from sklearn.ensemble import RandomForestRegressor** - ensemble method for analyzing non-linear relationships.

### 5.4. Evaluation metrics:
- **sklearn.metrics import mean_squared_error, r2_score** - for evaluating the model performance.