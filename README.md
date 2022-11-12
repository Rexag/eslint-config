# @rexag.zhang/eslint-config

ESLint config for JavaScript, TypeScript, Vue 2, Vue 3, Prettier.

## Usage

```bash
pnpm i -D @rexag.zhang/eslint-config-basic # JavaScript only

# Or yarn add -D / npm install -D

pnpm i -D @rexag.zhang/eslint-config-ts # JavaScript and TypeScript

pnpm i -D @rexag.zhang/eslint-config-vue # JavaScript, TypeScript and Vue 2/3 (Auto detect)

pnpm i -D @rexag.zhang/eslint-config-prettier # Prettier only

pnpm i -D @rexag.zhang/eslint-config # JavaScript, TypeScript, Vue 2/3 and Prettier
```

## Quick start

### Vue 3

```bash
pnpm i -D @rexag.zhang/eslint-config
```

```javascript
// .eslintrc.js
module.exports = {
  root: true,
  extends: ['@rexag.zhang/eslint-config'],
  rules: {
    // Your custom rules
  },
}
```

```jsonc
// .prettierrc
{
  "singleQuote": true,
  "semi": true,
  "arrowParens": "avoid",
  "jsxSingleQuote": true,
  "endOfLine": "lf",
  "trailingComma": "es5"
}
```

### VSCode

```jsonc
// settings.json
{
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ],
  "eslint.probe": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "html",
    "vue",
    "json",
    "json5",
    "jsonc",
    "yaml"
  ]
}
```
## License

ISC License © 2022-PRESENT [rexag.zhang](https://github.com/Rexag)
