# 🛒 Amazon E-Commerce Sales & Product Analysis Dashboard

## 📊 Project Overview
This Power BI project focuses on **Amazon Product Sales Analysis** for the **“Boys” category**, providing a complete view of sales performance, product trends, and customer behavior.  
The dashboard helps e-commerce teams and category managers make **data-driven decisions** by offering deep insights into **sales, returns, and product performance** across different geographies.

The solution includes **three interactive pages**:
- **Overview Dashboard (Macro Sales)**  
- **Products Dashboard (Catalog View)**  
- **ProductsView Dashboard (Micro Detail)**  

---

## 🎯 Objectives

### 🔹 Business & Analytical Goals
- Provide **comprehensive visibility** into Amazon sales trends and performance.  
- Enable **multi-level navigation** from overall category to specific product insights.  
- Track key KPIs like **Total Sales**, **Seller Count**, **Units Sold**, and **Return Rate**.  
- Identify **top-performing states and cities** to optimize inventory and marketing.  
- Highlight **product-specific issues** through return and review analysis.

### 🔹 Technical Goals
- Implement **interactive page navigation** and **drill-through analysis** in Power BI.  
- Utilize **DAX** for KPI calculations, trend analysis, and return-rate computation.  
- Design a **clean, e-commerce-style interface** for intuitive user experience.  

---

## 🧠 Dashboard Structure & Insights

### 🟢 **1. Overview Dashboard (Macro Sales)**
**Purpose:** Provides a high-level view of category performance and geographic insights.  

**Key Metrics:**
- **Total Sales:** 120.30K  
- **Seller Count:** 85.00  
- **Filter Sales:** 500.00  
- **Order Status Filters:** Shipped, Cancelled, Pending, etc.  

**Insights:**
- **Top States:** Maharashtra, Karnataka, Uttar Pradesh, Tamil Nadu.  
- **Top Cities:** Bengaluru, Hyderabad, Chennai.  
- **Sales Trend by City:** The time-series line graph reveals strong volatility and **seasonal peaks** (values around 17.0 and 15.0), helping identify high-demand periods and plan inventory efficiently.

---

### 🟣 **2. Products Dashboard (Catalog View)**
**Purpose:** Displays a structured catalog of all available products in the "Boys" category.  

**Key Features:**
- Product categories such as *BoysBelts, BoysDhotis, BoysGloves,* etc.  
- Product listing grid showcasing individual items like:  
  - *612 League Boys' Printed Polos*  
  - *Adidas Boys' Plain Regular Fit T-Shirts*  

**Functionality:**
- Acts as a **selection layer** — users can choose a product here to analyze detailed performance in the *ProductsView* section.

---

### 🔵 **3. ProductsView Dashboard (Micro Product Detail)**
**Purpose:** Offers a deep dive into an individual product’s sales, returns, and customer engagement.  

**Example Product:** *“612 League Boy's Plain Regular Fit T-Shirt”*

**Key Metrics:**
- **Sale Amount:** 9.81K  
- **Units Sold:** 31  
- **Return (Lost):** 237.00  
- **Customer Reviews:** 176  

**Insights:**
- **Sales Trend (Units by Month):** Shows a **sharp decline** from April to June — possibly due to product fatigue, competition, or poor seasonal demand.  
- **Return Rate:** Exceptionally high returns (237 vs. 31 units sold) indicate **quality or sizing issues**, requiring immediate review.  

---

## ⚙️ Technical Implementation

| Component | Description |
|------------|-------------|
| **Tool Used** | Microsoft Power BI Desktop |
| **Data Source** | Amazon product sales data (category: Boys) |
| **DAX Calculations** | Sales Aggregations, Return Ratios, Seller Count, Review Count |
| **Visuals Used** | Line Charts, Bar Charts, Card KPIs, and Slicers |
| **UX Design** | Clean, intuitive layout with card-based navigation for smooth interaction |

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| **Total Sales** | 120.30K |
| **Seller Count** | 85.00 |
| **Units Sold** | Product-wise sales performance |
| **Return (Lost)** | 237.00 |
| **Customer Reviews** | 176 |
| **Top Locations** | Maharashtra, Karnataka, UP, Tamil Nadu |

---

## 🧩 Features
- ✅ Multi-level interactive navigation  
- ✅ Real-time KPI cards with DAX calculations  
- ✅ State & City-level sales segmentation  
- ✅ Time-series trend visualization for each product  
- ✅ Clean, professional Power BI UI  

---

## 💡 Business Impact
This dashboard allows **e-commerce managers and analysts** to:
- Identify **high-performing and underperforming products**  
- Recognize **regional demand trends** for better inventory allocation  
- Monitor **returns and reviews** to improve product quality  
- Enhance **decision-making** through visual data storytelling  

---

## 🛠️ Tools & Technologies
- **Microsoft Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Power Query Editor**  
- **Data Modeling & Relationships**  

---

## 🧭 How to Use
1. Open the `.pbix` file in **Power BI Desktop**.  
2. Use the **navigation buttons** to move between Overview, Products, and ProductView pages.  
3. Apply **filters** (Category, City, Order Status, etc.) for dynamic exploration.  
4. Hover on KPIs and visuals for detailed tooltips.  

---

## 📸 Dashboard Previews
**Overview Page**
![Amazon Dashboard Overview](https://ik.imagekit.io/r4tkneg47/Screenshot%202025-10-02%20192137.png?updatedAt=1762619627076)

**ProductsView Page**
![Amazon Dashboard Product View](https://ik.imagekit.io/r4tkneg47/Screenshot%202025-10-02%20192159.png?updatedAt=1762619629682)

---

## 👤 Author
**Amit Ghume**  


---

> “Turning e-commerce data into insights that power smarter business decisions.”

