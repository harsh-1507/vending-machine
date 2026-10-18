# 🥤 JustVend — Advanced Vending Machine Simulator

A feature-rich vending machine simulator built with Python that brings the convenience of a real-world vending machine to an interactive, keyboard-driven application. JustVend combines customer authentication, category-based shopping, cart management, payment processing, digital receipts, and an administrative dashboard in one system.

## ✨ Features

### 👤 User Authentication
- Create an account and log in securely.
- Password input with masked characters.
- Manage user accounts, including account deletion.
- Maintain user sessions throughout the shopping experience.

### 🛍️ Shopping Experience
- Browse products organized into categories such as Snacks, Beverages, and Chocolates.
- View product prices and real-time stock availability.
- Select products and quantities with input validation.
- Add items to a shopping cart, modify quantities, or remove products.
- View an automatically calculated cart total.

### 💳 Checkout & Payments
- Process purchases through an interactive checkout system.
- Validate payment amounts before completing transactions.
- Calculate and display change for overpayments.
- Update inventory automatically after successful purchases.
- Generate digital receipts for completed transactions.

### 📦 Inventory Management
- Add new products and manage existing inventory.
- Update product prices, quantities, and categories.
- Monitor stock availability to prevent overselling.
- Store inventory information persistently using JSON files.

### 📊 Admin Dashboard
- Access administrative features through an owner panel.
- Manage products and inventory.
- View sales reports and order history.
- Monitor total revenue and transaction counts.
- Manage registered users.

### 💾 Data Persistence
- Automatically save application data in JSON format.
- Preserve inventory, user accounts, orders, and revenue between sessions.
- Generate transaction receipts as text files.
- Handle file operations and invalid inputs with appropriate error handling.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Core application logic |
| `json` | Data serialization and persistent storage |
| `os` | File and directory operations |
| `datetime` | Timestamps for transactions and receipts |
| `time` | Delays and interface feedback |
| `readchar` | Interactive keyboard input handling |

## 📁 Project Structure

```text
JustVend/
├── src/
│   └── vending_machine.py
├── data/
│   ├── vending_data.json
│   └── users.json
├── docs/
│   └── README.md
└── receipts/
    └── receipt_*.txt
```

*Note: The exact file structure may vary depending on where the application is run and how generated data is stored.*

## 🚀 Getting Started

### Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

### 1. Clone the Repository

```bash
git clone https://github.com/harsh-1507/vending-machine.git
cd vending-machine
```

### 2. Install Dependencies

Install the required third-party library:

```bash
python -m pip install readchar
```

On Windows, you can also use:

```powershell
py -m pip install readchar
```

### 3. Run the Application

If the entry-point file is in the `src` directory:

```bash
python src/vending_machine.py
```

If `vending_machine.py` is in the project root, run:

```bash
python vending_machine.py
```

Choose the command that matches your actual project structure.

## 🧑‍💻 How to Use

### For Customers

1. Launch JustVend.
2. Sign up for an account or log in with existing credentials.
3. Browse the available product categories.
4. Select products and specify quantities.
5. Review your cart and modify it if necessary.
6. Proceed to checkout and enter the payment amount.
7. Complete the transaction and receive a digital receipt.

### For Administrators

1. Select the Owner Panel from the main menu.
2. Authenticate using the configured administrator password.
3. Add products or modify existing inventory.
4. Review sales reports, revenue, and order history.
5. Monitor stock levels and manage registered users.

## 🧠 Concepts Demonstrated

JustVend applies several fundamental programming concepts:

- **File Handling:** Reading and writing application data.
- **Data Structures:** Dictionaries, lists, and nested data structures.
- **Exception Handling:** Managing invalid inputs and file operation errors.
- **Modular Programming:** Organizing functionality into reusable functions.
- **Input Validation:** Checking quantities, payment amounts, and user inputs.
- **State Management:** Maintaining user sessions and shopping cart state.
- **Data Persistence:** Preserving application state using JSON.
- **Transaction Processing:** Updating stock, recording orders, and generating receipts.

## 🔮 Future Improvements

Potential enhancements include:

- Password hashing and stronger authentication.
- Product search and filtering.
- Low-stock alerts and inventory summaries.
- Support for multiple payment methods.
- Exportable sales reports and analytics.
- Unit tests for shopping, checkout, and inventory operations.
- A graphical user interface or web-based storefront.

## 👥 Team JustVend

Developed by:

- **Yash Mangal**
- **Shubham Kuvad**
- **Harsh Lotiya**

## 📄 License

This project was developed for educational purposes. Licensing and reuse terms can be added as required.

---

*JustVend — Smart shopping, simplified.* 🥤
