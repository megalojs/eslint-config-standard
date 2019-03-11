# eslint-config-standard
eslint-config-standard for megalo project


## install
```bash
npm i eslint @megalo/eslint-config-standard
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

## recommendations
We recommend using it with @megalo/cli-serve. [Click this enter to portal](https://github.com/megalojs/megalo-cli/tree/master/packages/@megalo/cli-service)
