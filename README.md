# Grid Ways using Recursion (Java)

This program calculates the total number of ways to reach the bottom-right corner
of an `n x m` grid from the top-left corner.

## 📌 Rules
- You can move only **right** or **down**
- Uses **recursion**

## 🧠 Approach
- Base case: when destination is reached
- Boundary case: when index goes out of grid
- Recursive calls:
  - Move right
  - Move down

## ⏱️ Time Complexity
O(2^(n+m))

## 📊 Formula (Optimized)
(n-1 + m-1)! / ((n-1)! (m-1)!)

## ✅ Sample Output
6
