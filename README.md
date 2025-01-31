# S.O.L.I.D Principles in React

## Introduction

The S.O.L.I.D principles are a set of five design principles aimed at making software designs more understandable, flexible, and maintainable. This repository illustrates how these principles can be effectively applied in React applications.

## Principles

### 1. Single Responsibility Principle (SRP)

**Definition:** Every function/module/component should have only one responsibility.

**Application:**
- Break large components into smaller, focused components.
- Extract code unrelated to the main component functionality into separate utility functions.
- Encapsulate connected functionality into custom hooks.

**Goal:**
- Enhance maintainability by ensuring components manage only one concern.

[**Code Example**](https://github.com/Safnaj/React-SOLID-Principles/tree/main/src/principles/SRP)

---

### 2. Open-closed Principle (OCP)

**Definition:** Software entities should be open for extension but closed for modification.

**Application:**
- Structure components to allow extensions without altering their original functionality.

**Goal:**
- Facilitate easier feature additions while maintaining existing functionality, thus reducing the risk of introducing bugs.

[**Code Example**](https://github.com/Safnaj/React-SOLID-Principles/tree/main/src/principles/OCP)

---

### 3. Liskov Substitution Principle (LSP)

**Definition:** Subtype objects should be substitutable for supertype objects without affecting the correctness of the program.

**Application:**
- Prefer composition over inheritance for code reuse in React.

**Goal:**
- Create flexible, interchangeable components that can be composed to form complex UI elements.

[**Code Example**](https://github.com/Safnaj/React-SOLID-Principles/tree/main/src/principles/LSP)

---

### 4. Interface Segregation Principle (ISP)

**Definition:** Clients should not depend on interfaces they do not use.

**Application:**
- Ensure components only depend on the props they actually utilize, promoting minimal dependencies.

**Goal:**
- Improve maintainability and increase flexibility by making components more focused and reusable.

[**Code Example**](https://github.com/Safnaj/React-SOLID-Principles/tree/main/src/principles/ISP)

---

### 5. Dependency Inversion Principle (DIP)

**Definition:** High-level modules should not depend on low-level modules; both should depend on abstractions.

**Application:**
- Avoid direct dependencies between components, promoting the use of common abstractions.

**Goal:**
- Enhance testability and decouple components, ensuring changes to one component do not necessitate changes in others.

[**Code Example**](https://github.com/Safnaj/React-SOLID-Principles/tree/main/src/principles/DIP)

---

## References

- [Applying SOLID Principles in React](https://konstantinlebedev.com/solid-in-react/)
- [How to Implement the SOLID Principle in React?](https://javascript.plainenglish.io/solid-principle-in-react-11272c41b529)
- [Write React Clean-Code - SOLID](https://www.youtube.com/watch?v=MSq_DCRxOxw)
