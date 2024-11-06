# E-commerce-Data-Science-Project

**Set Up Your Environment**
Navigate to Root folder
Create a Virtual Environment
```console
python -m venv ecommerce-env
```
Activate it by running
```console
ecommerce-env\Scripts\activate
```
**Install Required Packages**
Run the following command to install essential libraries:
```console
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm statsmodels joblib jupyter flask gunicorn

```
**Directory Structure**
Inside your project folder, create the following subfolders:

**E-commerce Data Science Project/**
```console
│
├── data/          # For raw and processed data files
├── notebooks/     # For exploratory analysis and experiments in Jupyter Notebooks
├── models/        # For storing trained model files
├── app/           # For deployment files (like Flask app)
├── visuals/       # For saving visualizations
├── reports/       # For storing reports and Power BI dashboards
└── README.md      # Project overview and documentation
```

**Data Acquisition**
https://archive.ics.uci.edu/dataset/502/online+retail+ii

**Launch Jupyter Notebook**
jupyter notebook