# @micromint1npm/inventore-provident-cum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@micromint1npm/inventore-provident-cum');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@micromint1npm/inventore-provident-cum
[npm-version-svg]: https://versionbadg.es/ljharb/@micromint1npm/inventore-provident-cum.svg
[deps-svg]: https://david-dm.org/ljharb/@micromint1npm/inventore-provident-cum.svg
[deps-url]: https://david-dm.org/ljharb/@micromint1npm/inventore-provident-cum
[dev-deps-svg]: https://david-dm.org/ljharb/@micromint1npm/inventore-provident-cum/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@micromint1npm/inventore-provident-cum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@micromint1npm/inventore-provident-cum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@micromint1npm/inventore-provident-cum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@micromint1npm/inventore-provident-cum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@micromint1npm/inventore-provident-cum
[codecov-image]: https://codecov.io/gh/ljharb/@micromint1npm/inventore-provident-cum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@micromint1npm/inventore-provident-cum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@micromint1npm/inventore-provident-cum
[actions-url]: https://github.com/micromint1npm/inventore-provident-cum/actions
