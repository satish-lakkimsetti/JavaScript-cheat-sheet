### **Variables & Data Types**
```javascript
let x = 10;       // Block-scoped
const y = "Hi";   // Constant
var z = true;     // Function-scoped
```
- **Primitive types**: string, number, boolean, null, undefined, symbol, bigint  
- **Reference types**: object, array, function

---

### **Control Flow**
```javascript
if (x > 5) { ... } else { ... }
switch (value) { case 1: ...; break; default: ...; }
```
- Loops: `for`, `while`, `do...while`, `for...of`, `for...in`  
- `break`, `continue`

---

### **Functions**
```javascript
function greet(name) { return `Hello, ${name}`; }
const add = (a, b) => a + b;
```
- Supports: default parameters, rest/spread operators, arrow functions

---

### **Objects & Arrays**
```javascript
const person = { name: "Lucky", age: 25 };
const fruits = ["apple", "banana"];
```
- Access: `obj.key`, `obj["key"]`, `arr[0]`  
- Array methods: `push`, `pop`, `shift`, `unshift`, `splice`, `slice`, `map`, `filter`, `reduce`, `forEach`

---

### **Operators**
```javascript
===, !==, >, <, >=, <=  
&& (and), || (or), ! (not)
```

---

### **Type Checking**
```javascript
typeof x;         
Array.isArray([]); 
```

---

### **Modules**
```javascript
// export
export default function greet() { ... }

// import
import greet from './module.js';
```

---

### **Asynchronous JavaScript**
```javascript
async function fetchData() {
  const res = await fetch(url);
  const data = await res.json();
}
```
- Other tools: `Promise`, `.then`, `.catch`, `.finally`

---

### **Error Handling**
```javascript
try {
  // risky code
} catch (err) {
  console.error(err);
} finally {
  // always executes
}
```

---

### **DOM Manipulation**
```javascript
document.getElementById("id");
document.querySelector(".class");
element.addEventListener("click", handler);
```

---

### **Miscellaneous Tools**
- `setTimeout(fn, ms)`, `setInterval(fn, ms)`  
- `JSON.stringify()`, `JSON.parse()`  
- `Math.random()`, `Math.floor()`  
- `Date.now()`

---
