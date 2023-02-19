# leetCode-03
# twoSum JavaScript function

This is a JavaScript function that takes an array of integers and a target integer as input, and returns an array of two indices that add up to the target integer.

The `twoSum` function uses `Array.forEach()` to loop over each element of the input array, calculates the complement (the difference between the target and the current element), and searches for the complement in the array using `Array.indexOf()`. If the complement is found, the function adds the current index and the complement index to the result array. The function returns an empty array if no pair of indices add up to the target integer.

Example usage:

```javascript
const nums = [2, 7, 11, 15];
const target = 9;
const result = twoSum(nums, target);
console.log(result); // should output [0, 1]


