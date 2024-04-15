# 1️⃣ **Introduction to DSA (20 mins)**

## 🎯 **Objective**:

Unveil the significance of Data Structures and Algorithms in modern computing.

## 💻 **Tools Needed**:

- Code editor (e.g., VS Code)
- Web browser with JavaScript console access (e.g., Chrome Developer Tools)

## 📘 **Content Overview**:

This segment will introduce participants to the fundamental concepts of Data Structures and Algorithms (DSA), emphasizing their essential role in efficient problem-solving and application development using JavaScript.

---

## 📋 **Detailed Breakdown**:

### 🌐 **Introduction to the Concept of DSA (5 mins)**

- **Discussion**: What are Data Structures? What are Algorithms?
- **Explanation**: Briefly define and distinguish between data structures (ways to organize data) and algorithms (steps to solve problems).
- **Realization**: Why every programmer needs to understand these concepts.

### 🛠️ **Demonstration: Real-life Application of DSA (15 mins)**

- **Activity 1**: Demonstrate a simple problem - finding the maximum number in an array.

  - **Code Example**:

    ```javascript
    let numbers = [15, 46, 74, 22, 98, 5];
    let max = numbers[0];

    for (let i = 1; i < numbers.length; i++) {
      if (numbers[i] > max) {
        max = numbers[i];
      }
    }
    console.log("The maximum number is:", max);
    ```

  - **Explanation**: Discuss how an algorithm iterates through the array to find the maximum number.

- **Activity 2**: Introduce a basic data structure - Queue.

  - **Code Example**:

    ```javascript
    class Queue {
      constructor() {
        this.items = [];
      }
      enqueue(element) {
        this.items.push(element);
      }
      dequeue() {
        if (this.items.length > 0) {
          return this.items.shift();
        }
      }
      peek() {
        return this.items[0];
      }
      isEmpty() {
        return this.items.length === 0;
      }
    }

    let queue = new Queue();
    queue.enqueue("John");
    queue.enqueue("Jane");
    queue.enqueue("Doe");
    console.log("First in line:", queue.peek());
    ```

  - **Explanation**: Show how a queue works with enqueue and dequeue operations, illustrating the FIFO (First In, First Out) principle.

- **Real-world Connection**: Discuss how these structures and algorithms are used in everyday applications, such as managing tasks in a computer's operating system or handling users in a web service queue.
