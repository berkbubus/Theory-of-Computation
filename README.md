# Algorithmic Problems and Solutions

This repository contains solutions, explanations, and analysis of selected algorithmic problems from the textbook *Algorithm Design* by Kleinberg and Tardos. Each problem is handled with detailed visual or code-based explanations, authored by Berk Bubuş and Ahmet Uman.

---

## 📄 Included Problems

### 1. [4-Dimensional Matching (Chapter 8 - Exercise 7)](./Question_4DM.pdf)

This problem explores the **NP-completeness of the 4-Dimensional Matching (4-DM)** problem. The core tasks include:

- Understanding the classical 3-Dimensional Matching (3-DM) problem.
- Explaining the reduction from 3-DM to 4-DM.
- Demonstrating how to prove 4-DM is NP-complete.
- Visualizing gadgets (variable, clause, garbage) for reductions from 3-SAT to 3-DM.

Key topics covered:
- Hypergraphs and hyperedges
- Polynomial-time verification
- Gadgets in reductions

---

### 2. [Auction Update Analysis (Chapter 13 - Question 10)](./Question_Auction.pdf)

This exercise investigates how many times the **maximum bid is updated** in an online auction scenario where bids arrive in random order.

Highlights:
- Analysis of expected number of updates using harmonic numbers
- Connection to the **Euler–Mascheroni constant**
- Python code for exact harmonic calculation and empirical simulation
- Comparison between theoretical and real-life results

Key formula:
> Expected updates ≈ Hₙ ≈ ln(n) + γ

---

### 3. [Knapsack Approximation (Chapter 11 - Question 11)](./Question_Knapsack.pdf)

This section deals with solving the **Knapsack Problem** using approximation techniques.

Included content:
- Recap of greedy solution
- Precision-scaling with ε and max weight
- Explanation of rounding techniques (without losing critical weight/value information)
- Step-by-step example of applying the scaling approach

Concepts:
- Pseudo-polynomial time approximation
- Trade-off between runtime and accuracy via ε

---

## 📁 File Structure

```
├── Question_4DM.pdf
├── Question_Auction.pdf
├── Question_Knapsack.pdf
└── README.md
```
---

## 🧠 Authors

- **Berk Bubuş**
- **Ahmet Uman**

---

## 📚 Source

All problems are based on *Algorithm Design* by Jon Kleinberg and Éva Tardos.
