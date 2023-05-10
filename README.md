# Banking System

This is a simple banking system implemented in C++. It allows users to perform various banking operations such as creating a new account, depositing and withdrawing amounts, checking the account balance, and managing account information.

## How to Use

1. Clone or download the repository to your local machine.
2. Compile the C++ code using a C++ compiler.
3. Run the compiled executable.

## Features

The banking system provides the following features:

1. Create a new account: Allows the user to create a new bank account by providing the necessary details such as account number, account holder name, type of account (Savings or Current), and initial deposit amount.
2. Display account details: Allows the user to view the details of a specific account by entering the account number.
3. Modify account details: Allows the user to modify the details of an existing account.
4. Deposit amount: Allows the user to deposit a specific amount into an account.
5. Withdraw amount: Allows the user to withdraw a specific amount from an account.
6. Balance inquiry: Allows the user to check the balance of an account.
7. Display all accounts: Displays a list of all the existing accounts.
8. Close an account: Allows the user to close an existing account.
9. Exit: Terminates the program.

## File Storage

The account details are stored in a binary file named "account.dat". The file is created in the same directory as the executable. Each account is stored as an object of the `account` class.

## Note

- The program uses the `fstream` library to read and write data to the binary file.
- The program is designed to handle basic banking operations and does not include advanced features such as transaction history, multiple user support, or encryption.

## School Information

This program was created as part of a project for IIIT KOTA C++ Lab.
