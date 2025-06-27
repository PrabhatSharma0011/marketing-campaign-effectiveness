# 📊 Marketing Campaign Effectiveness Project

**Objective**  
Analyze the effectiveness of different contact methods and campaign strategies in driving term deposit subscriptions.

**Dataset**  
[Bank Marketing Dataset from Kaggle](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)

**Tools Used**  
- Python (Pandas, NumPy, SciPy)
- SQL (concepts implemented using Pandas)
- Jupyter Notebook
- Statistical Testing (Chi-Square)

**Project Workflow**
1. Load and clean the dataset using `pandas.read_csv()`
2. Explore data with SQL-style aggregations using `groupby()` and `value_counts()`
3. Calculate conversion rates by contact method and campaign month
4. Run Chi-Square test to check for significance in contact method vs deposit outcome
5. Present key business insights and recommendations

**Key Insights**
- **Cellular** contact had a higher conversion rate (~14%) compared to **telephone** (~9%)
- March and August were the most effective campaign months
- Chi-Square test result (p < 0.05) shows that contact method has a statistically significant effect on conversions

**Business Recommendation**
- Prioritize cellular contacts and optimize campaign timing around peak conversion months to boost effectiveness

**Files Included**
- `Marketing_Campaign_Effectiveness.ipynb` – Full notebook analysis
- `README.md` – Project overview

**Author**  
Prabhat Sharma  
*Aspiring Data Analyst | Final Year CS Undergraduate*

