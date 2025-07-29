# 📊 Sales Performance Dashboard

An interactive Power BI dashboard visualizing key sales metrics across regions, products, and channels. The project provides insights into conversion rates, churn, and revenue using dynamic visuals and calculated KPIs.

---

## 🚀 Getting Started

1. **Clone or download** this repository to your local machine.
2. Ensure the file `data/sales_data.xlsx` is present in the `data` folder.
3. Open `Sales_Dashboard.pbix` using Power BI Desktop.
4. Refresh the data source if prompted to load the latest data.
5. Explore the dashboard visuals and interact with slicers/filters.

---

## 🧰 Tech Stack

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
├── data/sales_data.xlsx
├── Sales_Dashboard.pbix
├── screenshots/dashboard_view.png
├── README.md
```

---

## 📌 Key Visuals

- 📈 **Bar Chart** – Sales by Region  
- 🥧 **Pie Chart** – Sales by Product  
- 📉 **Line Chart** – Churn Rate over Time  
- 🔢 **Cards** – Total Sales, Avg. Conversion Rate  
- 🔘 **Slicer** – Region filter  

---

## 📐 DAX Calculations

```dax
Conversion Rate = DIVIDE(Sales[Conversions], Sales[Customers])
Churn Rate = DIVIDE(Sales[Churned], Sales[Customers])
```

---

## 🧠 Learning Path (if you're new)
1. Learn Excel basics and create sales datasets
2. Learn Power BI: importing, visualizations, formatting
3. Learn DAX: calculated columns and measures
4. Learn Git & GitHub for version control
5. Understand key business KPIs (Sales, Conversion, Churn)

---

## 📸 Screenshot

![Dashboard Preview](./screenshots/dashboard_view.png)

---

## 👨‍💻 Author

**Divyansh**
