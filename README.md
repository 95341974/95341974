hello-world-npm
This is a simple npm package that demonstrates the Github Package Registry.

Installation
Before installing, make sure to authenticate with GitHub Package Registry or using a .npmrc file. See "Configuring npm for use with GitHub Package Registry."

$ npm install @codertocat/hello-world-npm

Or add this package to your package.json file:

``` "dependencies": { "@codertocat/hello-world-npm": "1.0.0" } ```

Usage
``` const myPackage = require('@codertocat/hello-world-npm'); myPackage.helloWorld(); ```
