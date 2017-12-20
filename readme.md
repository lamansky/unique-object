# unique-object

Returns a copy of an Object or Map with duplicate values removed.

This module is an alias of [`unique-map`](https://github.com/lamansky/unique-map), which supports both Maps and Objects.

## Installation

```bash
npm install unique-object --save
```

## Usage Example

```javascript
const uniqueObject = require('unique-object')

const obj = {
  1: 'A',
  2: 'A',
  3: 'B',
}

const u = uniqueObject(obj)
u[1] // 'A'
u[2] // undefined
u[3] // 'B'
```

For more details, see the documentation for the [`unique-map`](https://github.com/lamansky/unique-map) module.
