# Dashboard-designing-task-3
# 📊 Sales & Profit Performance Dashboard – Power BI

This project presents an **interactive Power BI dashboard** built using a Superstore Sales dataset. It provides actionable insights into sales, profit trends, and customer segments to help business stakeholders make data-driven decisions.

---

## 📁 Project Structure

├── Superstore_Dataset.xlsx          # Dataset used for dashboard  
├── Sales_Profit_Dashboard.pbix      # Power BI dashboard file  
├── Sales_Insights_Summary.pptx      # Executive summary presentation  
└── README.md                        # Project documentation  


---

## 🎯 Objective

- Design an interactive dashboard using real-world sales data
- Visualize key KPIs such as **Sales**, **Profit**, **Quantity**
- Enable filtering and deep-dive analytics via slicers
- Empower business teams to track performance and identify improvement areas

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Dataset Source**: Superstore Sales (Kaggle)
- **Data Fields**: Sales, Profit, Category, Segment, Region, Order Date, Customer, Product

---

## 📊 Dashboard Pages & Visuals

### 📄 **Page 1: Sales Overview**

| Visual Type           | X-Axis / Group       | Y-Axis / Values          | Purpose                                 |
|------------------------|----------------------|---------------------------|------------------------------------------|
| KPI Cards             | –                    | `Sales`, `Profit`, `Quantity` | Show overall performance summaries      |
| Line Chart            | `Order Date`         | `Sales`, `Profit`         | View sales/profit trends over time       |
| Bar Chart             | `Segment`            | `Sales`                   | Segment-wise sales comparison            |
| Stacked Column Chart  | `Category`           | `Sales`                   | Category/Sub-Category contribution       |
| TreeMap               | `Region`             | `Sales`                   | Regional sales distribution              |
| Slicers               | `Segment`, `Region`, `Category`, `Order Date` | – | Add interactive filtering       |

---

### 📄 **Page 2: Profit Deep Dive**

| Visual Type           | X-Axis / Group       | Y-Axis / Values          | Purpose                                 |
|------------------------|----------------------|---------------------------|------------------------------------------|
| Line Chart            | `Order Date`         | `Profit`                  | Track profitability over time           |
| Table / Matrix        | –                    | `Product`, `Sales`, `Profit`, `Profit Margin` | Product-level performance |
| Bar Chart             | `Customer Name`      | `Profit`                  | Identify top/bottom customers            |
| Slicers               | `Sub-Category`, `Region` | –                       | Enable drill-down by filters             |

---

## 🧭 Dashboard Features

- ✅ Interactive slicers for filtering data
- 📌 Custom color themes for consistent look and feel
- 📈 Time-series trend visualizations
- 📚 Navigation buttons between pages
- 📊 Tooltips on hover for detailed context
- 📥 Downloadable summary report (PPT)

---

## 📌 Business Insights Uncovered

- 📉 Profit margins vary significantly by sub-category
- 🏆 Technology performs best in terms of profit and sales
- 📍 West Region consistently delivers highest profits
- 🔍 Some furniture items result in frequent losses
- 📆 Q4 shows seasonal spikes in overall sales

---

## 🚀 Getting Started

1. **Install Power BI Desktop**
2. Open the `Sales_Profit_Dashboard.pbix` file
3. Interact using slicers and navigation buttons
4. Review the summary PPT in `Sales_Insights_Summary.pptx`

---

## 📧 Contact

**Author:** [Your Name]  
**Email:** your.email@example.com  
**LinkedIn:** [Your LinkedIn Profile]

---

