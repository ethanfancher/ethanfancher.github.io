# Ethan Fancher's ePortfolio Entry

## Overview

Welcome to my ePortfolio, where I present a comprehensive overview of my software development journey during my academic career. This portfolio encapsulates my technical growth, focusing on three distinct projects that highlight my capabilities in object-oriented programming, user interface design, data structures, and algorithm optimization. Each project is carefully chosen to demonstrate both the breadth and depth of my programming skills and problem-solving abilities.

## Project 1: Object-Oriented Hierarchy for Vehicle Management

### Artifact Description

This Java project models a hierarchical system for managing various types of vehicles, with a particular focus on bicycles and two-wheeled vehicles. It utilizes object-oriented principles to simulate real-world interactions between different vehicle types through a well-defined class structure.

### Code Example

```java
public class Bicycle extends TwoWheeled {
    private boolean hasBasket;

    public Bicycle(String model, double speed, boolean hasBasket) {
        super(model, speed);
        this.hasBasket = hasBasket;
    }

    // Method to display bicycle details
    public void displayDetails() {
        System.out.println("Bicycle Model: " + getModel() + " Speed: " + getSpeed() + " Basket: " + hasBasket);
    }
}
```

### Skills and Improvements

- **Designing Class Hierarchies:** Created a logical, extendable class structure using inheritance to simplify and organize code, making future modifications more manageable.
- **Implementing OOP Principles:** Demonstrated encapsulation, inheritance, and polymorphism to build a robust, scalable system.
- **Code Refactoring:** Improved the readability and maintainability of the code by refining and optimizing existing implementations, including adding comprehensive constructors and method overloading.
- **Reflection:** Gained deeper insights into Java and object-oriented design, specifically how effective use of inheritance and polymorphism can create scalable software architectures. This enhancement also bolstered my debugging skills and my ability to implement user feedback to refine functionality.

## Project 2: Java Swing Application for Detox Destinations

### Artifact Description

A desktop application created using Java Swing that showcases various detox destinations with their descriptions and images. It's designed for ease of use, with interactive features that allow users to sort and view destinations efficiently.

### Code Example

```java
DefaultListModel<TextAndIcon> model = new DefaultListModel<>();
JList<TextAndIcon> list = new JList<>(model);
model.addElement(new TextAndIcon("Destination Name", new ImageIcon("path/to/image.jpg")));

// Function to sort destinations alphabetically
public void sortDestinations() {
    Collections.sort(model, new Comparator<TextAndIcon>() {
        @Override
        public int compare(TextAndIcon o1, TextAndIcon o2) {
            return o1.getText().compareToIgnoreCase(o2.getText());
        }
    });
}
```

### Skills and Improvements

- **GUI Design:** Developed a visually appealing interface that enhances user interaction and accessibility.
- **Data Handling:** Managed complex data sets using custom data structures, improving the application's efficiency and scalability.
- **Algorithm Implementation:** Integrated a sorting algorithm to dynamically organize data, significantly enhancing the user experience by making information retrieval more intuitive.
- **Reflection:** This project deepened my understanding of user interface design and the importance of aligning technical solutions with user needs. The feedback loop from users and peers was crucial for iterative development, leading to a more refined and user-focused application.

## Project 3: Binary Search Tree for Bid Data Management

### Artifact Description

A C++ implementation that uses a Binary Search Tree (BST) to manage and efficiently organize bid data. This project was enhanced by incorporating AVL Tree features to ensure high performance and scalability as the data grows.

### Code Example

```cpp
void rotateLeft(Node* &root) {
    Node* newRoot = root->right;
    root->right = newRoot->left;
    newRoot->left = root;
    root = newRoot;

    // Update heights
    updateHeight(root->left);
    updateHeight(root);
}
```

### Skills and Improvements

- **Algorithm Optimization:** Demonstrated how AVL tree balancing techniques can significantly improve data access times, showcasing advanced problem-solving skills in optimizing algorithms.
- **Programming Proficiency:** Mastered complex C++ programming constructs, including pointers and dynamic memory management, to effectively handle large data structures.
- **Reflection:** The project sharpened my skills in data structure implementation, focusing on the balance between complexity and efficiency. The enhancement process was a valuable lesson in precision and efficiency, emphasizing the importance of maintaining performance as applications scale.

## Final Reflection

These projects reflect a journey of continuous growth and adaptation. By addressing diverse programming challenges, I have honed a comprehensive skill set that extends from detailed coding practices to high-level system design and user experience considerations. This ePortfolio not only highlights my technical proficiency but also my ability to integrate feedback, anticipate user needs, and maintain a forward-thinking approach in software development.

This collection of work demonstrates my commitment to excellence, innovation, and the

 effective application of computing principles in real-world scenarios, marking significant milestones in my development as a software engineer.
