# prettier-config

Prettier config for my projects

## Install

```bash
$ npm install -D @kirkeaton/prettier-config
```

## Usage

`package.json`

```json
{
  "name": "my-project",
  "version": "1.0.0",
  "prettier": "@kirkeaton/prettier-config"
}
```

`.prettierrc`

```
"@kirkeaton/prettier-config"
```

`.prettierrc.js` or `prettier.config.js`

```js
import defaultPrettierConfig from "@kirkeaton/prettier-config";

const config = {
  ...defaultPrettierConfig,
  // your overrides here
};

export default config;
```
