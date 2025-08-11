# 📚 DSA Interview Questions for TrialX — (Easy → Medium)

A curated set of **29** DSA problems. Each entry: **Title · Level · Problem · Examples**.

---

## 1. Balanced Binary Tree

**Level:** Easy


**Problem:**

Given binary tree, determine if it is height-balanced (depths of two subtrees of every node never differ by more than 1).


**Examples:**

```
Input: [3,9,20,null,null,15,7]
Output: true

Input: [1,2,2,3,3,null,null,4,4]
Output: false

Input: []
Output: true

Input: [1]
Output: true
```

---


## 2. Binary Search (Classic)

**Level:** Easy


**Problem:**

Given sorted array `nums` and `target`, return the index of `target` or `-1` if not found. (0-based)


**Examples:**

```
Input: nums = [1,2,3,4,5], target = 3
Output: 2

Input: nums = [1,2,3,4,5], target = 6
Output: -1

Input: nums = [], target = 1
Output: -1

Input: nums = [2], target = 2
Output: 0
```

---


## 3. Check for Anagram

**Level:** Easy


**Problem:**

Given two strings `s` and `t`, return true if `t` is an anagram of `s`, otherwise false.


**Examples:**

```
Input: s = "anagram", t = "nagaram"
Output: true

Input: s = "rat", t = "car"
Output: false

Input: s = "listen", t = "silent"
Output: true

Input: s = "aabb", t = "abab"
Output: true
```

---


## 4. Contains Duplicate

**Level:** Easy


**Problem:**

Given array `nums`, return true if any value appears at least twice, else false.


**Examples:**

```
Input: [1,2,3,1]
Output: true

Input: [1,2,3,4]
Output: false

Input: []
Output: false

Input: [2,2,2,2]
Output: true
```

---


## 5. First Unique Character in String

**Level:** Easy


**Problem:**

Given a string `s`, return the first non-repeating character. If none exists, return `-1`.


**Examples:**

```
Input: "apple"
Output: 'a'

Input: "aabb"
Output: -1

Input: "swiss"
Output: 'w'

Input: "leetcode"
Output: 'l'
```

---


## 6. Lowest Common Ancestor of BST

**Level:** Easy / Medium


**Problem:**

Given a binary search tree and two nodes, return their lowest common ancestor (LCA).


**Examples:**

```
Input: root = [6,2,8,0,4,7,9,null,null,3,5], p=2, q=8
Output: 6

Input: root = [6,2,8,0,4,7,9,null,null,3,5], p=2, q=4
Output: 2

Input: root = [2,1], p=2, q=1
Output: 2

Input: root = [5,3,6,2,4], p=2, q=4
Output: 3
```

---


## 7. Move Zeroes

**Level:** Easy


**Problem:**

Given an integer array `nums`, move all `0`s to the end while maintaining the relative order of the non-zero elements. Do it in-place.


**Examples:**

```
Input: [0,1,0,3,12]
Output: [1,3,12,0,0]

Input: [1,0]
Output: [1,0]

Input: [0,0,1]
Output: [1,0,0]

Input: [4,2,4,0,0,3]
Output: [4,2,4,3,0,0]
```

---


## 8. Sliding Window Sum of Size K

**Level:** Easy


**Problem:**

Given an array `nums` and an integer `k`, return the sum of each contiguous subarray of length `k`. If `k` is greater than the length of the array, return `-1`.


**Examples:**

```
Input: nums = [1, 3, 2, 5, 4], k = 3
Output: [6, 10, 11]

Input: nums = [5, 5, 5, 5], k = 2
Output: [10, 10, 10]

Input: nums = [9, 3, 1, 7, 2, 6], k = 3
Output: [13, 11, 10, 15]

Input: nums = [2, 1, 4], k = 4
Output: -1
```

---


## 9. Two Sum (1-based indices)

**Level:** Easy


**Problem:**

Given an array `arr` and a target `target`, return the **1-based indices** of the two numbers that add up to `target`. Assume exactly one solution exists.


**Examples:**

```
Input: arr = [2,7,11,15], target = 9
Output: [1,2]

Input: arr = [1,2,3,4,6], target = 10
Output: [4,5]

Input: arr = [3,2,4], target = 6
Output: [2,3]

Input: arr = [1,5,3,7], target = 8
Output: [1,4]
```

---


## 10. Valid Parentheses

**Level:** Easy


**Problem:**

Given a string `s` containing only '(', ')', '{', '}', '[' and ']', determine if it is valid (correct matching and ordering).


**Examples:**

```
Input: "()"
Output: true

Input: "(]"
Output: false

Input: "{[]}"
Output: true

Input: "([)]"
Output: false
```

---


## 11. Clone Graph

**Level:** Medium


**Problem:**

