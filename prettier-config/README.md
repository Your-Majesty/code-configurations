# Shareable Prettier config

### Quick start

```bash
$ yarn add -D @yourmajestyco/prettier-config
```

or

```bash
$ npm install @yourmajestyco/prettier-config -D
```

Add to your `package.json`:

```json
{
    "name": "app",
    "version": "1.33.7",
    "prettier": "@yourmajestyco/prettier-config"
}
```

or `.prettierrc.js`:

```js
module.exports = {
    ...require('@yourmajestyco/prettier-config'),
    // override
    semi: false
};
```
