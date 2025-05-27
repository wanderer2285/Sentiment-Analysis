# 📬 Employee Sentiment and Engagement Analysis

This project focuses on analyzing employee communication to assess sentiment and engagement levels across time. By combining NLP techniques, data analysis, and predictive modeling, the objective is to uncover insights that can help organizations improve employee morale and reduce attrition.

---

## 🎯 Project Objective

The main goal is to evaluate employee sentiment and engagement by performing the following:

- **Sentiment Labeling**: Automatically label each message as Positive, Negative, or Neutral.
- **Exploratory Data Analysis (EDA)**: Visualize and understand trends in employee communications.
- **Employee Score Calculation**: Compute monthly sentiment scores for each employee.
- **Employee Ranking**: Identify and rank employees based on their sentiment scores.
- **Flight Risk Identification**: Flag employees who sent 4 or more negative emails in a month.
- **Predictive Modeling**: Use linear regression to analyze sentiment trends over time.

---

## 📂 Detailed Tasks

###  Task 1: Sentiment Labeling
- Labeled employee messages as **Positive**, **Negative**, or **Neutral**.
- Used a large language model (LLM) 
- Augmented the original dataset (`test.csv`) with a sentiment column.

###  Task 2: Exploratory Data Analysis (EDA)
- Analyzed sentiment trends over months.
- Identified peak negative and positive periods.
- Compared communication sentiment across departments and individuals.

###  Task 3: Employee Score Calculation
- Calculated monthly sentiment scores per employee.
- Visualized top and bottom performers.

###  Task 4: Employee Ranking
- Ranked employees based on cumulative sentiment scores.
- Visualized top and bottom performers

###  Task 5: Flight Risk Detection
- Employees with 4+ negative emails in a month were flagged as flight risks.
- Provided month-wise breakdown of high-risk employees.

###  Task 6: Predictive Modeling
- Built a **linear regression model** using time-based features.
- Aimed to forecast employee sentiment trends.

---

## 📈 Model Performance

- **Root Mean Squared Error (RMSE)**: `2.903`
- **R² Score**: `-0.064`
- The linear regression model had **limited predictive power** based on time features alone.

---

## 🧠 Key Recommendations

- Use **richer NLP features** for sentiment prediction (e.g., TF-IDF, embeddings).
- Try **advanced models** like **XGBoost** or **Random Forest** for better performance.
- Track sentiment trends **quarterly** to detect early signs of disengagement or dissatisfaction.

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

