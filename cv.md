## ALIAKSANDR ANDREICHUK

#### Junior Frontend Developer

---

### Contacts

![phone](./icons/phone.png)+375 33 681 50 59
![email](./icons/gmail.png) coldlycalculatedsoul@gmail.com
![skype](./icons/skype.png) live:.cid.5692a38b347e856
![discord](./icons/discord.png) peregreenus

### About Myself

All my life I often had to learn and master new things from scratch. Whether it is a full-time profession or a separate skill, I quickly manage to adapt to new conditions and do my job and my goals well.

So I mastered silk-screen printing and a programmable machine for making three-dimensional stickers in one of the printing houses of Gomel, the position of a software engineer in the Education Department of the city of Mozyr, and much more, which I had never encountered before. I approach any work creatively, I focus on business and get carried away with the process, not being afraid of routine and monotony. I consider courage, creativity and responsibility as my main advantages.

I am interested in web development not only because it is a popular and promising area in IT, but also because programming, and in particular web development, is a combination of creativity and the exact sciences. This is the best opportunity to develop a creative personality and the best opportunity to build a career in today's technological world.

### Education

**MOZYR STATE PEDAGOGICAL UNIVERSITY NAMED AFTER I.P.SHAMYAKIN**
_Philological department
***Years:*** 2013 - 2018
***Specialization:*** Russian language and literature, Bachelor's degree_

**SUKHOI STATE TECHNICAL UNIVERSITY OF GOMEL**
_Upgrading and Retraining Institute
***Years:*** 2018 - 2020
***Specialization:*** Web design and computer graphics, Web designer-programmer_

### Skills

- HTML
- CSS/SCSS
- Git/GitHub
- JavaScript

### Courses

| Name                              | Sponsor                                    | Duration            |
| --------------------------------- | ------------------------------------------ | ------------------- |
| Web design and computer graphics  | SUKHOI STATE TECHNICAL UNIVERSITY OF GOMEL | 2018 - 2020         |
| JavaScript Development (Training) | EPAM                                       | February - May 2022 |

### Languages

- English (Pre-Intermediate)
- Russian (native)

### Code Example

I would like for you to write me a function that, when given a number n (n >= 1 ), returns the nth number in the Fibonacci Sequence.

For example:

```JavaScript
   nthFibo(4) == 2
```

Because 2 is the 4th number in the Fibonacci Sequence.

For reference, the first two numbers in the Fibonacci sequence are 0 and 1, and each subsequent number is the sum of the previous two.

**_Solution:_**

```JavaScript
function nthFibo(n) {
  const arr = [0, 1];
  for (let i = 2; i <= n; i++) {
    arr.push(arr[i - 1] + arr[i - 2]);
  }

  return arr[n - 1];
}
```
