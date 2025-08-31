# 🛍️ Ansh Ecommerce Sales Dashboard

![Ansh Ecommerce Sales Dashboard](<img width="1536" height="1024" alt="ansh eccomerce sales dashboard" src="https://github.com/user-attachments/assets/c6ed448a-ad9f-4c3b-ad7f-fc8a4769d7a3" />
)

## 📌 Project Overview  
The **Ansh Ecommerce Sales Dashboard** provides a detailed analysis of ecommerce sales performance using Python, Power BI, and data visualization techniques.  
It helps businesses track **revenue, profit, payment trends, customer insights**, and **regional performance** to make data-driven decisions.

---

## 🚀 Key Features  
- 📊 **Sales & Profit Analysis** – Understand total revenue & profit trends  
- 🛒 **Top Products & Categories** – Find the best-selling products & categories  
- 💳 **Payment Mode Insights** – Track COD, UPI, EMI, and card usage  
- 🌎 **Regional Insights** – Discover top-performing states & cities  
- 📈 **Monthly Trends** – Visualize monthly profit & sales patterns  

---

## 📊 Key Metrics (KPIs)

| **Metric**          | **Value** | **Description**                     |
|---------------------|-----------|-------------------------------------|
| 💰 **Total Sales**  | 438K      | Total revenue generated            |
| 📦 **Quantity Sold**| 5615      | Total number of products sold      |
| 📈 **Total Profit** | 37K       | Overall profit earned             |
| 🛒 **Avg. Order Value (AOV)** | 121K | Average spend per order         |

---

## 📂 Dataset Description  

The dashboard is built using **two datasets**:

### **1️⃣ Details.csv**
- **Purpose:** Contains transaction-level order details  
- **Columns:**  
  `Order ID`, `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, `PaymentMode`

### **2️⃣ Orders.csv**
- **Purpose:** Contains customer & order-level details  
- **Columns:**  
  `Order ID`, `Order Date`, `Customer Name`, `State`, `City`

---

## ⚙️ Installation & Usage  

Clone the repository:
```bash
git clone https://github.com/Anshagrwl/ansh-ecommerce-sales-dashboard.git
cd ansh-ecommerce-sales-dashboard
pip install -r requirements.txt
python analysis.py
📌 Insights from Dashboard

🔹 Maharashtra, Madhya Pradesh & Uttar Pradesh contribute the highest revenue
🔹 COD dominates payment methods (44% of transactions)
🔹 Clothing contributes the highest quantity sold (63%)
🔹 November shows the highest profit spike
🔹 Printers & Bookcases lead in profitability

✍️ Author

Ansh Aggarwal
📌 Data Analyst & Dashboard Developer
🚀 Passionate about data-driven decision-making
