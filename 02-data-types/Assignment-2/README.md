# Assignment-2 - Accessing DOM Element without Modifying JS

## 🎯 Task
You are given the following JavaScript code which you *cannot modify*:

```javascript
console.log(elzero.innerHTML); // object
console.log(typeof elzero);    // object
```
Your task is to make this code work correctly without writing any additional JavaScript.

## ✅ Solution
Add an HTML element with the id elzero.
The JS code will automatically reference this element.

Example:
<div id="elzero"></div>

*How it works*

elzero becomes a DOM element object.
elzero.innerHTML returns the content inside the element (currently empty).
typeof elzero is "object" because all DOM elements are JavaScript objects.
typeof elzero is "object" because all DOM elements are JavaScript objects.

## 👩‍💻 Author

Mona Elshal
Frontend Developer
