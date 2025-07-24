## 🏦 Simple Bank System 

## 💡 Features

### 🔹 Welcome
- Prints a simple random bank name on startup.

### 🔹 Account Creation
- Prompts the user for their **name** and **initial balance** (as a float).

### 🔹 Main Menu (Looped Interface)
- **Check Balance**  
  → Displays the current account balance.

- **Deposit**  
  → Prompts for an amount and adds it to the balance.

- **Withdraw**  
  → Prompts for an amount. Deducts it if sufficient balance is available; otherwise, displays a warning.

- **Exit**  
  → Exits the program with a thank-you message.

### 🔹 Additional Details
- Each operation is implemented using a **dedicated function**.
- After each action, the user’s **name and updated balance** are shown.
- Handles **invalid menu choices** gracefully with an error message.
- Uses `float` for storing and updating balance to support decimal transactions.
