# CPP_Experiment_21_Sorting-Algorithm

# 📘 Experiment: Sorting Algorithms in C++

---

## 🎯 AIM
To implement and understand **Selection Sort, Insertion Sort, and Quick Sort** in C++ and analyze their working, complexity, and differences.

---

## 📌 OBJECTIVES
- Learn different sorting algorithms.  
- Understand algorithm design techniques (**comparison-based sorting**).  
- Compare performance and use cases of each sorting algorithm.  
- Implement sorting algorithms in C++ using arrays and vectors.  

---

## 📖 THEORY

### 🔹 Selection Sort
- **Concept:** Finds the minimum element from the unsorted part of the array and swaps it with the first unsorted element.  
- **Complexity:**  
  - Worst-case: O(n²)  
  - Best-case: O(n²)  
- **Use Case:** Small arrays or when memory writes are costly (fewer swaps).  

### 🔹 Insertion Sort
- **Concept:** Builds a sorted portion of the array one element at a time by inserting each new element at its correct position.  
- **Complexity:**  
  - Worst-case: O(n²)  
  - Best-case (already sorted): O(n)  
- **Use Case:** Small or nearly sorted arrays.  

### 🔹 Quick Sort
- **Concept:** Divide-and-conquer algorithm.  
  1. Pick a pivot.  
  2. Partition array: elements < pivot go left, elements > pivot go right.  
  3. Recursively sort left and right subarrays.  
- **Complexity:**  
  - Average: O(n log n)  
  - Worst-case: O(n²)  
- **Use Case:** Large arrays, general-purpose sorting.  

---

## 🧩 COMPARISON TABLE

| Feature                  | Selection Sort       | Insertion Sort       | Quick Sort          |
|---------------------------|-------------------|-------------------|-------------------|
| Method                    | Selection-based    | Insertion-based    | Divide & Conquer  |
| Complexity (Worst)        | O(n²)             | O(n²)             | O(n²)             |
| Complexity (Average)      | O(n²)             | O(n²)             | O(n log n)        |
| Space                     | In-place          | In-place          | In-place          |
| Stability                 | No                | Yes               | No (standard)     |
| Best Use Case             | Small arrays      | Nearly sorted     | Large arrays      |

---

## ⚙️ ALGORITHM

### Selection Sort
1. Loop through array from start to end.  
2. Find the minimum element in the unsorted part.  
3. Swap it with the first unsorted element.  
4. Repeat until the array is sorted.  

### Insertion Sort
1. Start from the second element.  
2. Compare with the sorted portion and insert at the correct position.  
3. Repeat for all elements until the array is sorted.  

### Quick Sort
1. Choose a pivot (usually last element).  
2. Partition array: elements < pivot go left, > pivot go right.  
3. Recursively apply Quick Sort to left and right subarrays.  

---

## 📝 PROGRAM DESCRIPTION
- **Selection Sort:** Implemented using pointers and loops; swaps minimum elements sequentially.  
- **Insertion Sort:** Iterates through elements, inserting them into the sorted portion.  
- **Quick Sort:** Uses recursion, partitioning, and swapping to efficiently sort arrays.  

---

## 🧠 CONCEPTS USED
- Arrays and Vectors in C++.  
- Pointers (for Selection Sort).  
- Recursion (for Quick Sort).  
- Loops and Conditional Statements.  
- Object-Oriented Programming concepts (from previous programs).  

---

## ✅ CONCLUSION
- Sorting algorithms are fundamental for programming and data manipulation.  
- **Selection Sort:** Simple but inefficient for large arrays.  
- **Insertion Sort:** Efficient for nearly sorted data.  
- **Quick Sort:** Fast for large datasets due to divide-and-conquer.  
- Understanding these algorithms improves problem-solving and algorithmic thinking.
