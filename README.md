# Daily-Leetcode-problem-solution11
PROBLEM

You are given two strings s1 and s2 of equal length. A string swap is an operation where you choose two indices in a string (not necessarily different) and swap the characters at these indices.
Return true if it is possible to make both strings equal by performing at most one string swap on exactly one of the strings. Otherwise, return false.

Intuition

The goal is to determine if at most one swap in one of the strings can make s1 equal to s2

Approach

If s1 == s2, they are already equal, so return true.
Find the indices where s1[i] != s2[i].
If there are more than two mismatched indices, return false.
If exactly two mismatches, check if swapping these two characters in s1 makes it equal to s2.
If only one mismatch exists, or more than two, return false.

Complexity

Time complexity:
O(n)

Space complexity:
O(1)
