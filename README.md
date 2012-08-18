# compare.js

compare.js implements JavaScript's comparison operators for Node.js the way you would expect them to be.

## Installation

    $ npm install compare.js

## Features

- Supports comparison of numbers, strings, booleans, functions and undefined.
- Supports comparison in a type-safe manner.
- Supports comparison by value and by reference.
- Supports comparison with `undefined` correctly.

## Quick Start

Using compare.js is easy. All you need to do is to add a reference to it within your Node.js application:

```javascript
var cmp = require('compare.js');
```

Now you are able to use the various comparison operators:

<table>
  <tr><th>Operator</th><th>Description</th></tr>
  <tr><td>cmp.eq(first, second)</td><td>equal</td></tr>
  <tr><td>cmp.ne(first, second)</td><td>not equal</td></tr>
  <tr><td>cmp.gt(first, second)</td><td>greater than</td></tr>
  <tr><td>cmp.ge(first, second)</td><td>greater than or equal</td></tr>
  <tr><td>cmp.lt(first, second)</td><td>less than</td></tr>
  <tr><td>cmp.le(first, second)</td><td>less than or equal</td></tr>
  <tr><td>cmp.id(first, second)</td><td>identical</td></tr>
</table>

Please note that each comparison operator works on each combination of types and does what you would expect it to do.

That's it :-)!

## Copyright

(c) Copyright 2012 [Golo Roden](http://www.goloroden.de), contact using webmaster@goloroden.de