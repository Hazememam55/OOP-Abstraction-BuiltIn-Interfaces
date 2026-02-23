# Abstraction & Built-in Interfaces in C#
s
---

## 📖 Overview
This project is a collection of small C# programs that demonstrate **Object-Oriented Programming (OOP)** principles — mainly **Abstraction**, **Encapsulation**, and the use of **Built-in Interfaces** such as `ICloneable`.

The assignment consists of three mini-projects, each focusing on a specific OOP concept and real-world scenario.

---

## 🧱 Project 01: 3D Point Class

### Goal
Create a 3D Point class that demonstrates **constructor chaining**, **operator overloading**, and **object cloning** using the `ICloneable` interface.

###  Concepts Practiced
- Constructor overloading and chaining  
- Overriding `ToString()`  
- Using `==` operator and comparison  
- Input validation with `TryParse`, `Parse`, and `Convert`  
- Sorting arrays of objects  
- Implementing the **`ICloneable`** interface  

###  What I Learned
- How constructor chaining improves readability and reusability.  
- How to properly override and use built-in methods like `ToString()` and `Equals()`.  
- How `ICloneable` allows creating deep copies of objects.  
- How to implement sorting logic for custom classes based on properties (X, Y).

---

## ➕ Project 02: Maths Utility Class

### 🎯 Goal
Implement a `Maths` class that performs basic arithmetic operations (**Add, Subtract, Multiply, Divide**) using **static methods**, so no instance creation is needed.

### 💡 Concepts Practiced
- Static methods and classes  
- Code reusability without object instantiation  
- Basic mathematical operations  

### 🧠 What I Learned
- How static members are shared across the class.  
- How to organize utility-like logic inside a static class.  
- The benefit of calling methods directly without creating objects.

---

## 🛍️ Project 03: E-Commerce Discount System

### 🎯 Goal
Design a system for an e-commerce platform to calculate discounts for various user types and discount strategies using **abstraction** and **inheritance**.

### 💡 Concepts Practiced
- Abstract classes and abstract methods  
- Implementing multiple concrete discount types:
  - `PercentageDiscount`
  - `FlatDiscount`
  - `BuyOneGetOneDiscount`
- Abstract user hierarchy with:
  - `RegularUser`
  - `PremiumUser`
  - `GuestUser`
- Polymorphism to dynamically apply different discount rules  
- Real-world abstraction and interface design  

### 🧠 What I Learned
- How abstraction hides implementation details while exposing essential behavior.  
- How polymorphism allows extending discount types or user roles easily.  
- How to integrate user input with abstract class logic to calculate discounts dynamically.

---

## ⚙️ How to Run

1. Open the solution in **Visual Studio** or **Visual Studio Code**.  
2. Build the project.  
3. Run each project separately using:
   ```bash
   dotnet run
   
---

4. Follow the console prompts for:
   -  **Entering coordinates for points (Project 1)**  
   -  **Performing arithmetic operations (Project 2)**  
   -  **Choosing user type and product details (Project 3)**  

---

## 🧠 Key Takeaways
- 💡 **Abstraction** simplifies system design by focusing on *what should be done*, not *how*.  
- ⚙️ **Built-in interfaces** like `ICloneable` demonstrate the power of reusability and standardization.  
- 🧩 **Polymorphism** and **Encapsulation** together create flexible, maintainable C# applications.  

