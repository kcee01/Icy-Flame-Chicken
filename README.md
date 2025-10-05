# Icy-Flame-Chicken
Restaurant App build up 

# Icy-Flame-Chicken Management System

A simple Python-based **Restaurant Management System** with a GUI built using **Tkinter**, SQLite for database management, and Excel export functionality. This application allows restaurant staff to record sales, track expenses, view daily summaries, and export reports to Excel.

---

## Features

- **Record Sales**
  - Add items sold with price and payment type.
  - Payment types supported: `cash`, `ewallet`, `orangemoney`, `smega`, `myzaka`.

- **Record Expenses**
  - Track daily expenses with description and amount.

- **Daily Summary**
  - Displays total sales by payment type.
  - Shows total electronic payments (all non-cash payments).
  - Calculates total expenses.
  - Calculates cash in hand (`cash sales - expenses`).

- **Daily Records**
  - View detailed sales and expenses for the day.
  - Refresh records to see updates in real time.

- **Export to Excel**
  - Export daily summary, sales, and expenses to an Excel file (`.xlsx`).

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/restaurant-management.git
   cd restaurant-management
````

2. **Install required Python packages**

   ```bash
   pip install openpyxl
   ```

3. **Run the application**

   ```bash
   python main.py
   ```

> Make sure you have Python 3.x installed on your system.

---

## Usage

1. Open the application.

2. Navigate between tabs to:

   * Record sales.
   * Record expenses.
   * View daily summary.
   * Export reports to Excel.

3. Use the "Refresh" buttons to update the records or summary after adding sales or expenses.

---

## Database

* Uses **SQLite** (`restaurant.db`) to store:

  * Sales: `id`, `item`, `price`, `date`, `payment_type`.
  * Expenses: `id`, `description`, `amount`, `date`.

---

## Excel Export

* Exported file contains three sheets:

  1. **Summary** – Sales by payment type, total electronic payments, expenses, cash in hand.
  2. **Sales Today** – All sales recorded for the current day.
  3. **Expenses Today** – All expenses recorded for the current day.

---

## Technologies Used

* Python 3.x
* Tkinter (GUI)
* SQLite (Database)
* OpenPyXL (Excel export)

---

## License

This project is open-source and available under the [MIT License](LICENSE).

---

## Author

**Cliff Keabetswe** – *Developer & Maintainer*

* GitHub: https://github.com/kcee01
* Email: innocliffkeab@gmail.com
* Linkedin: https://www.linkedin.com/in/cliff-keabetswe-0a8583250/

```


