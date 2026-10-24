# Expense Tracker



A clean and modern expense tracking web app built with plain HTML, CSS, and JavaScript. It helps users manage income and expenses, monitor their balance, and visualize spending trends through charts.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

## Overview

Expense Tracker is a simple personal finance dashboard designed to help users:

- Add income and expense transactions
- Track total balance in real time
- View spending by category
- Monitor monthly financial trends with charts
- Delete unwanted records instantly
- Manage everything from a single page

This project is lightweight, responsive, and does not require any backend or database setup.

## Features

- Responsive dashboard layout
- Income and expense toggle
- Add transaction form with description, amount, category, and date
- Real-time summary cards for:
  - Total balance
  - Total income
  - Total expenses
- Monthly bar chart for income vs expense
- Category-wise donut chart for spending breakdown
- Transaction list with delete option
- Toast notifications for actions and validation
- Mobile-friendly design

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Chart.js

## Project Structure

```text
expense-tracker.html
README.md
```

## Workflow

The app follows a simple and user-friendly workflow:

1. Open the app in a browser.
2. Select whether the entry is an income or expense.
3. Fill in the transaction details:
   - Description
   - Amount
   - Category
   - Date
4. Click "Add Transaction".
5. The app updates:
   - Balance summary cards
   - Transaction list
   - Monthly chart
   - Category chart
6. If needed, delete any entry from the transaction list.
7. Continue tracking your finances over time.

## How It Works

The app stores transactions in an in-browser JavaScript array and re-renders the UI whenever a transaction is added or removed. Summary cards calculate totals automatically, and Chart.js generates the visual analytics for monthly and category-based spending.

## Run the Project

Since this is a front-end HTML app, you can run it in any of the following ways:

### Option 1: Open directly in browser

- Download or clone the repository
- Open `expense-tracker.html` in your browser

### Option 2: Use a local server (recommended)

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/expense-tracker.html
```

## Example User Flow

```text
User opens app
   ↓
User adds salary as income
   ↓
User adds rent and groceries as expenses
   ↓
Dashboard updates totals and charts
   ↓
User reviews monthly spending and balance
```

## Future Enhancements

- LocalStorage support to retain data after refresh
- Edit transaction functionality
- Budget planner
- CSV export/import
- Dark mode
- Multi-currency support

## License

This project is open for personal and educational use.

## Author

Built for personal finance tracking and learning front-end web development.

---

If you want, I can also create a more premium README with a banner image, badges, and a project screenshot section.
