# LeetCode (30 Days of JavaScript)

## About the problem
- *Problem Number* : 2620
- *Problem Name* :  [Counter](https://leetcode.com/problems/counter/)
- *Problem difficulty* : Easy 🟢
- *Programming language used* - JavaScript

## Problem

Given an integer n, return a counter function. This counter function initially returns n and then returns 1 more than the previous value every subsequent time it is called (n, n + 1, n + 2, etc).
 

Example 1:
```cpp
Input: 
n = 10 
["call","call","call"]
Output: [10,11,12]
Explanation: 
counter() = 10 // The first time counter() is called, it returns n.
counter() = 11 // Returns 1 more than the previous time.
counter() = 12 // Returns 1 more than the previous time.
```
The function returned by createHelloWorld should always return "Hello World".`

Example 2:
```cpp
Input: args = [{},null,42]
Output: "Hello World"
Explanation:
const f = createHelloWorld();
f({}, null, 42); // "Hello World"
```
Any arguments could be passed to the function but it should still always return "Hello World".
 

Constraints:
`0 <= args.length <= 10`


## Approach Explanation
Solved using high order function 👍

### If you have suggestions for improvement or would like to contribute to this solution, feel free to create a pull request. 🙌😇
