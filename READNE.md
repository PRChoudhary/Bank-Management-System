# Banking Management System

A simple C++ banking system that allows users to create accounts, perform transactions, and manage account balances. The system supports user authentication, deposits, withdrawals, and provides account summaries. Bank managers can log in to view a list of users and account details.

## Features
- **User Authentication**: Users can create accounts and log in using their credentials.
- **Deposit and Withdrawal**: Users can deposit and withdraw money from their accounts.
- **Account Summary**: Users can view their account balance and transaction history.
- **Account Management**: Users can close their accounts.
- **Bank Manager Login**: Managers can view the list of all users and their account details.
- **Persistent Storage**: Account data is stored in `users.txt` and is updated with each transaction.

## How It Works
- User data is stored in `users.txt` with username, password, and balance.
- The system allows transactions such as deposits and withdrawals, updating the balance in real-time.
- A bank manager has access to a list of all users and their account balances.

## Files
- `users.txt`: Stores user information (username, password, balance).
- `managers.txt`: Stores manager login credentials.

## How to Run
1. Clone the repository.
2. Compile the code using any C++ compiler (e.g., g++, clang).
   ```bash
   g++ -o bank bank.cpp
   ./bank
