# AI-Driven Customer Segmentation & Business Strategy Recommendation

## Project Overview
Businesses often struggle to identify high-value customers and design personalized marketing strategies. This project uses machine learning techniques to segment customers based on their purchasing behavior and demographic attributes.

The goal is to help businesses understand different customer groups and create targeted marketing strategies.

---

## Objectives
- Identify customer segments using machine learning
- Analyze customer spending patterns
- Provide business strategy recommendations
- Visualize insights through an interactive dashboard

---

## Dataset
The dataset contains customer demographic and spending information.

Features used in the analysis:

- CustomerID
- Age
- Annual Income
- Spending Score

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI

---

## Methodology

### 1. Data Preprocessing
- Data cleaning
- Handling duplicates
- Feature scaling using StandardScaler

### 2. Exploratory Data Analysis (EDA)
- Income distribution analysis
- Spending behavior analysis
- Age distribution insights

### 3. Customer Segmentation
K-Means Clustering algorithm was applied to group customers based on similar behavior.

The Elbow Method was used to determine the optimal number of clusters.

### 4. Dashboard Visualization
An interactive Power BI dashboard was created to visualize customer segments and behavioral insights.

---

## Customer Segments Identified

1. **VIP Customers** – High income and high spending  
2. **Potential Customers** – Medium income and moderate spending  
3. **Budget Buyers** – Lower income with moderate spending  
4. **Low Value Customers** – Low income and low spending  

---

## Business Recommendations

### VIP Customers
- Offer loyalty programs
- Provide exclusive offers

### Potential Customers
- Targeted marketing campaigns
- Personalized product recommendations

### Budget Buyers
- Discount campaigns
- Bundle offers

### Low Value Customers
- Cost-efficient marketing strategies

---

## Expected Business Impact
The segmentation approach enables businesses to:

- Improve marketing efficiency
- Deliver personalized customer experiences
- Potentially increase conversion rates by **15–20%**

---

## Project Structure

```
AI-Customer-Segmentation
│
├── data
│   └── mall_customers.csv
│
├── notebook
│   └── customer_segmentation.ipynb
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── images
│   └── dashboard_preview.png
│
└── README.md
```

---

## Author
YARRAMNEEDI SATYA VENKATA NAGA SHANKAR

B.Tech Artificial Intelligence and Machine Learning  
Kalasalingam Academy of Research and Education
