# Andrei Kapiankou
## Frontend developer

***
![avatar](https://github.com/Maedayel/rsschool-cv/blob/gh-pages/Avatar.jpg)

### Contact info
* Email - maedayel@gmail.com
* Discord - Pe4enegek#6524
* Github - https://github.com/Maedayel

***

### About me

I started my career as a developer on January 3rd, 2022.
For 1 year I was engaged in advertising and website promotion in Yandex and Google.
At the current job, I optimized some of the tasks.

I think I've always liked development, but I've been doing related things.

***

### Skills

* HTML and CSS
* Javascript
* Git, Github 

***
### Code examples
#### Combine objects

Your task is to write a function that takes two or more objects and returns a new object which combines all the input objects.

All input object properties will have only numeric values. Objects are combined together so that the values of matching keys are added together.
```
const objA = { a: 10, b: 20, c: 30 }
const objB = { a: 3, c: 6, d: 3 }
combine(objA, objB) // Returns { a: 13, b: 20, c: 36, d: 3 }
``` 
The combine function should be a good citizen, so should not mutate the input objects.

```
function combine(...arg) {
  let comboObj = {};
    for (let i = 0; i < arg.length; i++) {
    for (const key in arg[i]) {
      if (!comboObj[key]) {
        comboObj[key] = arg[i][key]
      } else {
        comboObj[key] += arg[i][key]
      }
    }
      }
return comboObj;
}
``` 
***

### Education

* Completed HTML and CSS courses almost 3 years ago
* I am taking the course "Full JavaScript + React course - from scratch to the result" on the Udemy platform

***

### My project
[cv.md](https://github.com/Maedayel/rsschool-cv/edit/gh-pages/cv.md)

***

### Languages

* __Russian__ - native speaker
* __English__ - A1 or A2. 



