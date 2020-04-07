# eslint-config

[![Build Status](https://travis-ci.org/darwintantuco/eslint-config.svg?branch=master)](https://travis-ci.org/darwintantuco/eslint-config)

My personal eslint config

## Dependencies

- eslint
- typescript
- @typescript-eslint/parser
- @typescript-eslint/eslint-plugin
- eslint-plugin-react
- eslint-plugin-jsx-a11y
- eslint-config-prettier

## Installation

### npm

```
npm install @darwintantuco/eslint-config --save-dev
```

### yarn

```
yarn add @darwintantuco/eslint-config --dev
```

## Usage

Update `.eslintrc.js`

```js
// .eslintrc.js
module.exports = {
  extends: ['@darwintantuco/eslint-config'],
}
```

Or add eslint config in `package.json`

```json
{
  "eslintConfig": { "extends": ["@darwintantuco/eslint-config"] },
  "scripts": {
    "lint:js": "eslint 'js/**/*.{js,jsx,ts,tsx}'"
  }
}
```

## License

MIT
