jQuery Snowfall plugin
======================

Version 1.0
---

Bug fixes, removed `requestAnimationFrame` polyfill.

Updated to use [gulpjs](http://gulpjs.com/) for build process.

=====================

###options
```JavaScript
size {min, max},  (default: {10, 20})
interval,         (default: 500)
color,            (default: '#fff')
content,          (default: '&#10052;')
disappear         Disappear animation (default: 'linear')
```

How to use :

```JavaScript
$.snowfall.start();
```
or
```JavaScript
$.snowfall.start({
  color: '#000',
  content: '<i class="fa fa-snowflake-o"></i>'
});
```

- Stop Falling -

```JavaScript
$.snowfall.stop();
```
