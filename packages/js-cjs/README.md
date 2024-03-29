# @x-and-ai/eslint-config-js-cjs

X and AI JavaScript CommonJS ESLint Configuration

## Objectives

This ESLint configuration

- is designed for scripting with CommonJS, for example, in webpack configuration scripts.
- supports parsing ECMAScripts 10 (2019) and below except ES modules.

## Requirements

- Node.js >= 16
- ESLint >= 8.7.0
- Prettier >= 2.5.1

## Installation

```sh
yarn add -D @x-and-ai/eslint-config-js-cjs
```

## Usage

```js
module.exports = {
  extends: ['@x-and-ai/eslint-config-js-cjs'],
};
```
