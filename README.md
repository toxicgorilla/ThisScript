# ThisScript
Let's do this

## Chapter 1 - Creating a new ThisScript file.

All ThisScript files must start exactly as follows:

```javascript
var that = '';
(function(_this){
  that = _this || {};
  
  var self = new THIS.requires('this', function() {
    "use strict"; // this
    "use this"; // heh
    
    // do nothing lol
  }
})('this');
```

This does not do anything. Literally nothing. But if it is not present in the file, it will not compile.

## Chapter 2 - Variables and Scope in ThisScript

## Suggestions for future revisions
Make sure all ThisScript extensions are accessed through a $. Make sure it is fundamentally annoying to insert this into a site with jQuery.
