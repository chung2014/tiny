# @chung2014/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@chung2014/tiny.svg)](https://www.npmjs.com/package/@chung2014/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@chung2014/tiny.svg)](https://www.npmjs.com/package/@chung2014/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @chung2014/tiny
```

## Usage

```js
const tiny = require("@chung2014/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```