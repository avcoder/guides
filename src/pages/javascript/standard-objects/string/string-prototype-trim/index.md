---
title: String.prototype.trim
---
## String.prototype.trim
The trim() method returns a string with any whitespace removed from its beginning and end.  Whitespace includes tabs, spaces, no-break space, line feed character, carriage return character, etc.  When the trim() method is called by a string, that string itself is not changed.

For example, to trim "     popcorn    ":
```javascript
const food = "     popcorn    ";
console.log(food.trim());  // output is "popcorn"
console.log(food);         // output is "     popcorn    "
```


#### More Information:
[MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)


