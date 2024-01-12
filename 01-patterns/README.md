# Must do Pattern Problems before starting DSA

This contains all the important pattern problems that you must solve before starting DSA.

### Pattern 1

xxxxx<br>
xxxxx<br>
xxxxx<br>
xxxxx<br>
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

### Pattern 2

x<br>
xx<br>
xxx<br>
xxxx<br>
xxxxx

```javascript
function printPattern2(n) {
  let pattern2 = "";
  for (let i = 1; i <= n; i++) {
    for (let j = 1; j <= i; j++) {
      pattern2 += "*";
    }
    pattern2 += "\n";
  }
  return pattern2;
}

console.log(printPattern2(5));
```

### Pattern 3

1<br>
12<br>
123<br>
1234<br>
12345

```javascript
function printPattern3(n) {
  let pattern3 = "";
  for (let i = 1; i <= n; i++) {
    for (let j = 1; j <= i; j++) {
      pattern3 += j;
    }
    pattern3 += "\n";
  }
  return pattern3;
}

console.log(printPattern3(5));
```
