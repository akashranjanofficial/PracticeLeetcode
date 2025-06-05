# LeetCode Problem List with Patterns

This document contains a curated list of LeetCode problems organized by topic and difficulty level. Each problem includes prerequisite concepts AND the key algorithmic patterns to help you recognize similar problems and solutions.

---

## 1. Arrays

### Easy
- **[Two Sum](https://leetcode.com/problems/two-sum/)**  
  *Prerequisites:* Array traversal, basic hash map usage  
  *Patterns:* **Hash Map Lookup**, **Complement Pattern**

- **[Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)**  
  *Prerequisites:* Single pass iteration, tracking minimum/maximum values  
  *Patterns:* **Single Pass**, **Min/Max Tracking**, **Greedy Algorithm**

- **[Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)**  
  *Prerequisites:* Using sets or hash maps for frequency counting  
  *Patterns:* **Hash Set for Duplicates**, **Early Return Pattern**

- **[Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)**  
  *Prerequisites:* Iterative DP (Kadane's Algorithm)  
  *Patterns:* **Kadane's Algorithm**, **Dynamic Programming (1D)**, **Optimal Substructure**

### Medium
- **[Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)**  
  *Prerequisites:* Prefix/suffix product computation without division  
  *Patterns:* **Prefix/Suffix Arrays**, **Space Optimization**, **Two-Pass Technique**

- **[Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)**  
  *Prerequisites:* In-place modification and index mapping  
  *Patterns:* **Index as Hash Key**, **In-Place Modification**, **Cyclic Sort**

- **[Find Peak Element](https://leetcode.com/problems/find-peak-element/)**  
  *Prerequisites:* Binary search variant  
  *Patterns:* **Modified Binary Search**, **Peak Finding**

- **[Merge Intervals](https://leetcode.com/problems/merge-intervals/)**  
  *Prerequisites:* Sorting intervals and merging overlapping ranges  
  *Patterns:* **Interval Merging**, **Sort + Merge**, **Sweep Line**

### Hard
- **[Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)**  
  *Prerequisites:* Two-pointer technique and boundary handling  
  *Patterns:* **Two Pointers**, **Left/Right Max Arrays**, **Dynamic Programming**

- **[Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)**  
  *Prerequisites:* Hash table usage for managing unsorted data  
  *Patterns:* **Hash Set for O(1) Lookup**, **Sequence Building**, **Union Find (Alternative)**

---

## 2. Strings

### Easy
- **[Valid Anagram](https://leetcode.com/problems/valid-anagram/)**  
  *Prerequisites:* Character frequency counting, basic string manipulation  
  *Patterns:* **Frequency Counter**, **Hash Map Comparison**, **Sorting for Comparison**

- **[Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)**  
  *Prerequisites:* Two-pointer technique on strings  
  *Patterns:* **Two Pointers (Opposite Ends)**, **Character Filtering**

- **[Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)**  
  *Prerequisites:* Iterative character comparison  
  *Patterns:* **Vertical Scanning**, **Horizontal Scanning**, **Divide and Conquer**

- **[Count and Say](https://leetcode.com/problems/count-and-say/)**  
  *Prerequisites:* Iterative string generation, pattern recognition  
  *Patterns:* **Simulation**, **String Building**, **Look and Say Pattern**

### Medium
- **[Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)**  
  *Prerequisites:* Sliding window technique  
  *Patterns:* **Sliding Window**, **Hash Set for Duplicates**, **Two Pointers**

- **[Group Anagrams](https://leetcode.com/problems/group-anagrams/)**  
  *Prerequisites:* Sorting or hash mapping of strings  
  *Patterns:* **Grouping by Key**, **Hash Map with Custom Keys**, **Sorting as Key**

- **[Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)**  
  *Prerequisites:* Expanding from the center or dynamic programming  
  *Patterns:* **Expand Around Centers**, **Dynamic Programming (2D)**, **Manacher's Algorithm**

### Hard
- **[Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)**  
  *Prerequisites:* Advanced sliding window with frequency mapping  
  *Patterns:* **Sliding Window with Constraints**, **Frequency Matching**, **Template Matching**

- **[Wildcard Matching](https://leetcode.com/problems/wildcard-matching/)**  
  *Prerequisites:* Dynamic programming with recursion  
  *Patterns:* **Dynamic Programming (2D)**, **Pattern Matching**, **Greedy + DP**

- **[Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)**  
  *Prerequisites:* Recursive and DP approaches for pattern matching  
  *Patterns:* **Dynamic Programming (2D)**, **Recursion with Memoization**, **State Machine**

---

## 3. Linked Lists

### Easy
- **[Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)**  
  *Prerequisites:* Pointer manipulation and basic linked list traversal  
  *Patterns:* **Iterative Reversal**, **Recursive Reversal**, **Three Pointers**

- **[Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)**  
  *Prerequisites:* Iterative merging of lists  
  *Patterns:* **Two Pointers (Different Lists)**, **Merge Process**, **Dummy Head**

- **[Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)**  
  *Prerequisites:* Fast and slow pointers (Floyd's Cycle Detection)  
  *Patterns:* **Floyd's Tortoise and Hare**, **Cycle Detection**, **Two Pointers (Different Speeds)**

- **[Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)**  
  *Prerequisites:* Pointer manipulation and intersection logic  
  *Patterns:* **Two Pointers with Length Alignment**, **Hash Set for Visited Nodes**

- **[Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)**  
  *Prerequisites:* Reverse half the list and compare corresponding nodes  
  *Patterns:* **Fast/Slow Pointers to Find Middle**, **Reverse Second Half**, **Two Pointers Comparison**

### Medium
- **[Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)**  
  *Prerequisites:* Two-pointer technique  
  *Patterns:* **Two Pointers with Gap**, **One Pass Solution**, **Dummy Head**

- **[Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)**  
  *Prerequisites:* Deep copy techniques and hash mapping  
  *Patterns:* **Hash Map for Node Mapping**, **Three Pass Algorithm**, **Interweaving Nodes**

- **[Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)**  
  *Prerequisites:* Iterative traversal with carry propagation  
  *Patterns:* **Carry Propagation**, **Parallel Processing**, **Dummy Head**

- **[Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)**  
  *Prerequisites:* Recursive traversal and pointer adjustments  
  *Patterns:* **DFS on Linked List**, **Stack for Backtracking**, **Recursive Flattening**

### Hard
- **[Reverse Nodes in k-Group](https://leetcode.com/problems/reverse-nodes-in-k-group/)**  
  *Prerequisites:* Advanced pointer manipulation and sublist reversal  
  *Patterns:* **Iterative Reversal in Groups**, **Pointer Manipulation**, **Length Checking**

---

## 4. Stacks

### Easy
- **[Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)**  
  *Prerequisites:* Basic stack operations and symbol matching  
  *Patterns:* **Stack for Matching**, **LIFO for Nested Structures**, **Hash Map for Pairs**

- **[Min Stack](https://leetcode.com/problems/min-stack/)**  
  *Prerequisites:* Enhancing a stack with auxiliary tracking  
  *Patterns:* **Auxiliary Stack**, **Stack with Metadata**, **Monotonic Stack**

### Medium
- **[Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)**  
  *Prerequisites:* Stack-based evaluation of postfix expressions  
  *Patterns:* **Stack for Expression Evaluation**, **Operator Processing**

- **[Basic Calculator II](https://leetcode.com/problems/basic-calculator-ii/)**  
  *Prerequisites:* Parsing arithmetic expressions using stacks  
  *Patterns:* **Stack for Operators**, **Precedence Handling**, **Expression Parsing**

- **[Simplify Path](https://leetcode.com/problems/simplify-path/)**  
  *Prerequisites:* Processing file paths with stack operations  
  *Patterns:* **Stack for Path Components**, **String Processing**

- **[Remove K Digits](https://leetcode.com/problems/remove-k-digits/)**  
  *Prerequisites:* Greedy strategy combined with stack-based digit removal  
  *Patterns:* **Monotonic Stack**, **Greedy Algorithm**, **Stack for Building Result**

### Hard
- **[Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)**  
  *Prerequisites:* Advanced stack usage for index tracking and area computation  
  *Patterns:* **Monotonic Stack**, **Stack for Index Tracking**, **Divide and Conquer (Alternative)**

---

## 5. Queues

### Easy
- **[Design Circular Queue](https://leetcode.com/problems/design-circular-queue/)**  
  *Prerequisites:* Array-based queue implementation and boundary management  
  *Patterns:* **Circular Buffer**, **Modular Arithmetic**, **FIFO Implementation**

- **[Moving Average from Data Stream](https://leetcode.com/problems/moving-average-from-data-stream/)**  
  *Prerequisites:* Fixed-size window processing  
  *Patterns:* **Sliding Window**, **Queue for Fixed Window**, **Running Sum**

### Medium
- **[Number of Recent Calls (Recent Counter)](https://leetcode.com/problems/number-of-recent-calls/)**  
  *Prerequisites:* Implementing a time-based sliding window using a queue  
  *Patterns:* **Time-based Sliding Window**, **Queue for Time Series**, **Monotonic Queue**

- **[Design Hit Counter](https://leetcode.com/problems/design-hit-counter/)**  
  *Prerequisites:* Handling time-stamped events with queue data structures  
  *Patterns:* **Time Window Management**, **Queue for Events**, **Bucketing by Time**

### Hard
- **[Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)**  
  *Prerequisites:* Efficient sliding window maximum computation using a deque  
  *Patterns:* **Monotonic Deque**, **Sliding Window Maximum**, **Deque for Range Queries**

---

## 6. Trees

### Easy
- **[Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)**  
  *Prerequisites:* Recursive or iterative (stack-based) tree traversal  
  *Patterns:* **Tree Traversal (Inorder)**, **Stack for Iterative DFS**, **Recursion**

- **[Symmetric Tree](https://leetcode.com/problems/symmetric-tree/)**  
  *Prerequisites:* Recursive comparison of mirrored subtrees  
  *Patterns:* **Tree Symmetry Check**, **Recursive Comparison**, **Mirror Traversal**

- **[Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)**  
  *Prerequisites:* Recursion for calculating tree depth  
  *Patterns:* **Tree Height Calculation**, **Post-order Traversal**, **DFS with Depth**

- **[Insert into a Binary Search Tree](https://leetcode.com/problems/insert-into-a-binary-search-tree/)**  
  *Prerequisites:* BST properties and recursive insertion  
  *Patterns:* **BST Insertion**, **Binary Search Tree Property**, **Recursive Tree Modification**

### Medium
- **[Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)**  
  *Prerequisites:* Inorder traversal and BST validation  
  *Patterns:* **BST Validation**, **Range Checking**, **Inorder Traversal Property**

- **[Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)**  
  *Prerequisites:* Breadth-first search (BFS) using a queue  
  *Patterns:* **BFS on Trees**, **Level-by-Level Processing**, **Queue for Tree Traversal**

- **[Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)**  
  *Prerequisites:* Recursive tree reconstruction using traversal orders  
  *Patterns:* **Tree Construction from Traversals**, **Divide and Conquer**, **Hash Map for Index Lookup**

- **[Lowest Common Ancestor of a Binary Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)**  
  *Prerequisites:* Recursive search for intersection of paths  
  *Patterns:* **LCA in Binary Tree**, **Post-order Traversal**, **Path Finding**

### Hard
- **[Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)**  
  *Prerequisites:* Advanced recursion with proper handling of null markers  
  *Patterns:* **Tree Serialization**, **Pre-order with Null Markers**, **String Parsing**

- **[Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)**  
  *Prerequisites:* DFS combined with dynamic programming on tree nodes  
  *Patterns:* **Tree DP**, **Post-order Traversal**, **Path Sum Variants**

---

## 7. Graphs

### Easy
- **[Number of Islands](https://leetcode.com/problems/number-of-islands/)**  
  *Prerequisites:* Grid-based DFS/BFS traversal  
  *Patterns:* **Connected Components**, **DFS/BFS on Grid**, **Union Find (Alternative)**

- **[Walls and Gates](https://leetcode.com/problems/walls-and-gates/)**  
  *Prerequisites:* Multi-source BFS in grids  
  *Patterns:* **Multi-source BFS**, **Distance Calculation**, **Grid Traversal**

- **[Shortest Path in Binary Matrix](https://leetcode.com/problems/shortest-path-in-binary-matrix/)**  
  *Prerequisites:* BFS for optimal path finding in grids  
  *Patterns:* **BFS for Shortest Path**, **Grid Pathfinding**, **8-directional Movement**

### Medium
- **[Clone Graph](https://leetcode.com/problems/clone-graph/)**  
  *Prerequisites:* Graph traversal and node-copy mapping  
  *Patterns:* **Graph Cloning**, **DFS/BFS with Hash Map**, **Deep Copy**

- **[Course Schedule](https://leetcode.com/problems/course-schedule/)**  
  *Prerequisites:* Cycle detection using DFS/BFS  
  *Patterns:* **Cycle Detection in Directed Graph**, **Topological Sort**, **DFS with Colors**

- **[Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)**  
  *Prerequisites:* Topological sorting for ordering courses  
  *Patterns:* **Topological Sort**, **Kahn's Algorithm**, **DFS Post-order**

- **[Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/)**  
  *Prerequisites:* Using union-find or DFS to check connectivity without cycles  
  *Patterns:* **Tree Validation**, **Union Find**, **Connected Components + Cycle Detection**

- **[Redundant Connection](https://leetcode.com/problems/redundant-connection/)**  
  *Prerequisites:* Union-find to detect cycles  
  *Patterns:* **Union Find**, **Cycle Detection**, **Edge Processing**

- **[Minimum Height Trees](https://leetcode.com/problems/minimum-height-trees/)**  
  *Prerequisites:* Layered BFS to determine tree centers  
  *Patterns:* **Tree Center Finding**, **Topological Sort on Trees**, **Leaf Removal**

### Hard
- **[Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/)**  
  *Prerequisites:* Tarjan's algorithm and advanced DFS for bridge detection  
  *Patterns:* **Tarjan's Bridge Algorithm**, **DFS with Low-link Values**, **Critical Edges**

---

## 8. Sorting & Searching

### Easy
- **[First Bad Version](https://leetcode.com/problems/first-bad-version/)**  
  *Prerequisites:* Basic binary search  
  *Patterns:* **Binary Search for First Occurrence**, **API-based Binary Search**

- **[Search Insert Position](https://leetcode.com/problems/search-insert-position/)**  
  *Prerequisites:* Binary search for finding an insertion index  
  *Patterns:* **Binary Search for Insertion Point**, **Lower Bound**

- **[Binary Search](https://leetcode.com/problems/binary-search/)**  
  *Prerequisites:* Standard binary search implementation  
  *Patterns:* **Classic Binary Search**, **Divide and Conquer**

- **[Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)**  
  *Prerequisites:* Two-pointer technique for in‑place merging  
  *Patterns:* **Two Pointers (Merge)**, **In-place Merge**, **Backward Processing**

- **[Find Peak Element](https://leetcode.com/problems/find-peak-element/)**  
  *Prerequisites:* Binary search variant for locating peaks  
  *Patterns:* **Modified Binary Search**, **Peak Finding**

### Medium
- **[Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)**  
  *Prerequisites:* Modified binary search for rotated arrays  
  *Patterns:* **Binary Search on Rotated Array**, **Pivot Finding**

- **[Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)**  
  *Prerequisites:* Locating the rotation pivot using binary search  
  *Patterns:* **Binary Search for Minimum**, **Rotation Point Detection**

- **[Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)**  
  *Prerequisites:* Quickselect algorithm or heap data structure  
  *Patterns:* **Quickselect**, **Min/Max Heap**, **Partition Algorithm**

- **[Merge Intervals](https://leetcode.com/problems/merge-intervals/)**  
  *Prerequisites:* Sorting intervals then merging overlapping ones  
  *Patterns:* **Interval Merging**, **Sort + Sweep**, **Greedy Algorithm**

- **[Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/)**  
  *Prerequisites:* Scheduling overlapping intervals using a priority queue  
  *Patterns:* **Interval Scheduling**, **Min Heap for Events**, **Sweep Line Algorithm**

---

## 9. Dynamic Programming (DP)

### Easy
- **[Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)**  
  *Prerequisites:* Simple recurrence relations and memoization  
  *Patterns:* **1D DP**, **Fibonacci Pattern**, **Bottom-up DP**

- **[Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)**  
  *Prerequisites:* Kadane's Algorithm (1D DP)  
  *Patterns:* **Kadane's Algorithm**, **1D DP**, **Optimal Subarray**

### Medium
- **[House Robber](https://leetcode.com/problems/house-robber/)**  
  *Prerequisites:* 1D DP for sequential decision making  
  *Patterns:* **1D DP**, **Adjacent Constraints**, **Max at Each Position**

- **[Unique Paths](https://leetcode.com/problems/unique-paths/)**  
  *Prerequisites:* 2D DP formulation on grids  
  *Patterns:* **2D DP**, **Grid Path Counting**, **Combinatorics (Alternative)**

- **[Minimum Path Sum](https://leetcode.com/problems/minimum-path-sum/)**  
  *Prerequisites:* Cumulative sum DP on matrices  
  *Patterns:* **2D DP**, **Grid Path Optimization**, **Space Optimization**

- **[Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)**  
  *Prerequisites:* DP with or without binary search optimization  
  *Patterns:* **LIS Pattern**, **1D DP**, **Binary Search + DP**, **Patience Sorting**

- **[Coin Change](https://leetcode.com/problems/coin-change/)**  
  *Prerequisites:* Bottom-up DP on overlapping subproblems  
  *Patterns:* **Unbounded Knapsack**, **Coin Change Pattern**, **Min/Max DP**

- **[Combination Sum IV](https://leetcode.com/problems/combination-sum-iv/)**  
  *Prerequisites:* DP for counting permutations  
  *Patterns:* **Counting DP**, **Unbounded Knapsack**, **Order Matters**

- **[Decode Ways](https://leetcode.com/problems/decode-ways/)**  
  *Prerequisites:* DP applied to string decoding  
  *Patterns:* **String DP**, **Decision Tree DP**, **Fibonacci-like Pattern**

### Hard
- **[Edit Distance](https://leetcode.com/problems/edit-distance/)**  
  *Prerequisites:* 2D DP formulation for string transformations  
  *Patterns:* **2D String DP**, **Edit Distance (Levenshtein)**, **String Matching DP**

---

## 10. Backtracking

### Easy
- **[Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)**  
  *Prerequisites:* Recursion with constraint management  
  *Patterns:* **Backtracking with Constraints**, **Valid Combinations**, **DFS Tree**

- **[Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)**  
  *Prerequisites:* Recursive mapping of digits to letters  
  *Patterns:* **Backtracking for Combinations**, **Cartesian Product**, **DFS**

### Medium
- **[Subsets](https://leetcode.com/problems/subsets/)**  
  *Prerequisites:* Recursively generating the power set  
  *Patterns:* **Power Set Generation**, **Include/Exclude Pattern**, **Bit Manipulation (Alternative)**

- **[Permutations](https://leetcode.com/problems/permutations/)**  
  *Prerequisites:* Backtracking using swapping or visited markers  
  *Patterns:* **Permutation Generation**, **Backtracking with Swapping**, **DFS with State**

- **[Combination Sum](https://leetcode.com/problems/combination-sum/)**  
  *Prerequisites:* Recursive exploration of candidate sums  
  *Patterns:* **Combination with Repetition**, **Target Sum Backtracking**, **Pruning**

- **[Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)**  
  *Prerequisites:* Backtracking combined with palindrome checking  
  *Patterns:* **String Partitioning**, **Backtracking + Validation**, **Precomputed Palindromes**

- **[Word Search](https://leetcode.com/problems/word-search/)**  
  *Prerequisites:* Grid traversal with recursive backtracking  
  *Patterns:* **Grid Backtracking**, **DFS with Path Tracking**, **State Restoration**

- **[Combination Sum II](https://leetcode.com/problems/combination-sum-ii/)**  
  *Prerequisites:* Backtracking while managing duplicate candidates  
  *Patterns:* **Backtracking with Duplicates**, **Skip Duplicates Pattern**, **Sorted Input Processing**

### Hard
- **[N-Queens](https://leetcode.com/problems/n-queens/)**  
  *Prerequisites:* Advanced backtracking with conflict checking  
  *Patterns:* **Constraint Satisfaction**, **Conflict Detection**, **Board State Backtracking**

- **[Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)**  
  *Prerequisites:* Deep recursive search with constraint propagation  
  *Patterns:* **Constraint Satisfaction Problem**, **Backtracking with Multiple Constraints**, **Grid State Management**

---

## 11. Advanced Data Structures

### Medium
- **[Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)**  
  *Prerequisites:* Basic tree structures and recursive insertion  
  *Patterns:* **Trie Data Structure**, **Prefix Matching**, **Tree Construction**

- **[Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)**  
  *Prerequisites:* Trie implementation with wildcard support  
  *Patterns:* **Trie with Wildcards**, **DFS on Trie**, **Pattern Matching**

- **[Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)**  
  *Prerequisites:* Combining hash maps and dynamic arrays for O(1) operations  
  *Patterns:* **Hash Map + Array Combination**, **Swap and Pop**, **O(1) Random Access**

- **[Range Sum Query - Mutable](https://leetcode.com/problems/range-sum-query-mutable/)**  
  *Prerequisites:* Binary Indexed Tree (BIT) or Segment Tree usage  
  *Patterns:* **Segment Tree**, **Binary Indexed Tree (Fenwick Tree)**, **Range Query Data Structures**

### Hard
- **[Word Search II](https://leetcode.com/problems/word-search-ii/)**  
  *Prerequisites:* Combining a Trie with DFS/backtracking  
  *Patterns:* **Trie + DFS**, **Multi-string Search**, **Backtracking Optimization**

- **[Count of Range Sum](https://leetcode.com/problems/count-of-range-sum/)**  
  *Prerequisites:* Advanced segmentation using BIT or Segment Tree  
  *Patterns:* **Merge Sort + Counting**, **Coordinate Compression**, **Binary Indexed Tree**

- **[Design Skiplist](https://leetcode.com/problems/design-skiplist/)**  
  *Prerequisites:* Understanding probabilistic balancing and layered linked lists  
  *Patterns:* **Probabilistic Data Structures**, **Multi-level Linked Lists**, **Skip List Operations**

- **[LFU Cache](https://leetcode.com/problems/lfu-cache/)**  
  *Prerequisites:* Hash maps with doubly linked lists for efficient caching  
  *Patterns:* **LFU Cache Design**, **Hash Map + Doubly Linked List**, **Frequency Tracking**

- **[All O(1) Data Structure](https://leetcode.com/problems/all-oone-data-structure/)**  
  *Prerequisites:* Advanced frequency tracking with constant-time operations  
  *Patterns:* **Multi-level Hash Maps**, **Doubly Linked List of Buckets**, **Frequency Management**

- **[Implement Magic Dictionary](https://leetcode.com/problems/implement-magic-dictionary/)**  
  *Prerequisites:* Trie with support for one-character mismatches  
  *Patterns:* **Trie with Modifications**, **DFS with Error Allowance**, **Wildcard Matching**

---

## Common Algorithmic Patterns Summary

### Core Patterns to Master:
1. **Two Pointers** - Array problems, linked lists, string problems
2. **Sliding Window** - Substring problems, array subarrays
3. **Hash Map/Set** - Frequency counting, lookups, duplicates
4. **Binary Search** - Sorted arrays, search space reduction
5. **DFS/BFS** - Trees, graphs, connected components
6. **Dynamic Programming** - Optimization problems, overlapping subproblems
7. **Backtracking** - Generate all solutions, constraint satisfaction
8. **Greedy** - Local optimal choices leading to global optimum
9. **Union Find** - Connected components, cycle detection
10. **Monotonic Stack/Queue** - Next greater/smaller elements, sliding window extremes

### Advanced Patterns:
- **Topological Sort** - Ordering with dependencies
- **Trie** - Prefix matching, string search
- **Segment Tree/BIT** - Range queries and updates
- **Floyd's Cycle Detection** - Linked list cycles
- **Kadane's Algorithm** - Maximum subarray problems
- **Quick Select** - Kth element problems
- **Merge Sort Pattern** - Divide and conquer sorting
- **Coordinate Compression** - Large range problems

# LeetCode Study Guide with Patterns

A comprehensive, pattern-focused approach to mastering data structures and algorithms through LeetCode problems.

## 📚 Overview

This repository contains a curated collection of **150+ LeetCode problems** organized by topic and enhanced with **algorithmic patterns** to accelerate your learning and interview preparation.

### Why This Guide?

- 🎯 **Pattern-Focused Learning**: Each problem includes the key algorithmic patterns it uses
- 📈 **Progressive Difficulty**: Problems are organized from Easy → Medium → Hard within each topic
- 🔗 **Direct Links**: Every problem title links directly to LeetCode
- 📝 **Prerequisites Listed**: Know exactly what concepts you need before attempting each problem
- ⚡ **Interview Ready**: Focus on the most important patterns that appear in technical interviews

## 🗂️ Problem Categories

### Core Data Structures
| Category | Easy | Medium | Hard | Key Patterns |
|----------|------|--------|------|--------------|
| **Arrays** | 4 | 4 | 2 | Two Pointers, Sliding Window, Prefix/Suffix |
| **Strings** | 4 | 3 | 3 | Sliding Window, Two Pointers, Pattern Matching |
| **Linked Lists** | 5 | 4 | 1 | Two Pointers, Fast/Slow Pointers, Reversal |
| **Stacks** | 2 | 4 | 1 | Monotonic Stack, Expression Evaluation |
| **Queues** | 2 | 2 | 1 | Sliding Window, BFS, Deque |
| **Trees** | 4 | 4 | 2 | DFS, BFS, Tree DP, Traversals |
| **Graphs** | 3 | 6 | 1 | DFS/BFS, Union Find, Topological Sort |

### Advanced Topics
| Category | Easy | Medium | Hard | Key Patterns |
|----------|------|--------|------|--------------|
| **Sorting & Searching** | 5 | 5 | 0 | Binary Search, Two Pointers, QuickSelect |
| **Dynamic Programming** | 2 | 7 | 1 | 1D/2D DP, State Machines, Optimization |
| **Backtracking** | 2 | 6 | 2 | DFS, Constraint Satisfaction, Pruning |
| **Advanced Data Structures** | 0 | 4 | 6 | Trie, Segment Tree, LRU/LFU Cache |

## 🎯 Essential Patterns to Master

### 🥇 **Must-Know Patterns** (Master These First)
1. **Two Pointers** - Array problems, palindromes, sorted arrays
2. **Sliding Window** - Substring/subarray problems
3. **Hash Map/Set** - Frequency counting, fast lookups
4. **Binary Search** - Sorted data, search space reduction
5. **DFS/BFS** - Tree/graph traversal, connected components
6. **Dynamic Programming** - Optimization, overlapping subproblems

### 🥈 **Important Patterns**
7. **Backtracking** - Generate solutions, constraint satisfaction
8. **Greedy Algorithm** - Local optimum → global optimum
9. **Union Find** - Connected components, cycle detection
10. **Monotonic Stack/Queue** - Next greater/smaller elements

### 🥉 **Advanced Patterns**
- **Topological Sort** - Dependencies, ordering
- **Trie** - Prefix matching, autocomplete
- **Segment Tree/BIT** - Range queries
- **Floyd's Cycle Detection** - Linked list problems
- **Coordinate Compression** - Large range optimization

## 🚀 Getting Started

### For Beginners
1. **Start with Arrays & Strings** - Build fundamental pattern recognition
2. **Master Two Pointers** - Appears in 20+ problems across categories
3. **Learn Hash Maps** - Essential for O(1) lookups and frequency counting
4. **Practice Trees** - Foundation for many advanced algorithms

### For Intermediate
1. **Focus on Dynamic Programming** - High-impact pattern for interviews
2. **Master Binary Search** - More than just sorted array search
3. **Learn Graph Algorithms** - DFS, BFS, Union Find
4. **Practice Backtracking** - Generate all valid solutions

### For Advanced
1. **Advanced Data Structures** - Trie, Segment Tree, LRU Cache
2. **Complex Graph Algorithms** - Topological sort, shortest paths
3. **Optimization Techniques** - Space/time complexity improvements

## 📖 How to Use This Guide

### 1. **Choose Your Learning Path**
```
Beginner: Arrays → Strings → Linked Lists → Trees
Intermediate: + DP → Graphs → Binary Search → Backtracking  
Advanced: + Advanced Data Structures → Complex Algorithms
```

### 2. **Pattern-First Approach**
- Read the pattern description for each problem
- Implement the core pattern first
- Then solve the specific problem
- Look for similar patterns in other problems

### 3. **Progressive Practice**
- Master Easy problems in a category first
- Move to Medium only after consistent success
- Hard problems often combine multiple patterns

## 📊 Study Schedule Suggestions

### 🎯 **30-Day Sprint** (Interview Prep)
- **Week 1**: Arrays, Strings, Two Pointers (5 problems/day)
- **Week 2**: Trees, Linked Lists, Stacks/Queues (4 problems/day)
- **Week 3**: DP, Graphs, Binary Search (3 problems/day)
- **Week 4**: Review + Mock Interviews (2 problems/day + practice)

### 📚 **3-Month Deep Dive** (Comprehensive)
- **Month 1**: Master all Easy problems + core patterns
- **Month 2**: Focus on Medium problems + pattern combinations
- **Month 3**: Hard problems + advanced data structures + system design

### 🔄 **Ongoing Maintenance**
- **Daily**: 1-2 problems to maintain skills
- **Weekly**: Focus on one pattern category
- **Monthly**: Mock interview + review weak areas

## 🏆 Success Metrics

### Track Your Progress
- [ ] **Fundamentals**: Can solve 90% of Easy problems without hints
- [ ] **Intermediate**: Can identify patterns in Medium problems within 5 minutes
- [ ] **Advanced**: Can solve Hard problems by combining multiple patterns
- [ ] **Interview Ready**: Can explain approach before coding + handle follow-ups

### Pattern Mastery Checklist
- [ ] Two Pointers (15+ problems solved)
- [ ] Sliding Window (10+ problems solved)
- [ ] Hash Map Patterns (20+ problems solved)
- [ ] Binary Search (10+ problems solved)
- [ ] Tree Traversals (15+ problems solved)
- [ ] Dynamic Programming (15+ problems solved)
- [ ] Graph Algorithms (10+ problems solved)
- [ ] Backtracking (8+ problems solved)

## 💡 Pro Tips

### During Problem Solving
1. **Read Twice, Code Once** - Understand the problem completely first
2. **Pattern Recognition** - "What pattern does this remind me of?"
3. **Start Simple** - Brute force first, then optimize
4. **Test Edge Cases** - Empty inputs, single elements, duplicates
5. **Time/Space Analysis** - Always discuss complexity

### For Interviews
- **Think Out Loud** - Explain your thought process
- **Ask Clarifying Questions** - Edge cases, constraints, examples
- **Start with Brute Force** - Then optimize step by step
- **Write Clean Code** - Variable names, structure, comments
- **Test Your Solution** - Walk through with examples

## 🔗 Quick Links

- [**Full Problem List**](leetcode-patterns-guide.md) - Complete guide with all problems and patterns
- [**LeetCode**](https://leetcode.com) - Practice platform
- [**Pattern Templates**](patterns/) - Code templates for each pattern *(coming soon)*
- [**Mock Interviews**](mock-interviews/) - Practice problems by company *(coming soon)*

## 📈 Updates

- **v2.0** (Current) - Added algorithmic patterns to all problems
- **v1.0** - Initial problem categorization and prerequisite listing



