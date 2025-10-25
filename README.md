# 📊 CodeAlpha Data Analytics Internship — Task 3  
## 🎨 E-Commerce Sales Dashboard — Data Visualization Project  
👨‍💻 **By Sri Venkata Satyanarayana Gattu**

---

## 🧩 Project Overview
This project was developed as part of my **CodeAlpha Data Analytics Internship (Task 3)**.  
The goal is to analyze e-commerce sales data and create **stunning visualizations** that provide clear business insights and help stakeholders make **data-driven decisions**.  

Using Python visualization libraries like **Matplotlib, Seaborn, and Plotly**, I built an **interactive and analytical dashboard** that covers trends, profitability, customer demographics, and category-level performance.

---

## 🎯 Objectives
- Visualize sales and profit trends over time  
- Compare category and regional performance  
- Understand customer demographics and satisfaction  
- Identify top-performing segments, products, and time periods  
- Build an interactive dashboard for better business insights  

---

## 🗂️ Dataset Description
You can use either:
- **Kaggle Dataset:** [E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
  _(Rename file to `data.csv` if downloaded manually)_  
- OR  
- **Auto-generated Sample Data** (included in this notebook — no need to download anything)

### Key Columns
| Column | Description |
|---------|-------------|
| `date` | Order date |
| `product_category` | Category of product |
| `region` | Sales region |
| `customer_age` | Age of customer |
| `sales_amount` | Sales value |
| `profit` | Profit earned |
| `discount_applied` | Whether discount was given |
| `payment_method` | Payment mode used |
| `quantity` | Quantity sold |
| `satisfaction` | Customer satisfaction rating |

---

## 🧹 Data Preprocessing Steps
1. Converted date columns to proper datetime format  
2. Extracted `year`, `month`, `quarter`, and `day_of_week`  
3. Created an `age_group` field using `pd.cut()`  
4. Calculated new metrics — `profit_margin`, `rolling averages`  
5. Adjusted sales for discounts and seasonal spikes  
6. Removed inconsistencies and prepared data for visualization  

---

## 📊 Visualizations & Insights

### 1️⃣ **Sales Trend Analysis**
- **Type:** Line chart  
- Shows daily, weekly, and monthly sales trends with 7-day and 30-day moving averages  
- Helps visualize growth and seasonality patterns  
📁 Output: `sales_trend_analysis.png`

### 2️⃣ **Category Performance**
- **Type:** Multi-chart dashboard (sales, profit, margin, quantity by category)  
- Highlights which categories are most profitable and have high demand  
📁 Output: `category_performance.png`

### 3️⃣ **Regional Sales Heatmap**
- **Type:** Seaborn Heatmap  
- Displays category-wise sales distribution across regions  
📁 Output: `regional_heatmap.png`

### 4️⃣ **Monthly Performance**
- **Type:** Line chart (multi-year comparison)  
- Analyzes seasonal trends and monthly sales spikes  
📁 Output: `monthly_comparison.png`

### 5️⃣ **Customer Demographics**
- **Type:** Multi-chart view  
- Analyzes age distribution, payment methods, satisfaction levels, and purchase behavior  
📁 Output: `customer_demographics.png`

### 6️⃣ **Comprehensive Dashboard**
- **Type:** Grid layout (KPIs + visuals)  
- Combines key performance indicators (sales, profit, transactions) and supporting charts  
📁 Output: `comprehensive_dashboard.png`

### 7️⃣ **Interactive Visualizations (Plotly)**
- **Sunburst Chart:** Visualizes category → region → sales flow  
- **Scatter Plot:** Customer age vs sales, color-coded by product category  
📁 Output:  
  - `interactive_sunburst.html`  
  - `interactive_scatter.html`

---

## 📈 Key Insights
- **Total Records Processed:** 82,000+  
- **Best Performing Category:** Electronics  
- **Top Region:** North Zone  
- **Average Profit Margin:** 27.4%  
- **Discounted Orders:** ~30% of all sales  
- **Seasonal Trend:** Sales peak during Oct–Dec due to festival offers  
- **Customer Behavior:**  
  - Most buyers aged **26–35 years**  
  - **Credit Cards** used by ~35% of customers  
  - High satisfaction ratings correlate with lower discount usage  

---

## ⚙️ Technologies & Libraries Used
| Library | Purpose |
|----------|----------|
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Mathematical operations |
| **Matplotlib** | Static visualizations |
| **Seaborn** | Statistical plots and heatmaps |
| **Plotly** | Interactive dashboards |
| **Datetime** | Date and time processing |
| **Warnings** | Clean notebook output |

---

---

## 📫 Author

**Name:** Sri Venkata Satyanarayana Gattu  
**Role:** CodeAlpha Data Analytics Intern  
**LinkedIn:** [linkedin.com/in/satyanarayanagattu](https://www.linkedin.com/in/satyanarayanagattu)  
**GitHub:** [github.com/SatyanarayanaG2908](https://github.com/SatyanarayanaG2908)

---

## 🏁 Conclusion

This project showcases the power of **Data Visualization** in converting complex datasets into clear, meaningful insights.  
It acts as a practical demonstration of how businesses can use **analytics dashboards** to make informed decisions, optimize strategies, and improve profitability.

⭐ *If you liked this project, don’t forget to give it a star and connect with me on [LinkedIn](https://www.linkedin.com/in/satyanarayanagattu)!*  
💬 *I’d love to hear your thoughts and feedback.*

---


