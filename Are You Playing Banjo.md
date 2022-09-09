# CodeWars JavaScript Solutions

---

## Are You Playing Banjo?

Create a function which answers the question "Are you playing banjo?".
If your name starts with the letter "R" or lower case "r", you are playing banjo!

The function takes a name as its only argument, and returns one of the following strings:

name + " plays banjo" 
name + " does not play banjo"

---

### Given Code


```javascript
function areYouPlayingBanjo(name) {
  // Implement me
  return name;
}
```

---

### Solution


```javascript
function areYouPlayingBanjo(name) {
  // Implement me
  let phrase = ' plays banjo' ;
  let phrase2 = ' does not play banjo' ;
  if ( name[0] == "R" || name[0] == "r" )
  return (name + phrase);
  else
    return (name + phrase2);
}
```


---


[See on CodeWars.com](https://www.codewars.com/)