# @marcobiedermann/prettier-config

Shared [Prettier](https://prettier.io/) config for my projects

## Install

```sh
npm install --save-dev @marcobiedermann/prettier-config
```

## Usage

Reference config in `.package.json`.

```json
{
  "prettier": "@marcobiedermann/prettier-config"
}
```

Or import the config in `.prettierrc.js`, which could be extended.

```js
module.exports = {
  ...require('@marcobiedermann/prettier-config'),
};
```

## Reference

- [Sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations)
