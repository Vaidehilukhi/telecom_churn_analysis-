## Telecom Customer Churn Analysis
### End-to-End Data Analysis & Machine Learning Project

##  Problem Statement

> A telecom company is losing customers every month. This project identifies **why customers churn**, **who is most at risk**, and builds a **machine learning model** to predict churn — enabling the business to take proactive action before losing customers.

---

## Project Goals

1. Perform in-depth EDA to uncover churn patterns
2. Identify the **top factors** driving customer churn
3. Build and compare **4 ML models** to predict churn
4. Visualize findings in a **Power BI Dashboard**
5. Provide actionable **business recommendations**

---

## Project Structure

```
telecom-churn-analysis/
│
├── Telecom_churn_analysis.ipynb         # Complete analysis + ML models
│
├── telecom_customer_churn.csv           # Main dataset (7,043 customers × 38 features)
├── telecom_data_dictionary.csv          # Column descriptions
├── telecom_zipcode_population.csv       # ZIP code population data
│
├── README.md
└── .gitignore
```

---

##  Dataset

| Property | Value |
|---|---|
| Rows | 7,043 customers |
| Columns | 38 features |
| Target Variable | `Customer Status` (Churned / Stayed / Joined) |
| Churn Rate | ~26.5% |

---

## Analysis Performed

### Exploratory Data Analysis (EDA)
- ✅ Overall churn rate & distribution
- ✅ Churn reasons & categories (why customers leave)
- ✅ Contract type vs churn
- ✅ Tenure vs churn (grouped by tenure range)
- ✅ Monthly & total charges vs churn
- ✅ Gender, age, partner & dependents analysis
- ✅ Internet service & type analysis
- ✅ Feature correlation heatmap
- ✅ ZIP code population analysis

### Machine Learning (4 Models Compared)
| Model | Notes |
|---|---|
| Logistic Regression | Baseline model |
| Decision Tree | Interpretable rules |
| Random Forest | Ensemble, high accuracy |
| Gradient Boosting | Best performance |

- ✅ Feature engineering & label encoding
- ✅ StandardScaler normalization
- ✅ Cross-validation (5-fold)
- ✅ ROC-AUC comparison
- ✅ Confusion matrix
- ✅ Feature importance chart

---

##  Key Findings

| # | Insight |
|---|---|
| 1 | **~26% of customers churned** — major revenue impact |
| 2 | **Competitor offers** are the #1 churn reason |
| 3 | **Month-to-month** customers churn 3× more than yearly contract customers |
| 4 | **New customers (0–12 months)** are at the highest risk |
| 5 | **Higher monthly charges** are associated with higher churn |
| 6 | Customers **without dependents or partner** churn more |

---

##  Business Recommendations

1. **Incentivize long-term contracts** — offer discounts to switch from month-to-month plans
2. **Early retention program** — proactive support for customers in their first 12 months
3. **Competitive pricing** — review pricing strategy since competitors are the #1 churn driver
4. **Deploy ML model** — flag at-risk customers monthly for targeted outreach
5. **Loyalty rewards** — recognize and reward long-tenure customers

---

## Technologies Used

- **Python 3.10** — core language
- **Pandas & NumPy** — data manipulation
- **Matplotlib & Seaborn** — visualization
- **Scikit-learn** — ML models, evaluation metrics
- **Power BI** — interactive dashboard

---

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/telecom-churn-analysis.git
   cd telecom-churn-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `Telecom_Churn_Analysis.ipynb` and run all cells.

---


