# 🛍️ Integrated Retail Analytics for Store Optimization using Advanced Machine Learning

# 📄 Description
Developed a comprehensive machine learning pipeline to optimize retail store operations and enhance customer experience. The project integrates **data preprocessing, anomaly detection, segmentation, personalization, market basket analysis, and demand forecasting** to help retailers make data-driven decisions.

# 🧩 Key Tasks

* **Data Preprocessing:**

  * Merged sales, store, and feature datasets (CPI, fuel price, temperature, unemployment).
  * Handled missing values with median imputation and normalized skewed data.

* **Exploratory Data Analysis (EDA):**

  * Identified top-performing stores, departments, and store types.
  * Analyzed seasonal spikes in sales (holidays, promotions).
  * Explored external factors (inflation, fuel prices, unemployment) affecting sales.

* **Anomaly Detection:**

  * Detected unusual sales patterns using IQR and time-series rolling averages.

* **Segmentation & Personalization:**

  * Applied **K-Means clustering** (4 optimal clusters) for store and department segmentation.
  * Designed cluster-based marketing and inventory strategies (Luxury, Value, Budget, Compact stores).

* **Market Basket Analysis:**

  * Applied **Apriori algorithm** to identify frequent item associations.
  * Suggested bundled offers, optimized layouts, and targeted promotions.

* **Demand Forecasting:**

  * Built **SARIMA** models for short-term forecasts.
  * Used **Random Forest** and **Holt-Winters** models for long-term demand prediction.
  * Incorporated external factors for accurate forecasting.
    
# 📊 Insights

* **Top Earning Stores:** Store 20 and Store 4
* **Top Performing Departments:** 1–15, 38, 40, 72, 90–95 (25% higher sales)
* **Store Type A** outperformed B and C in revenue
* **2023 sales trends:** Clear seasonal peaks during Black Friday & Christmas
* **External factors:** CPI ↑ steadily, fuel prices ↑ post-2011, unemployment ↓ over time
* **Market Basket:** Strong product associations → bundled promotions boost sales

# 🛠️ Skills & Tools

* **Programming:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Statsmodels, MLxtend, Matplotlib, Seaborn
* **Techniques:** Data Cleaning, Feature Engineering, Anomaly Detection, Clustering, Market Basket Analysis, Time-Series Forecasting
* **ML Models:** K-Means, SARIMA, Random Forest, Holt-Winters

# 👤 Author

Shruti Walunj

Would you like me to **make a shorter LinkedIn-friendly version** of this README too (like the Layoffs one) so you can use it as a LinkedIn post?
