# Money Tracking

### Project Overview
Money Tracking is a console application developed in C# for tracking financial transactions. It allows users to add, edit, and delete both expenses and incomes, providing a calculation of total savings through a command-line interface. The application saves data to a file, ensuring that users can resume tracking where they left off.

### Features
The application includes the following functionality:

- **Tracking Expenses and Incomes:** Enter, view, and manage both expense and income transactions.
- **Sorting and Filtering:** Sort transactions by month, amount, or title, and filter by expenses or incomes.
- **Editing and Removing Transactions:** Easily modify or delete transactions.
- **Data Persistence:** Save and load transaction data to and from a file.
- **Intuitive Command-Line Interface:** A text-based interface guides users through tracking their finances.

The command-line interface is simple and easy to navigate, resembling the following mock-up:

> ```csharp
> Welcome to TrackMoney
> You have currently (-) X kr on your account.
> Pick an option:
> (1) Show items (All/Expense(s)/Income(s))
> (2) Add New Expense/Income
> (3) Edit Item (edit, remove)
> (4) Save and Quit
> ```

### Requirements
The project satisfies the following requirements:

- [X] Item Modeling: Each transaction has a title, amount, and month.
- [X] Distinguishes between income and expense items.
- [X] Transaction Display: View a list of transactions sorted by various criteria.
- [X] Sort by month, amount, or title.
- [X] Option to display only expenses or only incomes.
- [X] Editing and Removing Transactions: Modify or delete items as needed.
- [X] Text-Based User Interface: Provides a user-friendly command-line experience.
- [X] Data Persistence: Load and save the transaction list to a file for future use.

### Objective
This project demonstrates my C# skills in object-oriented programming by modeling real-world financial tracking concepts, implementing sorting and filtering functionality, and creating a user-friendly, text-based interface.

### Solution

- UML diagram: https://www.sharecanvas.io/p/individual-project---money-tracking
