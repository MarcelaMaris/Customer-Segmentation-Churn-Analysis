<p align="center">
  <img src="cover_customer.png" width="100%" alt="Customer Segmentation & Churn Analysis Dashboard cover">
</p>

## <img src="icons/cohort.png" width="50">  &nbsp;&nbsp; Customer Segmentation & Churn Analysis — Everything Plus
<br>

![Python](https://img.shields.io/badge/Python-3.10%2B-0A3756?style=flat&logo=python&logoColor=F5F7FA&labelColor=E8AA3A)
![Pandas](https://img.shields.io/badge/Pandas-lib-0A3756?style=flat&logo=pandas&logoColor=F5F7FA&labelColor=E8AA3A)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-0A3756?style=flat&logo=jupyter&logoColor=F5F7FA&labelColor=E8AA3A)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-0A3756?style=flat&logo=tableau&logoColor=F5F7FA&labelColor=E8AA3A)
![Machine Learning](https://img.shields.io/badge/ML-KMeans%20%7C%20LogReg%20%7C%20RandomForest-0A3756?style=flat&logo=academia&logoColor=F5F7FA&labelColor=E8AA3A)

> This project analyses **customer behaviour, segmentation, and inactivity risk** using transactional data  
> from a fictional e-commerce retailer, *Everything Plus*.
>
> The objective is to understand **how customers differ in purchasing patterns**,  
> **which profiles generate the most value**, and **how analytics can support retention and marketing decisions**.
>
> The project combines **Python-based exploratory and predictive analysis** with an  
> **interactive Tableau dashboard**, translating behavioural data into **business-ready insights**.
>
> It mirrors how a **Data Analyst or Business Analyst** would investigate customer value, churn signals,  
> and segmentation in a real commercial environment.<br>
---

## <img src="icons/objectives.png" width="30">  &nbsp;&nbsp;Objectives

- Prepare and clean large-scale transactional data for analysis.
- Build **customer-level behavioural features** (frequency, value, recency).
- Identify **distinct customer segments** based on purchasing behaviour.
- Evaluate relationships between behaviour and **inactivity risk (churn proxy)**.
- Develop predictive models to **prioritise retention actions**.
- Communicate insights through **clear dashboards and recommendations**.

---

## <img src="icons/features.png" width="30">  &nbsp;&nbsp;Key Analyses & Features

- **Data Cleaning & Validation:**  
  Handling missing customer IDs, invalid transactions, and extreme values.

- **Exploratory Data Analysis (EDA):**  
  Purchase frequency, revenue distribution, product performance, and temporal trends.

- **Customer Behaviour Profiling:**  
  Construction of frequency, monetary value, and average order value (AOV) metrics.

- **Customer Segmentation:**  
  K-Means clustering to identify:
  - A large **standard customer group**
  - A **high-frequency, loyal segment**
  - A very small **high-ticket / extreme-value segment**

- **Hypothesis Testing:**  
  Proportion Z-tests to evaluate whether individual behavioural variables  
  are linearly associated with inactivity.

- **Predictive Modelling:**  
  Logistic Regression and Random Forest models to estimate **inactivity risk**  
  using multiple behavioural signals simultaneously.

---

## <img src="icons/dataset.png" width="30">  &nbsp;&nbsp;Dataset

**Source:**  
Simulated transactional dataset representing an e-commerce retailer.

**Key Fields**
- Invoice and product identifiers  
- Transaction dates  
- Quantity and unit price  
- Customer identifiers  

**Notes**
- Monetary values are treated as **generic currency units**.
- The dataset is fictional and designed to simulate realistic e-commerce behaviour.

---

## <img src="icons/dashboard.png" width="30">  &nbsp;&nbsp;Interactive Dashboard

Insights are summarised in an **interactive Tableau dashboard** designed for  
marketing and business stakeholders.

### Dashboard highlights
1. **Customer segmentation overview**  
   Distribution of customers across behavioural clusters.

2. **Frequency × Ticket analysis**  
   Visual comparison of purchase frequency and average order value.

3. **Spending patterns**  
   Identification of high-value vs. low-value customer profiles.

🔗 **Live Tableau dashboard:**  
https://public.tableau.com/app/profile/marcela.stephanie.pereira.maris1628/viz/DashboarddeAnlisedeClientes/Dashboard1

---

## <img src="icons/conclusions.png" width="30">  &nbsp;&nbsp;Key Insights

- The customer base is **highly heterogeneous**, with strong dispersion in frequency and spending.
- Most customers belong to a **low-frequency, moderate-value segment**.
- A small group of **high-frequency customers** contributes significantly to total revenue.
- Extremely high-ticket customers exist but represent **rare, outlier profiles**.
- Simple statistical tests did not reveal strong linear relationships with churn,  
  while machine learning models captured **complex behavioural interactions**.

---

## <img src="icons/recommendations.png" width="30">  &nbsp;&nbsp;Recommendations

- **Segment-specific strategies**
  - High-frequency customers: loyalty programmes and retention incentives.
  - Standard customers: cross-selling and personalised offers.
  - High-ticket customers: premium support and tailored engagement.

- **Early warning system**
  Monitor inactivity signals (e.g. declining frequency, increasing recency gaps).

- **Model refinement**
  In a production environment:
  - Use **time-based validation**
  - Define churn with **forward-looking windows**
  - Avoid data leakage by excluding features used to define the target

- **Experimentation**
  Test retention actions via A/B testing to measure uplift and ROI.

---

## <img src="icons/impact.png" width="30">  &nbsp;&nbsp;Business Impact

- Enabled **data-driven customer segmentation**.
- Supported **prioritisation of retention efforts**.
- Highlighted opportunities in **product mix and pricing strategy**.
- Delivered insights in a **dashboard-ready format** for decision-makers.

---

## <img src="icons/techstack.png" width="30">  &nbsp;&nbsp;Tech Stack

- **Languages & Libraries:** Python (3.10), Pandas, NumPy, Matplotlib, Seaborn  
- **Statistical Analysis:** SciPy, Statsmodels  
- **Machine Learning:** scikit-learn (K-Means, Logistic Regression, Random Forest)  
- **Visualisation:** Tableau, Jupyter Notebook  
- **Version Control:** Git & GitHub  

---

<p align="center">
  <sub>📊 Designed & developed by <b>Marcela Maris</b> — Data Analytics Portfolio</sub><br>
  <sub><i>Customer Analytics • Segmentation • Churn Modelling</i></sub>
</p>






