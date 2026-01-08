# Vehicle-Weight-Prediction-for-Non-Coverage-Roads
This repository provides the code and documentation supporting the research “Vehicle Weight Prediction for Non-Coverage Roads.” The study develops an interpretable and transferable machine-learning framework to estimate Gross Vehicle Weight (GVW) on road segments lacking direct Weigh-In-Motion (WIM) instrumentation.

Using large-scale WIM datasets from New York, California, and Texas (2021), the repository implements and compares Multiple Linear Regression (MLR) , Random Forest (RF), Extreme Gradient Boosting (XGBoost)

Model performance is evaluated using standard accuracy metrics (R², RMSE, MAE, MAPE), along with a Transferability Index (TI) that quantifies cross-state generalization. SHAP (SHapley Additive exPlanations) is used to provide model interpretability and to identify the most influential predictors of GVW.

The results demonstrate that vehicle class and number of axles are the dominant predictors of GVW, enabling reliable estimation on non-instrumented roadways. The proposed framework supports cost-effective freight monitoring, pavement management, and sustainable transportation infrastructure planning.

Key Features include Large-scale multi-state WIM data preprocessing, Interpretable ML models for GVW prediction, Cross-state transferability assessment and SHAP-based feature importance analysis

Technologies Used include Python, scikit-learn, XGBoost, SHAP, pandas, numpy, matplotlib

Datasets : The models are trained and evaluated using 2021 WIM datasets from New York, California, Texas. The raw data access may be subject to state DOT data-sharing policies.
