# @taktikorg/doloremque-nostrum-laboriosam <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has Symbol support. Supports spec, or shams.

## Example

```js
var hasSymbols = require('@taktikorg/doloremque-nostrum-laboriosam');

hasSymbols() === true; // if the environment has native Symbol support. Not polyfillable, not forgeable.

var hasSymbolsKinda = require('@taktikorg/doloremque-nostrum-laboriosam/shams');
hasSymbolsKinda() === true; // if the environment has a Symbol sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@taktikorg/doloremque-nostrum-laboriosam
[2]: https://versionbadg.es/inspect-js/@taktikorg/doloremque-nostrum-laboriosam.svg
[5]: https://david-dm.org/inspect-js/@taktikorg/doloremque-nostrum-laboriosam.svg
[6]: https://david-dm.org/inspect-js/@taktikorg/doloremque-nostrum-laboriosam
[7]: https://david-dm.org/inspect-js/@taktikorg/doloremque-nostrum-laboriosam/dev-status.svg
[8]: https://david-dm.org/inspect-js/@taktikorg/doloremque-nostrum-laboriosam#info=devDependencies
[11]: https://nodei.co/npm/@taktikorg/doloremque-nostrum-laboriosam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@taktikorg/doloremque-nostrum-laboriosam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@taktikorg/doloremque-nostrum-laboriosam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@taktikorg/doloremque-nostrum-laboriosam
[codecov-image]: https://codecov.io/gh/inspect-js/@taktikorg/doloremque-nostrum-laboriosam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@taktikorg/doloremque-nostrum-laboriosam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@taktikorg/doloremque-nostrum-laboriosam
[actions-url]: https://github.com/taktikorg/doloremque-nostrum-laboriosam/actions
