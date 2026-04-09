# Air Pollution and Life Expectancy: A Cross-Country Analysis

## Project Overview
This project investigates the relationship between PM2.5 air pollution and life expectancy using World Bank panel data from 195 countries over the period 2000-2020. Using OLS regression with economic controls (GDP per capita and health expenditure per capita), we quantify how air quality is associated with longevity after accounting for a country's wealth and healthcare spending.

---

## How to Run the Code

### Requirements
 
Make sure the following Python libraries are installed. You can install them all at once with:
 
```bash
pip install pandas numpy matplotlib seaborn openpyxl statsmodels scikit-learn pycountry
```

### Steps
 
1. **Run the preprocessing notebook:**
   Open `195_Data_Processing` in Jupyter Notebook or JupyterLab and run all cells (Kernel → Restart & Run All).
   The notebook loads `195_final_cleaned_dataset.xlsx` using a relative path, so the dataset must be in the same folder as the notebooks.
 
3. **Run the EDA notebook:**
   Open `195_EDA.ipynb` and run all cells to see EDA results.
   This notebook produces all visualizations and correlation analyses described in Section 4 of the report.
 
4. **Run the modelling notebook:**
   Open `195_modelling_training_testing_evaluating.ipynb` and run all cells.
   This notebook fits two OLS models, performs an 80/20 train-test split, and computes R² and RMSE for both training and test sets.
 
> **Note:**
> This project uses API calls to fetch datasets from the World Bank. Occasionally, requests may return a 502 Bad Gateway error. This is a temporary server-side issue related to the API or its upstream services, and not due to the implementation of this project. Generally, retrying the request after a short delay resolves the issue.
 
---

## Authors

| Name | GitHub |
|------|--------|
| Krystal Kim | @rlawndms |
| Gurkeerat Kakar | @gskakar |
| Seijah Koopmans | @seijah-pixel |
| Tiandra Wallace | @tiaari04 |
