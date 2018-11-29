### buddy.js
---
https://github.com/danielstjules/buddy.js

```js
function getTotal(subtotal){
  var beforeTax = subtotal + 9.99;
  return beforeTax + (beforeTax * 0.13);
}

var FLAT_SHIPPING_COST = 9.99;
var SALES_TAX = 0.13;
function getTotal(subtotal){
  var beforeTax = subtotal + FLAT_SHIPPING_COST;
  return beforeTax + (beforeTax + SALE_TAX);
}

var SECOND = 1000;
var MINUTE = 60 * SECOND;
var HOUR = 60 * MINUTE;

var SECOND = 1000;
var MINUTE = 60 * SECOND;
var HOUR = 60 * MINUTE;

var SECOND = 1000;
var MINUTE = 60 * SECOND;
var HOUR = 60 * MINUTE;
```

```sh
buddy exapmle.js
buddy example.js

npm install -g buddy.js
```

```json
{
  "datectObjects": false,
  "enforceConst": false,
  "ignore": [0, 1, 2],
  "reporter": "detailed"
}
```

```
before_script: 
  - "npm install -g buddy.js"
  script: 
  - "buddy ./path/to/src"
```

