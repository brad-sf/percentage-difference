# PercentageDifference - JavaScript

Return the percentage difference between two numbers, optionally rounding.

## Installation
`npm install percentage-difference`

## Usage

`percentDiff(base, peak[, round])`

Node.JS:
```javascript
const {percentDiff} = require('percentage-difference');

console.log( percentDiff(600, 700); // 16.666666666666664
console.log( percentDiff(600, 700, true); // 17
console.log( percentDiff(700, 600, true); // -14
```

ES6:
```javascript
import {percentDiff} from 'percentage-difference';

console.log( percentDiff(600, 700); // 16.666666666666664
console.log( percentDiff(600, 700, true); // 17
console.log( percentDiff(700, 600, true); // -14
```
