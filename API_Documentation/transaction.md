# Transactions API

The **Transactions API** lets you create and manage financial transactions for accounts.  

### Available Endpoints
- **GET `/transactions`** – Retrieve all transactions  
- **POST `/transactions`** – Create a new transaction  
- **GET `/transactions/{transactionId}`** – Get transaction details  
- **PUT `/transactions/{transactionId}`** – Update transaction details  
- **DELETE `/transactions/{transactionId}`** – Delete a transaction  

Each transaction includes:  
- `transactionId` – Unique identifier  
- `accountId` – The account linked to the transaction  
- `amount` – Positive (credit) or negative (debit)  
- `currency` – Transaction currency  
- `description` – Details of the transaction  
- `date` – Timestamp of the transaction
