# Nuxt Hotjar [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> Add nuxt hotjar to your nuxt.js application.

**Note:** nuxt hotjar is not enabled in dev mode.
You can set environment variable `NODE_ENV` to `production` for testing in dev mode.

## Setup
- Add `nuxt-hotjar` dependency using yarn or npm to your project
- Add `nuxt-hotjar` to `modules` section of `nuxt.config.js`
```js
  modules: [
    ['nuxt-hotjar', { 
        id: 'hjsv', 
        sv: 'hjid'
    }],
]
```

## Options

### `id`
- Required
- Hotjar ID

### `sv`
- Hotjar Snippet Version


## License

MIT © [Neveena]()


[npm-image]: https://badge.fury.io/js/nuxt-hotjar.svg
[npm-url]: https://npmjs.org/package/nuxt-hotjar
[travis-image]: https://travis-ci.org/neveena/nuxt-hotjar.svg?branch=master
[travis-url]: https://travis-ci.org/neveena/nuxt-hotjar
[daviddm-image]: https://david-dm.org/neveena/nuxt-hotjar.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/neveena/nuxt-hotjar
[coveralls-image]: https://coveralls.io/repos/neveena/nuxt-hotjar/badge.svg
[coveralls-url]: https://coveralls.io/r/neveena/nuxt-hotjar
