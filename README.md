![Arrow.js](http://i.imgur.com/rZSWaEl.png)
===

Arrow is a small JavaScript library for displaying a arrow pointing to the browser download location. Perfect for pointing at that new file you downloaded!

### Get Started

Include the javascript in your HTML

```html
<script type="text/javascript" src="arrow.js">
```

Or use the minified version

```html
<script type="text/javascript" src="arrow-0.1.6.min.js">
```

### Installing with Bower

Bower requires [Node](http://nodejs.org/) and [npm](http://npmjs.org/). 

    bower install arrow-js

### How to use

#### API

```javascript
//Display the Arrow for 6 seconds
//
//@param seconds {integer} Show the arrow for this many seconds then fade out. It is optional
Arrow.show();
```

#### Properties

```javascript
//Get Arrow.js Version
Arrow._version;

//Get Current Browser
Arrow._browser;

//Get Current Browser Version
Arrow._browserVersion 
```

### Browser Support

Chrome 4+, Firefox 3.5+, IE 8+

* The Firefox download manager was introduced in version 23 so the arrow will point in the top right.

* Chrome downloads start at the bottom left of the page.

* IE 9/10 downloads start in the bottom center.

* IE 8 downloads come up in the center of the screen unless the security warnings comes up at the top of the page. So the arrow points at the top left.

### Screenshots

Chrome

![Chrome](http://i.imgur.com/1zW8EYG.png)

Firefox

![Firefox](http://i.imgur.com/6EgcJId.png)

IE 9/10 Wide Screen

![IE 9/10 Wide](http://i.imgur.com/WyDd3j4.png)

IE 9/10 Narrow Screen

![IE 9/10 Narrow](http://i.imgur.com/fztArJ3.png)

### Library Size

Original: 12054 bytes.

Minified: 4449 bytes.

### Maintainer

[Petar Bojinov](https://github.com/pbojinov)

### License

The MIT License (MIT)

Copyright (c) 2013 Perion Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

