

# LeetCode 1 - Two Sum

**Difficulty:** Easy

**Topic:** Array, HashMap

**Language:** Python

## Problem Description

Given an array of integers nums and an integer target,
return the indices of the two numbers such that they add
up to target.

You may assume that each input has exactly one solution,
and you may not use the same element twice.

You can return the answer in any order.

## Example 1

**Input:**
nums = [2,7,11,15], target = 9

**Output:**
[0,1]

**Explanation:**
nums[0] + nums[1] = 2 + 7 = 9.

## Example 2

**Input:**
nums = [3,2,4], target = 6

**Output:**
[1,2]

## Example 3

**Input:**
nums = [3,3], target = 6

**Output:**
[0,1]

## Constraints

- 2 <= nums.length <= 10^4
- -10^9 <= nums[i] <= 10^9
- -10^9 <= target <= 10^9
- Only one valid answer exists.

## Approach: HashMap

1. Create an empty dictionary.
2. Iterate through the array.
3. Calculate difference = target - current number.
4. Check whether difference exists in dictionary.
5. If found, return both indices.
6. Otherwise, store current number and index.

## Python Solution

See: [001_Two_Sum.py](001_Two_Sum.py)

## Complexity Analysis

**Time Complexity:** O(n)

**Space Complexity:** O(n)

## LeetCode Link

https://leetcode.com/problems/two-sum/
