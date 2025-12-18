<p align="center">
  <img src="cover_customer.png" width="100%" alt="Customer Segmentation & Churn Analysis Dashboard cover">
</p>

## <img src="icons/cohort.png" width="55">  &nbsp;&nbsp; Customer Segmentation & Churn Analysis - Everything Plus
<br>

![Python](https://img.shields.io/badge/Python-3.10%2B-0A3756?style=flat&logo=python&logoColor=F5F7FA&labelColor=E8AA3A)
![Pandas](https://img.shields.io/badge/Pandas-lib-0A3756?style=flat&logo=pandas&logoColor=F5F7FA&labelColor=E8AA3A)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-0A3756?style=flat&logo=jupyter&logoColor=F5F7FA&labelColor=E8AA3A)
![Tableau](https://img.shields.io/badge/Tableau-Dashboard-0A3756?style=flat&logo=tableau&logoColor=F5F7FA&labelColor=E8AA3A)
![Machine Learning](https://img.shields.io/badge/ML-KMeans%20%7C%20LogReg%20%7C%20RandomForest-0A3756?style=flat&logo=academia&logoColor=F5F7FA&labelColor=E8AA3A)
> This project was developed as part of the **Data Analytics Bootcamp at [TripleTen](https://tripleten.com)**.  
> Using **transactional data** from a fictional retailer, Everything Plus, the project identifies **behavioral patterns**, segments customers, and predicts **churn risk** to support data-driven retention strategies and targeted marketing actions.
> 
> The analysis was conducted in **Jupyter Notebooks** and summarized in an **interactive Tableau dashboard**, combining **EDA**, **K-Means clustering**, hypothesis testing, and predictive modeling.
> 
> 🔗 **Live dashboard:** https://public.tableau.com/app/profile/marcela.stephanie.pereira.maris1628/viz/DashboarddeAnlisedeClientes/Dashboard1  
> 💻 **Repository:** https://github.com/MarcelaMaris/Customer-Segmentation-Churn-Analysis

---

## <img src="icons/objectives.png" width="30">  &nbsp;&nbsp;Objectives
- Clean and prepare transaction data; build **customer-level behavioural features**.
- Perform **EDA** on order frequency, average ticket, products and revenue.  
- Segment customers with **K-Means** and interpret cluster profiles.  
- Test hypotheses relating behavior to **inactivity (churn)**.  
- Train predictive models (Logistic Regression, Random Forest) to **flag at-risk customers**.
- Translate analytical findings into **business-ready dashboards and recommendations**.

---

 ## <img src="icons/features.png" width="30">  &nbsp;&nbsp;Key Analyses & Features
- 📈 **Cluster overview** – Bar chart showing the number of customers per cluster.  
- 🫧 **Frequency × Ticket bubble chart** – Scatterplot illustrating customer segmentation based on purchase frequency and average ticket.  
- 📦 **Spend distribution** – Histogram showing the distribution of total customer spend.  


---

## 📌 Conclusions
- Most customers have **low purchase frequency** (median = 2) and **moderate average ticket**, indicating a predominantly occasional buyer base.
- **Volume leaders ≠ Revenue leaders**: the top-selling items by units were not always the ones generating the most revenue, highlighting cross-selling and pricing opportunities.
- Customer segmentation (K=3) revealed three clear profiles:
  - 🟦 **Standard group** (majority): low frequency, moderate ticket — stable but not high-value.
  - 🟥 **High-ticket group**: very small, few orders but extremely high AOV — potentially corporate buyers or outliers.
  - 🟩 **High-frequency group**: loyal and frequent buyers with lower AOV — ideal for loyalty or upselling campaigns.
- Predictive churn models achieved **exceptionally high performance (F1 ≈ 1.00)**. While this shows strong patterns in the data, it also raises concerns about **potential overfitting or data leakage**, especially around churn definition.
- **Behavior alone wasn’t strongly correlated with churn** in hypothesis tests, but machine learning captured complex combinations of features that were predictive.

---

## 📝 Recommendations
- **Targeted retention campaigns per segment**  
  - 🟩 High-frequency: loyalty perks, subscription offers, early access.  
  - 🟦 Standard: cross-selling and personalized recommendations.  
  - 🟥 High-ticket: dedicated account management and premium services.
  
- **Early churn warning system**  
  Monitor “days since last purchase” continuously and trigger proactive re-engagement actions for at-risk customers.

- **Refine churn definition and validation**  
  Use rolling windows or survival analysis to define inactivity more robustly, and adopt **time-based validation** to avoid data leakage.

- **Feature engineering**  
  Enrich the model with seasonality, product mix, acquisition channel, or region to improve accuracy and generalization.

- **Model monitoring and retraining**  
  Reassess churn models periodically as customer behavior and business strategy evolve.

- **Experimentation layer**  
  Test retention actions on at-risk segments and measure uplift, closing the loop between prediction and marketing effectiveness.


---
## <img src="icons/impact.png" width="30">  &nbsp;&nbsp;Business Impact
- Identified distinct customer segments for **personalized marketing**.  
- Built a churn prediction model to **prioritize retention efforts**.  
- Highlighted strategic opportunities in product mix and pricing.  
- Delivered insights through a **Tableau dashboard** for easy business adoption.


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





