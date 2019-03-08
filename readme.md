# has-css-js-selector 
[![Build Status](https://travis-ci.org/bartveneman/has-css-js-selector.svg?branch=master)](https://travis-ci.org/bartveneman/has-css-js-selector) 
[![Known Vulnerabilities](https://snyk.io/test/github/bartveneman/has-css-js-selector/badge.svg)](https://snyk.io/test/github/bartveneman/has-css-js-selector) 
![Dependencies Status](https://img.shields.io/david/bartveneman/has-css-js-selector.svg) 
![Dependencies Status](https://img.shields.io/david/dev/bartveneman/has-css-js-selector.svg) 
[![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![Project: Wallace](https://img.shields.io/badge/Project-Wallace-29c87d.svg)](https://www.projectwallace.com/oss)

A test to determine wether a selector contains a JavaScript selector

## Installation

```bash
npm install has-css-js-selector

# or

yarn add has-css-js-selector
```

## Usage

```js
const hasJsSelector = require('has-css-js-selector')

console.log(hasJsSelector('.js-toggle'))
// => true

console.log(hasJsSelector('.nothing-to-see-here'))
// => false
```

## Related projects

- [CSS Analyzer](https://github.com/projectwallace/css-analyzer) - CSS
  statistics module
- [Wallace CLI](https://github.com/bartveneman/wallace-cli) - CSS statistics in
  your CLI
- [Color Sorter](https://github.com/bartveneman/color-sorter) - Sort CSS colors
  by hue, saturation, lightness and opacity
- [Gromit CLI](https://github.com/bartveneman/gromit-cli) - A test framework to
  assert that CSS statistics don't exceed certain thresholds.

## License

MIT © Bart Veneman
