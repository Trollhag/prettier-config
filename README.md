# @trollhag/prettier-config

[![push](https://github.com/Trollhag/prettier-config/actions/workflows/ci.push.yml/badge.svg)](https://github.com/Trollhag/prettier-config/actions/workflows/ci.push.yml)
[![release](https://github.com/Trollhag/prettier-config/actions/workflows/ci.release.yml/badge.svg)](https://github.com/Trollhag/prettier-config/actions/workflows/ci.release.yml)
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
