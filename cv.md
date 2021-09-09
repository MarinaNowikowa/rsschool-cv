# Marina Nowikowa

## Junior Frontend Developer
---

## Contact information:

**Phone:** +375336268174
**E-mail:** nowikowamarina0@gmail.com
**Telegram:** @m_nowikowa
---
## About Myself:

I have worked in an international outsourcing company in finance for 7,5 years in the field of finance, so I know what a responsible approach to work, deadlines, teamwork and the importance of working with a Customer are. I finished courses in front-end development. The main thing for me is development and growth in a new profession. 

---
## Skills and Proficiency:

* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code 
* React, Redux
---
## Code example:

**Array Deep Count KATA from CODEWARS:** Array.prototype.length will give you the number of top-level elements in an array. Your task is to create a function deepCount that returns the number of ALL elements within an array, including any within inner-level arrays.

```
function deepCount(a){
   const newArrLength =[]

  function arrayLength(a) {
    newArrLength.push(a.length)
    a.forEach( (el)=>{
      if (Array.isArray(el)) {
        arrayLength(el)
      }
    },
    )
  }

  arrayLength(a)

  return newArrLength.reduce((acc, cur)=> acc+cur)
}
```
---
## Courses:

* TeachmeSkills - "Front-end Developer"
* RS Schools Course «JavaScript/Front-end 2021Q3» (in progress)
---
## Languages:

* English - Intermediate
* German - Upper-Intermediate
