# COMP 251 — Assignment 2: Search, Divide & Conquer, Dynamic Programming, and Greedy

This assignment contains four problems, each focusing on a different algorithmic paradigm:

- **Q1:** Complete search to solve a board game puzzle.
- **Q2:** Divide and conquer to count swaps for sorting.
- **Q3:** Dynamic programming for constrained stair climbing.
- **Q4:** Greedy algorithm for scheduling assignments.

---

## Q1 — Complete Search: Ball Jump Puzzle

**Description:**  
Given a fixed 5×9 board with balls (`o`), empty holes (`.`), and walls (`#`), a ball can jump over an adjacent ball into an empty hole, removing the jumped ball. The goal is to find:
1. The minimum number of balls remaining.
2. The minimum moves to reach that state.

The algorithm explores all valid sequences of moves recursively to guarantee the optimal solution.

**Example:**  
Initial:
