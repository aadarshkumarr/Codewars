# CodeWars JavaScript Solutions

---

## Grasshopper - If/else syntax debug

If/else syntax debug
While making a game, your partner, Greg, decided to create a function to check if the user is still alive called checkAlive/CheckAlive/check_alive. Unfortunately, Greg made some errors while creating the function.

checkAlive/CheckAlive/check_alive should return true if the player's health is greater than 0 or false if it is 0 or below.

The function receives one parameter health which will always be a whole number between -10 and 10.



---

### Given Code


```javascript
function checkAlive (health) {
  if () {
    health < 0
    return false
  } else () {
    return true
  }
}
```

---

### Solution


```javascript
function checkAlive(health) {
  if (health <= 0) {
    return false;
  } 
  else {
    return true;
  }
}
```

---

[See on CodeWars.com](https://www.codewars.com/kata/57089707fe2d01529f00024a)