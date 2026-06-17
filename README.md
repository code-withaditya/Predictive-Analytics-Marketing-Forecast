# Data-Driven Forecasting & Marketing Mix Optimization

This repository houses two predictive analytics models built in Google Colab designed to process historical datasets, evaluate statistical trends, and deliver business intelligence for corporate resource allocation.

---

## 📈 Project 1: Chronological Trend Forecasting (Time-Series)
* **Dataset:** International Air Passengers Dataset (Monthly historical tracking).
* **Model:** Holt-Winters Exponential Smoothing (with Additive Trend & Seasonality).
* **Objective:** Predict future consumer travel volume while isolating overarching growth trends from repeating summer spikes.
* **Performance:** Delivered clean trend-tracking with a Mean Absolute Error (**MAE**) of **31.79** and an **RMSE** of **39.26**.

---

## 📊 Project 2: Advertising Channel ROI Optimization (Regression)
* **Dataset:** ISLR Advertising Spend Data.
* **Model:** Multiple Linear Regression.
* **Objective:** Mathematically isolate how specific marketing budgets (TV, Radio, Newspaper) interact to drive overall retail product sales.

$$\text{Sales} = \beta_0 + \beta_1(\text{TV}) + \beta_2(\text{Radio}) + \beta_3(\text{Newspaper}) + \epsilon$$

### 🛠️ Performance Metrics & Evaluation
* **Mean Absolute Error (MAE):** **1.46** (On average, sales predictions deviate by only 1,460 units).
* **Root Mean Squared Error (RMSE):** **1.78** (Confirms tight error dispersion with minimal extreme outliers).
* **R-squared Score ($R^2$):** **0.90** (90% of all variance in sales numbers is entirely explained by the combination of advertising spend).

### 💡 Corporate Attribution Weights (ROI Insights)
* **Radio:** Every \$1,000 invested increases product sales by **189 units**.
* **TV:** Every \$1,000 invested increases product sales by **45 units**.
* **Newspaper:** Every \$1,000 invested increases product sales by just **3 units**.

---

## 🚀 The "So What?" Business Impact
Instead of relying on gut feelings to budget millions of corporate dollars, data teams can use these synchronized frameworks to optimize operational spend:
1. **Supply Chain Management:** Predicting monthly airline demands allows carriers to optimize fuel hedging and scale cabin crew scheduling up to 24 months in advance.
2. **Capital Efficiency:** The regression model explicitly warns stakeholders that Newspaper spending is heavily underperforming. Executives can programmatically reallocate budget away from Newspaper and into Radio to experience a **63x improvement in customer acquisition efficiency**.
