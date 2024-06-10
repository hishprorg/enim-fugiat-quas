# @hishprorg/enim-fugiat-quas <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@hishprorg/enim-fugiat-quas');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@hishprorg/enim-fugiat-quas
[2]: https://versionbadg.es/inspect-js/@hishprorg/enim-fugiat-quas.svg
[5]: https://david-dm.org/inspect-js/@hishprorg/enim-fugiat-quas.svg
[6]: https://david-dm.org/inspect-js/@hishprorg/enim-fugiat-quas
[7]: https://david-dm.org/inspect-js/@hishprorg/enim-fugiat-quas/dev-status.svg
[8]: https://david-dm.org/inspect-js/@hishprorg/enim-fugiat-quas#info=devDependencies
[11]: https://nodei.co/npm/@hishprorg/enim-fugiat-quas.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishprorg/enim-fugiat-quas.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishprorg/enim-fugiat-quas.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishprorg/enim-fugiat-quas
[codecov-image]: https://codecov.io/gh/inspect-js/@hishprorg/enim-fugiat-quas/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@hishprorg/enim-fugiat-quas/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@hishprorg/enim-fugiat-quas
[actions-url]: https://github.com/hishprorg/enim-fugiat-quas/actions
