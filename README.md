# caesar-cipher-tool ![Node.js CI](https://github.com/melonattacker/ceasar-cipher-tool/workflows/Node.js%20CI/badge.svg)
caesar-cipher-tool is a caesal cipher library for javascript and Node.js.

You can shift alphabets to the right by the number(0-25) you specify. 

## Installation

```
$ npm i caesar-cipher-tool
```

## Usage

```:js
const tool = require('caesar-cipher-tool');

const output = tool.caesar("Hello, World.", 3);
console.log(output); // Khoor, Zruog.
```
