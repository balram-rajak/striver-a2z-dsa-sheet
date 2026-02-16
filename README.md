# Striver's A2Z DSA Sheet

[![Sheet](https://img.shields.io/badge/Striver-A2Z_DSA_Sheet-red)](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2)
[![Language](https://img.shields.io/badge/Language-Java-orange)](https://www.java.com/)
[![Progress](https://img.shields.io/badge/Progress-35%2F455-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Complete solutions for **Striver's A2Z DSA Course/Sheet** - A comprehensive roadmap for learning Data Structures and Algorithms.

## 📚 About

This repository contains my solutions to all problems in Striver's A2Z DSA Sheet, a structured learning path covering everything from basics to advanced topics in Data Structures and Algorithms.

**Sheet Link:** [Striver's A2Z DSA Course Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2)

**Secondary Sheets:** 
- [a2z-old-sheet](https://bugaddr.github.io/a2z_old_sheet/)
- [Excel sheet](https://docs.google.com/spreadsheets/d/1W1VUEWc7OeYd_y62yCNhtTqp0-hLWWfRNZCtFsHfKDU/edit?usp=sharing)

## 🗂️ Repository Structure

```
striver-a2z-dsa-sheet/
│
├── advanced-maths/
│   ├── segmented-sieve-gfg-product-range-primes.cpp
│   └── sieve-of-eratosthenes.cpp
│
└── learn-the-basics/
    ├── arrays/
    │   └── easy/
    │       ├── remove-duplicates-sorted-array.cpp
    │       ├── rotate-array-by-k.cpp
    │       └── search-x-in-sorted-array.cpp
    │
    ├── basic-maths/
    │   ├── armstrong-number.cpp
    │   ├── check-prime.cpp
    │   ├── count-digits.java
    │   ├── count-digits1.java
    │   ├── gcd.cpp
    │   ├── lc-7.java
    │   ├── lcm.cpp
    │   ├── palindrome-optimized.java
    │   ├── palindrome-simple.java
    │   ├── print-divisors.cpp
    │   └── reverse-a-number.java
    │
    ├── complexity/
    │   └── power-set-exponential-complexity.cpp
    │
    ├── hashing/
    │   ├── counting-frequencies.py
    │   ├── frequency-of-most-frequent-element.cpp
    │   ├── highest-and-lowest-frequency-elements.java
    │   └── top-k-frequent-in-array.java
    │
    ├── patterns/
    │   ├── index-triangle.js
    │   ├── p-22.cpp
    │   └── pattern-problems.ipynb
    │
    └── recursion/
        ├── factorials-less-or-equal-to-n.java
        ├── factorials-of-n.java
        ├── fibonacci.java
        ├── is-string-palindrome.java
        ├── print-1-to-n.java
        ├── print-name-n-times.java
        ├── reverse-array.java
        ├── sum-of-n-natural-numbers.java
        └── understand-recursion-by-print-something-n-times.java
```

> **Note:** All folder and file names follow kebab-case convention (lowercase with hyphens) for better compatibility across platforms and adherence to open-source best practices.

## 🚀 Progress Tracker

### **Overall Progress: 0/455 Problems Solved**

| Step | Topic | Total | Solved | Status |
|------|-------|-------|--------|--------|
| 1 | Learn the Basics | 31 | 31 | ✅ |
| 2 | Sorting Techniques | 7 | 0 | 🔄 In Progress |
| 3 | Arrays | 40 | 3 | 🔄 In Progress |
| 4 | Binary Search | 35 | 1 | 🔄 In Progress |
| 5 | Strings | 15 | 0 | ⬜ Not Started |
| 6 | Linked Lists | 31 | 0 | ⬜ Not Started |
| 7 | Recursion | 25 | 0 | ⬜ Not Started |
| 8 | Bit Manipulation | 15 | 0 | ⬜ Not Started |
| 8.1 | Learn Bit Manipulation | 8 | 0 | ⬜ Not Started |
| 8.2 | Interview Problems | 5 | 0 | ⬜ Not Started |
| 8.3 | Advanced Maths | 5 | 1 | 🔄 In Progress |
| 9 | Stacks & Queues | 30 | 0 | ⬜ Not Started |
| 10 | Sliding Window | 12 | 0 | ⬜ Not Started |
| 11 | Heaps | 17 | 0 | ⬜ Not Started |
| 12 | Greedy Algorithms | 20 | 0 | ⬜ Not Started |
| 13 | Binary Trees | 39 | 0 | ⬜ Not Started |
| 14 | Binary Search Trees | 16 | 0 | ⬜ Not Started |
| 15 | Graphs | 54 | 0 | ⬜ Not Started |
| 16 | Dynamic Programming | 56 | 0 | ⬜ Not Started |
| 17 | Tries | 7 | 0 | ⬜ Not Started |
| 18 | Strings (Advanced) | 5 | 0 | ⬜ Not Started |

**Legend:**
- ✅ Completed
- 🔄 In Progress
- ⬜ Not Started

## 📝 Problem Format

Each solution file includes:

```java
/**
 * Problem: [Problem Name]
 * Link: [LeetCode/GFG Link/ Any other]
 * Topics: [Array, Hash Table, etc.]
 * 
 * Approach:
 * [Explanation of the approach]
 * 
 * Time Complexity: O(?)
 * Space Complexity: O(?)
 */
```

## 🔧 Setup and Usage

### **Prerequisites**
- Java Development Kit (JDK) 11 or higher
- VS Code with Java Extension Pack (or any Java IDE)
- Git

### **Clone Repository**
```bash
git clone https://github.com/balram-rajak/striver-a2z-dsa-sheet.git
cd striver-a2z-dsa-sheet
```
### create `inputf.in` and `outputf.in` files in root directory of repository
```bash
type nul > inputf.in
type nul > outputf.in
```

### ⚡ Quick run with VS Code TaskRunner

**Press `Ctrl+Shift+B`** — automatically compiles, times execution, and handles I/O redirection (`inputf.in` → `outputf.in`).

**Supports:** C++, Java, Python, JavaScript

**Workflow:**
1. Write input → `inputf.in`
2. Hit `Ctrl+Shift+B`
3. Check output → `outputf.in`

**Rebuild TaskRunner** (if modified):
```bash
cd lib
g++ -std=c++17 TaskRunner.cpp -o TaskRunner.exe
```

Extend language support in [lib/TaskRunner.cpp](lib/TaskRunner.cpp).

## 🔗 Resources

### **Primary Resources**
- [Striver's A2Z DSA Course Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2)
- [Take U Forward YouTube Channel](https://www.youtube.com/@takeUforward)
- [Striver's SDE Sheet](https://takeuforward.org/interviews/strivers-sde-sheet-top-coding-interview-problems/)

### **Practice Platforms**
- [LeetCode](https://leetcode.com/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)
- [Coding Ninjas](https://www.codingninjas.com/)

### **Additional Resources**
- [CP Algorithms](https://cp-algorithms.com/)
- [Visualgo](https://visualgo.net/) - Algorithm Visualizations

## 💻 Tech Stack

- **Primary Language:** C++
- **Alternative Languages:** Java, Javascript, Python (for some problems)
- **IDE:** VS Code
- **Version Control:** Git & GitHub

## 📊 Topic-wise Breakdown

### **Data Structures**
- Arrays, Strings
- Linked Lists (Single, Double, Circular)
- Stacks, Queues, Deques
- Trees (Binary, BST, AVL, Segment)
- Heaps (Min/Max)
- Graphs (Adjacency List/Matrix)
- Tries
- Disjoint Set Union (DSU)

### **Algorithms**
- Sorting & Searching
- Two Pointers & Sliding Window
- Recursion & Backtracking
- Greedy Algorithms
- Dynamic Programming
- Graph Algorithms (BFS, DFS, Dijkstra, Floyd-Warshall, etc.)
- Bit Manipulation
- Mathematical Algorithms

## 🎯 Goals

- ✅ Complete all 455 problems
- ✅ Understand multiple approaches for each problem
- ✅ Optimize solutions for time and space complexity
- ✅ Build strong problem-solving foundations
- ✅ Prepare for coding interviews

## 📈 Learning Strategy

1. **Understand the Problem** - Read carefully and identify patterns
2. **Think of Approaches** - Brute force first, then optimize
3. **Code the Solution** - Write clean, readable code
4. **Test Thoroughly** - Check edge cases
5. **Analyze Complexity** - Time and space complexity
6. **Review & Revise** - Come back to difficult problems

## 🤝 Contributing

This is a personal learning repository. However, if you find any issues or have suggestions:

1. Open an issue
2. Suggest improvements
3. Share alternative approaches

## 📝 Notes

- Solutions are written with focus on clarity and learning
- Multiple approaches included where applicable
- Each problem has detailed comments explaining the logic
- Complexity analysis provided for all solutions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Balram Rajak** ([@balram-rajak](https://github.com/balram-rajak))

---

⭐ **Star this repo** if you find it helpful!

💬 **Let's connect** and discuss DSA and problem-solving strategies!

📧 Open to collaboration and learning together!

---

### 📌 Quick Links

- [View Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2)
- [My LeetCode Profile](https://leetcode.com/u/Eternal_Servant/)
- [My GeeksforGeeks Profile](https://www.geeksforgeeks.org/profile/balramrajat1999)

**Happy Coding! 🚀**
