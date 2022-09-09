# CodeWars JavaScript Solutions

---

## Beginner Series #1 School Paperwork

Your classmates asked you to copy some paperwork for them. You know that there are 'n' classmates and the paperwork has 'm' pages.

Your task is to calculate how many blank pages do you need. If n < 0 or m < 0 return 0.

Example:
n= 5, m=5: 25
n=-5, m=5:  0

---

### Given Code


```javascript
function paperwork(n, m) {
  
}
```

---

### Solution


```javascript
function paperwork(n, m) {
  
  if ( n > 0 && m > 0)
    return (m*n)
  else
    return 0  
}
```


---


[See on CodeWars.com](https://www.codewars.com/kata/55f9b48403f6b87a7c0000bd/train/javascript)