# Automobile Sales Performance Tracking & Interactive Analytics

## 🎯 1. Business Problem & Objective
Automotive manufacturers and marketers struggle to optimize advertising spend across fluctuating macroeconomic cycles. The goal of this project is to analyze historical automobile sales data to identify trends during recession vs. non-recession periods, allowing stakeholders to make data-driven decisions on inventory management and promotional investments.

---

## 🛠️ 2. Technical Stack & Methodology
* **Data Processing & Analytics:** Python, Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Geospatial & Interactive Elements:** Folium

### Data Pipeline Flow:
1. **Data Cleaning:** Handled missing values, aligned date filters, and segmented data blocks into historical recession vs. non-recession eras.
2. **Exploratory Data Analysis (EDA):** Evaluated sales volume variations across vehicle types (e.g., family cars, sports cars, small cars).
3. **Marketing Analytics:** Analyzed advertising expenditure returns relative to vehicle sales velocity.

---

## 📊 3. Visualizations & Core Insights

> 💡 **Recruiter Note:** The complete interactive visual breakdown can be viewed by opening the Jupyter Notebook inside this directory.

### Key Data Insights Discovered:
* **The 1994-1995 Peak:** Historical analysis revealed that overall automotive sales volume peaked sharply during the 1994-1995 non-recession cycle, driven by high consumer confidence.
* **Recession-Resilient Segments:** Conversely, during economic downturns (recession periods), **medium-sized family cars** captured the highest resilient majority share of total advertising conversion. 
* **Strategic Takeaway:** During recessions, marketing budgets should pivot aggressively toward practical, medium family vehicles rather than luxury or sports segments, as consumer utility prioritization shifts.

---

## 🚀 4. How to Run This Project Locally

To interact with the data models and interactive plots on your local machine:

1. Clone this portfolio repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn folium