# Accounts API

The **Accounts API** lets you manage customer bank accounts.  

### Available Endpoints
- **GET `/accounts`** – Retrieve all accounts  
- **POST `/accounts`** – Create a new account  
- **GET `/accounts/{accountId}`** – Get account details  
- **PUT `/accounts/{accountId}`** – Update account details  
- **DELETE `/accounts/{accountId}`** – Delete an account  

Each account includes:  
- `accountId` – Unique identifier  
- `accountType` – e.g., Savings, Checking  
- `currency` – e.g., USD, EUR  
- `balance` – Current balance in the account
