# 📊 Sales Performance Dashboard

An interactive Power BI dashboard visualizing key sales metrics across regions, products, and channels. The project provides insights into conversion rates, churn, and revenue using dynamic visuals and calculated KPIs. It uses a sample Excel dataset and showcases visuals often used in analyst and consulting roles.

---

## 🚀 Features

- 📊 Visualizes sales across Region, Product, and Channel
- 💡 Calculates and displays **Conversion Rate** and **Churn Rate** using DAX
- 📈 Includes bar, pie, line charts, cards, and interactive slicers
- 📋 Based on clean Excel input and formatted for presentation-level quality

---

## 🛠️ Tech Stack

| Tool     | Purpose                          |
|----------|----------------------------------|
| Power BI | Building interactive dashboards  |
| Excel    | Storing and preprocessing data   |
| DAX      | Custom metrics (Conversion, Churn) |
| GitHub   | Version control and sharing      |

---

## 📁 Project Structure

```
sales-performance-dashboard/
├── data/
│   └── sales_data.xlsx
├── Sales_Dashboard.pbix
├── screenshots/
│   └── dashboard_view.png
└── README.md
```

---

## 📸 Sample Output

### 🔹 Dashboard View
![Dashboard Output](screenshots/dashboard_view.png)

---

## 💻 How to Run Locally

1. Open Power BI Desktop
2. Load the `data/sales_data.xlsx` file
3. Recreate visualizations using standard visuals and calculated columns:

```DAX
Conversion Rate = DIVIDE(Sales[Conversions], Sales[Customers])
Churn Rate = DIVIDE(Sales[Churned], Sales[Customers])
```

4. Save the file as `Sales_Dashboard.pbix`

---

## 📝 Getting Started

1. **Prerequisites**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
   - Microsoft Excel (any recent version)

2. **Setup Steps**
   - Clone or download this repository to your local machine
   - Open Power BI Desktop
   - Load the Excel file from `data/sales_data.xlsx`
   - Explore and interact with the visuals and slicers

---

## 🧠 Learning Path (for beginners)

1. Learn Excel basics and create sales datasets
2. Learn Power BI: importing, visualizations, formatting
3. Learn DAX: calculated columns and measures
4. Learn Git & GitHub for version control
5. Understand key business KPIs (Sales, Conversion, Churn)

---

## 🧪 Sample Data (Preview)

| Date       | Region | Product | Channel     | Sales  | Customers | Conversions | Churned |
|------------|--------|---------|-------------|--------|-----------|-------------|---------|
| 2024-01-05 | North  | Laptop  | Online      | 55000  | 100       | 75          | 10      |
| 2024-01-06 | South  | Mobile  | Retail      | 62000  | 90        | 68          | 5       |
| 2024-01-07 | West   | Laptop  | Distributor | 47000  | 80        | 65          | 3       |

---

## 👨‍💻 Author

**Divyansh**  
📧 [work.divyansh2610@gmail.com](mailto:work.divyansh2610@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/divyansh-03659126b)  
💻 [GitHub](https://github.com/divvyaanssh)

---

## 🏁 Project Status

✅ Completed — Created for business analyst portfolio with Power BI and Excel-based KPIs.

---

## 📌 Notes

- You can modify the Excel dataset to reflect industry-specific sales KPIs.
- Screenshots are helpful to showcase dashboard visuals in interviews or portfolios.