# Strategy Design Pattern 🧩

The **Strategy Design Pattern** is a behavioral design pattern that allows selecting an algorithm’s behavior at runtime. It helps in defining a family of algorithms, encapsulating them, and making them interchangeable without modifying the client code.

This pattern promotes the **Open-Closed Principle (OCP)** by allowing new strategies to be added **without altering existing code**.

## 🔹 Importance of the Strategy Design Pattern
* **Promotes Flexibility** Allows dynamically changing the behavior of a class without modifying its code.

* **Adheres to OCP (Open-Closed Principle)** New strategies can be added **without modifying existing logic**.

* **Encapsulates Algorithms** Different algorithms (or behaviors) are separated into individual classes, improving **code maintainability**.

* **Reduces Code Duplication** Avoids large `if-else` or `switch` statements by delegating behavior to separate strategy classes.

* **Improves Testability** Individual strategies can be **unit tested separately**, making debugging easier.

* **Enhances Scalability** Easily extend functionality by adding new strategies **without breaking existing code**.

## 🎯 Problem Statement
Your task is to **refactor a given class** that violates the **Strategy Design Pattern** principles by **separating different behaviors into interchangeable strategies**. This will make the system more **flexible, scalable, and aligned with SOLID principles**.

For a detailed explanation and starter code, refer to `strategy_pattern.ipynb`. 🚀

## 🚀 How to Solve?
1. Open the Jupyter Notebook: `strategy_pattern.ipynb`
2. Follow through the instructions and run the notebook.

## 🤝 Contributing
Want to contribute? You can:
- Add new **examples** demonstrating Strategy Design Pattern.
- Improve existing **explanations and documentation**.
- Submit a pull request with your **refactored solutions**.

For detailed guidelines, check [CONTRIBUTING.md](CONTRIBUTING.md).