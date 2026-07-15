# 🔢 Fibonacci Sequence Generator

![Java](https://img.shields.io/badge/Java-21-orange?logo=openjdk)
![IDE](https://img.shields.io/badge/IDE-Eclipse-purple?logo=eclipseide)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Bootcamp](https://img.shields.io/badge/Cloudberry-Java%20Automation-blue)

---

# 📖 Overview

This project demonstrates how to generate the **Fibonacci Sequence** using Java.

The Fibonacci sequence is a series of numbers where each number is the sum of the two previous numbers.

Example:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34...

This exercise was completed as part of my **Cloudberry Java Automation Bootcamp** to strengthen my understanding of loops, variables, and mathematical logic in Java.

---

# 🎯 Learning Objectives

✅ Understand the Fibonacci sequence

✅ Practice using variables

✅ Use loops to generate a sequence

✅ Perform mathematical calculations

✅ Display formatted output

---

# 🛠 Technologies Used

- ☕ Java 21
- 💻 Eclipse IDE
- 🖥 Windows 11

---

# 📂 Project Structure

```
Fibonacci/
│
├── src/
│   └── Fibonacci.java
│
└── README.md
```

---

# 💻 Sample Code

```java
int first = 0;
int second = 1;

System.out.println("Fibonacci Sequence:");

for (int i = 1; i <= 10; i++) {
    System.out.print(first + " ");

    int next = first + second;
    first = second;
    second = next;
}
```

---

# ▶ Sample Output

```
Fibonacci Sequence:

0 1 1 2 3 5 8 13 21 34
```

---

# 🧠 Concepts Learned

📌 Variables

📌 Integer Arithmetic

📌 For Loops

📌 Sequence Generation

📌 Mathematical Logic

📌 Iteration

---

# 📸 Screenshots

## Eclipse Project

> *(Insert screenshot here)*

Example:

```
images/eclipse-project.png
```

---

## Program Code

> *(Insert screenshot here)*

Example:

```
images/code.png
```

---

## Console Output

> *(Insert screenshot here)*

Example:

```
images/output.png
```

---

# 🚀 Future Improvements

- Allow the user to choose how many Fibonacci numbers to generate
- Accept user input with the Scanner class
- Display each Fibonacci number on a separate line
- Validate user input
- Calculate larger sequences using the `long` data type

---

# 📚 What I Learned

This project helped me understand how mathematical sequences can be generated using Java loops and variables. It reinforced the importance of updating variable values during each iteration and strengthened my problem-solving skills for algorithm development.

The Fibonacci sequence is commonly used to practice programming logic and serves as a foundation for more advanced algorithmic concepts.

---

# 👨‍💻 Author

**Tracy Joseph**

QA Automation Student

Cloudberry Java Automation Bootcamp

GitHub:
https://github.com/TOJ-QA

---

⭐ Thank you for checking out my Fibonacci Sequence project!
