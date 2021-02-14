# has-private-fields <sup>[![Version Badge][2]][1]</sup>

[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has private fields (`class { #x; }`) support.

## Example

```js
var hasPrivateFields = require('has-private-fields');

hasPrivateFields() === true; // if the environment has native class private fields support
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/has-private-fields
[2]: https://versionbadg.es/inspect-js/has-private-fields.svg
[5]: https://david-dm.org/inspect-js/has-private-fields.svg
[6]: https://david-dm.org/inspect-js/has-private-fields
[7]: https://david-dm.org/inspect-js/has-private-fields/dev-status.svg
[8]: https://david-dm.org/inspect-js/has-private-fields#info=devDependencies
[9]: https://ci.testling.com/inspect-js/has-private-fields.png
[10]: https://ci.testling.com/inspect-js/has-private-fields
[11]: https://nodei.co/npm/has-private-fields.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/has-private-fields.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/has-private-fields.svg
[downloads-url]: https://npm-stat.com/charts.html?package=has-private-fields
