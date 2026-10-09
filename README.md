<div align="center">

# 🍬 Sweet Shop Management System

### A simple, menu-driven application to manage sweets, inventory, and customer billing.

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Handling-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-11557C?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Student_Project-FF69B4?style=for-the-badge)

*Organize your sweet shop inventory and make billing easier!*

</div>

---

## 🌟 About the Project

**Sweet Shop Management System** is a menu-driven Python project designed to make basic sweet shop operations easier. It allows the user to manage sweet records, view available items, search for sweets, update or delete records, and calculate a customer's bill.

The project also includes an option to display a chart of sweets, making it a useful beginner project for practising Python programming, data handling, and basic data visualization.

## ✨ Features

| Option | Feature | Description |
|---|---|---|
| ➕ | Add a sweet | Add a sweet's code, name, cost, quantity, and main ingredient. |
| 📋 | View all sweets | Display the available sweet records in a tabular format. |
| 🔎 | Search | Find a sweet using the application's search option. |
| 🗑️ | Delete | Remove a sweet record using its code. |
| ✏️ | Update | Modify the details of an existing sweet. |
| 🧾 | Create a bill | Select a sweet and quantity to calculate the due amount and enter customer details. |
| 📊 | Show chart | Open the chart option for visualizing sweet-related data. |
| 🚪 | Quit | Exit the application. |

## 🛠️ Technologies Used

- **Python** — application logic and menu-driven interaction.
- **Pandas** — tabular data handling and display.
- **Matplotlib** — intended for chart-based data visualization.
- **SQL / Database concepts** — include this if your project version connects to an SQL database for storing records.

> **Note:** Update the technology list to match the libraries and database actually imported and used in your final code.

## 🚀 Getting Started

### 1. Prerequisites

Install Python 3. If your code uses Pandas and Matplotlib, install them with:

```bash
python -m pip install pandas matplotlib
```

If your version connects to an SQL database, install the appropriate database connector too.

### 2. Download or clone the project

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

Alternatively, download the project files and open the project folder on your computer.

### 3. Run the application

Save the Python program as `Sweet Shop.py`, then run:

```bash
python "Sweet Shop.py"
```

Follow the numbered menu displayed in the terminal and enter the option you want to use.

## 🧁 Sample Inventory

The application can display sweet details in a table like this:

| Sweet | Cost | Quantity | Main Ingredient |
|---|---:|---:|---|
| Brownie | 200 | 10 | Chocolate |
| Truffle | 400 | 15 | Dark Chocolate |
| Cake | 500 | 10 | Milk |
| Muffins | 100 | 20 | Flour |
| Jellies | 50 | 7 | Gelatin |
| Macaroons | 300 | 2 | Flour |

*These are example records; the inventory can differ when the application is run.*

## 🧾 How Billing Works

1. Choose **Create a Bill** from the menu.
2. Select a sweet using its displayed code.
3. Enter the required quantity.
4. The application calculates the due amount based on the sweet's cost and the quantity entered.
5. Enter the customer's name and billing date.

**Tip:** Before using the project for real transactions, add validation for unavailable sweet codes, invalid quantities, and purchases exceeding the available stock.

## 🎯 Learning Outcomes

By building this project, a student can practise:

- Writing menu-driven Python programs.
- Creating and managing records.
- Working with tabular data using Pandas.
- Implementing basic create, read, update, and delete (CRUD) operations.
- Calculating bills from item prices and quantities.
- Exploring data visualization with Matplotlib.
- Improving input validation and error handling.

## 🔮 Future Improvements

- [ ] Validate sweet codes and prevent duplicate records.
- [ ] Check stock availability before completing a bill.
- [ ] Automatically update inventory after a purchase.
- [ ] Generate and save printable bills or receipts.
- [ ] Store records persistently in an SQL database.
- [ ] Add clearer charts for inventory and sales.
- [ ] Improve error messages and input validation.
- [ ] Add automated tests for billing and inventory operations.

## 👩‍💻 Project Details

- **Project name:** Sweet Shop Management System
- **Project type:** Python application
- **Purpose:** Sweet inventory management and billing practice
- **Author:** *Add your name here*

---

<div align="center">

### 🍭 Made with Python and a little sweetness!

If you find this project useful, feel free to ⭐ the repository.

</div>
