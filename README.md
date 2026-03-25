# 🤖 AI Search Visualizer — 21CSC206T

> An interactive, browser-based application that visualizes classical AI search algorithms and adversarial game-playing — built as a course project for **Artificial Intelligence (21CSC206T)**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Artificial Intelligence](https://img.shields.io/badge/Artificial%20Intelligence-Course%20Project-00D4AA?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## 🚀 Live Demo

👉 **[View The Live Application](https://adhiishhh.github.io/ai-search-visualizer/)**

---

## 📌 About The Project

**AI Search Visualizer** is an interactive web application that demonstrates how classical AI search algorithms explore a grid environment to find a path from a **Start node** to a **Goal node**. It also features a fully playable **Tic-Tac-Toe game** powered by the **Minimax algorithm with Alpha-Beta Pruning**.

This project was developed as part of the **Artificial Intelligence** curriculum and covers core topics from Units I, II, and III — including uninformed search, informed search, adversarial game-playing, and intelligent agent design.

---

## 🎯 Features

- 🔍 **5 Search Algorithms** — BFS, DFS, UCS, A\*, and Greedy Best-First, all animated step by step
- 🎮 **Minimax AI** — Unbeatable Tic-Tac-Toe agent with Alpha-Beta Pruning
- 🌲 **Decision Tree Viewer** — Shows MAX/MIN nodes and pruned branches in real time
- ⬛ **Maze Generator** — Recursive backtracking maze for complex test environments
- 📊 **Live Statistics** — Nodes visited, path length, path cost, and execution time
- 🖱 **Interactive Grid** — Draw walls, place start/end points by clicking or dragging
- 🌐 **Zero Dependencies** — Single HTML file, no install needed, runs in any browser

---

## 🧠 AI Concepts Covered

This project directly maps to the following AI topics from the syllabus:

| Concept | Description |
|---|---|
| **State Space** | Grid cells = states; adjacency = transitions; walls = blocked states |
| **Problem Formulation** | Start cell = Initial state, End cell = Goal state, walls = obstacles |
| **Search Agents** | Algorithms act as planning agents navigating the state space |
| **Uninformed Search** | BFS and DFS explore without domain knowledge |
| **Informed Search** | A\* and Greedy use Manhattan distance heuristic to guide search |
| **Adversarial Search** | Minimax algorithm for two-player zero-sum game (Tic-Tac-Toe) |
| **Alpha-Beta Pruning** | Cuts off branches that won't affect the final decision |
| **Intelligent Agent** | AI player perceives board, reasons optimally, and acts — a rational agent |

---

## 🔬 Algorithms Implemented

### Uninformed Search (Unit II)

| Algorithm | Data Structure | Optimal? | Complete? | Notes |
|---|---|---|---|---|
| BFS | Queue (FIFO) | ✅ Yes | ✅ Yes | Guarantees shortest path |
| DFS | Stack (LIFO) | ❌ No | ❌ No | Memory efficient |
| UCS | Priority Queue | ✅ Yes | ✅ Yes | Minimum cost expansion |

### Informed Search (Unit II)

| Algorithm | Data Structure | Optimal? | Complete? | Notes |
|---|---|---|---|---|
| A\* | Priority Queue | ✅ Yes | ✅ Yes | f(n) = g(n) + h(n) |
| Greedy Best-First | Priority Queue | ❌ No | ❌ No | Heuristic only, fast but not optimal |

### Adversarial Search (Unit III)

| Algorithm | Type | Notes |
|---|---|---|
| Minimax | Game Tree DFS | MAX maximizes, MIN minimizes |
| Alpha-Beta Pruning | Minimax optimization | Reduces O(b^d) to O(b^(d/2)) |

---

## 🗂 File Structure

```
ai-search-visualizer/
├── index.html       # Complete application — all logic, UI, and styles in one file
└── README.md        # Project documentation
```

---

## 🛠 Getting Started

No installation or build step required. This is a pure frontend project.

```bash
# 1. Clone the repository
git clone https://github.com/adhiishhh/ai-search-visualizer.git

# 2. Navigate into the folder
cd ai-search-visualizer

# 3. Open index.html in your browser
open index.html
# or just double-click index.html
```

---

## 📚 Curriculum Coverage

| Unit | Topic | Covered In App |
|---|---|---|
| **Unit I** | Introduction to AI, State Space, Problem Formulation | Grid = state space, start/goal/walls = problem |
| **Unit II** | BFS, DFS, UCS, A\*, Greedy, Heuristic Search | All 5 algorithms implemented and visualized |
| **Unit III** | Minimax, Alpha-Beta Pruning, Intelligent Agents | Tic-Tac-Toe AI with decision tree visualization |

---

## 👨‍💻 Team

| Name | Register Number |
|---|---|
| **Adhish Kumar M T** | RA2411056010066 |
| **Goureesankar Roy** | RA2411056010068 |

**Course:** 21CSC206T — Artificial Intelligence
**Section:** AP1
**Due Date:** 24.03.2026

---

## 📄 License

This project is licensed under the MIT License.
