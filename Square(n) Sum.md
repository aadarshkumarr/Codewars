# CodeWars JavaScript Solutions

---

## Square(n) Sum

Complete the square sum function so that it squares each number passed into it and then sums the results together.

For example, for [1, 2, 2] it should return 9 because 1^2 + 2^2 + 2^2 = 9.

---

### Given Code


```javascript
function squareSum(numbers){
}
```

---

### Solution


```javascript
function squareSum(numbers){
let res = 0;
  for( let i =0; i < numbers.length; i++){
    res = res + numbers[i] ** 2;
  }
    return res
  }
```


---


[See on CodeWars.com](https://www.codewars.com/kata/515e271a311df0350d00000f/train/javascript)