# 🏦 District Benefit Transfer (DBT) – Exploratory Data Analysis

## 📘 Overview
This project performs an **Exploratory Data Analysis (EDA)** on India’s **Direct Benefit Transfer (DBT)** dataset to identify **patterns, trends, and insights** across states and districts.  
It focuses on **fund disbursement, transaction patterns, and welfare impact** through data-driven insights.

> 📊 *“Data-driven governance promotes transparency, accountability, and efficiency in public welfare.”*

---

## 👨‍💻 Author & Institution
**Name:** Parikshit Abuj  
**PRN:** 22070521009  
**Semester:** 7 (Section A)  
**Institute:** Symbiosis Institute of Technology, Nagpur  
**Guide:** Dr. Piyush Chauhan  

---

## 🧩 Project Objectives
- Analyze yearly growth and performance of DBT across India  
- Identify **top-performing states and districts** by transfer amount and transactions  
- Study the **relationship between transaction volume and transfer amount**  
- Apply **ML models (K-Means, Regression, Decision Tree, Logistic Regression)** for pattern discovery and classification  
- Support **data-driven decision making** in governance  

---

## 🧹 Data Cleaning & Preprocessing
1. Standardized column names (lowercase, underscores)  
2. Handled missing values (121 null rows removed)  
3. Checked and confirmed no duplicate rows  
4. Corrected data types (numeric columns as float, FY as string)  
5. Final cleaned dataset: **3,704 entries**

---

## 📈 Key Insights from EDA

### 📅 Yearly Trends
- Total DBT Transfers grew from **₹0.25 trillion (2019–20)** to **₹7 trillion (2022–23)**  
- Drop in 2023–24 likely due to **scheme restructuring and validation**

### 🏙️ Top 10 Districts by Transfers
- **Pune, Aurangabad, Belagavi, South 24 Parganas** lead in total funds  
- These regions have strong digital infrastructure and higher welfare coverage

### 🧾 Top 10 Districts by Transactions
- **Bengaluru Urban, Mumbai Suburban, Pune, Chennai** dominate in total transactions  
- Reflects high adoption of digital welfare systems in urban areas

### 📊 Distributions
- **Right-skewed** distributions show most districts handle smaller DBT volumes  
- Only a few major districts manage **large-scale disbursements**

### 🌍 Top States by Weighted Average Transfer per Transaction
- **Lakshadweep, Meghalaya, Tripura, Assam** top the list  
- Indicates high-value transactions in smaller regions

---

## 🤖 Machine Learning Models Applied

### 1. **K-Means Clustering (K=3)**
Grouped districts into:
- **Cluster 0:** Low volume  
- **Cluster 1:** Moderate volume  
- **Cluster 2:** High volume (economic hubs)

### 2. **Simple Linear Regression**
- Analyzed relationship between **Transactions vs Transfers**  
- R² = **0.6357**, showing strong positive correlation

### 3. **Logistic Regression**
- Classified districts as **High** or **Low** DBT areas  
- Accuracy: **90.6%**, Precision (High): **91.5%**, Recall: **88.9%**

### 4. **Decision Tree Classifier**
- Accuracy: **90.2%**  
- Balanced precision and recall for both classes

---

## 🧮 Tools & Libraries Used
| Category | Libraries |
|-----------|------------|
| **Data Handling** | pandas, numpy |
| **Visualization** | matplotlib, seaborn, plotly |
| **ML Models** | scikit-learn |
| **Notebook** | Jupyter Notebook |
| **Environment** | Python 3.10+ |

---

## 📊 Visualizations Included
- Yearly Trend of DBT Transfers  
- Yearly DBT Transactions  
- Top 10 Districts / States (Transfers & Transactions)  
- Weighted Average Transfer per Transaction  
- Distribution Charts (Transfers, Transactions)  
- K-Means Cluster Plot  
- Regression Line Plot  
- Confusion Matrix (Logistic & Decision Tree)

---

## 🏁 Conclusion
- DBT initiatives have **significantly improved transparency and delivery**.  
- **Uttar Pradesh, Bihar, and Maharashtra** are top-performing states by transaction volume.  
- **Technology-driven governance** ensures efficient fund transfers and inclusion.  
- Machine learning helps classify and understand welfare performance patterns effectively.  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/dbt_eda_project.git
