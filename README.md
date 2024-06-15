# DCIT318 Assignment 2

## Description

This repository contains a C# console application demonstrating various aspects of object-oriented programming (OOP) in C#. The project is divided into three parts:

1. **Inheritance and Method Overriding**: Demonstrates inheritance and method overriding using a base class `Animal` and derived classes `Dog` and `Cat`.
2. **Abstract Classes and Methods**: Demonstrates abstract classes and methods using an abstract class `Shape` and derived classes `Circle` and `Rectangle`.
3. **Interfaces**: Demonstrates the use of interfaces with an `IMovable` interface and implementing classes `Car` and `Bicycle`.

## Repository Structure

- `InheritanceAndMethodOverriding/`: Contains the implementation for inheritance and method overriding.
- `AbstractClassesAndMethods/`: Contains the implementation for abstract classes and methods.
- `Interfaces/`: Contains the implementation for interfaces.

## Getting Started

### Prerequisites

- .NET Core SDK
- Visual Studio or any other C# IDE
- Git

### Installation

1. **Clone the repository**:

    ```sh
    git clone https://github.com/your-username/dcit318-assignment2-ID.git
    cd dcit318-assignment2-ID
    ```

2. **Open the project**:

    - Open the project in Visual Studio or your preferred C# IDE.

3. **Build and Run**:

    - Build the solution to restore the dependencies.
    - Run the application to see the output for each part of the assignment.

## Tasks

### 1. Inheritance and Method Overriding

This part demonstrates inheritance and method overriding.

- **Files**:
  - `InheritanceAndMethodOverriding/Program.cs`
  - `InheritanceAndMethodOverriding/Animal.cs`
  - `InheritanceAndMethodOverriding/Dog.cs`
  - `InheritanceAndMethodOverriding/Cat.cs`

- **Description**:
  - Defines a base class `Animal` with a method `MakeSound`.
  - Creates derived classes `Dog` and `Cat` that override the `MakeSound` method.
  - In the `Main` method, instances of `Animal`, `Dog`, and `Cat` are created, and their `MakeSound` methods are called.

### 2. Abstract Classes and Methods

This part demonstrates abstract classes and methods.

- **Files**:
  - `AbstractClassesAndMethods/Program.cs`
  - `AbstractClassesAndMethods/Shape.cs`
  - `AbstractClassesAndMethods/Circle.cs`
  - `AbstractClassesAndMethods/Rectangle.cs`

- **Description**:
  - Defines an abstract class `Shape` with an abstract method `GetArea`.
  - Creates derived classes `Circle` and `Rectangle` that implement the `GetArea` method.
  - In the `Main` method, instances of `Circle` and `Rectangle` are created, and their areas are displayed.

### 3. Interfaces

This part demonstrates the use of interfaces.

- **Files**:
  - `Interfaces/Program.cs`
  - `Interfaces/IMovable.cs`
  - `Interfaces/Car.cs`
  - `Interfaces/Bicycle.cs`

- **Description**:
  - Defines an interface `IMovable` with a method `Move`.
  - Creates classes `Car` and `Bicycle` that implement the `IMovable` interface.
  - In the `Main` method, instances of `Car` and `Bicycle` are created, and their `Move` methods are called.

## Version Control

Each task has been committed separately to provide a clear history of the work done on this assignment.

## Submission

Submit a compressed folder of this repository to Sakai.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Instructor: [Instructor's Name]
- Course: DCIT318 - Object-Oriented Programming

