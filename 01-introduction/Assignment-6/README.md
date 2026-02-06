# Assignment-6 - Prevent Execution of Existing Code

## 🎯 Task
Prevent the execution of the following code without deleting or modifying it:

```javascript
console.log("Iam In Console");
document.write("Iam In Page");
```
You can write code before it to stop it from executing.

## 🧠 Method
Method 1: Prevent code execution by overriding console.log and document.write with empty functions so the original code stays in the file but does nothing.

```Javascript
   // Prevent execution
console.log = function(){};
document.write = function(){};
   // Original code (unchanged)
console.log("Iam In Console");
document.write("Iam In Page");
```
## 👩‍💻 Author
Mona Elshal.
Frontend Developer.