# eslint-config-react

[![npm version](https://img.shields.io/npm/v/eslint-config-backpacker-react)](https://www.npmjs.com/package/eslint-config-backpacker-react)
[![Build](https://github.com/backpacker/eslint-config-react/workflows/build/badge.svg)](https://github.com/backpacker/eslint-config-react/actions?query=workflow%3Abuild)

Extends [eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb) and [a few others](./package.json).

To install, run

```sh
yarn add --dev eslint-config-backpacker-react
```

Then extend it inside your `.eslintrc.js` file

```js
module.exports = {
  ...
  extends: [
    "backpacker-react",
  ],
};
```
