"# Motor_Insurance" 
Build a machine learning model that predicts ultimate claim cost using FNOL data.

Identify the most influential FNOL and policy variables affecting cost.

Improve reserve allocation accuracy by at least 15% compared to current benchmarks.

Integrate interpretability (SHAP/LIME) to meet regulatory and actuarial standards.

Deploy the solutions into GMA’s live claims ecosystem with minimal disruption.


Step 1: Data Collection & Understanding
Compile historical FNOL, claims, policy, and third-party datasets.

Assess data completeness, types, missingness, and distribution.

Step 2: Data Preparation
Clean categorical and numerical fields.

Handle outliers — especially high-value claims.

Feature engineering including:

days between accident and FNOL

accident severity score

weather and road conditions

driver and vehicle risk profiles

Step 3: Exploratory Data Analysis (EDA)
Study claim frequency and severity trends.

Analyze correlation between driver behavior and claim amounts.

Understand distribution of settlement amounts.

Visualize third-party involvement impact.

Step 4: Model Development
Baseline model (Linear Regression, Random Forest).

Advanced ensemble methods (XGBoost, LightGBM).

Apply transformations for skewed targets (log-transform).

Evaluate using RMSE, MAE, MAPE.

Step 5: Validation & Explainability
Validate on holdout test set.

Use SHAP to identify critical predictive variables.

Prepare explainability reports for actuaries and regulators.

Step 6: Deployment
Package model into Docker container.

Expose prediction API through FastAPI/Flask service.
