# Ethan Fancher's ePortfolio 

## Overview

Welcome to my ePortfolio, where I present a comprehensive overview of my software development journey during my academic career. This portfolio encapsulates my technical growth, focusing on three distinct projects that highlight my capabilities in object-oriented programming, user interface design, data structures, and algorithm optimization. Each project is carefully chosen to demonstrate both the breadth and depth of my programming skills and problem-solving abilities.


# Professional Self-Assessment

## Introduction

As I conclude my Computer Science program and prepare my ePortfolio for submission, I reflect on the transformative experiences and skills I've developed. This program has equipped me with deep technical knowledge and refined my problem-solving abilities, enhancing my competence and employability in the competitive field of computer science. This professional self-assessment serves to introduce the various facets of my learning and achievements, emphasizing how they collectively enhance my readiness and distinction in the tech industry.

## Showcasing Strengths and Professional Development

Throughout the Computer Science program, I have engaged in a rigorous exploration of both foundational and advanced topics that have significantly shaped my professional ethos and technical acumen. My coursework and the development of my GitHub and ePortfolio have been pivotal in showcasing my strengths in key areas such as algorithm design, software engineering, and simulated project management.

This experience not only honed my technical skills but also set a strong foundation for my career goals.

## Key Competencies in Computer Science

### Collaborating in a Simulated Team Environment

While most of my team collaboration was simulated through academic exercises, these experiences were invaluable in teaching me effective communication and project coordination skills. They allowed me to practice merging diverse ideas into cohesive solutions and managing virtual teams, which is increasingly relevant in today's remote working environments.

### Communicating with Simulated Stakeholders

I developed my ability to communicate complex technical details to non-technical audiences through simulated stakeholder presentations and reports. This practice has been crucial in preparing me to engage real stakeholders effectively, ensuring that I can articulate the implications of technical work clearly and persuasively.

### Data Structures and Algorithms

My academic projects frequently involved the application of complex data structures and algorithms to optimize software functionality. Projects like the Binary Search Tree in C++ demonstrated my coding skills and deep understanding of data management, crucial for handling large-scale data efficiently.

### Software Engineering and Database Management

The Java Swing application project to manage detox destination data highlights my ability to develop and maintain sophisticated software architectures. This project underscored my capabilities in designing systems that ensure data integrity and optimal performance, demonstrating my proficiency in database management.

### Security

Security has been a recurring theme in my studies and projects. I applied secure coding practices throughout the development of my projects, particularly focusing on protecting user data. This preparation aligns with the cybersecurity needs of future employers, showcasing my readiness to contribute to their resilience.

## Artifacts Summary and Portfolio Integration

The artifacts selected for my ePortfolio—from the Java Swing GUI application to the sophisticated Binary Search Tree implementation in C++—represent a broad spectrum of computer science disciplines. Each artifact showcases specific technical skills and contributes to a narrative about my ability to tackle complex challenges and innovate within the technology landscape. These projects collectively illustrate my readiness to engage with advanced software solutions, emphasizing my preparedness to make impactful contributions in a dynamic professional setting.

## Conclusion

This ePortfolio is more than a collection of projects; it is a testament to a journey of continuous learning and professional growth. As I step forward, ready to contribute to and thrive in the ever-evolving field of computer science, I am confident that the skills and experiences documented here will serve as a robust foundation for a successful career. My journey through the Computer Science program has not only prepared me technically but has also instilled in me a passion for innovation and excellence in all my future endeavors.


# Enhancments:

## Enhancement 1: Object-Oriented Hierarchy for Vehicle Management

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

## Enhancement 2: Java Swing Application for Detox Destinations

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

## Enhancement 3: Binary Search Tree for Bid Data Management

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
