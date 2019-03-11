# eslint-config-standard
eslint-config-standard for megalo project


## install
```bash
npm i eslint eslint-config-standard
```

## configure
If you have already configured the eslint-related webpack configuration, 
you can create a file `.eslintrc.js` in project root directory, that`s all content of file:
```js
module.exports = {
  root: true,
  extends: [
    '@megalo/standard'
  ]
}

```
