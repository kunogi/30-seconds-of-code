---
title: Random hex color code
tags: math,random,beginner
firstSeen: 2017-12-24T14:39:21+02:00
lastUpdated: 2022-02-25T07:05:18.397Z
---

Generates a random hexadecimal color code.

- Use `Math.random()` to generate a random 24-bit (6 * 4bits) hexadecimal number.
- Convert it to a hexadecimal string and get rid of the leading '0.'.

```js
const randomHexColorCode = () => {
  return '#' + Math.random().toString(16).slice(2, 8);
};
```

```js
randomHexColorCode(); // '#e34155'
```
