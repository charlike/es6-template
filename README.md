# [es6-template][author-www-url] [![npmjs.com][npmjs-img]][npmjs-url] [![The MIT License][license-img]][license-url] [![npm downloads][downloads-img]][downloads-url] 

> Small, sync and async es6 template engine, built on top of [gana][] and ES6/ES2015 Template Strings, working on `node@0.10` too!

[![code climate][codeclimate-img]][codeclimate-url] [![standard code style][standard-img]][standard-url] [![travis build status][travis-img]][travis-url] [![coverage status][coveralls-img]][coveralls-url] [![dependency status][david-img]][david-url]

## Background

Behind the scenes es6-template uses [gana][] which in turns use [gana-compile][]. So the footprint and codebase is very small (**~1-2kb** minified and not gzipped), easy (just sync and async `.compile` and `.render` methods) and very well tested (this one has **~25 tests**).

Works well on browsers and even in `node@0.10`. [Read more](https://github.com/tunnckocore/gana#background) on `gana` readme.

## Install
```
npm i es6-template --save
```

## Usage
> For more use-cases see the [tests](./test.js)

```js
const es6template = require('es6-template')
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/tunnckoCore/es6-template/issues/new).  
But before doing anything, please read the [CONTRIBUTING.md](./CONTRIBUTING.md) guidelines.

## [Charlike Make Reagent](http://j.mp/1stW47C) [![new message to charlike][new-message-img]][new-message-url] [![freenode #charlike][freenode-img]][freenode-url]

[![tunnckoCore.tk][author-www-img]][author-www-url] [![keybase tunnckoCore][keybase-img]][keybase-url] [![tunnckoCore npm][author-npm-img]][author-npm-url] [![tunnckoCore twitter][author-twitter-img]][author-twitter-url] [![tunnckoCore github][author-github-img]][author-github-url]

[npmjs-url]: https://www.npmjs.com/package/es6-template
[npmjs-img]: https://img.shields.io/npm/v/es6-template.svg?label=es6-template

[license-url]: https://github.com/tunnckoCore/es6-template/blob/master/LICENSE
[license-img]: https://img.shields.io/npm/l/es6-template.svg

[downloads-url]: https://www.npmjs.com/package/es6-template
[downloads-img]: https://img.shields.io/npm/dm/es6-template.svg

[codeclimate-url]: https://codeclimate.com/github/tunnckoCore/es6-template
[codeclimate-img]: https://img.shields.io/codeclimate/github/tunnckoCore/es6-template.svg

[travis-url]: https://travis-ci.org/tunnckoCore/es6-template
[travis-img]: https://img.shields.io/travis/tunnckoCore/es6-template/master.svg

[coveralls-url]: https://coveralls.io/r/tunnckoCore/es6-template
[coveralls-img]: https://img.shields.io/coveralls/tunnckoCore/es6-template.svg

[david-url]: https://david-dm.org/tunnckoCore/es6-template
[david-img]: https://img.shields.io/david/tunnckoCore/es6-template.svg

[standard-url]: https://github.com/feross/standard
[standard-img]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg

[author-www-url]: http://www.tunnckocore.tk
[author-www-img]: https://img.shields.io/badge/www-tunnckocore.tk-fe7d37.svg

[keybase-url]: https://keybase.io/tunnckocore
[keybase-img]: https://img.shields.io/badge/keybase-tunnckocore-8a7967.svg

[author-npm-url]: https://www.npmjs.com/~tunnckocore
[author-npm-img]: https://img.shields.io/badge/npm-~tunnckocore-cb3837.svg

[author-twitter-url]: https://twitter.com/tunnckoCore
[author-twitter-img]: https://img.shields.io/badge/twitter-@tunnckoCore-55acee.svg

[author-github-url]: https://github.com/tunnckoCore
[author-github-img]: https://img.shields.io/badge/github-@tunnckoCore-4183c4.svg

[freenode-url]: http://webchat.freenode.net/?channels=charlike
[freenode-img]: https://img.shields.io/badge/freenode-%23charlike-5654a4.svg

[new-message-url]: https://github.com/tunnckoCore/ama
[new-message-img]: https://img.shields.io/badge/ask%20me-anything-green.svg

[gana-compile]: https://github.com/tunnckocore/gana-compile
[gana]: https://github.com/tunnckocore/gana