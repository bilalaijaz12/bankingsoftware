# Banking Software
## About
Version: 1.0.0

Open Source

## Objectives
Create an open source software for processing banking transactions.
40% of all banking systems are written in COBOL. This open source application is to change the banking system.
Making the banking system faster, safer, easier and more secure is beneficial for the entire industry.
Providing an open source foundation for banking software using advanced applications and architecture. 

## Architecture
At the moment here's my idea for the software layout:
### UI:
* Application bones built with Python
* Main UI built using webpages (HTML + CSS)
* Submits and inputs done through JavaScript

### Backend:
* Server hosted by AWS
* No-SQL database structure
* Use NOde.js to retreive and send data from database
* Transaction database stored in blockchain

## Requirements:
* IDE and/or text editor
* Node.js
* ExpressJS library
* Python 3
* Local server (XAMPP, WAMP, etc.)

## System Design:
Admin Account:
* Login for branch manager to edit transactions and account 
* Stored in NoSQL database
* Admin.html

Teller Accounts:
* Login for tellers to perform transactions
* Stored in NoSQL database
* Index.html

Customer Accounts:
* Data able to be accessed by third party banking apps

Data:
* Branch/region routing number
* Customer specific account numbers (Object[account] = routing #, account #, balance, transactions, card #, etc.)
* Customer sensitive info (name, email, phone #, address)

Built in applications:
* OFAC