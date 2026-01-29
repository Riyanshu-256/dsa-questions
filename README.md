# dsa-questions

🏆 **Syllabus-Specific DSA Practice Repository**  
📂 **20+ Topic-Wise Modules** · ✅ **880+ Curated Questions**

A structured, production-ready Data Structures & Algorithms repository designed for **systematic practice**, **interview preparation**, and **academic mastery**.

![GitHub Repo stars](https://img.shields.io/github/stars/Riyanshu-256/dsa-questions?style=social)
![GitHub issues](https://img.shields.io/github/issues/Riyanshu-256/dsa-questions)
![GitHub last commit](https://img.shields.io/github/last-commit/Riyanshu-256/dsa-questions)

---

## 🚀 Overview

This repository contains a carefully curated collection of DSA problems organized **topic-wise** to align with:

- **University syllabi**
- **FAANG-style interviews**
- **General competitive programming patterns**

Each module is designed to help you:

- Build **conceptual clarity**
- Practice **pattern-based problem solving**
- Revisit and **revise weak topics** efficiently

**Who is this for?**

- 🎓 **Students** preparing for university exams or placements  
- 💼 **Interview candidates** targeting product-based and service-based companies  
- 🧑‍💻 **Developers** revising DSA for career growth or switching roles  

---

## 📑 Table of Contents

1. [Topics Covered](#-topics-covered)  
2. [Repository Structure](#%EF%B8%8F-repository-structure)  
3. [Getting Started](#-getting-started)  
4. [How to Use Effectively](#%EF%B8%8F-how-to-use-effectively)  
5. [Recommended Practice Plan](#-recommended-practice-plan)  
6. [Contribution Guidelines](#-contribution-guidelines)  
7. [Content & Formatting Standards](#-content--formatting-standards)  
8. [Roadmap](#-roadmap)  
9. [Maintainer](#-maintainer)  
10. [Support](#-support)

---

## 🧩 Topics Covered

Core DSA topics covered across the modules include:

- **Language & Basics**  
  - Java basics / implementation patterns
- **Foundations & Recursion**  
  - Recursion patterns (backtracking foundations, divide & conquer thinking)
- **Arrays & Searching/Sorting**  
  - Arrays  
  - Searching (binary search variants, edge cases)  
  - Sorting (comparison-based + special cases)  
- **Matrix & Hashing**  
  - 2D arrays / matrix problems  
  - Hashing and frequency maps / sets  
- **Strings**  
  - Pattern matching, manipulation, edge cases  
- **Linked List**  
  - Singly, doubly, circular lists, fast–slow pointer patterns  
- **Stack & Queue / Deque**  
- **Trees & Binary Search Trees**  
- **Heap / Priority Queue**  
- **Graphs** (BFS, DFS, shortest paths, connectivity, etc.)  
- **Greedy Algorithms**  
- **Backtracking**  
- **Dynamic Programming**  
- **Trie**  
- **Segment Tree**  
- **Disjoint Set (Union-Find)**  
- **Final Mixed / Revision Sets**

> Each topic includes progressively challenging questions with a focus on patterns and optimal time/space complexity.

---

## 🗂️ Repository Structure

High-level layout:

```text
DSA-QUESTIONS/
└── dsa-questions/
    ├── P00_allQuestions.md        # Master index of questions
    ├── P01_javaBasics.md          # Language-specific preliminaries
    ├── P04_recursion.md           # Recursion patterns
    ├── P05_arrays.md
    ├── P06_searching.md
    ├── P07_sorting.md
    ├── P08_matrix.md
    ├── P09_hashing.md
    ├── P10_strings.md
    ├── P11_linkedList.md
    ├── P12_stacks.md
    ├── P13_queue.md
    ├── P14_dequeue.md
    ├── P15_tree.md
    ├── P16_binarySearchTree.md
    ├── P17_heap.md
    ├── P18_graphs.md
    ├── P19_greedy.md
    ├── P20_backtracking.md
    ├── P21_dp.md
    ├── P22_trie.md
    ├── P23_segmentTree.md
    ├── P24_disjointSets.md
    └── P25_finalQuestions.md      # Mixed / revision set
```

You can open any `PXX_*.md` file directly in your editor or browser and start solving.

---

## 🧰 Getting Started

There is **no build setup required** – this is a pure markdown-based question bank.

1. **Clone the repository**

   ```bash
   git clone https://github.com/Riyanshu-256/dsa-questions.git
   cd dsa-questions
   ```

2. **Open in your preferred editor**

   - VS Code / IntelliJ / any markdown-friendly editor  
   - Or browse files directly on GitHub

3. **Choose a module**

   - Start with `P00_allQuestions.md` to see the complete index  
   - Or jump to a specific topic like `P05_arrays.md` or `P21_dp.md`

---

## 🧭 How to Use Effectively

- **Pick one topic at a time**  
  Avoid jumping randomly; finish a topic fully for deeper understanding.

- **Track your progress**  
  - Mark questions as: _Unsolved / Attempted / Solved / Revisit_  
  - Optionally maintain a separate progress tracker (spreadsheet / Notion / markdown).

- **Implement, don’t just read**  
  - For each question, write the solution in your language of choice.  
  - Focus on optimal complexity and edge cases.

- **Revisit weak areas**  
  - Use the topic-wise breakdown to quickly come back to areas you struggle with.

---

## 📆 Recommended Practice Plan

- **Beginner (2–3 weeks)**  
  - Java basics, arrays, searching, sorting, strings, recursion basics.

- **Intermediate (3–5 weeks)**  
  - Linked lists, stacks/queues/deques, trees, binary search trees, hashing, matrices.

- **Advanced (4–6+ weeks)**  
  - Graphs, greedy, backtracking, dynamic programming, trie, segment tree, disjoint sets, final mixed sets.

Use this just as a guideline – adjust based on your schedule and familiarity.

---

## 🤝 Contribution Guidelines

Contributions are welcome! To keep this repository **clean and consistent**, please follow these steps:

1. **Fork** the repository.  
2. **Create a feature branch**:

   ```bash
   git checkout -b feature/topic-name-improvement
   ```

3. **Make your changes**  
   - Add new questions in the correct topic file.  
   - Maintain the existing numbering and formatting style.  
   - If needed, update `P00_allQuestions.md` to keep the index in sync.

4. **Commit with clear messages**:

   ```bash
   git commit -m "Add X new questions to Y topic" 
   ```

5. **Open a Pull Request**  
   - Provide a short description of what you changed and why.  
   - Mention if it’s a new topic, new questions, or corrections.

> Please keep content high-quality, unambiguous, and aligned with standard DSA expectations.

---

## 📐 Content & Formatting Standards

To maintain a **production-quality** question bank:

- **Question clarity**
  - Clearly describe input, output, and constraints.
  - Mention edge cases where relevant.

- **Consistent formatting**
  - Use ordered/unordered lists where appropriate.  
  - Use code fences for sample inputs/outputs or pseudo-code.

- **Naming & organization**
  - Follow the existing `PXX_topicName.md` convention.  
  - Keep related questions grouped logically within a file.

---

## 🗺️ Roadmap

Planned and potential enhancements:

- Add **difficulty tags** (Easy / Medium / Hard) per question.  
- Add **links to reference solutions** in a separate solutions repository or branch.  
- Add **company tags** (e.g., "Asked in Google / Amazon / Microsoft") where applicable.  
- Provide **checklist-style progress trackers** per topic.  
- Add **language-specific solution guidelines** (Java / C++ / Python templates).

If you’d like to work on any of these, feel free to open an issue or PR.

---

## 👤 Maintainer

**Riyanshu Sharma**  
GitHub: [@Riyanshu-256](https://github.com/Riyanshu-256)

---

## ⭐ Support

If this repository helps you, please consider:

- Giving it a **⭐ on GitHub**  
- Sharing it with friends or juniors preparing for DSA

Happy Coding and Problem Solving! 🚀

