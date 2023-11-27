Bank Management System in C++
My-CPP-Mini-Project
This project is a simple Bank Management System implemented in C++, created by Abhishek Rajendra Mohite during the 3rd semester.

Overview
This C++ program serves as a Bank Management System, allowing users to perform various banking operations. It includes features such as creating a new account, depositing and withdrawing funds, checking the balance, listing all account holders, closing an account, and updating account information.

Features
1. New Account Creation
Users can create a new bank account by providing necessary details such as account number, account holder name, account type (Savings/Current), and initial deposit amount.

2. Deposit and Withdrawal
Account holders can deposit and withdraw funds from their accounts.

3. Balance Enquiry
Users can check the balance of a specific account by entering the account number.

4. Account Holder List
The system provides a list of all account holders, displaying their account number, name, account type, and balance.

5. Close an Account
Account holders have the option to close their accounts by providing the account number.

6. Update an Account
Users can update account details, including the account holder's name, account type, and balance.


Code Structure
The code is organized into a class called account, which represents a bank account. It includes member functions for account operations such as opening an account, displaying account information, updating account details, depositing, withdrawing, and generating a report.

Usage
Compile the program using a C++ compiler.
Run the executable.
Follow the on-screen prompts to navigate through different banking operations.
Important Notes
The program stores account information in a binary file called account.dat.
Account balances have specific minimum requirements (>=440 for Savings and >=1000 for Current).
The system can handle up to 3 accounts.

Author
Abhishek Rajendra Mohite

License
This code is available under the Abhishek Rajendra Mohite license.
