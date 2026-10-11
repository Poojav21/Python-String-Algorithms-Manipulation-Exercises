# Define the content of our README.md documenting the brute-force string algorithms
readme_content = """# Python String Algorithms (Brute-Force Implementations)

This repository contains essential string manipulation exercises implemented using intuitive **brute-force approaches**. These solutions are highly educational, serving as a great foundation for understanding string properties, search patterns, and index manipulation before optimizing with more advanced techniques (like Sliding Window, Two-Pointers, or Dynamic Programming).

## Table of Contents
1. [Basic String Traversal](#1-basic-string-traversal)
2. [Permutations with Repetition](#2-permutations-with-repetition)
3. [Unique Pairs (Combinations)](#3-unique-pairs-combinations)
4. [Substring Generation](#4-substring-generation)
5. [Vowel Counting](#5-vowel-counting)
6. [Palindrome Verification](#6-palindrome-verification)
7. [Palindromic Substrings](#7-palindromic-substrings)
8. [Longest Substring Without Repeating Characters](#8-longest-substring-without-repeating-characters)

---

## Summary of Algorithms

### 1. Basic String Traversal
* **Description:** Iterating over a string using index-based tracking.
* **Time Complexity:** $O(N)$

### 2. Permutations with Repetition
* **Description:** Generates all possible 2-character permutations from a set of characters.
* **Approach:** Nested loop iteration yielding $N^2$ pairs.
* **Time Complexity:** $O(N^2)$

### 3. Unique Pairs (Combinations)
* **Description:** Extracts pairs without repetition, ensuring order is preserved.
* **Approach:** Two-pointer indices where the second pointer starts at `i + 1`.
* **Time Complexity:** $O(N^2)$

### 4. Substring Generation
* **Description:** Enumerates every possible contiguous segment of the string.
* **Approach:** Slicing from index `i` to `j` across all indices.
* **Time Complexity:** $O(N^3)$ (due to $O(N^2)$ slices and $O(N)$ string copying)

### 5. Vowel Counting
* **Description:** Linear check to find vowels within a text block.
* **Time Complexity:** $O(N)$

### 6. Palindrome Verification
* **Description:** Verifies if a string reads the same forwards and backwards.
* **Approach:** Compares matching indices from outside boundaries inward.
* **Time Complexity:** $O(N)$

### 7. Palindromic Substrings
* **Description:** Finds substrings that are valid palindromes (and extracts the longest one).
* **Approach:** Nested check checking every generated substring.
* **Time Complexity:** $O(N^3)$ brute-force check.

### 8. Longest Substring Without Repeating Characters
* **Description:** Finds the length of the longest contiguous segment with unique elements.
* **Approach:** Checks uniqueness on all substrings using `set()` conversion.
* **Time Complexity:** $O(N^3)$ brute-force check.

---

## Purpose
This codebase demonstrates how to write clean, easily-readable Python solutions as initial algorithmic baselines for technical interviews.
"""

