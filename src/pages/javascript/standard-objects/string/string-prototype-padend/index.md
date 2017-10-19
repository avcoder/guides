---
title: String.prototype.padEnd
---
## String.prototype.padEnd
By default, padEnd inserts spaces at the end of a string until your desired string length is achieved.  padEnd is good for any kind of console output where you are trying to align data. 

For example, to padEnd "Pears" up to 10 characters:
```javascript
"Pears".padEnd(10);  // output is "Pears     "
```
Since padEnd knows that "Pears" has 5 characters, it will insert spaces until a total length of 10 characters is achieved.


By default, spaces are assumed, but the second parameter can be used to tell padEnd which character to pad with.
For example, to padEnd the string "Chapter 1" with periods up to 40 characters:
```javascript
"Chapter 1".padEnd(40, ".");  // output is "Chapter 1..............................."
```




#### More Information:
[MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd)


