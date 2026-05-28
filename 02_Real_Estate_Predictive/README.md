# Real Estate Valuation & Predictive Analytics: King County, USA 🏠

## 📌 Business Problem
A regional real estate investment firm wants to optimize its property acquisition strategy in King County, Washington (including Seattle). To maximize return on investment (ROI), the business needs to move away from legacy, intuition-based pricing models and implement a data-driven approach to identify housing valuation drivers and accurately forecast transaction prices.

## 🛠️ Data Architecture & Tech Stack
* **Core File:** `House_Sales_in_King_Count_USA.ipynb`
* **Tech Stack:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
* **Dataset Variables:** Historical data on home sales between May 2014 and May 2015, featuring 21 columns including price, square footage (`sqft_living`), bedroom/bathroom counts, location coordinates, view grading, and renovation history.

## 🔍 Key Insights & Analysis
* **Primary Valuation Driver:** Feature correlation analysis reveals that interior living area space (`sqft_living`) holds the strongest linear correlation with home sales pricing.
* **Geographic Premium:** Properties graded with high-tier waterfront views command a substantial price premium, requiring distinct categorization during predictive modeling.
* **Data Cleansing:** Handled missing values in key structural parameters (bedrooms and bathrooms) using median imputation to prevent model bias.

## 🚀 Business Outcomes & Model Implementation
* **Pipeline Development:** Built a multi-stage data processing pipeline utilizing feature scaling, polynomial transformations, and linear regression frameworks.
* **Strategic Value:** The resulting predictive model allows the acquisition team to input raw property characteristics and instantly evaluate whether an active listing is undervalued relative to market fair value.