Base visual component implementation
====================================

[![build status](https://img.shields.io/travis/stbsdk/component.svg?style=flat-square)](https://travis-ci.org/stbsdk/component)
[![npm version](https://img.shields.io/npm/v/stb-component.svg?style=flat-square)](https://www.npmjs.com/package/stb-component)
[![dependencies status](https://img.shields.io/david/stbsdk/component.svg?style=flat-square)](https://david-dm.org/stbsdk/component)
[![devDependencies status](https://img.shields.io/david/dev/stbsdk/component.svg?style=flat-square)](https://david-dm.org/stbsdk/component?type=dev)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/stbsdk)


It's a wrapper around the [SPA component](https://github.com/spasdk/component).


## Installation ##

```bash
npm install stb-component
```


## Usage ##

Add the singleton to the scope:

```js
var component = require('stb-component');
```


## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/stbsdk/component/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`stb-component` is released under the [MIT License](license.md).
