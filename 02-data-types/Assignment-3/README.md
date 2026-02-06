# Assignment-3 - Print Complex Text Without Template Literals

## 🎯 Task
Print the following text exactly in the console *without using Template Literals*:

`I'm In
\\
Love \\ """ '''
++ With ++
\"""\"""
""JavaScript""``

## 💻 Solution

Use *normal string concatenation* with escape characters and \n for new lines. Example:

```javascript
console.log(
  "I'm In\n" + 
  "\\\\\n" + 
  "Love \\\\ \"\"\" '''\n" + 
  "++ With ++\n" + 
  "\\\"\"\"\\\"\"\"\n" + 
  "\"\"JavaScript\"\"``"
);
```
## ✅ Explanation

\n → to add a new line
\\ → to print a backslash \
\" → to print a double quote "
Strings are concatenated using + because Template Literals (`) are not allowed

## 👩‍💻 Author

Mona Elshal
Frontend Developer
