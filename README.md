# Sales-Analysis
Analysis for Sales 

# 📊 Sales Dashboard

A comprehensive Power BI sales performance dashboard providing real-time visibility into revenue, profit, loss, and product trends across categories and time periods.

---

## 🚀 Overview

This project is a fully interactive **Sales Dashboard** built with **Power BI Desktop**, designed to give business managers and analysts a clear, data-driven view of sales performance. It consolidates key metrics — from monthly profit/loss trends to sub-category loss breakdowns — into a single, intuitive interface.

**Live KPIs at a glance:**

| Metric | Value |
|---|---|
| 💰 Total Sales | $1.93M |
| ✅ Total Profit | $371,300 |
| ❌ Total Loss | $123,400 |
| 📦 Units Sold | 32,000 |
| 📈 Profit Ratio | 75.06% |

---

## 📸 Preview

![Sales Dashboard Preview](./Sales_Dashboard.pdf)

---

## ✨ Features

- **Monthly Profit & Loss Tracking** — Side-by-side bar chart comparing profit and loss for each month of the year
- **Sales by Category** — Horizontal bar breakdown across Technology, Furniture, and Office Supplies
- **Sales by Month** — Line chart showing volume trends from December through February
- **Profit % vs Loss % Donut Chart** — Instant visual read on overall profitability ratio
- **Loss by Sub-Category** — Ranked bar chart pinpointing the highest-loss product groups (Binders, Tables, Machines)
- **Top Products by Sales** — Ranked view of best-performing individual products, led by the Canon i-Series at ~$40K

---

## 🗂️ Project Structure

```
sales-dashboard/
├── Sales_Dashboard.pdf       # Exported dashboard snapshot
├── Sales_Dashboard.pbix      # Power BI source file
├── data/
│   └── sales_data.csv        # Underlying sales dataset
└── README.md
```

---

## 🛠️ Getting Started

### Prerequisites

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
- Windows 10 or later

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/sales-dashboard.git
   cd sales-dashboard
   ```

2. **Open the dashboard:**
   - Launch **Power BI Desktop**
   - Click `File → Open` and select `Sales_Dashboard.pbix`

3. **Connect your data** *(optional — to use your own dataset):*
   - Go to `Home → Transform Data`
   - Update the data source path to point to your own CSV file
   - Ensure your data includes columns for: `Date`, `Sales`, `Profit`, `Loss`, `Category`, `Sub-Category`, `Product Name`, `Quantity`

4. **Refresh & Explore:**
   - Click `Refresh` to load the latest data
   - Use the interactive filters and slicers to explore trends

---

## 📊 Dashboard Sections

| Section | Description |
|---|---|
| **Monthly Profit & Loss** | Compares profit and total loss per month |
| **Sales by Category** | Revenue split across Technology, Furniture, Office Supplies |
| **Sales by Month** | Monthly revenue trend line chart |
| **Profit% / Loss%** | Overall profitability donut chart (75% / 25%) |
| **Loss by Sub-Category** | Identifies loss hotspots by product group |
| **Top Products** | Ranked individual product sales performance |

---

## 💡 Key Insights

- **Technology** is the top revenue category at **$704K**, followed closely by Furniture ($622K) and Office Supplies ($602K)
- **December** is the peak sales month at **$241K**; February is the lowest at **$60K**
- **Binders, Tables, and Machines** account for over **62% of total losses** ($77K of $123.4K)
- The **Canon i-Series** is the single best-selling product at ~$40K in sales

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

Have questions or suggestions? Feel free to open an [issue](https://github.com/your-username/sales-dashboard/issues) or reach out directly.

---

*Built with Power BI Desktop · Data visualisation for smarter decisions*
