# 💸 Pricing Optimization Using Machine Learning

This project demonstrates how machine learning can be used to optimize pricing strategies by simulating a real-world retail environment. Through data generation, exploratory analysis, and predictive modeling, the project identifies optimal pricing points to maximize revenue based on customer demand, competition, and other key factors.

---

## 📌 Project Objectives

- Simulate a dataset that mimics real-world pricing conditions
- Explore relationships between price, demand, marketing, and competition
- Build a machine learning model to predict demand
- Identify pricing strategies that maximize revenue

---

## 🧪 Dataset Description

The dataset was synthetically generated to represent a business environment from 2020 to 2023 with the following features:

| Feature             | Description                                      |
|---------------------|--------------------------------------------------|
| `Price`             | Selling price per unit                          |
| `Demand`            | Quantity of units demanded                      |
| `COGS`              | Cost of Goods Sold                              |
| `Marketing_Spend`   | Advertising and promotional expenses            |
| `Customer_Segments` | Categorical: High, Medium, Low                  |
| `Seasonality`       | Categorical: Winter, Spring, Summer, Fall       |
| `Competitor_Price`  | Price of the same product by competitors        |
| `Date`              | Randomized dates from 2020 to 2023              |

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations were created using `matplotlib`, `seaborn`, and `plotly` to explore:

- Price distribution vs Competitor pricing
- Price vs Demand trends
- Effects of seasonality and marketing spend
- Time series trends across quarters and years

---

## 🤖 Machine Learning Model

A **Decision Tree Regressor** was used to predict demand based on input variables:

### Model Features
- `Price`
- `COGS`
- `Marketing_Spend`
- `Competitor_Price`
- Encoded `Customer_Segments` and `Seasonality`

### Evaluation Metrics
- `R² Score`: Model explanatory power
- `Mean Squared Error`: Accuracy of predictions

The model was used to simulate and test multiple pricing scenarios to estimate revenue and identify optimal pricing strategies.

---

## 📈 Revenue Optimization

Predicted revenue = `Price × Predicted Demand`

- Simulated multiple pricing scenarios
- Calculated expected revenue for each
- Identified price points that **maximize total revenue**

---

## 🛠️ Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn`, `plotly` for visualization
  - `scikit-learn` for machine learning
- **Environment**: Jupyter Notebook



















## Citations
https://thecleverprogrammer.com/2023/04/17/retail-price-optimization-using-python/
https://thecleverprogrammer.com/2024/07/22/price-optimization-using-python/
https://medium.com/operations-research-bit/a-practical-guide-to-pricing-optimisation-using-machine-learning-5ec4bf7f0d4c

