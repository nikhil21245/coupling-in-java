# Tight Coupling Example

## Description

This example demonstrates Tight Coupling in Java.

The `Car` class directly creates an `Engine` object using the `new` keyword.

```java
Engine engine = new Engine();
```

Because of this, `Car` is completely dependent on `Engine`.

## Class Diagram

```
Car
 ↓
Engine
```

## Advantages

- Simple
- Easy for small applications

## Disadvantages

- Difficult to modify
- Difficult to test
- Difficult to extend
- High dependency

## Output

```
Engine Started
Car is moving
```