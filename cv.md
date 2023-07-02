# Tuyara Grigoreva
### Junior Frontend Developer

---

### Contact information:

**E-mail:** tuyagrig@gmail.com<br>
**Telegram:** @veganwaldon<br>

---

### About:

I’m interested in Web Development, because I'm passionate about frontend.<br>
I enjoy learning and gaining skills and would like to be a well-qualified Frontend Developer.<br>

---

### Skills and Proficiency:

- HTML5, CSS3
- JavaScript, TypeScript
- Git, Github/Gitlab/Bitbucket, Jira, Confluence
- VS Code, IntelliJ IDEA, WebStorm
- Figma
- React
- Redux
- Webpack, Vite
- npm, yarn
- AntDesign, Material UI

---

### Code example:

**Peak array index KATA from CODEWARS:**
*Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```javascript
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

### Education:

- Bauman Moscow State Technical University, Master of Computer Science
- School 21 (Ecole 42), Programming Full Course

### Courses:

- React Pizza 2.0
- RS School «JavaScript/Front-end. Stage 0» (in progress)

---

### Languages:

- English \- Upper-intermediate
- Russian \- Fluent
- Sakha \- Native