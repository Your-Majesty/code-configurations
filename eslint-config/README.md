# Shareable eslint config

These rules are the most stringent, which allow you to control all types of data in your project, as well as more
strictly determine the order of imports.

### Quick start

```bash
$ npm install @yourmajestyco/eslint-config -D
```

Also you do not need to manually install ESLint, it will always be the newest.

Add to your `.eslintrc.json`:

```json
{
    "extends": "@yourmajestyco/eslint-config"
}
```

Check out eslint:

```
$ eslint "**/*.ts"
```

### Override rules

`.eslintrc.json` or `.eslintrc.js`:

```json5
{
    extends: '@yourmajestyco/eslint-config',
    rules: {
        // override extended rules
    }
}
```

### Optional

### import/no-deprecated by default "off"

```json
{
    "extends": "@yourmajestyco/eslint-config",
    "rules": {
        "import/no-deprecated": "error"
    }
}
```
