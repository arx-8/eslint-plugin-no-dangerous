# eslint-plugin-no-dangerous

Disallow dangerous code in JavaScript.

## Install

npm:

```s
npm i -D eslint-plugin-no-dangerous
```

yarn:

```s
yarn add -D eslint-plugin-no-dangerous
```

## Usage

Setup `.eslintrc.js`

```js
module.exports = {
  plugins: ["no-dangerous"],
  rules: {
    "no-dangerous/no-dangerous-date": "error",
  },
}
```

## Detailed documents

- [no-dangerous/no-dangerous-date](https://github.com/arx-8/eslint-plugin-no-dangerous/blob/main/docs/no-dangerous-date.md)

## :shield: Happy Safe Coding :shield:
