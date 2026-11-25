# ki-projects.github.io

```javascript
fetch('https://github.com')
  .then(response => response.json())
  .then(data => {
    data.forEach(item => console.log(item.name));
  });
```
