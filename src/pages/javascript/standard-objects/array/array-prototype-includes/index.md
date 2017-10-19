---
title: Array.prototype.includes
---
## Array.prototype.includes
The includes() method will return true, if the value you are searching for matches an element in the given array.

For example, to find out if "Mustard" is in an array:
```javascript
const food = ["Relish", "Mustard", "Ketchup"]
food.includes("Mustard");  // true
food.includes("Seed");     // false
```


By default, includes() starts searching from the beginning of the array, but the second parameter can be used to tell includes() which position in the array to start searching.

For example, to start searching at the second position of the array (which has an index of 1 since arrays are zero-based):
```javascript
const food = ["Relish", "Mustard", "Ketchup"]
food.includes("Mustard", 1);  // true
food.includes("Mustard", 2);  // false
```

If the second argument passed to includes() is a negative number, then the method will count backwards from the last array position and start searching there.

For example, to start searching at the second position of the array using a negative number:
```javascript
const food = ["Relish", "Mustard", "Ketchup"]
food.includes("Mustard", -2);  // true because it starts searching from "Mustard" onward
food.includes("Mustard", -1);  // false because it starts searching from "Ketchup" onward
```

#### More Information:
[MDN documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)


