---
title: head
tags: array,beginner
---

Returns the head of a list.

Use `arr[0]` to return the first element of the passed array.

```js
const head = arr => arr && arr.length ? arr[0] : undefined;
```

```js
head([1, 2, 3]); // 1
head(); // undefined
head([]); // undefined
head(null); // undefined
head(undefined); // undefined
if (head(arr) === undefined) { 
// do nothing, or something else
}
```
