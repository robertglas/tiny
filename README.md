# @rglas/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@rglas/tiny.svg)](https://www.npmjs.com/package/@rglas/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@rglas/tiny.svg)](https://www.npmjs.com/package/@rglas/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @rglas/tiny
```

## Usage

```js
const tiny = require("@rglas/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
