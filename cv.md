## James Holden

* email: dm25an22@gmail.com
* phone: +48 123 456 789

Recent computer science graduate with a passion for developing scalable web applications and
working across the full stack. I’ve built two web apps from the ground-up using React, Node, and
MongoDB.

### Technical skills
1. JavaScript
2. TypeScript
3. React
4. Redux (Thunk)
5. Next.js (SSR)
6. MongoDB
7. NodeJS
8. Express
9. REST
10. Jest/Enzyme
11. GIT
12. Webpack
13. HTML/CSS

### Selection Sort algorithm

```
function selectionSort(arr) {
  for (let i = 0; i < arr.length; i++) {
    let min = arr[i];
    for (let j = i + 1; j < arr.length; j++) {
      if (arr[j] < min) {
        min = arr[j];
        const swap = arr[i];
        arr[i] = min;
        arr[j] = swap;
      }
    }
  }
  return arr;
}
```