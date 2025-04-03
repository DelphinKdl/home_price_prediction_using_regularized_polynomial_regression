#  Housing Price Prediction - Regularized Polynomial Regression Model & Strategic Insights

---

##  Project Purpose

To demonstrate a complete machine learning pipeline — from data analysis and feature engineering to model training, evaluation, and interpretation — for predicting house sale prices with a real-world dataset.

---

##  Business Case

In the real estate market, pricing a house accurately is critical. Overpricing leads to delays in sales; underpricing leads to revenue loss.  
This project creates a model that **predicts home sale prices** and provides **practical suggestions to homeowners** on how they can increase their property’s value.

---

##  Goal

1. Build an accurate **regularized polynomial regression model** for house price prediction.  
2. Minimize model bias and overfitting using **Ridge and Lasso** techniques.  
3. Translate model insights into **actionable advice for homeowners** about upgrades and sales timing.

---

##  Deliverables

- Jupyter Notebook: `notebooks/Housing_Price_Modeling.ipynb`  
- Clean dataset and feature engineering pipeline   
- Visual breakdown of top price-driving features  
- Deployable Streamlit Web App (coming soon)

---

##  In Repository

-  `data/`: Raw and processed datasets
-  `notebooks/`: Full workflow from exploration to modeling
-  `src/`: Scripts for modeling, preprocessing, and visualization
-  `reports/figures/`: Plots and result images
-  `README.md`, `requirements.txt`

---

##  Results and Model Evaluation

- **RMSE (Test Set):** ~$21,000  
- **R² Score:** ~0.91  
- **Top Predictive Features:**  
  - `OverallQual` (Overall material and finish quality)  
  - `GrLivArea` (Above ground living area)  
  - `GarageCars` (Garage capacity)

These features strongly influence house prices. Homes with high-quality kitchens, garages, and larger living spaces typically receive higher offers.

---

##  Business Impact

Homeowners can use these insights to decide:
- Whether to **sell now** based on property value predictions.
- Which **home improvements** will result in the **highest ROI** (return on investment).

Real estate agents and agencies can leverage the model to give better advice to clients and align listing prices with market expectations.

---

##  Installation

```bash
git clone https://github.com/DelphinKdl/home_price_prediction_using_regularized_polynomial_regression.git
cd home_price_prediction_using_regularized_polynomial_regression
pip install -r requirements.txt
