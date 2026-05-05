# 🚀 Algorithm Visualizer – Interactive Sorting & Searching Visualizer

A **high-performance, browser-based Algorithm Visualizer** designed to demonstrate core Data Structures & Algorithms concepts through real-time, step-by-step animations. Built with a focus on **clean architecture, efficient rendering, and extensibility**, this project bridges the gap between theoretical DSA and intuitive visual understanding.

---

## 🌐 Live Demo

🔗 https://annnsshhhu.github.io/Algorithm-Visualizer/

---

## 📌 Overview

This project visualizes **6 Sorting Algorithms** and **2 Searching Algorithms** with an emphasis on:

* Real-time animation
* Performance metrics
* Clean separation of concerns (logic vs rendering)

It is designed not just as a learning tool, but as a **production-quality frontend system demonstrating algorithmic thinking + UI engineering**.

---

## ⚙️ Tech Stack

* **JavaScript (ES6+)**
* **HTML5**
* **CSS3**
* **Data Structures & Algorithms (DSA)**
* **DOM Manipulation**
* **Event-Driven Architecture**

---

## 🧠 Algorithms Implemented

### 🔽 Sorting Algorithms

* Bubble Sort
* Selection Sort
* Insertion Sort
* Merge Sort
* Quick Sort
* Heap Sort

### 🔍 Searching Algorithms

* Linear Search
* Binary Search

---

## ✨ Key Features

### 🎬 Real-Time Visualization

* Step-by-step animation of algorithm execution
* Clear distinction between comparisons, swaps, and final placement

### 🧩 Custom Animation Engine

* Built a dedicated `animations[]` pipeline
* Decouples algorithm logic from UI rendering
* Ensures scalability and maintainability

### ⚡ Optimized DOM Updates

* Achieved **O(1) updates** by mutating existing DOM nodes
* Avoids re-rendering → smooth high-frequency animations

### 📊 Live Metrics Dashboard

* Tracks:

  * Comparisons
  * Swaps
  * Execution Time
* Integrated **Big-O Complexity Panel** for theoretical reference

### 🔍 Searching Visualization

* **Linear Search:** Sequential highlighting
* **Binary Search:** Dynamic range narrowing visualization
* Clear success/failure feedback

### 🧱 Modular Architecture

* Central **Algorithm Registry**

  * Encapsulates:

    * Logic
    * Complexity metadata
    * Pseudocode
* Easily extendable for new algorithms

### 🎛 Interactive Controls

* Adjustable:

  * Array size
  * Animation speed
* Supports visualization of:

  * Best case
  * Average case
  * Worst case

---

## 🏗 Architecture Highlights

```text
Algorithm Logic → Animations[] → Rendering Engine → DOM Updates
```

* Algorithms generate **animation instructions**
* Renderer consumes instructions asynchronously
* UI remains responsive and consistent

---

## 🎯 How to Run Locally

```bash
1. Clone the repository
2. Open index.html in browser
```

OR use Live Server in VS Code.

---

## 🚀 Future Enhancements

* Pathfinding algorithms (BFS, Dijkstra, A*)
* Graph visualization module
* Sound-based feedback system
* React-based refactor for scalability
* Code execution panel alongside visualization

---

## 📈 Why This Project Matters

This project demonstrates:

* Strong **DSA fundamentals**
* Ability to **translate algorithms into interactive systems**
* Understanding of **performance optimization in frontend**
* Clean **software architecture design**

---

## 👨‍💻 Author

**Anshu Kumar**

---
