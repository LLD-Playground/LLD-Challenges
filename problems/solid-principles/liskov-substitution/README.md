# Liskov Substitution Principle (LSP) 🏛️  
The **Liskov Substitution Principle (LSP)** states that **subtypes must be substitutable for their base types without altering the correctness of the program**. In simple terms, if a class **inherits** from another, it should **honor the behavior** of the parent class instead of introducing unexpected changes.  

Violating LSP leads to **bugs, unexpected behavior, and fragile code**, making it difficult to extend or maintain. This principle ensures **robust inheritance** and promotes **polymorphism** in object-oriented design. 

## 🚀 Why is LSP Important?  
✅ Ensures **reliable inheritance** and prevents code breakage when extending classes.  
✅ Makes code **more predictable** by enforcing consistent behavior across subtypes.  
✅ Improves **maintainability** by reducing unintended side effects.  
✅ Strengthens **polymorphism**, allowing seamless object substitution.  

## 🎯 Problem Statement  
In many applications, subclassing is done incorrectly, leading to **unexpected behavior and broken functionality** when using derived classes in place of base classes.  

Your task is to **refactor a given class hierarchy** that violates LSP, ensuring that subclasses can replace their parent class without changing expected behavior.  

For a detailed explanation and starter code, refer to `liskov_substitution.ipynb`.  

## 🚀 How to Solve?
1. Open the Jupyter Notebook: `liskov_substitution.ipynb`
2. Follow through the instructions and run the notebook.

## 🤝 Contributing
Want to contribute? You can:
- Add new **examples** demonstrating LSP.
- Improve existing **explanations and documentation**.
- Submit a pull request with your **refactored solutions**.

For detailed guidelines, check [CONTRIBUTING.md](CONTRIBUTING.md).