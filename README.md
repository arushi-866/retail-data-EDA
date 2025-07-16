# **Retail Data Exploratory Analysis**

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Online Retail dataset** to identify:
- Sales trends over time
- Top-selling products and countries
- Customer behavior patterns
- Outliers and anomalies that affect business insights

The analysis helps businesses optimize **inventory planning**, **pricing strategies**, and **customer segmentation**.

---

##  Key Insights
- **Seasonality:** Peak sales in **November and December** due to holiday shopping.
- **Geography:** **UK dominates sales**, followed by Netherlands, Ireland, Germany, and France.
- **Products:** High-volume, low-cost **decorative household items** are top-sellers.
- **Customer Orders:** Most orders are small (**median = 3 items**), but extreme outliers exist.
- **Returns & Errors:** Negative quantities and prices indicate returns or data entry mistakes.

---

##  Tools Used
- **Programming:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

##  Visualizations
- **Monthly Sales Trends:** Identify seasonal patterns
- **Busiest Days of the Week**
- **Top Products & Countries by Sales**
- **Outlier Detection:** Boxplots for Quantity & Price
- **Scatter Plots:** Price vs Quantity analysis

---

##  Summary of Findings
### **1. Sales Trends**
- Peak in **Nov-Dec**, dip in summer months.

### **2. Busiest Days**
- **Thursdays and Tuesdays** are busiest; weekends are slower.

### **3. Top Countries**
- UK is the major contributor; other markets: Netherlands, Ireland, Germany, France.

### **4. Top Products**
- Decorative household items dominate.
- Most orders: small quantities, but outliers up to **80,995 units**.

### **5. Outliers**
- **Quantity & UnitPrice** have extreme values.
- Negative values → returns or incorrect data.

---

##  Actionable Insights
- **Inventory Planning:** Stock up on top products before **holiday season**.
- **Data Quality:** Clean anomalies for accurate reporting.
- **Customer Segmentation:** Focus on UK but expand in EU markets.
- **Pricing Strategy:** Investigate extreme price outliers.

---

## ▶ How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/retail-data-EDA.git
   cd retail-data-EDA
   jupyter notebook retail_eda.ipynb

