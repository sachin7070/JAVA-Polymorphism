# Java Polymorphism

Welcome to the Java Polymorphism repository! This repository contains examples and explanations of polymorphism in Java.

## Introduction

Polymorphism is a fundamental concept in object-oriented programming (OOP) that allows objects to be treated as instances of their parent class. It enables flexibility and extensibility in Java programs by allowing different objects to be treated uniformly through a common interface. Polymorphism is achieved through method overriding and method overloading.

## Syntax

### Method Overriding

Method overriding occurs when a subclass provides a specific implementation of a method that is already defined in its superclass. The syntax for method overriding in Java is as follows:

```java
class Superclass {
    void display() {
        System.out.println("Superclass method");
    }
}

class Subclass extends Superclass {
    @Override
    void display() {
        System.out.println("Subclass method");
    }
}
```

### Method Overloading

Method overloading allows a class to have multiple methods with the same name but different parameters. The syntax for method overloading in Java is as follows:

```java
class MyClass {
    void display(int num) {
        System.out.println("Displaying integer: " + num);
    }
    
    void display(String text) {
        System.out.println("Displaying string: " + text);
    }
}
```

### Types of Polymorphism in Java

There are two main types of polymorphism in Java:

### Compile-time Polymorphism (Method Overloading): 

Method overloading allows a class to have multiple methods with the same name but different parameters. The appropriate method is chosen at compile-time based on the number and types of arguments passed to it.

### Runtime Polymorphism (Method Overriding): 

Method overriding occurs when a subclass provides a specific implementation of a method that is already defined in its superclass. The method to be executed is determined at runtime based on the actual object type.

## Contents

This repository includes:

Examples of compile-time and runtime polymorphism in Java.
Explanation of method overloading and method overriding.
Code snippets illustrating how to use polymorphism in Java programs.

## Usage

Feel free to explore the examples and code snippets provided in this repository to understand how polymorphism works in Java. You can run the Java programs locally on your machine using a Java Development Kit (JDK) and an Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or NetBeans.

## Contributing

Contributions to this repository are welcome! If you have any improvements, additional examples, or corrections to make, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. You are free to use the code and examples in this repository for educational or commercial purposes.


