# 💰 Monthly Expense Tracker

A simple command-line Expense Tracker built with Python that helps users record and manage their daily expenses. All data is stored locally in a JSON file, making it lightweight and easy to use.

## ✨ Features

- ➕ Add a new expense
- 📅 View today's expenses
- 📊 View day-wise expenditure for the current month
- 📈 View total expenditure for the current month
- 📆 View total expenditure for the current year
- 💵 View total expenditure till date
- 🗑️ Delete an expense by date and time
- 💾 Persistent data storage using JSON

---

## 🛠️ Technologies Used

- Python 3
- JSON
- datetime module

---

## 📁 Project Structure

```
expense-tracker/
│
├── py.py              # Main application
├── data1.json         # Stores all expenses
├── README.md
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/expense-tracker-python.git
```

2. Navigate into the project

```bash
cd expense-tracker-python
```

3. Run the program

```bash
python py.py
```

---

## 📋 Menu

```
1. Add Expense
2. Show Today's Expense
3. Day-wise Monthly Expenditure
4. This Month's Total Expenditure
5. This Year's Total Expenditure
6. Total Expenditure Till Date
DEL. Delete an Expense
```

---

## 📦 Data Format

Expenses are stored in a JSON file in the following format:

```json
{
    "14:30:15": {
        "date": "2026-07-18",
        "Expense": 250.0
    }
}
```

---

## 🎯 Future Improvements

- Edit an existing expense
- Search expenses by date
- Expense categories
- Monthly budget tracking
- Graphical charts
- GUI using Tkinter
- SQLite database support
- Export reports to CSV

---

## 👨‍💻 Author

Atharv Vindal

