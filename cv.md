# Kikodze Viktor

### Contacts:
* **telegram:** @vitland
* **email:** vkikodze@gmail.com
* **discord:** vitland#8893

---

I've always wanted to be a developer, but circumstances did not allow me to take it seriously. Now I decided to make my dream a reality. My goal is to get enough knowledge and practice to get a job.

---

### Skills and Proficiency:

* HTML, CSS
* JavaScript (ES6+)
* Git, GitHub
* BEM
* Figma
* VSCode, WebStorm

---

### Code example:

```javascript
function numberOfPairs(gloves)
{
  let pairs =  gloves.reduce((acc, cur) => {
    acc[cur] = (acc[cur] || 0) + 1
    return acc
  } , {})
  
  return Object.values(pairs).reduce((acc, cur) => {
    return cur % 2 === 0 
      ? acc += cur / 2 
      : acc += (cur - 1) / 2, 0
  })
}
```

---

### Education
* **2022-2023 Yandex Practicum** Web-development
* **2008-2012 Moscow Pedagogical State University** Language interpretation and translation

---

### Language
* Russian - native
* English - C1