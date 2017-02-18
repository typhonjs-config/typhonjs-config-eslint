![typhonjs-config-eslint](http://i.imgur.com/mO59UgG.png)

[![NPM](https://img.shields.io/npm/v/typhonjs-config-eslint.svg?label=npm)](https://www.npmjs.com/package/typhonjs-config-eslint)
[![Gitter](https://img.shields.io/gitter/room/typhonjs/TyphonJS.svg)](https://gitter.im/typhonjs/TyphonJS)

Provides shared [ESLint](http://eslint.org/) configuration files for [TyphonJS](https://typhonjs.io). 

To install:

`npm install --save-dev typhonjs-config-eslint` or add to `package.json`.

To use:

Create a minimal `.eslintrc` file in the root path of a project.

```
/**
 * Loads https://github.com/typhonjs-node-config/typhonjs-config-eslint/blob/master/3.0/babel/es8/server/node/.eslintrc
 * NPM: https://www.npmjs.com/package/typhonjs-config-eslint
 */
{
   "extends": "./node_modules/typhonjs-config-eslint/3.0/babel/es8/server/node/.eslintrc"
}
```

The latest revision of this module includes basic and Babel based configs for ES6, ES7, & ES8. It should be noted that this module just contains ESLint config files and not any required dependencies such as [babel](https://www.npmjs.com/package/babel) or [eslint-plugin-babel](https://www.npmjs.com/package/eslint-plugin-babel). TyphonJS repos include as a dev dependency, [typhonjs-npm-build-test](https://www.npmjs.com/package/typhonjs-npm-build-test), which does include all dependencies for a complete dev toolchain.
