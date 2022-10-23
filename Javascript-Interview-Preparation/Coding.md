#### 1.
```
function sayHi() {
  console.log(name);
  console.log(age);
  var name = 'Ruchi';
  let age = 26;
}
sayHi();
```
---
#### 2. 
```
for (var i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 1);
}

for (let i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 1);
}
```
---
