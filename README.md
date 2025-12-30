# 🚀 DSA with Java – Kunal Kushwaha (Zero to Advanced)

Progress Tracker for completing **DSA with Java** playlist (69 videos).

---

## 📊 Progress
<!-- Progress Bar -->
<div>
  <progress id="progressBar" value="0" max="69" style="width: 100%; height: 20px;"></progress>
  <p><b><span id="percent">0</span>% Completed</b></p>
</div>

---

## ✅ Playlist Checklist (1–69)

> Tick the checkbox after completing each video 👇

- [ ] 1. Best Data Structures & Algorithms (DSA) Course – Clear Any FAANG Interview
- [ ] 2. Java vs C++ for Data Structures & Algorithms
- [ ] 3. How I Cleared My Google Interviews – Use LeetCode Effectively
- [ ] 4. Complete Git and GitHub Tutorial
- [ ] 5. Introduction to Programming – Types of Languages, Memory Management
- [ ] 6. Flow of Program – Flowcharts & Pseudocode
- [ ] 7. Introduction to Java – Architecture & Installation
- [ ] 8. First Java Program – Input/Output, Debugging & Datatypes
- [ ] 9. Conditionals and Loops + Calculator Program
- [ ] 10. Switch Statements + Nested Case
- [ ] 11. Functions / Methods in Java
- [ ] 12. Arrays & ArrayList in Java
- [ ] 13. Linear Search Algorithm
- [ ] 14. Binary Search Algorithm
- [ ] 15. Binary Search Interview Questions
- [ ] 16. Binary Search in 2D Arrays
- [ ] 17. Bubble Sort
- [ ] 18. Selection Sort
- [ ] 19. Insertion Sort
- [ ] 20. Cycle Sort
- [ ] 21. Strings & StringBuilder
- [ ] 22. Pattern Questions Trick
- [ ] 23. Introduction to Recursion
- [ ] 24. Time & Space Complexity (Big-O)
- [ ] 25. Bitwise Operators & Number Systems
- [ ] 26. Maths for DSA
- [ ] 27. Recursion – Level 1 Questions
- [ ] 28. Recursion – Array Questions
- [ ] 29. Recursion – Pattern Questions
- [ ] 30. Merge Sort (Recursion)
- [ ] 31. Quick Sort (Recursion)
- [ ] 32. Recursion – Subsets & Subsequences
- [ ] 33. Recursion – Permutations
- [ ] 34. Recursion – Google/Amazon Problems
- [ ] 35. Backtracking – Maze Problems
- [ ] 36. N-Queens, Sudoku Solver
- [ ] 37. OOP 1 – Classes & Objects
- [ ] 38. OOP 2 – Packages, Static, Singleton
- [ ] 39. OOP 3 – Inheritance, Polymorphism
- [ ] 40. OOP 4 – Access Control & Object Class
- [ ] 41. OOP 5 – Abstract Classes & Interfaces
- [ ] 42. OOP 6 – Generics, Lambda, Exception Handling
- [ ] 43. OOP 7 – Collections Framework
- [ ] 44. Linked List – Singly, Doubly, Circular
- [ ] 45. Linked List Interview Questions
- [ ] 46. Stack & Queue – Theory & Implementation
- [ ] 47. Stack & Queue Interview Questions
- [ ] 48. Tic Tac Toe Java Game
- [ ] 49. Binary Trees & BST
- [ ] 50. AVL Trees
- [ ] 51. Segment Trees
- [ ] 52. StringBuffer & Large Data Handling
- [ ] 53. BigInteger & BigDecimal
- [ ] 54. File Handling in Java
- [ ] 55. Binary Tree Interview Questions
- [ ] 56. Heap & Priority Queue
- [ ] 57. HashMap & HashTable
- [ ] 58. Karp-Rabin Algorithm
- [ ] 59. Count Sort
- [ ] 60. Radix Sort
- [ ] 61. Huffman Coding
- [ ] 62. Mo’s Algorithm / Square Root Decomposition
- [ ] 63. Construct Binary Tree from Traversals
- [ ] 64. Vertical Order Traversal
- [ ] 65. Word Ladder (Graph – Hard)
- [ ] 66. Two Sum IV (BST)
- [ ] 67. Kth Smallest Element in BST
- [ ] 68. Binary Tree to DLL
- [ ] 69. Correct Binary Tree with Swapped Nodes

---

## ⚙️ Auto Progress Script
> Works in **GitHub Pages / local markdown preview**

```html
<script>
  const checkboxes = document.querySelectorAll("input[type='checkbox']");
  const progressBar = document.getElementById("progressBar");
  const percent = document.getElementById("percent");

  function updateProgress() {
    const checked = document.querySelectorAll("input[type='checkbox']:checked").length;
    progressBar.value = checked;
    percent.innerText = Math.round((checked / 69) * 100);
  }

  checkboxes.forEach(cb => cb.addEventListener("change", updateProgress));
</script>
