# @trollhag/prettier-config

[![ci](https://github.com/trollhag/prettier-config/workflows/ci/badge.svg)](https://github.com/trollhag/prettier-config/actions/workflows/ci.yml)
[![license](https://img.shields.io/github/license/trollhag/prettier-config.svg)](https://github.com/trollhag/prettier-config/blob/main/LICENSE)

## Installation

Set registry scope in `.npmrc`

```
@trollhag:registry=https://npm.pkg.github.com
```

Install
```shell script
npm i -D prettier @trollhag/prettier-config
```

## Usage

Add a `.prettierrc.json` file with:

```json
"@trollhag/prettier-config"
```

## Extending

To extend this config file in your project, use a `.prettierrc.js` file:

```javascript
module.exports = {
  ...require('@trollhag/prettier-config'),
  printWidth: 100,
};
```

## License

MIT © Oscar Trollhag
