# Panteley Zhilkin

***

## Junior Frontend Developer

---

## Contact information:

**Phone:** +7 (999) 991-95-02
**E-mail:** zhilkin@vk.com
**Telegram:** @zhilkin

---

## Briefly About Myself:

By education — Bachelor of Theoretical Physics.

In Internet marketing, he grew from Jun to group leader in 2 years.

Aims to repeat this path in IT.

---

## Skills and Proficiency:

* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* Adobe Photoshop, Figma
* VS Code

---

## Code example:

**Peak array index KATA from CODEWARS:** *Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

---

## Courses:

* JS course on Code Basics from Hexlet
* JavaScript Manual on learnjavascript.ru (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

---

## Languages:

* English - Intermediate/Upper-intermediate