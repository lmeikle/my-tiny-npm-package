# @lmeikle/my-tiny-npm-package

[![npm (scoped)](https://img.shields.io/npm/v/@lmeikle/my-tiny-npm-package.svg)](https://www.npmjs.com/package/@lmeikle/my-tiny-npm-package)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@lmeikle/my-tiny-npm-package.svg)](https://www.npmjs.com/package/@lmeikle/my-tiny-npm-package)

Removes all spaces from a string.

## Install

```
$ npm install @lmeikle/my-tiny-npm-package
```

## Usage

```js
const tiny = require("@lmeikle/my-tiny-npm-package");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1