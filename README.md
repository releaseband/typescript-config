# Installing

create [.npmrc](https://docs.npmjs.com/cli/v7/configuring-npm/npmrc) file in the **root project folder**:

```
echo @releaseband:registry=https://npm.pkg.github.com > .npmrc
```

```
npm i -D @releaseband/typescript-config
```

`tsconfig.json`:

```js
{
  "extends": "@releaseband/typescript-config/tsconfig.json",
  "compilerOptions": {
    "outDir": "dist"
  },
  "include": [".eslintrc.js", "prettier.config.js", "src"],
  "exclude": []
}

```
