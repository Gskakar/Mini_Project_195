# Air Pollution and Life Expectancy: A Cross-Country Analysis

## Project Overview
This project investigates the relationship between PM2.5 air pollution and life expectancy using World Bank panel data from 195 countries over the period 2000–2020. Using OLS regression with economic controls (GDP per capita and health expenditure per capita), we quantify how air quality is associated with longevity after accounting for a country's wealth and healthcare spending.

---

## How to Run the Code

### Requirements
 
Make sure the following Python libraries are installed. You can install them all at once with:
 
```bash
pip install pandas numpy matplotlib seaborn openpyxl statsmodels scikit-learn pycountry
```

### Steps
 
1. **Place all files in the same directory.**
   The notebooks load `195_final_cleaned_dataset.xlsx` using a relative path, so the dataset must be in the same folder as the notebooks.
 
2. **Run the EDA notebook first:**
   Open `195_EDA.ipynb` in Jupyter Notebook or JupyterLab and run all cells (Kernel → Restart & Run All).
   This notebook produces all visualizations and correlation analyses described in Section 4 of the report.
 
3. **Run the modelling notebook second:**
   Open `195_modelling_training_testing_evaluating.ipynb` and run all cells.
   This notebook fits two OLS models, performs an 80/20 train-test split, and computes R² and RMSE for both training and test sets.
 
> **Note:** Both notebooks install dependencies with `!pip install ...` in the first cell, so they can also be run in Google Colab or any cloud Jupyter environment without any prior setup.
 
---

## Authors

| Name | GitHub |
|------|--------|
| Krystal Kim | @rlawndms |
| Gurkeerat Kakar | @gskakar |
| Seijah Koopmans | @seijah-pixel |
| Tiandra Wallace | @tiaari04 |
