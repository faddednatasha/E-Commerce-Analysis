# 📊 E-Commerce Analysis  
---

An end-to-end data analytics project exploring the Brazilian E-Commerce ecosystem. This project transforms raw transactional data into actionable business insights using Python for EDA and Power BI for interactive visualization.

---

## 📂 Repository Structure  

- **`data/`** → 📦 Contains interconnected datasets .
- **`Data_overview.ipynb`** → Initial dataset exploration and schema validation.
- **`EDA.ipynb` & `EDA_Report.ipynb`** → Deep-dive Exploratory Data Analysis.
- **`E-COM_VISUALIZATION.pbix`** → 📊 **Interactive Power BI Dashboard.**
- **`README.md`** → Project documentation.

---
<img width="1176" height="664" alt="image" src="https://github.com/user-attachments/assets/c977cbc3-c476-4997-93c5-c18de374d7f2" />

---

## 📖 Data Dictionary  

The analysis is built upon a relational schema of 10 datasets:

| Dataset | Description | Key Features |
| :--- | :--- | :--- |
| **orders** | Core transaction logs | Order status, timestamps (purchase, delivery). |
| **payments** | Financial details | Payment type, installments, transaction value. |
| **items** | Product-order links | Price, freight value, seller ID. |
| **customers** | Buyer demographics | Customer city, state, zip code. |
| **products** | Item metadata | Category names, dimensions, weight. |
| **reviews** | Satisfaction data | Review scores (1-5), comment timestamps. |
| **geolocation**| Spatial data | Latitude/Longitude coordinates for mapping. |

---

## 📈 Key Insights  

- **Revenue Driver:** **São Paulo (SP)** is the primary hub, contributing significantly to total revenue.
- **Payment Behavior:** **Credit Cards** are the preferred payment method, accounting for the majority of transactions.
- **Logistics Performance:** Delivery times vary significantly by region; northern states experience higher lead times.
- **Customer Satisfaction:** The average review score remains strong at ~4.0/5.0, indicating high service reliability.

---

## 🔍 Interactive Dashboard  

The Power BI dashboard provides a dynamic view of business performance.  

### **Dashboard Features:**
- **Sales KPI Tracking:** Total Revenue, Order Volume, and AOV.
- **Geospatial Mapping:** Revenue distribution across Brazilian states.
- **Order Lifecycle:** Monitoring delivery success vs. cancellation rates.
- **Payment Analysis:** Breakdown of installments and payment types.

---

## 🛠️ Tech Stack  

- **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Visualization:** Power BI Desktop
- **Tools:** VS Code, Jupyter Notebook, Git LFS

---

