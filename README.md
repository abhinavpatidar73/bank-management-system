# PS-8: Settlement Q&A Agent

## Project Overview

Settlement Q&A Agent is a simple Python command-line project made to trace payment transactions through three different records:

- Gateway
- Bank
- Ledger

The program checks the information available for a transaction and identifies whether the settlement is completed or if there is an issue that needs attention.

The project uses mock data for demonstration and learning purposes.

## Features

- Search for a transaction using its Transaction ID
- View Gateway transaction details
- View Bank transaction details
- View Ledger transaction details
- Check the settlement status
- Find pending or failed transactions
- Detect missing or unrecorded transactions
- Compare transaction amounts
- Compare transaction dates
- Search transactions by date
- Handle invalid Transaction IDs
- Handle invalid menu choices

## Technologies Used

- Python 3
- Dictionaries
- Functions
- Lists
- Loops
- Conditional statements
- Python `unittest` module

The project does not require any external Python packages.

## Project Files

```text
PS-8-Settlement-QA-Agent/
│
├── main.py
├── test_system.py
└── README.md