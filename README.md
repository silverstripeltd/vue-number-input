# vue-number-input

[![Build Status](https://img.shields.io/travis/fengyuanchen/vue-number-input.svg)](https://travis-ci.org/fengyuanchen/vue-number-input) [![Coverage Status](https://img.shields.io/codecov/c/github/fengyuanchen/vue-number-input.svg)](https://codecov.io/gh/fengyuanchen/vue-number-input) [![Downloads](https://img.shields.io/npm/dm/@chenfengyuan/vue-number-input.svg)](https://www.npmjs.com/package/@chenfengyuan/vue-number-input) [![Version](https://img.shields.io/npm/v/@chenfengyuan/vue-number-input.svg)](https://www.npmjs.com/package/@chenfengyuan/vue-number-input)

> Number input component for Vue 3.

- [Docs](src/README.md)
- [Demo](https://fengyuanchen.github.io/vue-number-input)

## Main files

```text
dist/
├── vue-number-input.js         (UMD, default)
├── vue-number-input.min.js     (UMD, compressed)
├── vue-number-input.esm.js     (ECMAScript Module)
├── vue-number-input.esm.min.js (ECMAScript Module, compressed)
└── vue-number-input.d.ts       (TypeScript Declaration File)
```

## Getting started

### Installation

```shell
npm install vue @chenfengyuan/vue-number-input
```

In browser:

```html
<script src="/path/to/vue.js"></script><!-- Vue.js is required -->
<script src="/path/to/vue-number-input.js"></script><!-- Register automatically once loaded -->
```

### Usage

```js
import Vue from 'vue';
import VueNumberInput from '@chenfengyuan/vue-number-input';

const app = Vue.createApp({});

app.component(VueNumberInput.name, VueNumberInput);
```

```html
<vue-number-input controls></vue-number-input>
```

## Browser support

Same as Vue 3.

## Versioning

Maintained under the [Semantic Versioning guidelines](https://semver.org/).

## License

[MIT](https://opensource.org/licenses/MIT) © [Chen Fengyuan](https://chenfengyuan.com/)
