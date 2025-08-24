# eBay Product Price - Web Scraping

An end-to-end **machine learning project** that predicts eBay product prices using a real-world scraped dataset. Built with the **CRISP-DM framework**, this project combines data mining, predictive modeling, and visualization to support smarter pricing strategies for sellers.

## Objectives

* Identify key features influencing product prices
* Build a predictive model with **MAE < 30**
* Provide an explainable, scalable ML pipeline
* Support sellers with actionable pricing insights
* Ratings & categories are strong predictors of price
* Transparent ML models improve seller trust
* Pipeline is modular → adaptable to other e-commerce platforms

## Dataset

* **Source**: Ethically scraped live eBay listings
* **Size**: 1,990+ records
* **Features**: Product name, price, rating, number of ratings, category
* **Kaggle Dataset:** [eBay Scraped Products](https://www.kaggle.com/datasets/topvirus/ebay-scraped-products)

## CRISP-DM Pipeline

1. **Business Understanding** → Improve pricing efficiency & competitiveness
2. **Data Collection** → Scraped live eBay listings (Python)
3. **Data Preparation** → Cleaned, normalized, engineered features (*Rating\_Factor*)
4. **Modeling** → Random Forest vs. XGBoost
5. **Evaluation** → Achieved **MAE = 25**, used **SHAP** for interpretability
6. **Deployment** → Price prediction function + Power BI dashboard

## Models & Results

* **Best Model**: XGBoost Regressor
* **Performance**:

  * MAE = 25
  * RMSE = 32
* **Interpretability**:

  * Random Forest Feature Importance
  * SHAP value explanations

## Visualizations & Dashboard

* Predicted vs. actual prices
* Price distribution by category
* Rating effects on pricing
* Interactive **Power BI dashboard** + Python prediction function

## Ethics & Fairness

* No personal identifiers collected
* GDPR-compliant data handling
* Data imbalance handled with over/under sampling
* Fairness checks across subgroups

## Repository Contents

```
├── code.ipynb                # Scraping, preprocessing, modeling
├── ebay_scraped_products.csv # Clean dataset (also on Kaggle)
├── README.md                 # Project documentation
```
## License

This project is licensed under the MIT License - see the LICENSE file for details.
