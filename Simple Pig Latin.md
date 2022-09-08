# CodeWars JavaScript Solutions

---

## Simple Pig Latin
Move the first letter of each word to the end of it, then add "ay" to the end of the word. Leave punctuation marks untouched.

Examples
```javascript
pigIt('Pig latin is cool'); // igPay atinlay siay oolcay
pigIt('Hello world !');     // elloHay orldway !
```

---

### Given Code


```javascript
function pigIt(str){
  //Code here
}
```

---

### Solution


```javascript
function pigIt(str){
  //Code here
  str = str.trim().split(/\s{1,}/);
    return str.map(val => {
        if (/^[A-Za-z]+$/.test(val)) {
            return `${val.slice(1)}${val.slice(0, 1)}ay`;
        }
        return val;
    }).join(' ');
}
```


---


[See on CodeWars.com](https://www.codewars.com/kata/520b9d2ad5c005041100000f/train/javascript)