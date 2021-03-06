# 100DaysOfCode

Day-by-day coding progress listed below (mostly LeetCode, with some Coursera and HackerRank sprinkled in).

[Personal Website](https://anthonyrchao.github.io)\
[LeetCode Profile](https://leetcode.com/anthonychao/)\
[HackerRank Profile](https://www.hackerrank.com/AnthonyChao)

---
LeetCode Problem Counter: **123/200** (as of 6/12/19)

---
### [LeetCode Learn - Data Structure and Algorithms](https://leetcode.com/explore/learn/)
[x] [Array and String](https://leetcode.com/explore/learn/card/array-and-string/)\
[x] [Hash Table](https://leetcode.com/explore/learn/card/hash-table/)\
[ ] [Linked List](https://leetcode.com/explore/learn/card/linked-list/)\
[ ] [Queue and Stack](https://leetcode.com/explore/learn/card/queue-stack/)\
[ ] [Binary Tree](https://leetcode.com/explore/learn/card/data-structure-tree/)\
[ ] [Binary Search Tree](https://leetcode.com/explore/learn/card/introduction-to-data-structure-binary-search-tree/)\
[ ] [N-ary Tree](https://leetcode.com/explore/learn/card/n-ary-tree/)\
[ ] [Trie](https://leetcode.com/explore/learn/card/trie/)\
[ ] [Recursion](https://leetcode.com/explore/learn/card/recursion-i/)\
[ ] [Binary Search](https://leetcode.com/explore/learn/card/binary-search/)\
[ ] [Decision Tree](https://leetcode.com/explore/learn/card/decision-tree/)


---
### Day 0: Wednesday, March 27, 2019

[x] [617. Merge Two Binary Trees](https://leetcode.com/problems/merge-two-binary-trees/)\
[x] [226. Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)\
[x] [965. Univalued Binary Tree](https://leetcode.com/problems/univalued-binary-tree/)

**Thoughts:** I am not as familiar as I thought with Trees. I had to look at the solutions for each of the questions. I will implement and familiarize myself with the different traversals for trees (DFS, BFS, Preorder, Inorder, Postorder) and do more problems to get more comfortable with recursive and iterative approaches.

The key insight to Merge Two Binary Trees is ...\
The key insight to Invert a Binary Tree is ...\
The key insight to check if a Binary Tree is Univalued is ...

---
### Day 1: Thursday, March 28, 2019

[x] [406. Queue Reconstruction by Height](https://leetcode.com/problems/queue-reconstruction-by-height/)

**Thoughts:** The key insight to **Queue Reconstruction by Height** is to sort the initial list of lists, `people`, by height descending and index ascending (via `people = sorted(people, key=lambda x: (-x[0], x[1]))`. We then initialize a `list` to house our result. Iterate over each `p` in `people` and insert `p` at index `p[1]` in `list`.

---
### Day 2: Friday, March 29, 2019

[x] [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)\
[x] [448. Find All Numbers Disappeared in an Array](https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/)

**Thoughts:** I did not find the optimal solution for 234 and 448 within the 20 minute time frame for each. I was able to write a working naive solution. Will return to this ... TODO.

---
### Day 3: Saturday, March 30, 2019

[x] [144. Binary Tree Preorder Traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/)\
[x] [94. Binary Tree Inorder Traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)\
[x] [145. Binary Tree Postorder Traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/)

**Thoughts:** For binary trees, practice the three different traversal methods: pre-order, in-order, and post order. Implement the methods both recursively and iteratively and compare the differences between them.

---
### Day 4: Sunday, March 31, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 1](https://www.coursera.org/specializations/data-structures-algorithms)

**Thoughts:** I struggled to get the tree height problem working. Will re-visit.

---
### Day 5: Monday, April 1, 2019

[x] [Integer between 1 and 1000 with greatest steps to reach 1 based on the Collatz Conjecture](https://repl.it/@AnthonyChao/maxcollatz)\
[x] [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)

---
### Day 6: Tuesday, April 2, 2019

[x] [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)

---
### Day 7: Wednesday, April 3, 2019

[x] [538. Convert BST to Greater Tree](https://leetcode.com/problems/convert-bst-to-greater-tree/)\
[x] [287. Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)

---
### Day 8: Thursday, April 4, 2019

[x] [347. Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)

---
### Day 9: Friday, April 5, 2019

[x] [7. Reverse Integer](https://leetcode.com/problems/reverse-integer/)

---
### Day 10: Saturday, April 6, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 2](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 11: Sunday, April 7, 2019

[x] [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

---
### Day 12: Monday, April 8, 2019

[x] [HackerRank - Solve Me First]()\
[x] [HackerRank - Simple Array Sum]()\
[x] [HackerRank - Compare the Triplets]()\
[x] [HackerRank - Let's Echo]()\
[x] [HackerRank - A Very Big Sum]()\
[x] [HackerRank - Diagonal Difference]()\
[x] [HackerRank - Plus Minus]()\
[x] [HackerRank - Staircase]()\
[x] [HackerRank - Mini-Max Sum]()\
[x] [HackerRank - Birthday Cake Candles]()\
[x] [HackerRank - Time Conversion]()\
[x] [HackerRank - Grading Students]()

[x] [724. Find Pivot Index](https://leetcode.com/problems/find-pivot-index/)\
[x] [747. Largest Number At Least Twice of Others](https://leetcode.com/problems/largest-number-at-least-twice-of-others/)\
[x] [66. Plus One](https://leetcode.com/problems/plus-one/)

---
### Day 13: Tuesday, April 9, 2019

[x] [498. Diagonal Traverse](https://leetcode.com/problems/diagonal-traverse/)\
[x] [54. Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)

---
### Day 14: Wednesday, April 10, 2019

[x] [118. Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/)

---
### Day 15: Thursday, April 11, 2019

[x] [67. Add Binary](https://leetcode.com/problems/add-binary/)

---
### Day 16: Friday, April 12, 2019

[x] [28. Implement strStr()](https://leetcode.com/problems/implement-strstr/)

---
### Day 17: Saturday, April 13, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 3, Lectures](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 18: Sunday, April 14, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 3, Problems](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 19: Monday, April 15, 2019

[x] [344. Reverse String](https://leetcode.com/problems/reverse-string/)\
[x] [167. Two Sum II - Input array is sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)\
[x] [485. Max Consecutive Ones](https://leetcode.com/problems/max-consecutive-ones/)\
[x] [27. Remove Element](https://leetcode.com/problems/remove-element/)\
[x] [561. Array Partition I](https://leetcode.com/problems/array-partition-i/)\
[x] [500. Keyboard Row](https://leetcode.com/problems/keyboard-row/)

---
### Day 20: Tuesday, April 16, 2019

[x] [151. Reverse Words in a String](https://leetcode.com/problems/reverse-words-in-a-string/)\
[x] [557. Reverse Words in a String III](https://leetcode.com/problems/reverse-words-in-a-string-iii/)

---
### Day 21: Wednesday, April 17, 2019

[x] [189. Rotate Array](https://leetcode.com/problems/rotate-array/)\
[x] [119. Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/)\
[x] [26. Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)

---
### Day 22: Thursday, April 18, 2019

[x] [283. Move Zeroes](https://leetcode.com/problems/move-zeroes/)\
[x] [209. Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)

---
### Day 23: Friday, April 19, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 4, Lectures](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 24: Saturday, April 20, 2019

[x] [1029. Two City Scheduling](https://leetcode.com/problems/two-city-scheduling/)\
[x] [1030. Matrix Cells in Distance Order](https://leetcode.com/problems/matrix-cells-in-distance-order/)

---
### Day 25: Sunday, April 21, 2019

[x] [UCSD DS & A Coursera Specialization - Data Structures - Week 4, Problems](https://www.coursera.org/specializations/data-structures-algorithms)\
[x] [705. Design HashSet](https://leetcode.com/problems/design-hashset/)

---
### Day 26: Monday, April 22, 2019

[x] [706. Design HashMap](https://leetcode.com/problems/design-hashmap/)\
[x] [136. Single Number](https://leetcode.com/problems/single-number/)\
[x] [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)\
[x] [349. Intersection of Two Arrays](https://leetcode.com/problems/intersection-of-two-arrays/)\
[x] [202. Happy Number](https://leetcode.com/problems/happy-number/)\
[x] [1. Two Sum](https://leetcode.com/problems/two-sum/)

---
### Day 27: Tuesday, April 23, 2019

[x] [205. Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/)\
[x] [599. Minimum Index Sum of Two Lists](https://leetcode.com/problems/minimum-index-sum-of-two-lists/)

---
### Day 28: Wednesday, April 24, 2019

[x] [387. First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)\
[x] [350. Intersection of Two Arrays II](https://leetcode.com/problems/intersection-of-two-arrays-ii/)

---
### Day 29: Thursday, April 25, 2019

[x] [219. Contains Duplicate II](https://leetcode.com/problems/contains-duplicate-ii/)\
[x] [359. Logger Rate Limiter](https://leetcode.com/problems/logger-rate-limiter/)\
[x] [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)

---
### Day 30: Friday, April 26, 2019

[x] [249. Group Shifted Strings](https://leetcode.com/problems/group-shifted-strings/)\
[x] [3. Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

---
### Day 31: Saturday, April 27, 2019

[x] [UCSD DS & A Coursera Specialization - Binary Search Trees - Week 5, Lectures](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 32: Sunday, April 28, 2019

[x] [UCSD DS & A Coursera Specialization - Binary Search Trees - Week 5, Lectures](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 33: Monday, April 29, 2019

[x] [170. Two Sum III - Data structure design](https://leetcode.com/problems/two-sum-iii-data-structure-design/)\
[x] [771. Jewels and Stones](https://leetcode.com/problems/jewels-and-stones/)

---
### Day 34: Tuesday, April 30, 2019

[x] [36. Valid Sudoku](https://leetcode.com/problems/valid-sudoku/)

---
### Day 35: Wednesday, May 1, 2019

[x] [53. Maximum Subarray](https://leetcode.com/problems/maximum-subarray/submissions/)

---
### Day 36: Thursday, May 2, 2019

[x] [652. Find Duplicate Subtrees](https://leetcode.com/problems/find-duplicate-subtrees/)

---
### Day 37: Friday, May 3, 2019

[x] [125. Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)

---
### Day 38: Saturday, May 4, 2019

[x] [5051. Valid Boomerang](https://leetcode.com/contest/weekly-contest-135/problems/valid-boomerang/)\
[x] [5050. Binary Search Tree to Greater Sum Tree](https://leetcode.com/contest/weekly-contest-135/problems/binary-search-tree-to-greater-sum-tree/)

---
### Day 39: Sunday, May 5, 2019

[x] [UCSD DS & A Coursera Specialization - Binary Search Trees - Week 6, Lectures & Problems](https://www.coursera.org/specializations/data-structures-algorithms)

---
### Day 40: Monday, May 6, 2019

[x] [454. 4Sum II](https://leetcode.com/problems/4sum-ii/)

---
### Day 41: Tuesday, May 7, 2019

[x] [288. Unique Word Abbreviation](https://leetcode.com/problems/unique-word-abbreviation/)

---
### Day 42: Wednesday, May 8, 2019

[x] [380. Insert Delete GetRandom O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/)

---
### Day 43: Thursday, May 9, 2019

[x] [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

---
### Day 44: Friday, May 10, 2019

None

---
### Day 45: Saturday, May 11, 2019

None

---
### Day 46: Sunday, May 12, 2019

None

---
### Day 47: Monday, May 13, 2019

None

---
### Day 48: Tuesday, May 14, 2019

[x] [707. Design Linked List](https://leetcode.com/problems/design-linked-list/)\
[x] [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)

---
### Day 49: Wednesday, May 15, 2019

[x] [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

---
### Day 50: Thursday, May 16, 2019

[x] [19. Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)

---
### Day 51: Friday, May 17, 2019

[x] [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)

---
### Day 52: Saturday, May 18, 2019

[x] [203. Remove Linked List Elements](https://leetcode.com/problems/remove-linked-list-elements/)

---
### Day 53: Sunday, May 19, 2019

[x] [328. Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/)

---
### Day 54: Monday, May 20, 2019

[x] [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)

---
### Day 55: Tuesday, May 21, 2019

None

---
### Day 56: Wednesday, May 22, 2019

[x] [2. Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)

---
### Day 57: Thursday, May 23, 2019

[x] [430. Flatten a Multilevel Doubly Linked List](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)\
[x] [1050. Actors and Directors Who Cooperated At Least Three Times](https://leetcode.com/problems/actors-and-directors-who-cooperated-at-least-three-times/)

---
### Day 58: Friday, May 24, 2019

[x] [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/)

---
### Day 59: Saturday, May 25, 2019

[x] [977. Squares of a Sorted Array](https://leetcode.com/problems/squares-of-a-sorted-array/)

---
### Day 60: Sunday, May 26, 2019

[x] [938. Range Sum of BST](https://leetcode.com/problems/range-sum-of-bst/)\
[x] [760. Find Anagram Mappings](https://leetcode.com/problems/find-anagram-mappings/)

---
### Day 61: Monday, May 27, 2019

[x] [61. Rotate List](https://leetcode.com/problems/rotate-list/)

---
### Day 62: Tuesday, May 28, 2019

[x] [138. Copy List with Random Pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)

---
### Day 63: Wednesday, May 29, 2019

[x] [791. Custom Sort String](https://leetcode.com/problems/custom-sort-string/)

---
### Day 64: Thursday, May 30, 2019

[x] [613. Shortest Distance in a Line](https://leetcode.com/problems/shortest-distance-in-a-line/)

---
### Day 65: Friday, May 31, 2019

None

---
### Day 66: Saturday, June 1, 2019

None

---
### Day 67: Sunday, June 2, 2019

[x] [1068. Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/)\
[x] [1069. Product Sales Analysis II](https://leetcode.com/problems/product-sales-analysis-ii/)\
[x] [584. Find Customer Referee](https://leetcode.com/problems/find-customer-referee/)\
[x] [586. Customer Placing the Largest Number of Orders](https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/)\
[x] [610. Triangle Judgement](https://leetcode.com/problems/triangle-judgement/)\
[x] [577. Employee Bonus](https://leetcode.com/problems/employee-bonus/)

---
### Day 68: Monday, June 3, 2019

[x] [607. Sales Person](https://leetcode.com/problems/sales-person/)\
[x] [183. Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/)

---
### Day 69: Tuesday, June 4, 2019

[x] [619. Biggest Single Number](https://leetcode.com/problems/biggest-single-number/)\
[x] [175. Combine Two Tables](https://leetcode.com/problems/combine-two-tables/)\
[x] [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/)\
[x] [177. Nth Highest Salary](https://leetcode.com/problems/nth-highest-salary/)

---
### Day 70: Wednesday, June 5, 2019

[x] [178. Rank Scores](https://leetcode.com/problems/rank-scores/)\
[x] [185. Department Top Three Salaries](https://leetcode.com/problems/department-top-three-salaries/)\
[x] [184. Department Highest Salary](https://leetcode.com/problems/department-highest-salary/)

---
### Day 71: Thursday, June 6, 2019

[x] [1064. Fixed Point](https://leetcode.com/problems/fixed-point/)

---
### Day 72: Friday, June 7, 2019

None

---
### Day 73: Saturday, June 8, 2019

None

---
### Day 74: Sunday, June 9, 2019

None

---
### Day 75: Monday, June 10, 2019

[x] [708. Insert into a Cyclic Sorted List](https://leetcode.com/problems/insert-into-a-cyclic-sorted-list/)

---
### Day 76: Tuesday, June 11, 2019

None

---
### Day 77: Wednesday, June 12, 2019

[x] [1075. Project Employees I](https://leetcode.com/problems/project-employees-i/)

### Restart

---
### Day 1: Thursday, February 5, 2020

[ ] [TBD]

---
### Day 2: Friday, February 6, 2020

[ ] [TBD]

### TODO

[ ] [46. Permutations](https://leetcode.com/problems/permutations/)\
[ ] [78. Subsets](https://leetcode.com/problems/subsets/)\
[ ] [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)\
[ ] [92. Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/)\
[ ] [341. Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/)\
[ ] [160. Intersection of Two Linked Lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)\
[ ] [621. Task Scheduler](https://leetcode.com/problems/task-scheduler/)\
[ ] [102. Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)\
[ ] [297. Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)\
[ ] [267. Palindrome Permutation II](https://leetcode.com/problems/palindrome-permutation-ii/)\
[ ] [386. Lexicographical Numbers](https://leetcode.com/problems/lexicographical-numbers/)\
[ ] [1031. Maximum Sum of Two Non-Overlapping Subarrays](https://leetcode.com/problems/maximum-sum-of-two-non-overlapping-subarrays/)\
[ ] [1032. Stream of Characters](https://leetcode.com/problems/stream-of-characters/)\
[ ] [41. First Missing Positive](https://leetcode.com/problems/first-missing-positive/)\
[ ] [5047. Minimum Score Triangulation of Polygon](https://leetcode.com/contest/weekly-contest-135/problems/minimum-score-triangulation-of-polygon/)\
[ ] [5049. Moving Stones Until Consecutive II](https://leetcode.com/contest/weekly-contest-135/problems/moving-stones-until-consecutive-ii/)\
[ ] [114. Flatten Binary Tree to Linked List](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
