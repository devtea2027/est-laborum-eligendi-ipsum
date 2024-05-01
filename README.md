# @devtea2027/est-laborum-eligendi-ipsum <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has `Symbol.toStringTag` support. Supports spec, or shams.

## Example

```js
var hasSymbolToStringTag = require('@devtea2027/est-laborum-eligendi-ipsum');

hasSymbolToStringTag() === true; // if the environment has native Symbol.toStringTag support. Not polyfillable, not forgeable.

var hasSymbolToStringTagKinda = require('@devtea2027/est-laborum-eligendi-ipsum/shams');
hasSymbolToStringTagKinda() === true; // if the environment has a Symbol.toStringTag sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@devtea2027/est-laborum-eligendi-ipsum
[2]: https://versionbadg.es/inspect-js/@devtea2027/est-laborum-eligendi-ipsum.svg
[5]: https://david-dm.org/inspect-js/@devtea2027/est-laborum-eligendi-ipsum.svg
[6]: https://david-dm.org/inspect-js/@devtea2027/est-laborum-eligendi-ipsum
[7]: https://david-dm.org/inspect-js/@devtea2027/est-laborum-eligendi-ipsum/dev-status.svg
[8]: https://david-dm.org/inspect-js/@devtea2027/est-laborum-eligendi-ipsum#info=devDependencies
[11]: https://nodei.co/npm/@devtea2027/est-laborum-eligendi-ipsum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2027/est-laborum-eligendi-ipsum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2027/est-laborum-eligendi-ipsum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2027/est-laborum-eligendi-ipsum
[codecov-image]: https://codecov.io/gh/inspect-js/@devtea2027/est-laborum-eligendi-ipsum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@devtea2027/est-laborum-eligendi-ipsum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@devtea2027/est-laborum-eligendi-ipsum
[actions-url]: https://github.com/devtea2027/est-laborum-eligendi-ipsum/actions
