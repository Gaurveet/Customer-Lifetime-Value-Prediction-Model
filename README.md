Customer Lifetime Value (LTV) Prediction

🎯 Objective
Predict the Lifetime Value (LTV) of customers based on their historical transaction data to support targeted marketing strategies.

🛠️ Tools Used
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

📦 Dataset
The dataset consists of:
- `customer_data.csv`: Contains customer IDs and signup dates.
- `transactions.csv`: Contains transaction-level purchase history.

🧪 Feature Engineering
For each customer:
- "Frequency": Number of purchases
- "Recency": Days since last purchase
- "AOV (Avg Order Value)": Average value per order

🤖 Model
- "Algorithm": XGBoost Regressor
- "Target": Total amount spent by customer (proxy for LTV)
- "Validation": MAE and RMSE on test set

📊 Evaluation
- "MAE": ~15.58
- "RMSE": ~41.85

📈 Visualizations
- Feature Importance (based on XGBoost)
- LTV Segment Distribution

📁 Project Structure
