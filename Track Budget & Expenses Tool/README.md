# 💰 Personal Budget & Expenses Tracker

A clean, beginner-friendly Python tool for managing daily expenses and tracking them against a monthly budget. This solution strictly follows a 5-step interactive menu structure and utilizes CSV file handling for data persistence.

## 🌟 Key Features

- **Add Expense**: Log daily spending with specific details (Date, Category, Amount, Description).
- **View Expenses**: Display all records in a formatted table with data validation (skips incomplete entries).
- **Track Budget**: Calculate total spending and compare it against a monthly budget with real-time balance updates.
- **Data Persistence**: Automatically save and load data from `expenses.csv` and `budget.txt`.
- **Interactive Menu**: Easy-to-use command-line interface with 5 options.

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your computer.

### Running the App

1. Save the script as `Track _Budget_&_Expences.py`.
2. Run it via terminal:

   ```bash
   python "Track _Budget_&_Expences.py"
   ```

## 🛠️ How to Use

### 1. Interactive Menu Options

1. **Add Expense**: Enter the date in `YYYY-MM-DD` format, a category (e.g., Food), the amount, and a brief description.
2. **View Expenses**: View all your stored expenses. The app validates each entry and notifies you if data is missing.
3. **Track Budget**:
   - View your current budget and total spent.
   - See your remaining balance or a warning if you've exceeded the limit.
   - You can update your budget directly from this menu.
4. **Save Expenses**: Manually save your data to the file.
5. **Exit**: Securely save all data and close the program.

### 2. Example Tracking Output

When you select Option 3, you will see a detailed summary:

```text
--- TRACK BUDGET ---
Current Budget: $1000.0
Monthly Budget: 1000.0
You have 700.0 left for the month
Total Spent so far: 300.0
Do you want to update it? (y/n): 
```

## 📝 Technical Details (For Learners)

This project focuses on several core Python concepts:

- **Dictionaries**: To store structured data (date, category, etc.).
- **Lists**: To manage the collection of expense dictionaries.
- **File I/O**: Reading from and writing to CSV/TXT files using `open()` and `os.path.exists()`.
- **Error Handling**: Using `try-except` blocks to prevent crashes during number input or file loading.
- **Validation**: Checking for empty fields or invalid numbers before displaying data.

---
*Developed to help beginners master Python logic and data management.*
