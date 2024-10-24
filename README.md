# Banking-System-simulation-in-Python-OOPs
This is a simple Python program that simulates a basic banking system using Object-Oriented Programming (OOP) principles. The system allows users to:

## Login using an account PIN.
## Deposit money into their account.
## Withdraw money if sufficient balance is available.
## Check their current balance.
## View transaction history (deposits and withdrawals).
Features:
Account Login: Secure login with a PIN.
Amount Deposit: Allows depositing money to increase the account balance.
Amount Withdrawal: Allows withdrawing money from the account with sufficient balance checks.
Transaction History: Displays a record of all transactions (deposits and withdrawals).
Show Balance: Easily check the current balance of the account.
Code Structure:
The program is implemented using a BankAccount class that encapsulates all functionalities such as login, deposit, withdrawal, transaction history, and balance checking.

Class: BankAccount
Attributes:

account_number: The unique account number of the user.
pin: The PIN for login validation.
balance: The account balance (default is 0).
transactions: A list to store transaction history.
Methods:

login(pin): Verifies the entered PIN for login.
deposit(amount): Deposits money into the account.
withdraw(amount): Withdraws money if the balance is sufficient.
show_balance(): Displays the current balance.
show_transactions(): Displays the history of transactions.
Sample Usage:
Here’s a step-by-step example of how the system works:

The user logs in using their PIN.
After a successful login, the user can:
Deposit money.
Withdraw money.
View their balance.
Check transaction history.
The user can repeat the above actions until they choose to exit.