Given a reference of a node in a connected undirected graph, return a deep copy (clone) of the graph. Each node contains a val and list of neighbors.


**Examples:**

```
Input: Node 1 connected to Node 2 (1--2)
Output: clone graph with same connections

Input: Single node with no neighbors
Output: clone node with no neighbors

Input: Triangle (1--2--3--1)
Output: cloned triangle

Input: null input
Output: null
```

---


## 12. Coin Change (Minimum Coins)

**Level:** Medium


**Problem:**

Given coins of different denominations and a total amount, compute the fewest number of coins that you need to make up that amount. If not possible, return -1.


**Examples:**

```
Input: coins = [1,2,5], amount = 11
Output: 3  // 5+5+1

Input: coins = [2], amount = 3
Output: -1

Input: coins = [1], amount = 0
Output: 0

Input: coins = [1,5,10], amount = 14
Output: 5  // 10+1+1+1+1
```

---


## 13. First Non-Repeating Character in Each Substring of Length K

**Level:** Medium


**Problem:**

Given a string `s` and an integer `k`, consider all substrings of length `k` in `s`. For each substring, return its first non-repeating character. If no such character exists, return `-1`. If `k` > `len(s)`, return `-1`.


**Examples:**

```
Input: s = "abcabcbb", k = 3
Substrings: ["abc","bca","cab","abc","bcb","cbb"]
Output: ['a','b','c','a','c','c']

Input: s = "abc", k = 4
Output: -1

Input: s = "aaaa", k = 2
Substrings: ['aa','aa','aa']
Output: [-1,-1,-1]

Input: s = "abac", k = 3
Substrings: ['aba','bac']
Output: ['b','b']
```

---


## 14. Group Anagrams

**Level:** Medium


**Problem:**

Given array of strings, group anagrams together. Return list of groups.


**Examples:**

```
Input: ["eat","tea","tan","ate","nat","bat"]
Output: [["eat","tea","ate"],["tan","nat"],["bat"]]

Input: [""]
Output: [[""]]

Input: ["a"]
Output: [["a"]]

Input: ["ab","ba","abc","cab"]
Output: [["ab","ba"],["abc","cab"]]
```

---


## 15. Kth Largest Element in an Array

**Level:** Medium


**Problem:**

Given array `nums` and integer `k`, return the `k`-th largest element in the array.


**Examples:**

```
Input: nums = [3,2,1,5,6,4], k = 2
Output: 5

Input: nums = [3,2,3,1,2,4,5,5,6], k = 4
Output: 4

Input: nums = [1], k = 1
Output: 1

Input: nums = [7,7,7,7], k = 1
Output: 7
```

---


## 16. Kth Largest Element in an Array (continued)

**Level:** Medium


**Problem:**

Given array `nums` and integer `k`, return the `k`-th largest element in the array.


**Examples:**

```
Input: nums = [3,2,1,5,6,4], k = 2
Output: 5

Input: nums = [3,2,3,1,2,4,5,5,6], k = 4
Output: 4

Input: nums = [1], k = 1
Output: 1

Input: nums = [7,7,7,7], k = 1
Output: 7
```

---


## 17. Longest Increasing Subsequence (LIS)

**Level:** Medium


**Problem:**

Given integer array `nums`, return length of longest strictly increasing subsequence.


**Examples:**

```
Input: [10,9,2,5,3,7,101,18]
Output: 4  // [2,3,7,101]

Input: [0,1,0,3,2,3]
Output: 4  // [0,1,2,3]

Input: [7,7,7,7]
Output: 1

Input: [1,2,3,4]
Output: 4
```

---


## 18. Longest Substring Without Repeating Characters

**Level:** Medium


**Problem:**

Given string `s`, find the length of the longest substring without repeating characters.


**Examples:**

```
Input: s = "abcabcbb"
Output: 3  // "abc"

Input: s = "bbbbb"
Output: 1  // "b"

Input: s = "pwwkew"
Output: 3  // "wke"

Input: s = "dvdf"
Output: 3  // "vdf"
```

---


## 19. Maximum Product Subarray

**Level:** Medium


**Problem:**

Given an integer array `nums`, find the contiguous subarray within an array (containing at least one number) which has the largest product and return the product.


**Examples:**

```
Input: [2,3,-2,4]
Output: 6  // [2,3]

Input: [-2,0,-1]
Output: 0

Input: [-2,3,-4]
Output: 24  // [-2,3,-4] => 24

Input: [0,2]
Output: 2
```

---


## 20. Maximum Subarray (Kadane’s Algorithm)

**Level:** Medium


**Problem:**

Given integer array `nums`, find the contiguous subarray with the largest sum and return that sum.


**Examples:**

```
Input: nums = [-2,1,-3,4,-1,2,1,-5,4]
Output: 6  // subarray [4,-1,2,1]

Input: nums = [1]
Output: 1

Input: nums = [-1,-2,-3]
Output: -1

Input: nums = [5,-1,5]
Output: 9
```

