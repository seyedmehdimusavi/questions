# how to remove dublicate element in array?
```java
//set
[...new Set(array)]
// filter
aaray.filter((item, index) => array.indexOf(item) === index)
// reduce
array.reduce((unique, item)=>
unique.includes(item) ? unique : [...unique, item], [])
```
