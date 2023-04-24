# `@deemsang/prettier-config`

> my [prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
# npm
npm install --save-dev @deemsang/prettier-config

# yarn
yarn add --dev @deemsang/prettier-config

# pnpm
pnpm add --save-dev @deemsang/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@deemsang/prettier-config"
}
```

**Or extend in `prettier.config.js`**:

```js
module.exports = {
  ...require('@deemsang/prettier-config'),
  // your overrides
};
```
