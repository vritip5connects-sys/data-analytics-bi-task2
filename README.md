# 📊 Data Analytics Internship — Task 2: SQL + Excel + Power BI

## 🗂️ Project Overview
Analysis of the **Superstore Sales Dataset** (9,994 records) using SQL, LibreOffice Calc, and dashboard visualizations to derive business insights on sales, profit, and customer trends.

---

## 📁 Folder Structure

```
data-analytics-bi-task2/
├── data/               # Raw dataset (Superstore CSV)
├── sql/                # SQL analysis queries
├── excel/              # LibreOffice Calc analysis file
├── dashboard/          # Dashboard charts and visuals
├── reports/            # Summary reports
└── screenshots/        # Screenshots of results
```

---

## 📦 Dataset

- **Source:** Sample Superstore Dataset
- **Records:** 9,994 rows × 21 columns
- **Key Fields:** `Order Date`, `Category`, `Sub-Category`, `Region`, `Sales`, `Quantity`, `Discount`, `Profit`

---

## 🗄️ SQL Analysis

Six queries written for SQLite covering:

| File | Analysis |
|------|----------|
| `01_sales_by_category.sql` | Total Sales & Profit by Category |
| `02_top_customers.sql` | Top 10 Customers by Sales |
| `03_monthly_trend.sql` | Monthly Sales Trend |
| `04_profit_by_region.sql` | Profit by Region |
| `05_subcategory_analysis.sql` | Sub-Category Sales & Profit |
| `06_discount_analysis.sql` | Discount Impact on Profit |

---

## 📊 Excel Analysis (LibreOffice Calc)

Pivot tables and charts created in `excel/superstore_analysis.xlsx`:

- **Pivot Table 1:** Sales & Profit by Category
- **Pivot Table 2:** Sales, Profit & Quantity by Region
- **Pivot Table 3:** Monthly Sales Trend (Year_Month)
- **Chart 1:** Bar Chart — Sales by Category
- **Chart 2:** Line Chart — Monthly Sales Trend

---

## 📈 Key Insights

- **Technology** is the highest revenue-generating category
- **West region** leads in both sales and profit
- Sales show a consistent **upward trend** year over year
- **High discounts (30%+)** negatively impact profit margins

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| SQLite | SQL querying and analysis |
| LibreOffice Calc | Pivot tables and charts |
| Git + GitHub | Version control |
| VS Code | Code editor |

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/vritip5connects-sys/data-analytics-bi-task2.git
   ```
2. Open SQL files in any SQLite client and import `data/Sample - Superstore.csv`
3. Open `excel/superstore_analysis.xlsx` in LibreOffice Calc or Excel

---

