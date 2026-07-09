# Coupling in Java

This repository demonstrates one of the most important Object-Oriented Programming concepts: **Coupling**.

It contains two implementations:

- Tight Coupling
- Loose Coupling

## What is Coupling?

Coupling refers to the degree of dependency between two classes.

- High Dependency → Tight Coupling
- Low Dependency → Loose Coupling

## Repository Structure

```
Coupling-in-Java
│
├── Tight-Coupling
└── Loose-Coupling
```

---

## Tight Coupling

In Tight Coupling, a class directly depends on another concrete class.

Example:

```
Car
 ↓
Engine
```

Characteristics

- High dependency
- Uses concrete classes
- Difficult to modify
- Difficult to test
- Less flexible

---

## Loose Coupling

In Loose Coupling, a class depends on an interface instead of a concrete implementation.

Example

```
          Engine
             ▲
      ----------------
      |              |
 PetrolEngine   ElectricEngine
             ▲
            Car
```

Characteristics

- Low dependency
- Depends on abstraction
- Easy to maintain
- Easy to test
- Highly flexible

---

## Technologies Used

- Java
- OOP
- Interfaces
- Constructor Injection

---

## Key Learning

✔ Difference between Tight and Loose Coupling

✔ Interface-based programming

✔ Dependency Injection

✔ SOLID Principles

✔ Real-world design approach

---

## Author

**Nikhil Kusale**
