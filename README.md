### Install

```
npm install @vidaq/eslint-config
```

### Install dependencies

```
npm install @typescript-eslint/parser typescript prettier
```

### Prettier Config

Create `.prettierrc` file on the root

```
{
    "singleQuote": true,
    "tabWidth": 2,
    "printWidth": 120,
    "trailingComma": "es5",
    "arrowParens": "avoid"
}
```

### Common problems

If you are getting error `context.getPhysicalFilename is not a function` you need to update eslint running this command `yarn upgrade -R eslint` [more info](https://github.com/prettier/eslint-plugin-prettier/issues/434).
