# lab1
# Vowel Count

**Difficulty Level: Easy**

Link to the problem: [Vowel Count - Codewars](https://www.codewars.com/kata/54ff3102c1bad923760001f3)

## Problem Description

Write a function that takes a string and returns the number of vowels (letters 'a', 'e', 'i', 'o', and 'u') in the string.

## Example

```javascript
function getCount(str) {
  let vowelsCount = 0;
  const vowels = ['a', 'e', 'i', 'o', 'u'];

  for (let char of str) {
    if (vowels.includes(char)) {
      vowelsCount++;
    }
  }

  return vowelsCount;
}

console.log(getCount('hello')); // 2
