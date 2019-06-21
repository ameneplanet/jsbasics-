# Fetch

apply filter on the list that fetch from url , it filter the items of the list that completed equal true.
```
fetch('https://jsonplaceholder.typicode.com/todos')
    .then(response => response.json())
    .then(data => data.filter(item => item.completed === true))
    .then(data => console.log(data))
```
* item 1
* item 2
* item 3