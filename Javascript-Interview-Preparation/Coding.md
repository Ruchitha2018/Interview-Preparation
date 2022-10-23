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

#### 3.
```
const shape = {
  radius: 10,
  diameter() {
    return this.radius * 2;
  },
  perimeter: () => 2 * Math.PI * this.radius,
};

console.log(shape.diameter());
console.log(shape.perimeter());
```
---
#### 4.
```
+true;
!'Lydia';
```
---
#### 5.

```
const bird = {
  size: 'small',
};

const mouse = {
  name: 'Mickey',
  small: true,
};
```
- All JS object property names (keys) can only be strings or Symbols
---

#### 6.

```
let c = { greeting: 'Hey!' };
let d;

d = c;
c.greeting = 'Hello';
console.log(d.greeting);
```
