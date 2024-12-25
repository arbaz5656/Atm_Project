# ATM System in Python

This project is a simple ATM system implemented in Python, using MySQL (via XAMPP) for backend storage. The system allows users to:
- Check current balance
- Deposit money
- Withdraw money
- View transaction history

## Features
1. **Account Management**:
   - Create new accounts.
   - Secure login with account number and password.

2. **Transactions**:
   - Deposit and withdraw money.
   - Automatically updates account balances.

3. **Transaction History**:
   - View the detailed history of deposits and withdrawals with timestamps.

4. **MySQL Integration**:
   - Data persistence using XAMPP's MySQL server.

## Database Schema
### Tables
1. **atm_db**:
   Stores account information (account holder name, account number, password).

2. **transaction_db**:
   Tracks current balance, deposit, and withdrawal amounts for each account.

3. **transaction_history**:
   Logs each deposit and withdrawal with details like type, amount, and date.

## Setup Instructions
### Prerequisites
- Python 3.x
- MySQL server (via XAMPP or standalone)
- `mysql-connector-python` library (`pip install mysql-connector-python`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/atm_Project/atm-system.git
   cd atm-system
