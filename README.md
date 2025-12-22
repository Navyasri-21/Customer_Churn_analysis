# 📖 Customer Churn Analysis
## Project Overview:
This Project analyzes telecom customer data to understand which customers are likely to churn and why.
The dashboard is built in **Power BI** using the 'telcom.csv' dataset.


## 🎯 Goals
- Calculate overall churn rate.
- Identify high-risk customer segments.
- Provide insights and recommendations to reduce churns.

  

## 📂  Dataset and Data Model
- Dataset:Customer demographics, services, contract type, payment method, and churn.
- Steps: Cleaned data, created calculated measures (Total Customers, Churned Customers, churn Rate, Total Revenue), and built the data model.
  <img width="654" height="974" alt="image" src="https://github.com/user-attachments/assets/8e1f3564-9de9-4931-ba6e-cfa826e62d05" />



## Detailed Analysis Pages

### Contract Analysis
<img width="1359" height="763" alt="image" src="https://github.com/user-attachments/assets/a939223e-2b37-4bf2-ab52-fbfabe32a051" />


<img width="1316" height="751" alt="image" src="https://github.com/user-attachments/assets/59c5fa8a-eaa5-43a5-bee9-1d8491c1fc9d" />


<img width="1320" height="675" alt="image" src="https://github.com/user-attachments/assets/f2083008-0db7-45b4-b4a2-89c003d456fa" />


<img width="1335" height="759" alt="image" src="https://github.com/user-attachments/assets/1170347c-2205-41af-b68e-19df65c5674b" />


<img width="1193" height="920" alt="image" src="https://github.com/user-attachments/assets/76aea695-cac2-4911-9c26-8575ca2ebcb1" />


## 📊  Key Insights (With Numbers)

📌  The overall **churn rate is 26.54%** with **1,869 churned customers out of 7,043**, leaving **5,174 active customers** in the base.  
📌 **Month‑to‑month contracts** are the most unstable: their churn rate is around **42.71%**, compared to roughly **11.2% for 1‑year contracts** and **2–3% for 2‑year contracts**, showing that long‑term contracts are far more resilient.  
📌 Customers paying via **electronic check** churn at about **45%**, while customers on automatic payments (credit card / bank transfer) churn closer to the mid‑teens (around **16%**), indicating that payment friction is a major churn driver.  
📌  Customers **without TechSupport** have churn above **40%**, significantly higher than those with TechSupport enabled, who churn closer to the mid‑20% range.  
📌  Revenue analysis shows roughly **₹2.8 Cr in churned revenue** and more than **₹1.2 Cr tagged as “high‑risk revenue”** from active customers with risky profiles (month‑to‑month, electronic check, no TechSupport, short tenure).  

## 💡 Recommendations (Number‑Driven)

 📌 **Contract strategy:**  
  - Target month‑to‑month customers (churn **42.71%**) with upgrades to **1‑year contracts (≈11.2% churn)** or longer.  
  - Even if only a portion of them convert, each **10 percentage‑point drop** in churn in this segment can save **hundreds of customers** and a meaningful share of the **₹1.2 Cr high‑risk revenue**.

 📌 **Payment method optimization:**  
  - Prioritize campaigns that move customers from **electronic check (≈45% churn)** to **auto‑pay methods (≈16% churn)**.  
  - If half of electronic‑check users switch, the churn rate for that group could drop by almost **15 percentage points**, directly protecting a large fraction of high‑risk revenue.

 📌 **Support and service bundling:**  
  - Focus on customers with **no TechSupport (>40% churn)** by offering discounted or bundled support plans.  
  - Bringing this group closer to the churn level of supported customers (mid‑20%) would mean roughly a **15–20 percentage‑point improvement** and a sizable reduction in future churned revenue.

📌  **Revenue‑focused retention:**  
  - Use the high‑risk revenue flag (≈**₹1.2 Cr**) to build a prioritized call/offer list starting with **high‑ARPU, high‑risk profiles** (month‑to‑month + electronic check + no TechSupport).  
  - Even converting **20–30%** of these high‑risk customers to safer profiles (longer contract + auto‑pay + TechSupport) can protect **tens of lakhs of rupees** in annual revenue.

 📌 **Model‑driven follow‑up:**  
  - Train a churn model using the above features (contract type, payment method, TechSupport, tenure, charges) and regularly score all **5,174 active customers**.  
  - Use score thresholds to trigger retention flows for the top **10–20% highest‑risk** customers, ensuring interventions are focused where the **numerical lift in churn reduction** is greatest.

## 🔧  Technologies Used

- Power BI Desktop / Power BI Service  
- Dataset: `telecom.csv`  
- Skills: Data cleaning, DAX measures, interactive dashboards, data storytelling

## Dataset Source

Due to dataset size, the raw data is not stored in this repository.

- Source: Kaggle – Telco Customer Churn Dataset  
- Dataset Name: Telco Customer Churn  
- Records: 7,043 customers  
- Format: CSV  

The dataset was downloaded from Kaggle and imported directly into Power BI.
