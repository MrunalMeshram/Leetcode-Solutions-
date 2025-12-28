# Second Largest Element

## 🧩 Problem Statement
Given an integer array, find the second largest element in the array.  
You may assume the array contains at least two elements.

### Notes
- Modify the function or parameters if needed
- Function signature may vary

---

## 💡 Approach
- Use a **min-heap of size 2**
- Keep only the two largest elements in the heap
- The root of the heap will be the second largest element

---

## ⏱️ Complexity
- **Time:** O(n log k) → k = 2
- **Space:** O(k)

---

## 🧪 Example
