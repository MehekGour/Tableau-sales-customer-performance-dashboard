# 📊 Tableau Sales & Customer Performance Dashboard

An interactive **Tableau dashboard project** built to analyze **sales performance and customer behavior** using KPIs, year-over-year comparisons, monthly trends, and detailed customer insights.

This project was completed by following the **Data With Baraa – Tableau Complete Project End-to-End** tutorial and applying the concepts step-by-step in Tableau.

---

## 📌 Project Overview

The project demonstrates how to build a real-world Tableau analytics project starting from:

- Understanding business requirements
- Planning dashboard layouts
- Preparing and modeling the data
- Creating calculated fields
- Building individual visualizations
- Designing KPI cards
- Creating Sales and Customer dashboards
- Adding filters and interactive navigation
- Formatting dashboards for a clean and professional presentation

The final project contains two main dashboards:

1. **Sales Dashboard**
2. **Customer Dashboard**

---

## 🎯 Business Objectives

The dashboard is designed to help stakeholders understand:

- Overall sales performance
- Profit performance
- Order performance
- Customer performance
- Year-over-year changes
- Monthly sales and profit trends
- Customer trends
- Sales per customer
- Highest and lowest performing periods
- Category and sub-category performance

---

# 📈 Sales Dashboard

The Sales Dashboard provides an overview of the company's sales performance.

### Key Performance Indicators

The dashboard includes KPIs for:

- 💰 **Total Sales**
- 💵 **Total Profit**
- 📦 **Total Quantity**

Each KPI compares the **Current Year (CY)** with the **Previous Year (PY)** to show year-over-year performance.

### Sales Analysis

The dashboard includes visualizations for:

- Sales by Category
- Profit by Category
- Monthly Sales Trends
- Monthly Profit Trends
- Current Year vs Previous Year comparisons
- Minimum and Maximum monthly performance

---

# 👥 Customer Dashboard

The Customer Dashboard focuses on customer-related performance.

### Key Performance Indicators

The dashboard includes:

- 👤 **Total Customers**
- 💰 **Sales per Customer**
- 📦 **Total Orders**

The KPIs provide **Current Year vs Previous Year** comparisons.

### Customer Analysis

The dashboard helps analyze:

- Customer trends over time
- Sales generated per customer
- Order trends
- Customer performance
- Highest and lowest performing months
- Current Year vs Previous Year customer metrics

---

# 📊 Dashboard Features

### Year Selection

A year parameter allows users to select the year they want to analyze.

The dashboard dynamically compares the selected year with the previous year.

### Year-over-Year Analysis

The project uses calculated fields to compare:

**Current Year vs Previous Year**

This makes it easier to identify whether business performance is improving or declining.

### Min/Max Analysis

Monthly charts highlight the **minimum and maximum performing months**, making important trends easier to identify.

### Interactive Navigation

The dashboard provides navigation between the:

- Sales Dashboard
- Customer Dashboard

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau** | Data visualization and dashboard development |
| **CSV / Dataset** | Data source |
| **Tableau Calculated Fields** | KPI and YoY calculations |
| **Table Calculations** | Min/Max and trend analysis |

---

# 🧮 Key Calculations

Some of the calculations used in the project include:

### Current Year Profit

```tableau
IF YEAR([Order Date]) = [Select Year]
THEN [Profit]
END
```

### Previous Year Profit

```tableau
IF YEAR([Order Date]) = [Select Year] - 1
THEN [Profit]
END
```

### Year-over-Year Profit Difference

```tableau
(
    SUM([CY Profit]) - SUM([PY Profit])
)
/
SUM([PY Profit])
```

### Min/Max Analysis

Table calculations such as `WINDOW_MAX()` and `WINDOW_MIN()` are used to identify the highest and lowest monthly values.

---

# 📂 Project Structure

```text
tableau-sales-customer-performance-dashboard/
│
├── README.md
│
├── Tableau/
│   └── Sales_Customer_Dashboard.twbx
│
├── Dataset/
│   └── dataset files
│
├── Screenshots/
│   ├── Sales_Dashboard.png
│   └── Customer_Dashboard.png


> Update the filenames above according to the files you actually upload to GitHub.

---


# 📸 Dashboard Preview


## Sales Dashboard

Add your Sales Dashboard screenshot here:

```markdown
![Sales Dashboard](<img width="411" height="278" alt="Screenshot 2026-11-15 135623" src="https://github.com/user-attachments/assets/be14b236-f4b0-4e7e-8db1-e72dc113e6f6" />
)
```

## Customer Dashboard

Add your Customer Dashboard screenshot here:

```markdown
![Customer Dashboard](<img width="411" height="278" alt="Screenshot 2026-11-15 135648" src="https://github.com/user-attachments/assets/a5f97629-f622-4fc8-b4de-b7136d1cd520" />
)
```

---

# 💡 Key Learning Outcomes

Through this project, I practiced:

- Tableau data modeling
- Connecting multiple data tables
- Understanding dimensions and measures
- Creating calculated fields
- Creating KPIs
- Year-over-year analysis
- Table calculations
- `WINDOW_MAX()` and `WINDOW_MIN()`
- Customer analysis
- Sales and profit analysis
- Dashboard design
- Interactive filters
- Dashboard navigation
- Data visualization best practices

---

# 📚 Learning Resource & Credits

This project was created as a **learning and portfolio project** by following the Data With Baraa Tableau project tutorial.

**Original Tutorial:**  
[Tableau Complete Project End-to-End | Like I Do in My Real Projects](https://youtu.be/dahrmqT5GD4)

**Creator:** Data With Baraa

The original project covers the complete Tableau workflow, including requirements analysis, mockup/design planning, data source preparation, chart development, Sales Dashboard creation, and Customer Dashboard creation.

For the official Tableau project materials, Data With Baraa also provides the datasets, workbooks, slides, and project files through his course resources.

---

# 👩‍💻 Author

**Mehek Gour**

Mechanical Engineering Student | Aspiring Data Analyst

### Skills

- SQL
- Python
- Excel
- Tableau
- Data Analytics
- Data Visualization

