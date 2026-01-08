# Retail FMCG Sales Analytics | Power BI & SQL

# Project Overview
This project simulates a real-world FMCG retail analytics scenario using SQL Server and Power BI.
The objective was to design a clean data model, generate realistic transactional data, and build
business-focused dashboards that support both operational analysis and executive decision-making.

---

# Tools & Technologies
- SQL Server (Database design, data generation, validation)
- Power BI (Data modeling, DAX, visualization)
- DAX (KPIs, time intelligence, rolling metrics)

---

# Data Model
The data follows a star schema design:

**Fact Tables**
- Orders
- Order Items

**Dimension Tables**
- Products
- Categories
- Customers
- Stores
- Calendar

The model supports scalable time-based analysis and category-level performance insights.

![Data Model](data_model.png)

---

# Dashboards

# Sales Overview
Provides a high-level view of overall business performance.
- Total Revenue, Orders, Customers
- Revenue by channel and store

![Sales Overview](dashboard_sales_overview.png)

---

# Time Intelligence
Focuses on growth trends and performance over time.
- Month-on-Month revenue growth
- Rolling 3-month revenue
- Running totals

![Time Intelligence](dashboard_time_intelligence.png)

---

### 3️⃣ Product & Category Performance
Analyses revenue drivers and pricing dynamics.
- Top products by revenue
- Category-level pricing vs volume analysis
- Margin awareness across product segments

![Product Performance](dashboard_product_category.png)

---

### 4️⃣ Executive Summary
A leadership-focused view designed for quick decision-making.
- Core KPIs (Revenue, Orders, Margin)
- Revenue trend analysis
- Key business insights and performance drivers

![Executive Summary](dashboard_executive_summary.png)

---

# Key Business Insights
- Revenue shows a stable upward trend with positive month-on-month growth.
- Performance is driven by a small set of high-performing products and categories.
- High-volume products operate at lower margins, indicating pricing pressure.
- Premium products contribute strong revenue with lower sales volumes.

---

# Future Enhancements
- Customer segmentation and repeat purchase analysis
- Promotion and discount impact analysis
- Forecasting and demand planning
