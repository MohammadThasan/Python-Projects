# 💰 Budget & Expenses Tracker

A beginner-friendly Python-based tool to help you track your monthly spending, set budgets, and manage your finances effectively.

## 🌟 Features

- **Add Expenses**: Quickly log your spending with a date, category, amount, and description.
- **View All Expenses**: Display your entire spending history in a clean, formatted table.
- **Set Monthly Budget**: Establish a spending limit for the month.
- **Track Budget**: Automatically calculate total spending and compare it against your budget to see how much you have left.
- **Data Persistence**: Automatically saves and loads your data from `expenses.csv` and `budget.txt`, so your records are never lost.
- **Educational Design**: Includes line-by-line comments explaining Python concepts for beginners.

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system.

### Installation

1. Clone the repository or download the source code.
2. Ensure you are in the project directory.

### Running the Application

To start the Budget Tracker, run the following command in your terminal:

```bash
python "Track _Budget_&_Expences.py"
```

## 🛠️ How it Works

The application uses global variables to manage state and simple file I/O to store data.

- **Storage**:
  - `expenses.csv`: Stores all individual expense records.
  - `budget.txt`: Stores your current monthly budget limit.
- **Logic Sections**:
  - **Global Setup**: Initializing data structures and file paths.
  - **Load and Save**: Functions to sync data with the local filesystem.
  - **Budget Logic**: Functions to set and track your spending goals.
  - **Expense Management**: Functions to add and view your spending records.
  - **Interactive Menu**: A user-friendly command-line interface.

## 📝 Example Usage

1. **Set Budget**: Choose option `3` and enter `1000`.
2. **Add Expense**: Choose option `1`, enter details like `24-02-2026`, `Food`, `15.50`, and `Lunch`.
3. **Track Budget**: Choose option `4` to see your balance:

   ```text
   Monthly Budget: $1000.0
   Total Spent:    $15.5
   You have $984.5 left for the month
   ```

## 👨‍🏫 Learning Python?

This project is specifically designed for learners! Each section of the code contains "LEARNER NOTES" that explain:

- **Lists**: How they act like shopping baskets.
- **Floats**: Handling decimal numbers.
- **Dictionaries**: Packaging data with labels.
- **Loops & Conditions**: Making decisions and repeating tasks.
- **File I/O**: Saving data permanently.

---
*Created with ❤️ for Python enthusiasts.*

