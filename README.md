# Software_ATM_Working

A functional ATM software application developed using C++, designed to simulate basic ATM functionalities such as balance inquiry, cash withdrawal, deposit, and account management.

# Features :

User Authentication: Secure PIN-based login system.

Balance Inquiry: Display the current account balance.

Cash Withdrawal: Withdraw specific amounts (with sufficient balance checks).

Deposit Funds: Add funds to the account.

Transaction History: Track recent transactions.

Error Handling: Handles invalid inputs, insufficient funds, and other common issues.

# Technologies Used :

Programming Language: C++

# Libraries Used :

<iostream>: For input/output operations.

<fstream>: For file handling to store and retrieve account data.

<string>: For efficient string manipulations.

<vector>: For managing transactions and data collections.

<iomanip>: For formatted output (e.g., currency formatting).

# How to Run :

Clone the Repository:

git clone https://github.com/DarkHacker28/Software_ATM_Working-using_Cpp

cd Software_ATM_Working  

# Compile the Code :
Use any C++ compiler (e.g., g++, clang++). For example:


g++ -o atm Software_ATM_Working.cpp 

Run the Program:

./atm  

# Follow the On-Screen Instructions:

Enter your user PIN to log in.
Choose from available options such as checking your balance, depositing money, or withdrawing cash.
File Structure
Software_ATM_Working.cpp: Core program file containing all the functionality.
accounts.txt: A file (or database) used to store user account information (PIN, balance, transaction history).

# Example Commands :
Login:
Enter your account PIN when prompted.
Check Balance:
Select the "Check Balance" option from the menu.
Withdraw Funds:
Choose the "Withdraw" option, specify the amount, and confirm.
Deposit Funds:
Select "Deposit," enter the amount to add, and confirm.
Future Enhancements
Add support for multiple user accounts.
Integrate with a GUI using frameworks such as Qt or SFML.
Implement encryption for storing user data securely.
Add an option to reset the PIN.

# Contribution :
Feel free to fork this repository and submit pull requests for improvements.



Name: Himanshu Singh
Email: https://github.com/DarkHacker28