---


## 21. Merge Intervals

**Level:** Medium


**Problem:**

Given a collection of intervals, merge all overlapping intervals and return the resulting list.


**Examples:**

```
Input: [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]

Input: [[1,4],[4,5]]
Output: [[1,5]]

Input: [[1,4],[2,3]]
Output: [[1,4]]

Input: [[6,8],[1,9],[2,4],[4,7]]
Output: [[1,9]]
```

---


## 22. Number of Islands (DFS/BFS)

**Level:** Medium


**Problem:**

Given a grid of '1's (land) and '0's (water), count islands. An island is surrounded by water and is formed by connecting adjacent lands horizontally or vertically.


**Examples:**

```
Input:
[
 ["1","1","0","0","0"],
 ["1","1","0","0","0"],
 ["0","0","1","0","0"],
 ["0","0","0","1","1"]
]
Output: 3

Input:
[
 ["1","1"],
 ["1","1"]
]
Output: 1

Input:
[
 ["0","0"],
 ["0","0"]
]
Output: 0

Input:
[
 ["1","0","1"],
 ["0","1","0"],
 ["1","0","1"]
]
Output: 5
```

---


## 23. Palindrome Partitioning (Minimum Cuts)

**Level:** Medium


**Problem:**

Given string `s`, partition `s` such that every substring is a palindrome. Return minimum cuts needed.


**Examples:**

```
Input: "aab"
Output: 1  // "aa"|"b"

Input: "a"
Output: 0

Input: "ab"
Output: 1  // "a"|"b"

Input: "racecar"
Output: 0
```

---


## 24. Product of Array Except Self

**Level:** Medium


**Problem:**

Given array `nums`, return array `answer` where `answer[i]` is product of all elements except `nums[i]`. Do this without division and in O(n).


**Examples:**

```
Input: [1,2,3,4]
Output: [24,12,8,6]

Input: [2,3,4,5]
Output: [60,40,30,24]

Input: [1,0,3,4]
Output: [0,12,0,0]

Input: [-1,1,0,-3,3]
Output: [0,0,9,0,0]
```

---


## 25. Search in Rotated Sorted Array

**Level:** Medium


**Problem:**

Given a sorted array that has been rotated at an unknown pivot, and a target value, return its index or `-1` if not found. (0-based)


**Examples:**

```
Input: nums = [4,5,6,7,0,1,2], target = 0
Output: 4

Input: nums = [4,5,6,7,0,1,2], target = 3
Output: -1

Input: nums = [1], target = 1
Output: 0

Input: nums = [6,7,1,2,3,4,5], target = 3
Output: 4
```

---


## 26. Subarray Sum Equals K

**Level:** Medium


**Problem:**

Given array `nums` and integer `k`, return the total number of continuous subarrays whose sum equals `k`.


**Examples:**

```
Input: nums = [1,1,1], k = 2
Output: 2

Input: nums = [1,2,3], k = 3
Output: 2  // [1,2] and [3]

Input: nums = [1,-1,0], k = 0
Output: 3  // [1,-1], [1,-1,0], [0]

Input: nums = [2,2,2], k = 4
Output: 2  // [2,2] (two subarrays)
```

---


## 27. Top K Frequent Elements

**Level:** Medium


**Problem:**

Given array `nums` and integer `k`, return the `k` most frequent elements.


**Examples:**

```
Input: nums = [1,1,1,2,2,3], k = 2
Output: [1,2]

Input: nums = [1], k = 1
Output: [1]

Input: nums = [4,1,-1,2,-1,2,3], k = 2
Output: [-1,2]

Input: nums = [1,2,3,4], k = 2
Output: [1,2]
```

---


## 28. Top K Frequent Elements (continued)

**Level:** Medium


**Problem:**

Given array `nums` and integer `k`, return the `k` most frequent elements.


**Examples:**

```
Input: nums = [1,1,1,2,2,3], k = 2
Output: [1,2]

Input: nums = [1], k = 1
Output: [1]

Input: nums = [4,1,-1,2,-1,2,3], k = 2
Output: [-1,2]

Input: nums = [1,2,3,4], k = 2
Output: [1,2]
```

---


## 29. Word Break

**Level:** Medium


**Problem:**

Given string `s` and a dictionary of strings `wordDict`, return true if `s` can be segmented into space-separated sequence of dictionary words.


**Examples:**

```
Input: s = "leetcode", wordDict = ["leet","code"]
Output: true

Input: s = "applepenapple", wordDict = ["apple","pen"]
Output: true

Input: s = "catsandog", wordDict = ["cats","dog","sand","and","cat"]
Output: false

Input: s = "cars", wordDict = ["car","ca","rs"]
Output: true
```

---
