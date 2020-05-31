# inr-converter

> Transform strings and numbers to INR format.

## Installation

```sh
$ npm install inr-converter
```

## Usage

```javascript
'use strict';
const { toRupees } = require("inr-converter");


console.log(toRupees("200000"));
console.log(toRupees(20000000));


/** 
 * Output :
 * 
 * 2,00,000
 * 2,00,00,000
 * 
*/

```

## License

ISC