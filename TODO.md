### Install all dependencies in the package

If you are using npm then you can use the following syntax:

```bash
npm install
```

or with yarn:

```bash
yarn install
```

### Adding first script

Jump to `package.json` and add a `"scripts"` key:

**package.json**

```json
{
  "scripts": {
    "webpack": "webpack"
  }
  /* ... */
}
```

This now enables you to run `yarn webpack` or `npm run webpack` right from your terminal.
