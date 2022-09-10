# CodeWars JavaScript Solutions

---

## Find the next perfect square!

You might know some pretty large perfect squares. But what about the NEXT one?

Complete the findNextSquare method that finds the next integral perfect square after the one passed as a parameter. Recall that an integral perfect square is an integer n such that sqrt(n) is also an integer.

If the parameter is itself not a perfect square then -1 should be returned. You may assume the parameter is non-negative.

Examples:(Input --> Output)

```javascript
121 --> 144
625 --> 676
114 --> -1 since 114 is not a perfect square
```

---

### Given Code


```javascript
function findNextSquare(sq) {
  // Return the next square if sq is a perfect square, -1 otherwise
  return -1;  
}
```

---

### Solution


```javascript
function findNextSquare(sq) {
  // Return the next square if sq is a perfect square, -1 otherwise
  let n1;
  let n2;
  if(Math.sqrt(sq)%1 === 0){
    n1 = Math.sqrt(sq);
    n2 = n1+1
    return n2**2
  }
  else{
    return -1;
    }
}
```


---


[See on CodeWars.com]()