# Nuxt Hotjar [![NPM version][npm-image]][npm-url] [![Dependency Status][daviddm-image]][daviddm-url] 
> Add nuxt hotjar to your nuxt.js application.

**Note:** nuxt hotjar is not enabled in dev mode.
You can set environment variable `NODE_ENV` to `production` for testing in dev mode.

## Setup
- Add `@netsells/nuxt-hotjar` dependency using yarn or npm to your project
- Add `@netsells/nuxt-hotjar` to `modules` section of `nuxt.config.js`
```js
modules: [
    ['@netsells/nuxt-hotjar', { 
        id: 'hjid', 
        sv: 'hjsv',
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

MIT © [Netsells](https://netsells.co.uk)


[npm-image]: https://badge.fury.io/js/%40netsells%2Fnuxt-hotjar.svg
[npm-url]: https://npmjs.org/package/@netsells/nuxt-hotjar
[travis-image]: https://travis-ci.org/netsells/nuxt-hotjar.svg?branch=master
[travis-url]: https://travis-ci.org/netsells/nuxt-hotjar
[daviddm-image]: https://david-dm.org/netsells/nuxt-hotjar.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/netsells/nuxt-hotjar
[coveralls-image]: https://coveralls.io/repos/netsells/nuxt-hotjar/badge.svg
[coveralls-url]: https://coveralls.io/r/netsells/nuxt-hotjar
