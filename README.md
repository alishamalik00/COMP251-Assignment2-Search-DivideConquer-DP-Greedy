After optimal moves, only 1 ball remains in 3 moves.

---

## Q2 — Divide and Conquer: Counting Swaps

**Description:**  
Given a queue of student IDs, count how many adjacent swaps are needed to sort them in ascending order. This is equivalent to counting **inversions** in the array.  
A modified merge sort is used to achieve `O(n log n)` efficiency.

**Example:**  
Input: `[3, 1, 2]`  
Process: swap (3,1) → swap (3,2) → sorted.  
Output: `2` swaps.

---

## Q3 — Dynamic Programming: Stair Climbing Strategy

**Description:**  
Given a list of step counts, decide whether to go up (`U`) or down (`D`) each time so that:
- You start and end at street level.
- You never go below street level or above 1000 stairs.
- You minimize the maximum height reached.

If no valid sequence exists, output `"IMPOSSIBLE"`.

**Example:**  
Input: `[20, 20, 20, 20]`  
Output: `"UDUD"` — valid path ending at street level, with max height only 20.

---

## Q4 — Greedy Algorithm: Homework Scheduling

**Description:**  
Given two arrays: `deadlines[]` and `weights[]` for assignments (1 hour each), schedule tasks to maximize the total weight completed before deadlines. Uses a greedy selection strategy:
1. Sort assignments by weight and deadline priority.
2. Assign each to the latest available slot before its deadline.

**Example:**  
Weights: `[23, 60, 14, 25, 7]`  
Deadlines: `[3, 1, 2, 1, 3]`  
Output plan corresponds to weights `[60, 14, 23]` — maximum achievable weight total.

---

**Note:**  
All code is tested on Ed with both public and hidden cases. Efficiency matters for Q2 and Q3; correctness is required for all.
