# lws-defined-hello

This is a simple npm package that demonstrates the [GitHub Package Registry](https://github.com/features/package-registry).

## Installation

Before installing, make sure to authenticate with GitHub Package Registry or using a `.npmrc` file. See "[Configuring npm for use with GitHub Package Registry](https://help.github.com/en/articles/configuring-npm-for-use-with-github-package-registry#authenticating-to-github-package-registry)."

`$ npm install @lahirwisada/lws-defined-hello`

Or add this package to your `package.json` file:

```
"dependencies": {
    "@lahirwisada/lws-defined-hello": "1.0.0"
  }
```

## Usage

```
const myPackage = require('@lahirwisada/lws-defined-hello');
myPackage.helloWorld();
```