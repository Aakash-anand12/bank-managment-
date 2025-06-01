# bank-managment-

# Bank Account Management System

A simple console-based Bank Account Management System written in C++. This project allows users to create accounts, deposit cash, and withdraw funds using a text-based interface.

## 💻 Features

- Create new account
- Add cash to an existing account
- Withdraw cash with password authentication
- File-based data storage using `Account.txt`

## 🛠 Technologies Used

- **C++**
- **File Handling**
- **Windows API** (for `Sleep()` and `system("cls")`)

## 📁 Project Structure

bank-account-management/
│
├── bankaccount.cpp # Main source code
├── Account.txt # Data file (auto-generated)
└── README.md # Project documentation



## 🚀 How to Run

1. **Compile the code**:
   ```bash
   g++ bankaccount.cpp -o bankapp

📝 Future Improvements

Replace file system with database (e.g. SQLite)

Encrypt stored passwords

GUI interface using frameworks like Qt or SFML

Add account deletion and modification

📜 License
This project is open source and free to use.

