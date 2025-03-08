

---

## **Graph Algorithms**
| Algorithm | Best Case | Worst Case | Data Structure Used | Advantages | Disadvantages |
|-----------|------------|-------------|----------------------|------------|--------------|
| **BFS (Breadth-First Search)** | O(1) | O(V + E) | Queue | Finds shortest path in unweighted graphs | Uses extra memory (queue) |
| **DFS (Depth-First Search)** | O(1) | O(V + E) | Stack (Recursive or Explicit) | Efficient for deep exploration | Can get stuck in deep paths (stack overflow in recursion) |
| **Dijkstra’s Algorithm** | O(V log V) | O(E log V) | Priority Queue (Min Heap) | Finds shortest path in weighted graphs | Doesn’t work with negative weights |
| **Bellman-Ford Algorithm** | O(V) | O(VE) | Array | Handles negative weights | Slower than Dijkstra |
| **Floyd-Warshall Algorithm** | O(V³) | O(V³) | Matrix | Computes all-pairs shortest paths | Not efficient for large graphs |
| **Kruskal’s Algorithm** | O(E log E) | O(E log E) | Disjoint Set (Union-Find) | Works well with sparse graphs | Sorting edges takes extra time |
| **Prim’s Algorithm** | O(V log V) | O(E log V) | Priority Queue | Good for dense graphs | Requires additional data structures |

---

## **Sorting Algorithms**
| Algorithm | Best Case | Worst Case | Data Structure Used | Advantages | Disadvantages |
|-----------|------------|-------------|----------------------|------------|--------------|
| **Quick Sort** | O(n log n) | O(n²) | Array (Recursion) | Fast in average case | Worst case O(n²) for sorted input |
| **Merge Sort** | O(n log n) | O(n log n) | Array (Recursion, Auxiliary Array) | Stable sorting | Requires extra space O(n) |
| **Heap Sort** | O(n log n) | O(n log n) | Heap (Binary Heap) | Doesn’t require extra space | Not stable |
| **Bubble Sort** | O(n) | O(n²) | Array | Simple to implement | Inefficient for large data |
| **Insertion Sort** | O(n) | O(n²) | Array | Efficient for small data | Slow for large data |
| **Selection Sort** | O(n²) | O(n²) | Array | Simple implementation | Always O(n²), even if sorted |

---

## **Dynamic Programming Algorithms**
| Algorithm | Best Case | Worst Case | Data Structure Used | Advantages | Disadvantages |
|-----------|------------|-------------|----------------------|------------|--------------|
| **Fibonacci (Recursion + Memoization)** | O(n) | O(n) | Array (DP Table) | Avoids redundant calculations | Extra space required for memoization |
| **Knapsack Problem (0/1)** | O(nW) | O(nW) | Matrix | Finds optimal solution | Uses extra memory |
| **Longest Common Subsequence (LCS)** | O(mn) | O(mn) | Matrix | Useful for string comparison | Takes O(mn) space |
| **Longest Increasing Subsequence (LIS)** | O(n log n) | O(n²) | Array | Efficient with binary search | Hard to implement optimally |

---

## **Data Structure Operations**
| Data Structure | Access | Search | Insertion | Deletion | Advantages | Disadvantages |
|---------------|--------|--------|-----------|----------|------------|--------------|
| **Array** | O(1) | O(n) | O(n) | O(n) | Fast access | Fixed size |
| **Linked List** | O(n) | O(n) | O(1) (Head) / O(n) (Tail) | O(1) (Head) / O(n) (Tail) | Dynamic size | Slow search |
| **Stack** | O(1) | O(n) | O(1) | O(1) | Fast LIFO operations | No direct access |
| **Queue** | O(1) | O(n) | O(1) | O(1) | Fast FIFO operations | No direct access |
| **Hash Table** | O(1) | O(1) | O(1) | O(1) | Fast lookups | Collisions possible |
| **Binary Search Tree (BST)** | O(log n) | O(log n) | O(log n) | O(log n) | Keeps data sorted | Unbalanced trees degrade performance |
| **AVL Tree** | O(log n) | O(log n) | O(log n) | O(log n) | Always balanced | Rotations take extra time |
| **Heap** | O(n) | O(log n) | O(log n) | O(log n) | Efficient for priority queues | No direct search |

---
