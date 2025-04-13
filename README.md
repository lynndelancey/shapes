# shapes
# Shapes Project

This project demonstrates the use of object-oriented programming principles in Java, including abstraction, inheritance, polymorphism, and method overriding. It includes an abstract `Shape` class and its three concrete subclasses: `Sphere`, `Cylinder`, and `Cone`. 

## Project Structure
- **Shape.java**: Defines the abstract `Shape` class with `surfaceArea()` and `volume()` abstract methods.
- **Sphere.java**: A subclass of `Shape` representing a sphere, with methods to calculate surface area and volume.
- **Cylinder.java**: A subclass of `Shape` representing a cylinder, with methods to calculate surface area and volume.
- **Cone.java**: A subclass of `Shape` representing a cone, with methods to calculate surface area and volume.
- **ShapeArray.java**: A driver class to instantiate objects of each shape, store them in an array, and display their details using the `toString()` method.

## Features
1. **Abstraction**: The `Shape` class provides a template for all shapes with abstract methods for surface area and volume calculations.
2. **Inheritance**: `Sphere`, `Cylinder`, and `Cone` extend the `Shape` class, inheriting its structure and overriding methods.
3. **Polymorphism**: The `ShapeArray` class demonstrates polymorphism by treating different shapes as instances of the `Shape` class.
4. **Dynamic Behavior**: Each shape class dynamically computes surface area and volume based on its attributes.

## UML Diagram
The UML diagram illustrates the relationship between the `Shape` abstract class and its subclasses. Please refer to the `shapes_project_diagram.png` file in this repository.

## How to Run
1. Compile all `.java` files using a Java compiler:
   ```bash
   javac Shape.java Sphere.java Cylinder.java Cone.java ShapeArray.java
