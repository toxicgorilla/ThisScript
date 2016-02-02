## ThisScript
Let's do this

# Chapter 1 - Creating a new ThisScript file.
All ThisScript files must start exactly as follows:

var that = '';
(function(_this, _self){
  that = _this || self || {};
  
  var self = new THIS.requires('this', function() {
    "use strict"; // this
    "use this"; // heh
  }
})('this', self);

This does not do anything. At all. But if it is not present in the file, it will not compile.

# Chapter 2 - Variables and Scope in ThisScript
