# Expense and Budget Tracker 2024

An Excel-based expense and budget tracking workbook for a business, covering **January to October 2024**. It records 1,000 expense transactions, compares actual spend against monthly category budgets, and provides a dashboard with charts and budget alerts.

## Features

- **Dashboard** with a month selector, total spend, total budget, remaining budget, categories over budget, and % of budget used.
- **Input sheet** for logging transactions with validated dropdowns and automatic month helper column.
- **Categories sheet** with monthly budget limits and typical vendor examples per category.
- **Monthly Summary** comparing monthly budget, YTD actual, YTD budget, variance, % used, and an over-budget alert.
- **Lists sheet** powering data validation dropdowns for departments, categories, payment methods, and statuses.
- **Charts** visualising budget vs. actual spend by category and month.

## Workbook Structure

| Sheet | Purpose |
| --- | --- |
| `Dashboard` | Summary KPIs, month filter, and charts |
| `Input` | Transaction log (1,000 records, Jan–Oct 2024) |
| `Categories` | Category list with monthly budget limits |
| `Monthly Summary` | Month-by-month budget vs. actual analysis |
| `Lists` | Dropdown source lists used by data validation |

## Transaction Fields

`Transaction ID`, `Date`, `Department`, `Category`, `Vendor / Description`, `Amount (USD)`, `Payment Method`, `Status`, `Month (helper)`

- **Departments:** Product, Admin, Marketing, HR, Operations, IT, Sales, Finance
- **Payment Methods:** Bank Transfer, Corporate Card, Reimbursement, Purchase Order, Cash, Auto Debit
- **Statuses:** Approved, Pending, Rejected

## Categories and Monthly Budgets

| Category | Monthly Budget (USD) |
| --- | ---: |
| Rent | 15,000 |
| Marketing | 14,300 |
| Travel | 13,400 |
| Professional Services | 8,500 |
| Equipment & IT | 5,500 |
| Software & Subscriptions | 4,400 |
| Training & Development | 4,200 |
| Meals & Entertainment | 2,200 |
| Utilities | 2,200 |
| Telephone & Internet | 1,400 |
| Miscellaneous | 1,300 |
| Office Supplies | 900 |
| **Total** | **73,300** |

## Getting Started

1. Download `Expense_Budget_Tracker_2024.xlsx`.
2. Open it in Microsoft Excel (recommended) or a compatible spreadsheet application.
3. Add new expenses on the **Input** sheet using the dropdown lists.
4. Use the **Dashboard** month selector to review spend versus budget.
5. Check the **Monthly Summary** sheet for variances and over-budget alerts.

## Notes

- Currency is US dollars (USD).
- The `Month (helper)` column is formula-driven and should not be edited manually.
- Charts and formulas are designed for Excel; some features may not render in other spreadsheet tools.

## Author

**Debangshi Dasgupta**

## Version

Initial release — 3 October 2024.
