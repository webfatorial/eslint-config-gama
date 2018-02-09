# eslint-config-gama
Gama ESLint Configuration

[![NPM version][npm-image]][npm-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![with w! works][webfatorial-image]][webfatorial-url]

The [sharable ESLint config](http://eslint.org/docs/developer-guide/shareable-configs.html) used in the gama.js projects. This config is also included in newly generated Gama projects. We recommend that you use this config for consistency, but it is not required.

## Usage

The default ESLint configuration lints for ES6.

Install the default configuration package and `eslint` dependency:

```
npm install --save-dev eslint-config-gama eslint
```

Add the config to a `.eslintrc.json` file or the `eslintConfig` object in `package.json` using the ESLint `extends` attribute:

```json
{
  "extends": "gama"
}
```

## License
[MIT](https://github.com/webfatorial/eslint-config-gama/blob/master/LICENSE)

[npm-image]: https://img.shields.io/npm/v/eslint-config-gama.svg
[npm-url]: https://npmjs.org/package/eslint-config-gama
[daviddm-image]: http://img.shields.io/david/webfatorial/eslint-config-gama.svg
[daviddm-url]: https://david-dm.org/webfatorial/eslint-config-gama
[webfatorial-image]: https://img.shields.io/badge/with%20w!-works-157bac.svg
[webfatorial-url]: http://webfatorial.works