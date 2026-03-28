# Bank Management System (Python)

This is a simple menu-driven Bank Management System implemented in Python.

## Features
- Create Savings Account (Current Account under development)
- Auto-generated Account Numbers (no duplicates)
- Deposit and Withdraw functionality
- Minimum balance rule (₹500)
- Interest calculation (7.25% for savings)
- Display all accounts

## How the Program Works

The program uses a menu-driven approach:

1. User selects an option from the menu:
   - Create Account
   - Deposit
   - Withdraw
   - Check Balance
   - Display All Accounts
   - Exit

2. Account Creation:
   - User selects account type (Savings only allowed)
   - Account number is generated automatically
   - Name and initial balance are stored

3. Deposit:
   - User enters account number and amount
   - Balance is updated

4. Withdrawal:
   - Ensures minimum balance of ₹500 is maintained
   - Deducts amount if valid

5. Check Balance:
   - Displays account holder details and balance
   - Shows interest for savings account

6. Display All Accounts:
   - Shows details of all accounts

## Concepts Used
- List, Tuple, Set, Dictionary
- Functions
- Random module
- Conditional statements and loops

## How to Run
1. Install Python
2. Run the file:
   python banking_management_system.py
