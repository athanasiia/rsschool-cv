# Anastasiya Haravik
## **Contacts**

*E-mail*: grvkan@gmail.com

*GitHub*: [athanasiia](https://github.com/athanasiia)

---

## **About Me**
Computer science student.
Interested in web development and looking forward to my first working experience.

---

## **Skills**

* HTML5, CSS3
* C++ Basics
* JavaScript Basics
* VS Code, VS
* Git, GitHub

---

## **Code Example**

**Lottery Ticket Kata from Codewars**: 
*Given a lottery ticket, represented by an array of 2-value arrays, you must find out if you've won the jackpot. To do this, you must first count the 'mini-wins' on your ticket. Each subarray has both a string and a number within it. If the character code of any of the characters in the string matches the number, you get a mini win. Once you have counted all of your mini wins, compare that number to the other input provided (win). If your total is more than or equal to (win), return 'Winner!'. Else return 'Loser!'.*

```js
function bingo(ticket, win){
  let miniWins = ticket.reduce((acc, curr) => 
        curr[0].split("").includes(String.fromCharCode(curr[1])) ? acc + 1 : acc, 0);

  return miniWins >= win ? 'Winner!' : 'Loser!';
}
```
---

## **Education**

#### *BELARUSIAN STATE UNIVERSITY OF INFORMATICS AND RADIOELECTRONICS*
Computer science and software engineering, in progress.

---

## **Language**
* English: Upper-intermediate;
* Belarusian: Native;
* Rissian: Native.