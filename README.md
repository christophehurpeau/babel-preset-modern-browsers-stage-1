# babel-preset-modern-browsers-stage-1

[![Greenkeeper badge](https://badges.greenkeeper.io/christophehurpeau/babel-preset-modern-browsers-stage-1.svg)](https://greenkeeper.io/)

[![NPM Version](http://img.shields.io/npm/v/babel-preset-modern-browsers-stage-1.svg?style=flat-square)](https://www.npmjs.org/package/babel-preset-modern-browsers-stage-1)
![Edge 14](https://img.shields.io/badge/Edge-14-green.svg?style=flat-square)
![Firefox 47](https://img.shields.io/badge/Firefox-47-green.svg?style=flat-square)
![Chrome 51](https://img.shields.io/badge/Chrome-52-green.svg?style=flat-square)
![Opera 38](https://img.shields.io/badge/Opera-39-green.svg?style=flat-square)
![Safari 9](https://img.shields.io/badge/Safari-10-green.svg?style=flat-square)

Babel stage 1 preset for modern browsers.


* [Installation](#installation)
* [Usage](#usage)
* [Compatibility Table](#compatibility-table)
* [Release Dates](https://github.com/christophehurpeau/babel-preset-modern-browsers#release-dates)

## Installation

```sh
npm install --save-dev babel-preset-modern-browsers babel-preset-modern-browsers-stage-1
```

## Usage

Add the following line to your `.babelrc` file:

```json
{
  "presets": ["modern-browsers", "modern-browsers-stage-1"]
}
```

## Difference with `babel-preset-stage-1`

### Today, there is no difference with `babel-preset-stage-1`.

You can safely use `babel-preset-stage-1` instead, because no modern browsers supports the features, as you can see in the compatibility table.

## Compatibility Table


| Feature | Edge | Firefox | Chrome | Opera | Safari |
| ------- | ---- | ------- | ------ | ----- | ------ |
| <h4>Stage 3</h4> ||||||
| [`async`/`await`](http://kangax.github.io/compat-table/esnext/#test-async_functions) | 14 | No | No | No | No |
| ↳ [transform-async-to-generator](https://babeljs.io/docs/plugins/syntax-trailing-function-commas) ||||||
| [trailing commas in function](http://kangax.github.io/compat-table/esnext/#test-trailing_commas_in_function_syntax) | 14 | No | No | No | 10 |
| ↳ [syntax-trailing-function-commas](https://babeljs.io/docs/plugins/syntax-trailing-function-commas) ||||||
| <h4>Stage 2</h4> ||||||
| [Object rest properties](http://kangax.github.io/compat-table/esnext/#test-object_rest_properties) | No | No | No | No | No |
| [Object spread properties](http://kangax.github.io/compat-table/esnext/#test-object_spread_properties) | No | No | No | No | No |
| ↳ [transform-object-rest-spread](https://babeljs.io/docs/plugins/transform-object-rest-spread) ||||||
| <h4>Stage 1</h4> ||||||
| [class properties](http://kangax.github.io/compat-table/esnext/#test-class_properties) | No | No | No | No | No |
| ↳ [babel-plugin-transform-class-properties](https://babeljs.io/docs/plugins/transform-class-properties) ||||||
| class constructor call | No | No | No | No | No |
| ↳ [babel-plugin-transform-class-constructor-call](https://babeljs.io/docs/plugins/transform-class-constructor-call) ||||||
| [class decorators](http://kangax.github.io/compat-table/esnext/#test-class_decorators) | No | No | No | No | No |
| ↳ [babel-plugin-transform-decorators](https://babeljs.io/docs/plugins/transform-decorators) ||||||
