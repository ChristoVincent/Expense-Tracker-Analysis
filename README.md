# 💸 India Expense Analytics Dashboard

> An interactive Power BI dashboard analyzing **22.05M** in personal/business expenses across **7 Indian cities**, **8 categories**, and **25+ merchants** — spanning the full year 2024.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 📊 Dashboard Preview

![Dashboard Preview]("C:\Users\chris\OneDrive\Pictures\Screenshots\Screenshot 2026-04-08 185316.png")

---

## 🔢 Key Metrics

| Metric | Value |
|---|---|
| 💰 Total Expenses | ₹22.05M |
| 📈 Max Single Transaction | ₹8,000 |
| 📉 Average Transaction | ₹4,028 |
| 🧾 Total Transactions | 5,475 |
| 🗓️ Date Range | Jan 1, 2024 – Dec 30, 2024 |

---

## 🗂️ Dataset Overview

The raw data (`large_expense_dataset.xlsx`) contains **5,475 rows** and **6 columns**:

| Column | Type | Description |
|---|---|---|
| `Date` | Date | Transaction date (2024) |
| `Category` | Text | Expense category (8 types) |
| `Merchant` | Text | Where money was spent (25+ merchants) |
| `Payment_Method` | Text | Card / Cash / UPI |
| `City` | Text | One of 7 Indian cities |
| `Amount` | Decimal | Transaction amount in INR |

---

## 📍 Cities Covered

`Delhi` · `Kolkata` · `Hyderabad` · `Pune` · `Mumbai` · `Chennai` · `Bangalore`

---

## 🏷️ Expense Categories

| Category | Approx. Share |
|---|---|
| 🛒 Groceries | ₹2.92M |
| ✈️ Travel | ₹2.84M |
| 🚌 Transport | ₹2.80M |
| 🧾 Bills | ₹2.74M |
| 🛍️ Shopping | ₹2.79M |
| ❤️ Health | ₹2.69M |
| 🍽️ Food | ₹2.68M |
| 🎭 Entertainment | ₹2.59M |

---

## 💳 Payment Methods

- **Cash** — 33.9% (1,854 transactions)
- **Card** — 33.1% (1,811 transactions)
- **UPI** — 33.1% (1,810 transactions)

---

## 🏪 Top 5 Merchants by Revenue

1. Supermarket — ₹1.49M
2. Local Store — ₹1.43M
3. Airline — ₹1.04M
4. Clinic — ₹1.04M
5. Uber — ₹1.03M

---

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (free download from [Microsoft](https://powerbi.microsoft.com/desktop/))
- Microsoft Excel (for viewing raw data)

### Steps to Open

```bash
# 1. Clone this repository
git clone https://github.com/YOUR_USERNAME/expense-dashboard.git
cd expense-dashboard

# 2. Open the dataset
# → large_expense_dataset.xlsx (raw data)

# 3. Open the dashboard
# → expense_dashboard.pbix (Power BI file)
```

### Refreshing Data
1. Open the `.pbix` file in Power BI Desktop
2. Go to **Home → Transform Data**
3. Update the file path to your local `large_expense_dataset.xlsx`
4. Click **Close & Apply**

---

## 🎛️ Dashboard Features

- **KPI Cards** — Total expenses, max, average, and transaction count at a glance
- **Category Pie Chart** — Proportional breakdown of all 8 categories
- **City Bar Chart** — Spending comparison across 7 cities
- **Merchant Bar Chart** — Top merchants ranked by total spend
- **Interactive Slicers** — Filter by:
  - Payment Method (Card / Cash / UPI)
  - Category
  - City
  - Date range (slider)

---

## 📁 Repository Structure

```
expense-dashboard/
│
├── large_expense_dataset.xlsx    # Raw transaction data (5,475 rows)
├── expense_dashboard.pbix        # Power BI report file
├── dashboard_preview.png         # Screenshot of the dashboard
└── README.md                     # This file
```

---

## 🤝 Contributing

Pull requests are welcome! If you'd like to add new visuals, time-series analysis, or forecasting models:

1. Fork the repo
2. Create a new branch (`git checkout -b feature/new-visual`)
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

---

## 👤 Author

Made with ❤️ and Power BI · [Your GitHub Profile](https://github.com/YOUR_USERNAME)
