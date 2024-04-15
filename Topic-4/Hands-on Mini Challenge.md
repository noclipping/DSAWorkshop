# 4️⃣ **Hands-on Mini Challenge (10 mins)**

## 🎯 **Objective**:

Provide participants with a practical experience to apply a simple algorithm, reinforcing their learning and understanding of algorithmic thinking.

## 💻 **Tools Needed**:

- Code editor (e.g., VS Code)
- Web browser with JavaScript console access (e.g., Chrome Developer Tools)

## 📘 **Content Overview**:

This mini challenge will encourage participants to implement a straightforward algorithm using JavaScript. The challenge will focus on solving a common problem that can be addressed efficiently with basic algorithms, promoting hands-on learning.

---

## 📋 **Detailed Breakdown**:

### 🚀 **Challenge Setup (2 mins)**

- **Introduction**: Briefly explain the challenge and the problem to be solved.
- **Problem Statement**: "Given an array of integers, write a function to calculate and return the sum of all elements."

### ✍️ **Coding Challenge (6 mins)**

- **Task**: Participants will write a function in JavaScript to solve the problem.
- **Starter Code**:

  ```javascript
  function sumArray(arr) {
    // Participants will fill in this function
  }

  let numbers = [10, 20, 30, 40, 50]; // Example array
  console.log("Sum of array:", sumArray(numbers));
  ```

- **Guidance**: Encourage participants to think about the problem and discuss their approach before coding. Offer hints if necessary, such as reminding them of the `reduce` method or the classic for-loop iteration technique.
- **Possible Solutions**:
  - Using a for-loop:
    ```javascript
    function sumArray(arr) {
      let sum = 0;
      for (let i = 0; i < arr.length; i++) {
        sum += arr[i];
      }
      return sum;
    }
    ```
  - Using the `reduce` method:
    ```javascript
    function sumArray(arr) {
      return arr.reduce((acc, val) => acc + val, 0);
    }
    ```

### 🗣️ **Discussion and Review (2 mins)**

- **Review Solutions**: Have a few participants share their solutions and reasoning.
- **Discussion**: Talk about how different approaches can solve the same problem and the benefits of each method (e.g., clarity vs. performance).

### 🎉 **Conclusion (1 min)**

- **Encouragement**: Praise the participants for their efforts and creativity.
- **Takeaway**: Highlight the importance of practicing coding problems to become proficient in applying algorithms.

---
