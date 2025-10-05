# Exp-21-Sorting-Algorithms-In-Cpp

# Experiment 21 – Sorting in C++

**Student:** Rachit Deshpande  
**PRN:** 24070123035  
**Batch:** A2  

---

## Aim  
To implement **Sorting techniques** in C++.  
- **Experiment 21 A**: Selection Sort  
- **Experiment 21 B**: Bubble Sort  
- **Experiment 21 C**: Quick Sort  

---

## Theory  

- **Selection Sort (21 A):**  
  - Repeatedly selects the smallest element and places it at correct position.  
  - Time Complexity: O(n²).  

- **Bubble Sort (21 B):**  
  - Repeatedly swaps adjacent elements if they are in the wrong order.  
  - Time Complexity: O(n²).  

- **Quick Sort (21 C):**  
  - Divide-and-conquer approach using a pivot element.  
  - Efficient for large datasets.  
  - Time Complexity: O(n log n) on average.  

---

## Algorithm  

### 21 A – Selection Sort  
1. Start the program.  
2. Input size and array.  
3. For each index `i`, find smallest element in rest of array.  
4. Swap smallest element with element at index `i`.  
5. Repeat until sorted.  
6. End program.  

### 21 B – Bubble Sort  
1. Start the program.  
2. Input size and array.  
3. For each pass, compare adjacent elements.  
4. Swap if left element > right element.  
5. Repeat passes until no swaps occur.  
6. End program.  

### 21 C – Quick Sort  
1. Start the program.  
2. Input size and array.  
3. Select last element as pivot.  
4. Partition array into elements < pivot and > pivot.  
5. Recursively apply quick sort on partitions.  
6. Combine results to form sorted array.  
7. End program.  

---

## Conclusion  

- Implemented **Selection, Bubble, and Quick Sort**.  
- Observed efficiency differences:  
  - Selection & Bubble → Simple, but slow (O(n²)).  
  - Quick Sort → Much faster on large inputs.  
- Sorting is essential for search optimization and data organization.  
