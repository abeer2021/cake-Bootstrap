# jQuery Easing Plugin

What is it? A jQuery plugin from GSGD to give advanced easing options. More info [here](http://gsgd.co.uk/sandbox/jquery/easing)


# AMD or CommonJS usage

```js
// CommonJS
var jQuery = require('jquery');
require('jquery.easing')(jQuery);

// AMD
define(['jquery', 'jquery.easing'], function (jQuery, easing) {
  easing(jQuery)
})
```

# Building and testing

* Clone the repo
* `npm install`
* Make changes
* Test against files in `/examples`
* Build minified version with `npm run uglify`
