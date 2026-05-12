# Flatering-in-Java
Java program demonstrating data filtering using Streams API, including examples of filtering lists based on conditions such as numbers, strings, and custom objects.

# 🔍 Java Filtering Example (Streams API)

This project demonstrates how to perform **filtering operations in Java** using the **Streams API**. It includes simple and practical examples for beginners to understand functional programming in Java.

---

## 🚀 Features

- Filter numbers based on conditions
- Filter strings using predicates
- Filter custom objects
- Uses Java Streams API
- Clean and beginner-friendly code

---

## 🛠 Tech Stack

- Java 8+
- Streams API
- Collections Framework

---
## 📂 Project Structure
src/
└── main/java/
└── FilteringExample.java


---

## 💡 Example Code

### 🔢 Filtering Numbers
java
List<Integer> numbers = Arrays.asList(10, 15, 20, 25, 30);

List<Integer> result = numbers.stream()
        .filter(n -> n > 20)
        .collect(Collectors.toList());

System.out.println(result);

### 🔢 Filtering String

List<String> names = Arrays.asList("Ravi", "John", "Ankit", "Raj");

List<String> result = names.stream()
        .filter(name -> name.startsWith("R"))
        .collect(Collectors.toList());

System.out.println(result);

## 📂 Project Structure
