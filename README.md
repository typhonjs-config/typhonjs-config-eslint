![typhonjs-config-eslint](http://i.imgur.com/mO59UgG.png)

[![NPM](https://img.shields.io/npm/v/typhonjs-config-eslint.svg?label=npm)](https://www.npmjs.com/package/typhonjs-config-eslint)
[![Gitter](https://img.shields.io/gitter/room/typhonjs/TyphonJS.svg)](https://gitter.im/typhonjs/TyphonJS)

Provides shared [ESLint](http://eslint.org/) configuration files for [TyphonJS](https://github.com/typhonjs). 

To install:

`npm install --save-dev typhonjs-config-eslint` or add to `package.json`.

To use:

Create a minimal `.eslintrc` file in the root path of a project like following.

```
/**
 * Loads https://github.com/typhonjs-node-config/typhonjs-config-eslint/blob/master/es6/server/node/.eslintrc
 * NPM: https://www.npmjs.com/package/typhonjs-config-eslint
 */
{
   "extends": "./node_modules/typhonjs-config-eslint/es6/server/node/.eslintrc"
}
```

Currently there are three ESLint configuration files
  - `./node_modules/typhonjs-config-eslint/es6/browser/.eslintrc`
  - `./node_modules/typhonjs-config-eslint/es6/server/node/.eslintrc`
  - `./node_modules/typhonjs-config-eslint/es5/server/node/.eslintrc`
