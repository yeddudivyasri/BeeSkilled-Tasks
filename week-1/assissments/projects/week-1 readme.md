# Week 1: Foundations of Java Programming 🚀

A beginner-friendly introduction to Java programming with **2 hands-on assignments** and **1 mini project**.

---

## 📚 What You'll Learn

- ✅ Variables & Data Types
- ✅ Scanner (User Input)
- ✅ Conditional Statements (if-else, switch)
- ✅ Loops (do-while)
- ✅ Input Validation
- ✅ Menu-Driven Programs

---

## 📁 Week 1 Structure

```
Week1/
├── Assignments/
│   ├── BasicCalculator.java       # Assignment 1
│   ├── GradeEvaluation.java       # Assignment 2
│   └── README.md
├── MiniProject/
│   ├── BankManagementApp.java     # Mini Project
│   └── README.md
└── README.md (this file)
```

---

## 🔧 Prerequisites

- **Java JDK** 8 or higher ([Download](https://www.oracle.com/java/technologies/downloads/))
- **Text Editor or IDE** (VS Code, IntelliJ IDEA, Eclipse)
- **Command Prompt/Terminal**

---

## 📋 Assignment 1: Basic Calculator Program

**File:** `Assignments/BasicCalculator.java`

A simple calculator that performs basic arithmetic operations.

### Features
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/) with error handling

### How to Run
```bash
cd Week1/Assignments
javac BasicCalculator.java
java BasicCalculator
```

### Example
```
Enter first number: 10
Enter operator (+, -, *, /): +
Enter second number: 5
Result: 15.0
```

### Key Concepts
- Scanner for user input
- switch statement
- Arithmetic operations

---

## 📋 Assignment 2: Grade Evaluation Program

**File:** `Assignments/GradeEvaluation.java`

Evaluates student grades based on marks.

### Features
- Takes marks (0-100) as input
- Assigns grades:
  - **A:** 90-100
  - **B:** 75-89
  - **C:** 60-74
  - **Fail:** Below 60

### How to Run
```bash
cd Week1/Assignments
javac GradeEvaluation.java
java GradeEvaluation
```

### Example
```
Enter student marks (0 - 100): 85
Grade: B
```

### Key Concepts
- if-else conditional statements
- Logical conditions
- User input validation

---

## 🎯 Mini Project: Bank Management Console App

**File:** `MiniProject/BankManagementApp.java`

A menu-driven banking application with account operations.

### Features
- 💰 **Deposit:** Add money to account
- 🏦 **Withdraw:** Remove money with validation
- 📊 **Check Balance:** View current balance
- 🚪 **Exit:** Close application

### How to Run
```bash
cd Week1/MiniProject
javac BankManagementApp.java
java BankManagementApp
```

### Example Usage
```
====================================
   Welcome to Bank Management App   
====================================

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice: 1
Enter amount to deposit: 1000
Successfully deposited ₹1000.0

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice: 3
Current Balance: ₹1000.0

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice: 2
Enter amount to withdraw: 500
Successfully withdrew ₹500.0

Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Enter your choice: 4
Thank you for using Bank Management App. Goodbye!
```

### Key Concepts
- Menu-driven design
- do-while loops
- switch statements
- Input validation
- Balance tracking

---

## 💡 Learning Outcomes

By completing Week 1, you will be able to:

- ✅ Create and compile Java programs
- ✅ Accept user input using Scanner
- ✅ Use conditional statements (if-else, switch)
- ✅ Implement loops for repetitive tasks
- ✅ Validate user input
- ✅ Build interactive console applications

---

## 🎯 How to Complete Week 1

### Step 1: Assignment 1
1. Open `BasicCalculator.java`
2. Compile and run it
3. Test with different numbers and operators
4. Try edge cases (division by zero)

### Step 2: Assignment 2
1. Open `GradeEvaluation.java`
2. Compile and run it
3. Test with different marks (0, 50, 75, 90, 100)
4. Verify grade assignments

### Step 3: Mini Project
1. Open `BankManagementApp.java`
2. Compile and run it
3. Test all operations (deposit, withdraw, balance, exit)
4. Try invalid inputs (negative amounts, overdraft)

---

## 🔧 Compilation & Execution Quick Reference

```bash
# Navigate to folder
cd Week1/Assignments

# Compile
javac BasicCalculator.java

# Run
java BasicCalculator
```

---

## 💻 Code Concepts Summary

| Concept | Used In | Purpose |
|---------|---------|---------|
| Scanner | All programs | Read user input |
| if-else | Assignment 2 | Conditional logic |
| switch | Assignment 1, Mini Project | Multi-way branching |
| do-while | Mini Project | Repeat menu until exit |
| Variables | All programs | Store data |

---

## ✅ Testing Checklist

- [ ] BasicCalculator: Test +, -, *, / operations
- [ ] BasicCalculator: Test division by zero error
- [ ] GradeEvaluation: Test marks at boundaries (0, 59, 60, 74, 75, 89, 90, 100)
- [ ] BankManagementApp: Test deposit with positive amount
- [ ] BankManagementApp: Test withdraw with sufficient balance
- [ ] BankManagementApp: Test withdraw with insufficient balance
- [ ] BankManagementApp: Test check balance
- [ ] BankManagementApp: Test exit option

---

## 🐛 Common Issues

### Issue: `javac: command not found`
**Solution:** Install JDK and add it to PATH

### Issue: `Scanner` throws exception
**Solution:** Provide input when program asks

### Issue: `java.lang.ArithmeticException: / by zero`
**Solution:** This is handled in BasicCalculator - test it!

### Issue: Menu doesn't repeat in Bank App
**Solution:** This program uses do-while loop - keep entering choices until you select Exit

---

## 📝 Best Practices

- ✅ Compile frequently to catch errors early
- ✅ Test with multiple inputs
- ✅ Test edge cases (0, negative, very large numbers)
- ✅ Add comments to explain code
- ✅ Follow Java naming conventions
- ✅ Validate all user inputs

---

## 📚 Additional Resources

- [Oracle Java Documentation](https://docs.oracle.com/javase/)
- [Java Tutorial](https://docs.oracle.com/javase/tutorial/)
- [GeeksforGeeks Java](https://www.geeksforgeeks.org/java/)

---

## 📊 Files Summary

| File | Type | Concepts |
|------|------|----------|
| BasicCalculator.java | Assignment | Scanner, switch, arithmetic |
| GradeEvaluation.java | Assignment | if-else, conditions |
| BankManagementApp.java | Mini Project | do-while, switch, validation |

---

## 🎉 Ready to Start?

1. Clone/download this repository
2. Navigate to `Week1/Assignments`
3. Start with `BasicCalculator.java`
4. Follow instructions above
5. Complete all assignments and mini project
6. Move to Week 2! 🚀

---

**Happy Learning! 💪**

**Last Updated:** June 8, 2026  
**Level:** Beginner  
**Language:** Java  
**Duration:** 1 Week
