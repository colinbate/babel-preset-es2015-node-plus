# babel-preset-es2015-node-plus

> Babel preset for all es2015 plugins needed with latest stable node, plus object spread and function bind from ES2016+.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-node-plus
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-node-plus"]
}
```

### Via CLI

```sh
$ babel script.js --preset es2015-node-plus
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-node-plus"]
});
```