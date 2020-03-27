# Is Unique LCCI

## Description
```
Implement an algorithm to determine if a string has all unique characters. What if you cannot use additional data structures?
```

## Example
```
Example 1:

Input: s = "leetcode"
Output: false

Example 2:

Input: s = "abc"
Output: true
```
## Solution:
```
/**
 * @param {string} astr
 * @return {boolean}
 */
var isUnique = function(astr) {
    return [...new Set(astr.split(''))].length === astr.length
};
```