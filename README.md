 **Inheritance in C++**  

---

## Aim  
To study and understand the concept of **Inheritance in Object-Oriented Programming (OOP)** and how it helps in reusing code and establishing relationships between classes.  

---

## Theory  
Inheritance is one of the core concepts of **Object-Oriented Programming (OOP)**. It allows a class (**derived class**) to inherit properties and methods from another class (**base class**).  

### Key Concepts:  
- **Base Class (Parent Class):** Provides common attributes and behaviors.  
- **Derived Class (Child Class):** Inherits from the base class and can also add its own features.  

### Types of Inheritance:  
1. **Single Inheritance** – One class inherits from one base class.  
2. **Multiple Inheritance** – A class inherits from more than one base class.  
3. **Multilevel Inheritance** – A class is derived from another derived class.  
4. **Hierarchical Inheritance** – Several classes inherit from one base class.  
5. **Hybrid Inheritance** – A mix of different types of inheritance.  

### Importance of Inheritance:  
- Promotes **code reusability**.  
- Establishes **hierarchical class structures**.  
- Supports **polymorphism**.  
- Reduces redundancy and improves maintainability.  

---

## Conclusion  
- Inheritance in C++ enables the creation of new classes based on existing ones, reducing duplication of code.  
- It ensures better program organization by creating a **hierarchical relationship** between classes.  
- It forms the foundation for advanced OOP features like **polymorphism** and **abstraction**, making programs more flexible and scalable.  

---
## Algorithm (PROGRAM-1)

1. **Start**  
2. Define a class **vehicle** with:  
   - A data member `brand = "Ford"`.  
   - A member function `colour()` that prints `"Red"`.  
3. Define a class **car** that inherits from **vehicle** (public inheritance) with:  
   - A data member `model = "Mustang"`.  
4. In the **main() function**:  
   - Create an object `c1` of type `car`.  
   - Call the function `c1.colour()`, which prints `"Red"`.  
   - Print the inherited data member `c1.brand`, which outputs `"Ford"`.  
   - Print the model of `c1`, which outputs `"Mustang"`.  
5. **End**  
