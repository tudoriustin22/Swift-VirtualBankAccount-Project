# 🏦 Virtual Bank System

A simple banking system final project built in **Swift ** as part of the **Programming Fundamentals in Swift Course by Meta**. This project simulates basic banking operations such as account creation, deposits, withdrawals, and balance inquiries using Swift Playground. Best practice is to take the .swift file code and then paste it into a blank playground file in either Xcode 16 or Swift Playgrounds app which is available on both  Mac or iPad.

## ✨ Features

- 📌 **Customer Onboarding** – Choose between a **debit** or **credit** account.
- 💰 **Deposit & Withdraw** – Perform transactions with a **credit limit** for credit accounts.
- 📊 **Balance Inquiry** – View available funds or credit limit.
- 🔄 **Looped Interaction** – Randomized user input for simulating user actions.
- 🚀 **Swift Playground Compatible** – Easy to run and experiment with.

## 🛠 Technologies Used

- **Swift 6**
- **Swift Playgrounds**

## 📜 How It Works

1. The system **welcomes the customer** and prompts for account selection.
2. The user chooses **debit or credit**.
3. The user is presented with transaction options:
   - **Check balance**
   - **Deposit funds**
   - **Withdraw funds**
   - **Exit the system**
4. The system executes actions based on **randomized input** (for simulation purposes).
5. Transactions are handled according to **account type constraints**.

## 🏗 Code Structure

### `VirtualBankSystem` (Class)
Handles customer interactions, account creation, and transaction execution.

- `welcomeCustomer()`
- `onboardCustomerAccountOpening()`
- `makeAccount(numberPadKey: Int)`
- `transferMoney(transferType: String, transferAmount: Int, bankAccount: inout BankAccount)`
- `checkBalance(bankAccount: BankAccount)`

### `BankAccount` (Struct)
Manages account balances and transactions.

- `debitDeposit(_ amount: Int)`
- `debitWithdraw(_ amount: Int)`
- `creditDeposit(_ amount: Int)`
- `creditWithdraw(_ amount: Int)`

## 🚀 Running the Project

1. Open **Swift Playgrounds** or **Xcode**.
2. Copy and paste the **VirtualBankSystem.swift** code into a Playground.
3. Run the Playground and observe the **banking system simulation**.

## 📌 Future Enhancements

- Add **user input handling** instead of randomized values.
- Implement a **UI-based banking system** using SwiftUI.
- Store transaction history for a more realistic experience.

---

📌 **Developer:** Tudor Iustin  
📌 **Course:** Programming Fundamentals in Swift (Meta)  
