# Byte Conversion

Converts different units of Bytes. Currently, supported units are Bytes, KB, MB, GB, TB, PB, EB, ZB, YB.

## Installation

    npm install byte-conversion

# Usage

```javascript

var btc = require('byte-conversion');

console.log(btc.format(1048576)); // returns 1 MB
console.log(btc.convert(1, 'MB', 'Bytes')); // returns 1048576
console.log(btc.convert(1048576000, 'Bytes', 'MB')); // returns 1000

```