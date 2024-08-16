# @trollhag/prettier-config

[![test](https://github.com/Trollhag/prettier-config/actions/workflows/test.yml/badge.svg)](https://github.com/Trollhag/prettier-config/actions/workflows/test.yml)
[![release](https://github.com/Trollhag/prettier-config/actions/workflows/release.yml/badge.svg)](https://github.com/Trollhag/prettier-config/actions/workflows/release.yml)
[![license](https://img.shields.io/github/license/trollhag/prettier-config.svg)](https://github.com/trollhag/prettier-config/blob/main/LICENSE)

## Installation

```shell script
npm i --save-dev prettier @trollhag/prettier-config
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
