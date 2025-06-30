
# Real Estate Sales Analysis (2016-2019)
This project explores property sales data from 2016 to 2019, focusing on residential transactions across multiple towns. The analysis covers price trends, valuation accuracy, and property categories.

## Dataset Summary
The dataset includes variables such as:
- **Sale Amount**: Final sale price of a property
- **Assessed Value**: Government-estimated property value
- **Sales Ratio**: Sale Amount / Assessed Value
- **Residential Type**: Property structure (e.g., Condo, Single Family)
- **Town** and **List Year**


## Data Cleaning
- Removed outliers using the **Interquartile Range (IQR)** method
- Standardized column names and formats
- Handled missing or inconsistent entries


## Key Insights
- Properties from 2016–2018 often sold **below assessed value**
- In 2019, both **Sale Amounts and Assessed Values increased sharply**, indicating a possible market correction
- Most common residential types: **Single Family** and **Condo**
- Towns like **Waterbury**, **New Haven**, and **Bridgeport** had the highest number of sales


## Contents
- `notebooks/` – Jupyter notebooks for EDA and visualization
- `data/` – Cleaned and raw datasets
- `results/` – Saved charts and figures
- `docs/` – Project summary and interpretation

📌
## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- Quarto for presentation


**Author:** Natacha Iradukunda and Gemima Grace Wishavura

