# 🥤 JustVend – Vending Machine Simulator

### A Python-Based Vending Machine Application

**JustVend** is a Python-based vending machine simulator designed to replicate the basic functionality of a real-world vending machine. It allows users to browse available products, make purchases, manage transactions, and generate receipts.

The application uses Python for its core functionality and JSON files for storing product and user data. It focuses on implementing practical programming concepts such as file handling, data management, user interaction, and transaction processing.

---

## ✨ Features

### 🛒 Product Management
- Display available products along with their prices.
- Browse products before making a purchase.
- Maintain product information and availability.
- Manage inventory through JSON-based data storage.

### 💳 Purchase & Transaction System
- Select products for purchase.
- Process customer transactions.
- Validate purchase-related inputs.
- Maintain transaction details.

### 📦 Inventory Management
- Keep track of available product quantities.
- Update inventory after purchases.
- Maintain product information persistently.
- Store vending machine data using JSON.

### 👤 User Management
- Maintain user information.
- Store user-related data locally.
- Manage user records through JSON files.

### 🧾 Receipt Generation
- Generate receipts for completed transactions.
- Store receipts as individual text files.
- Maintain a record of previous purchases.

### ⚡ Interactive Interface
- Simple command-line interface.
- Menu-driven navigation.
- User-friendly interaction through terminal input and output.

---

## 📁 Project Structure

The project follows a simple and organized structure, separating the main application from its data files.

```text
TEAM_JUSTVEND/
│
├── vending_machine.py   # Main application
│
├── vending_data.json    # Product and inventory data
├── users.json           # User information
│
├── receipt_1.txt        # Generated transaction receipt
├── receipt_2.txt        # Generated transaction receipt
├── receipt_3.txt        # Generated transaction receipt
│
├── README.md            # Project documentation
└── .gitignore           # Files excluded from Git
```

*Note: User data and generated receipts are maintained locally and are excluded from the public GitHub repository.*

---

## ⚙️ Requirements & Installation

### 📌 Requirements

- Python 3.x
- Git (optional, for cloning the repository)

No external Python libraries are required if using only Python's standard library.

### 📥 Clone the Repository

Open your terminal and execute:

```bash
git clone https://github.com/harsh-1507/vending-machine.git
```

Navigate to the project directory:

```bash
cd vending-machine
```

### ▶️ Run the Application

Execute the following command:

```bash
python vending_machine.py
```

On Windows, you can also use:

```bash
py vending_machine.py
```

The application will start in the terminal, allowing users to interact with the vending machine through its menu.

---

## 💾 Data Storage

JustVend uses JSON files to maintain application data between executions.

| File | Purpose |
|---|---|
| `vending_data.json` | Stores vending machine product and inventory information. |
| `users.json` | Stores user-related information locally. |
| `receipt_*.txt` | Stores generated transaction receipts. |

### 📦 JSON-Based Storage

JSON provides a lightweight and convenient way to store structured information without requiring an external database.

- Product information can be maintained in `vending_data.json`.
- User information is stored separately in `users.json`.
- Transaction receipts are generated as individual text files.

This approach keeps application data organized and makes it easier to maintain and update records.

---

## 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| 🐍 Python 3 | Core application development |
| 📄 JSON | Product and user data storage |
| 📝 File Handling | Reading and writing application data and receipts |
| 🔧 Git | Version control |
| 🐙 GitHub | Source code hosting and collaboration |

---

## 🎯 Project Objectives

The project focuses on applying fundamental programming concepts to build a practical application.

Key learning objectives include:

- Understanding file handling and persistent data storage.
- Working with JSON for structured data management.
- Implementing transaction and inventory management.
- Handling user input and validation.
- Organizing application functionality into manageable components.
- Developing an interactive command-line application.

---

## 👨‍💻 Contributors

**TEAM JUSTVEND**

Developed as a collaborative programming project.

---

## 📜 License

This project was developed for academic and educational purposes.

---

⭐ **Thanks for checking out JustVend!**
