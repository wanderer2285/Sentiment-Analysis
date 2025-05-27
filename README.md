# 🚀 Employee Sentiment Analysis

## 🔍 Summary
This project analyzes employee sentiment from emails to:
- Rank top positive/negative employees monthly
- Detect at-risk employees (flight risks)
- Predict future sentiment scores using linear regression

## 🔝 Top Employees
- **Most Positive**: Alice, John, Priya
- **Most Negative**: Tom, Nikhil, Sara

## ⚠️ Flight Risks
- 7 employees flagged based on 30-day window of ≥ 4 negative mails

## 📈 Model Performance
- RMSE: 2.903
- R² Score: -0.064
- Linear regression using time-based features showed limited predictive power

## 🧠 Key Recommendations
- Use richer text-based features (NLP)
- Consider advanced models (e.g., XGBoost)
- Monitor sentiment trends quarterly for proactive HR measures
