# glpi [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> Node client to interact with GLPI webservices plugin

## Developer Guide
##### Plugins GLPI-PROJECT » WebServices

This plugin provides a server for Web Services which allow an external application to check and control GLPI.

Currently, the servers implemented are:
* XMLRPC
* SOAP

It provides some methods and a development framework to alow other plugins to provide their own methods.

https://forge.glpi-project.org/projects/webservices/wiki/En_devguide

## Installation

```sh
$ npm install --save glpi
```

## Usage

```js
var glpi = require('glpi');

glpi('');
```
## License

ISC © [Alexander J. Salas B.](http://ajsb85.com)


[npm-image]: https://badge.fury.io/js/npm-glpi.svg
[npm-url]: https://npmjs.org/package/glpi
[travis-image]: https://travis-ci.org/ajsb85/npm-glpi.svg?branch=master
[travis-url]: https://travis-ci.org/ajsb85/npm-glpi
[daviddm-image]: https://david-dm.org/ajsb85/npm-glpi.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/ajsb85/npm-glpi
[coveralls-image]: https://coveralls.io/repos/ajsb85/npm-glpi/badge.svg
[coveralls-url]: https://coveralls.io/r/ajsb85/npm-glpi
