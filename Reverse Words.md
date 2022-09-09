# CodeWars JavaScript Solutions

---

## Reversed Words

Complete the solution so that it reverses all of the words within the string passed in.

Example(Input --> Output):

"The greatest victory is that which requires no battle" --> "battle no requires which that is victory greatest The"

---

### Given Code


```javascript
function reverseWords(str){
  return str; // reverse those words
}
```

---

### Solution


```javascript
function reverseWords(str){
  return str.split(" ").reverse().join(" ");
}
```


---


[See on CodeWars.com](https://www.codewars.com/kata/51c8991dee245d7ddf00000e/train/javascript)