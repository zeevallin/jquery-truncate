jQuery-Truncate
===============

Truncate texts to fit it's containers width.

Usage:
======

``` javascript
  $('p.description').truncate();
```

#### Set how many rows you allow:

``` javascript
  $('p.description').truncate({
    omission: "...",
    rows: 2
  });
```

#### Allow the omission to be custom HTML:

``` javascript
  $('p.description').truncate({
    omission: " <a>...read more</a>",
    rows: 5,
    html: true
  });
```


(The MIT License)

Copyright © 2012 Philip Vieira and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.