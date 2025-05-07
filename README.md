🚀 Project Objective
Predict weekly units sold for each SKU-store combination to support more accurate demand planning and inventory decisions.

This repository contains the full code, process, and learnings from a demand planning project where I tackled data preparation, feature engineering, and model evaluation using both linear and tree-based approaches.

🔍 Key Techniques Used
🧱 Feature Engineering
Log and power transformations to normalize highly skewed sales and pricing data.

Creation of aggregated features like:

Average units sold by SKU, store, and time period.

Interactions between store_id and sku_id.

Date-based features (e.g., month, weekday, week_of_year).

📈 Modeling
Baseline models: Linear Regression, Ridge, Lasso

Gradient Boosting models: XGBoost and LightGBM

Comparison of performance using MAE, RMSE, and R² metrics
