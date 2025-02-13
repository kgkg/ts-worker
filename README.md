# @breejs/ts-worker

[![build status](https://github.com/breejs/ts-worker/actions/workflows/ci.yml/badge.svg)](https://github.com/breejs/ts-worker/actions/workflows/ci.yml)
[![code coverage](https://img.shields.io/codecov/c/github/breejs/ts-worker.svg)](https://codecov.io/gh/breejs/ts-worker)
[![code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![made with lass](https://img.shields.io/badge/made_with-lass-95CC28.svg)](https://lass.js.org)
[![license](https://img.shields.io/github/license/breejs/ts-worker.svg)](LICENSE)
[![npm downloads](https://img.shields.io/npm/dt/@breejs/ts-worker.svg)](https://npm.im/@breejs/ts-worker)

> Typescript workers plugin for Bree!


## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [Contributors](#contributors)
* [License](#license)


## Install

[npm][]:

```sh
npm install @breejs/ts-worker
```

[yarn][]:

```sh
yarn add @breejs/ts-worker
```


## Usage

> **Note:** You must be using Bree v6.5.0 or greater!

Extend bree with the plugin:

```js
Bree.extend(require('@breejs/ts-worker'));

const bree = new Bree(config);
```


## Contributors

| Name              | Website                           |
| ----------------- | --------------------------------- |
| **Taylor Schley** | <https://github.com/shadowgate15> |


## License

[MIT](LICENSE) © [Taylor Schley](https://github.com/shadowgate15)


##

[npm]: https://www.npmjs.com/

[yarn]: https://yarnpkg.com/
