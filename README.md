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