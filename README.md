# @hutechwebsite/veniam-corporis-architecto-earum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@hutechwebsite/veniam-corporis-architecto-earum');

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

[package-url]: https://npmjs.org/package/@hutechwebsite/veniam-corporis-architecto-earum
[npm-version-svg]: https://versionbadg.es/ljharb/@hutechwebsite/veniam-corporis-architecto-earum.svg
[deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/veniam-corporis-architecto-earum.svg
[deps-url]: https://david-dm.org/ljharb/@hutechwebsite/veniam-corporis-architecto-earum
[dev-deps-svg]: https://david-dm.org/ljharb/@hutechwebsite/veniam-corporis-architecto-earum/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hutechwebsite/veniam-corporis-architecto-earum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hutechwebsite/veniam-corporis-architecto-earum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hutechwebsite/veniam-corporis-architecto-earum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hutechwebsite/veniam-corporis-architecto-earum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hutechwebsite/veniam-corporis-architecto-earum
[codecov-image]: https://codecov.io/gh/ljharb/@hutechwebsite/veniam-corporis-architecto-earum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hutechwebsite/veniam-corporis-architecto-earum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hutechwebsite/veniam-corporis-architecto-earum
[actions-url]: https://github.com/hutechwebsite/veniam-corporis-architecto-earum/actions
