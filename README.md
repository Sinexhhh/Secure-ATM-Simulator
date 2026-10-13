Secure ATM Simulator

A Java console application that models core ATM account operations. The project uses an interface-driven service layer and separate account models to keep responsibilities organized.

## Features

- Verify a user's PIN before account actions
- Change a PIN after validating the current PIN
- Retrieve an account balance
- Define and retrieve a withdrawal limit
- Represent general bank accounts and savings accounts with separate model classes
- Separate ATM service behavior from its interface

## Project Structure

```text
src/
├── interfaces/
│   └── ATMService.java
├── models/
│   ├── BankAccount.java
│   └── SavingAccount.java
├── services/
│   └── ATMServiceImpl.java
└── ATMApp.java
```

## Getting Started

### Requirements

- Java Development Kit (JDK)
- A Java IDE such as Eclipse or Visual Studio Code, or another Java build environment

### Run the application

1. Clone or download this repository.
2. Open the project in your Java IDE.
3. Confirm the source files are in the packages shown above and that the package declarations match their folders.
4. Run `ATMApp.java`.

## Design

- **`ATMService`** declares the operations offered by the ATM service.
- **`ATMServiceImpl`** provides the service implementation.
- **`BankAccount`** stores account details and provides PIN authentication, PIN updates, balance access, and withdrawal-limit access.
- **`SavingAccount`** models the savings account type.
- **`ATMApp`** is the application entry point.

## Scope

This project is intended for learning and demonstration. It models account behavior in Java; it is not connected to a real bank or payment network.

## Author

**Sinesh Babbar**

- GitHub: [@Sinexhhh](https://github.com/Sinexhhh)
- LinkedIn: [sineshbabbar](https://www.linkedin.com/in/sineshbabbar/)
