# JS tricks 😎

## (1)  Generate 'A' to 'Z' array []

```js
Array.from(new Array(26), (i,id) => String.fromCharCode(id + 'A'.charCodeAt()))
```

Result
```
["A", "B", "C", "D", "E", "F", "G", "H", "I", "J", "K", "L", "M", "N", "O", "P", "Q", "R", "S", "T", "U", "V", "W", "X", "Y", "Z"]
```
