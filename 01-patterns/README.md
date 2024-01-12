# Must do Pattern Problems before starting DSA

This contains all the important pattern problems that you must solve before starting DSA.

### Pattern 1

xxxxx
xxxxx
xxxxx
xxxxx
xxxxx

```javascript
function printPattern1(n) {
  let pattern1 = "";
  for (let i = 0; i < n; i++) {
    for (let j = 0; j < n; j++) {
      pattern1 += "*";
    }
    pattern1 += "\n";
  }
  return pattern1;
}

console.log(printPattern1(5));
```
