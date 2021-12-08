# Installing

```
npm i -D @releaseband/typescript-config
```

`tsconfig.json`:

```js
{
  "extends": "@releaseband/typescript-config/tsconfig.json",
  "include": [".eslintrc.js", "prettier.config.js", "src"],
  "exclude": []
}

```
