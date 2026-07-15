# 🚗 Car Sales Dashboard - Power BI

## 📌 Overview

The **Car Sales Dashboard** is an interactive and dynamic Power BI project developed to analyse car dealership sales performance.

The dashboard provides valuable insights into sales trends, key performance indicators (KPIs), vehicle preferences, dealer performance, and detailed sales information. It helps business stakeholders make data-driven decisions and identify opportunities for growth.

---

# 🎯 Project Objective

The main objective of this project is to design and develop a comprehensive **Car Sales Dashboard using Microsoft Power BI** to:

- Monitor overall sales performance.
- Analyse sales growth trends.
- Track important business KPIs.
- Understand customer vehicle preferences.
- Compare dealer and company performance.
- Support data-driven decision-making.

---

# 📊 Dashboard KPIs

## 1. Sales Overview

The dashboard provides:

- ✅ Year-to-Date (YTD) Total Sales
- ✅ Month-to-Date (MTD) Total Sales
- ✅ Year-over-Year (YOY) Sales Growth
- ✅ Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales

---

## 2. Average Price Analysis

Includes:

- ✅ YTD Average Vehicle Price
- ✅ MTD Average Vehicle Price
- ✅ YOY Growth in Average Price
- ✅ Difference between YTD Average Price and PTYD Average Price

---

## 3. Cars Sold Metrics

Tracks:

- ✅ YTD Cars Sold
- ✅ MTD Cars Sold
- ✅ YOY Growth in Cars Sold
- ✅ Difference between YTD Cars Sold and PTYD Cars Sold

---

# 📈 Dashboard Visualizations

## 📌 YTD Sales Weekly Trend

**Visualization:** Line Chart

Shows weekly sales performance throughout the year to identify:

- Sales patterns
- Growth trends
- Seasonal variations

---

## 📌 YTD Sales by Body Style

**Visualization:** Pie Chart

Displays sales distribution across different vehicle body styles:

- SUV
- Sedan
- Hatchback
- Coupe
- Truck

---

## 📌 YTD Sales by Car Color

**Visualization:** Pie Chart

Shows customer preferences based on vehicle colours and their contribution to total sales.

---

## 📌 YTD Cars Sold by Dealer Region

**Visualization:** Map Chart

Displays geographical sales performance by dealer region.

Used to identify:

- High-performing regions
- Regional sales trends
- Market opportunities

---

## 📌 Company-Wise Sales Trend

**Visualization:** Table/Grid

Provides company-level sales analysis:

| Company | YTD Sales |
|---------|-----------|
| Company Name | Sales Amount |

---

## 📌 Detailed Car Sales Information

**Visualization:** Data Table

Contains detailed transaction-level information:

- Car Model
- Company Name
- Body Style
- Vehicle Colour
- Sales Amount
- Dealer Region
- Sales Date
- Other sales attributes

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI | Dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and measures |
| Excel / CSV | Data source |

---

# 📂 Repository Structure

```
Car-Sales-Dashboard/
│
├── Dataset/
│   └── car_sales_data.csv
│
├── Dashboard/
│   └── Car_Sales_Dashboard.pbix
│
├── Screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

---

# 🔄 Data Processing Workflow

## 1. Data Preparation

Data was cleaned and transformed using Power Query.

Operations performed:

- Removed duplicate records
- Handled missing values
- Updated data types
- Created calculated fields

---

## 2. Data Modelling

A structured data model was created using:

- Sales Data
- Vehicle Information
- Dealer Region Data
- Date Table

---

## 3. DAX Measures

Created measures for:

- YTD Sales
- MTD Sales
- Previous Year Sales
- YOY Growth Percentage
- Average Price
- Cars Sold Count

---

# 🚀 How to Use

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/car-sales-dashboard.git
```

### Step 2: Open Power BI File

Open:

```
Dashboard/Car_Sales_Dashboard.pbix
```

using **Microsoft Power BI Desktop**.

### Step 3: Refresh Data

Click:

```
Home → Refresh
```

to load the latest data.

---

# 📷 Dashboard Preview

Add screenshots here:

```
![Car Sales Dashboard](Screenshots/dashboard_preview.png)
```

---

# 💡 Key Insights Generated

The dashboard helps identify:

- Overall sales performance
- Monthly and yearly growth trends
- Best-selling vehicle categories
- Popular car colours
- Regional sales performance
- Top-performing companies
- Detailed vehicle sales information

---

# 🚀 Future Enhancements

Future improvements may include:

- Machine Learning-based sales forecasting
- Customer segmentation analysis
- Real-time sales data integration
- Predictive analytics for vehicle demand
- Power BI Service deployment

---

# 👨‍💻 Author

**Thurunu Gunarathna**

Computer Science Graduate

**Skills:**

- Power BI
- Data Analytics
- SQL
- Python
- Machine Learning

---

# 📄 License

This project is developed for educational and portfolio purposes.
