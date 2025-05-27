# 🏦 Bank Account Simulator with Twilio SMS Alerts

A simple Python-based simulation of a bank account system that supports *withdrawals* and *deposits*, sends SMS alerts using Twilio, and logs all transactions.

## ✨ Features

- Deposit and withdraw funds securely
- Real-time SMS alerts for each transaction
- Custom exception handling for invalid transactions
- Transaction logging with timestamps


## 🧪 How It Works

1. *Create an Account*  
   A bank account is initialized with an account number, balance, and phone number.

2. *Withdraw/Deposit Funds*  
   The user can withdraw or deposit funds via console input.

3. *SMS Notification*  
   Every successful or failed transaction sends an SMS alert using Twilio.

4. *Logging*  
   All events (transactions, errors, etc.) are recorded in bank_transactions.log.


## 📦 Requirements

- Python 3.x
- [Twilio Account](https://www.twilio.com/)
- Twilio Python library:
  
  pip install twilio
