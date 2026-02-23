# ATM Functionality

project:
  name: ATM Functionality
  language: Java
  type: Console Application

description: >
  A simple Java console application that simulates basic ATM (Automated Teller Machine) operations.
  It demonstrates core ATM functionalities such as checking balance, withdrawing funds,
  depositing money, and navigating a menu driven system.

features:
  - Enter PIN to access account
  - Check current balance
  - Withdraw cash with balance validation
  - Deposit funds
  - Menu driven interaction

tech_stack:
  - Java
  - Core Java OOP
  - Maven (optional if pom.xml present)

project_structure:
  - Main.java : Program entry point
  - ATMOperations.java : Contains logic for withdraw, deposit & balance

how_to_run:
  steps:
    - Clone the repository
    - Open in Java IDE (Eclipse / IntelliJ / VS Code)
    - Run the Main class

learning_outcomes:
  - Understand basic ATM operations simulation
  - Learn Java conditional logic and loops
  - Practice console input handling
  - Apply object oriented concepts

    Bharati Basumatary

future_enhancements:
  - Add file database persistence
  - Implement transaction history
  - Secure PIN with lockout feature after invalid tries
  - Add GUI using Swing or JavaFX

