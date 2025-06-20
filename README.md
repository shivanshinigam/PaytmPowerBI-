# 💳 Paytm Transaction Dashboard (Power BI)

An interactive and professional Power BI dashboard to visualize and analyze user transactions from the Paytm ecosystem. This project transforms raw transaction data into actionable insights through dynamic visuals, KPIs, and filters.

---

## 📊 Dashboard Features

- 🔢 Total Income and Total Expense KPIs
- 🧾 Total Transactions and Average Transaction Per Day
- 📈 Income vs Expense Trend Line Chart
- 🧁 Donut Chart for Category-wise Spending
- 📅 Slicer for Month-Year filtering
- 📱 Filters for User Type, Transaction Type, and Device Used
- 📋 Transaction Details Table

---

## 🧩 Dataset Overview

The dataset used is a sample export of Paytm transaction history and contains the following key columns:

| Column             | Description                          |
|--------------------|--------------------------------------|
| Date               | Date of transaction                  |
| Transaction Type   | Nature of transaction (e.g. Recharge, Peer-to-Peer) |
| Transaction Value  | Amount involved in the transaction   |
| Device Used        | Device through which payment was made|
| User Type          | Type of user (New/Returning)         |
| User Retention     | Whether user was retained            |

Derived columns include:
- `TxnNature`: Categorized as "Income" or "Expense"
- `Month-Year`: For time-based filtering

---

## ⚙️ How to Use This Dashboard

1. Open Power BI Desktop.
2. Load the Paytm.xlsx dataset into Power BI.
3. Use Power Query Editor to:
   - Clean Transaction Value column (remove ₹, commas)
   - Convert data types (e.g., Date, Number)
   - Add calculated columns: `TxnNature`, `Month-Year`
4. Add DAX Measures:
   - `Total Income`
   - `Total Spent`
   - `Total Transactions`
   - `Average Per Day`
5. Design visuals:
   - KPI cards, line chart, donut chart, table, slicers
6. Adjust visual interactions to control how filters behave across visuals.

---

## Demo 

![Home - Paytm - Power BI - Google Chrome 18-Jun-25 5_26_45 PM](https://github.com/user-attachments/assets/a11b89d1-b66d-4219-8d35-d714e10b242a)
![Home - Paytm - Power BI - Google Chrome 18-Jun-25 5_26_27 PM](https://github.com/user-attachments/assets/1e8058f6-ad5a-4133-b515-d18b766e8920)



## 🚧 Project Structure

```bash
📁 /Paytm-PowerBI-Dashboard/
├── Paytm.xlsx                 # Raw dataset file
├── PaytmDashboard.pbix        # Power BI dashboard file
├── README.md                  # This file
