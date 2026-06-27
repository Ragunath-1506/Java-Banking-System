# 🏦 Java Banking System

A Java console-based Banking System that calculates the **Recurring Deposit (RD) Maturity Amount** using Object-Oriented Programming concepts, exception handling, and input validation.

---

## 📌 Project Overview

This application allows users to calculate the maturity amount of a Recurring Deposit (RD) account by entering the required details such as tenure, principal amount, age, and gender. The application validates user input before performing the calculation.

---

## ✨ Features

- Calculate Recurring Deposit (RD) maturity amount
- Input validation for user details
- Custom exception handling
- Object-Oriented Programming (OOP)
- Console-based user interface
- Organized package structure

---

## 🛠 Technologies Used

- Java
- Eclipse IDE
- Java Scanner Class
- Exception Handling
- Object-Oriented Programming (OOP)
- Git & GitHub

---

## 📂 Project Structure

```
SystemDessign/
│
├── src/
│   ├── com.wipro.bank.main
│   │      └── Main.java
│   │
│   ├── com.wipro.bank.acc
│   │      ├── Account.java
│   │      └── RDAccount.java
│   │
│   ├── com.wipro.bank.service
│   │      └── BankService.java
│   │
│   └── com.wipro.bank.exception
│          └── BankValidationException.java
│
└── module-info.java
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/Ragunath-1506/Java-Banking-System.git
```

2. Open the project in Eclipse IDE.

3. Run `Main.java`.

4. Enter the required details:

- Tenure (5 or 10 years)
- Principal Amount
- Age
- Gender

5. View the calculated RD maturity amount.

---

## 📥 Sample Input

```
Enter Tenure (5/10): 5
Enter Principal Amount: 100000
Enter Age: 24
Enter Gender (Male/Female): Male
```

## 📤 Sample Output

```
Recurring Deposit Maturity Amount: ₹128000.00
```

*(Output may vary depending on the interest rate and calculation logic.)*

---

## 📚 Concepts Demonstrated

- Classes and Objects
- Packages
- Inheritance
- Method Overriding
- Exception Handling
- Input Validation
- Scanner Class
- Service Layer Design

---

## 🔒 Input Validation

The application validates:

- Principal amount
- Tenure
- Age
- Gender

If invalid data is entered, a custom `BankValidationException` is thrown.

---

## 🎯 Future Enhancements

- Savings Account Module
- Fixed Deposit (FD) Calculation
- Database Integration (MySQL)
- GUI using JavaFX or Swing
- User Authentication
- Transaction History

---

## 👨‍💻 Author

**Ragunath M**

- GitHub: https://github.com/Ragunath-1506

---

## 📄 License

This project is created for learning and educational purposes.
