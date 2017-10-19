---
title: String.prototype.padStart
---
## String.prototype.padStart
By default, padStart inserts spaces at the beginning of a string until your desired string length is achieved.  padStart is good for any kind of console output where you are trying to align data. 

For example, to padStart "Apples" up to 10 characters:
```javascript
"Apples".padStart(10);  // output is "    Apples"
```
Since padStart knows that "Apples" has 6 characters, it will insert spaces until a total length of 10 characters is achieved.


By default, spaces are assumed, but the second parameter can be used to tell padStart which character to pad with.
For example, to padStart the string "3" with zeros up to 3 characters:
```javascript
"9".padStart(3, "0");  // output is "003"
```




#### More Information:
[MDN's documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart)


