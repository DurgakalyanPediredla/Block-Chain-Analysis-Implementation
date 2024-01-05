
**Problem Statement** This project focuses on developing a Python simulation that mimics transactional access to sensitive loan account data within a retail bank. Each instance where a bank employee accesses an account is treated as a transaction.

Each transaction represents a singular access to an account by a bank personnel. Given the sensitive nature of the data, it is imperative that access records are permanently and immutably stored within a blockchain network. This ensures a robust audit trail for monitoring and review processes.

All sensitive loan account details are stored in loan_account_statment.json. Any access to this information necessitates the permanent logging of these access records on a tamper-resistant blockchain network for audit trails. 

In this assignment, I wrote a Python code that generates a block with embedded transaction details in the form of a dictionary. The simulation will encompass numerous access requests by bank employees. The ultimate objective is to architect a blockchain structure containing data access transactions. Most transactional queries in the blockchain are conducted in JSON (JavaScript Object Notation format). A JSON format is very similar to a Python dictionary.

