**Viktoria Berenshtein.**

![Image text](https://github.com/VikelBerya/codewars-solves/blob/main/TalUcSCRWaE.jpg)  

Сontacts: Email: vikel-rostov@mail.ru, Discord Name: Viktoria Berya @VikelBerya.


At the moment, my goal is to develop in front-end development, because I am very interested in this area. 
Among my strengths, I can single out sociability, responsibility, developed emotional intelligence and creativity.
In 2020, I won a cash grant from my university to organize my own project aimed at teaching first-year students in soft skills, which was subsequently successfully implemented.
I'm currently learning JavaScript. Example of a solved problem from Codewars (Square Every Digit):

```
function numToSquare(num) {
    let array = [];
    let power = " ";
    while (num >= 1) {
        array.push(Math.trunc(num % 10));
        num = num / 10;
    }
    array.reverse();
    for (let i = 0; i < array.length; i++) {
        power = power + " " + Math.pow(array[i], 2);
    }
    return parseInt(power.split(' ').join(''), 10);
}

let num = 9119;
console.log(numToSquare(num));
```
I have no work experience.

I am a third-year student of SPBPU in the direction of system analysis.

English Level B1+.
