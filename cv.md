######  rsschool-cv
---
>**Dmitrii Ershov**
**Junior Frontend Developer**
---
>**Contacts**

|               |       details              |
| ------------- | -------------------------- |
| *Phone*       | +7 (927) 240 15 54         |
| *email*       | DmitriiErshovRu@gmail.com  |
| *telegram*    | @DAErshov                  |
| *Discord*     | Dmitrii_Ershov#4139        |
| *github*      | DmitriiErshov              |

---
>**About myself:**
My name is Dmitry, and at the age of 33 I realized that I wanted to change my job as an engineer. In the summer of 2021. I tried to write code for the first time. I am currently learning to be a JS developer.
---



>**Skills and Proficiency:** 

|                  |             |
| ---------------- | ----------- |
| *Html*           |  (basic)    |
| *CSS*            |  (basic)    |
| *Photoshop*      |  (basic)    |

---
>**Code example:** 
```
        function app() {
        const buttons = document.querySelectorAll('.button');
        const cards = document.querySelectorAll('.portfolio__item');
        
        function filter(category, items) {
            items.forEach((item) => {
                const isItemFiltered = !item.classList.contains(category)
                const isShowAll = category.toLowerCase() === 'all'
                if (isItemFiltered && !isShowAll) {
                    item.classList.add('hide')
                } else {
                    item.classList.remove('hide')
                }
            })
        }

        buttons.forEach((button) => {
            button.addEventListener('click', () => {
                const currentCategory = button.dataset.filter
                filter(currentCategory, cards)
            })
        })
        }
```

---
>**Courses:**  
RS school JS / FRONT-END. STAGE 0
---
>**Languages:**

|       lang       |     lvl     |
| ---------------- | ----------- |
| *English*        |  (basic)    |
| *Russian*        |  (basic)    |
---