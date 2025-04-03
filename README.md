# Home Price Prediction Using Regularized Polynomial Regression

This project aims to solve a real-world problem in the real estate market by accurately predicting home sale prices and offering actionable insights to homeowners.

Our two main objectives are:
1. **Developing a robust machine learning model** using regularized polynomial regression (Ridge) to forecast house sale prices.
2. **Providing strategic recommendations** to homeowners based on feature analysis, helping them decide how to improve their property or sell at a better price.

---
##  Project Highlights

-  **Polynomial Regression with Regularization**  
  Captures complex, non-linear relationships in the data while reducing overfitting using Ridge.

-  **Insight-Driven Recommendations**  
  Analyzes key drivers of home prices to advise on improvements or sale timing.

- ⚙ **Modular, Scalable Codebase**  
  Clean and reusable code structured using the `cookiecutter-data-science` template for reproducibility and scalability.
---
## 💡 Key Features

- Feature engineering with polynomial terms  
- Regularization tuning (hyperparameter optimization for alpha)  
- Performance evaluation using RMSE and R²  
- Visualizations for model behavior and insights  
- Recommendations based on model interpretation ( features boost price the most)

---
## 📁Project Structure

```bash
home_price_prediction/
├── data/                # Raw, processed, and external datasets
├── notebooks/           # Jupyter Notebooks for EDA and modeling
├── reports/             # Final visualizations and insights
├── src/                 # Source code (data prep, modeling, viz)
│   ├── data/            # Data loading and cleaning scripts
│   ├── features/        # Feature engineering and transformations
│   ├── models/          # Model training and evaluation logic
│   └── visualization/   # Plotting and results generation
├── requirements.txt     # Project dependencies
├── Makefile             # Reproducible workflow commands
└── README.md            # You are here
