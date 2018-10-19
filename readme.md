# qx-showdown

make the showdownjs.com html-md converter js library available in a qooxdoo application

# SYNOPSIS

```javascript
/* the following line gets qooxdoo to load the class which does not actually
   do anything itself, but it contains a copy of showdownjs which is now available
   in your code */
qxShowdown.Load;
/* now use showdown */
let converter = new showdown.Converter();
let md = '# hello, markdown!';
let html = converter.makeHtml(md);
```

# REFERENCE

- [https://github.com/showdownjs/showdown](https://github.com/showdownjs/showdown)
- [http://showdownjs.com](http://showdownjs.com)

# VERSION

showdownjs version: 1.8.7
