# @x-and-ai/eslint-config-ts-node

X and AI TypeScript Node.js ESLint Configuration

## Objectives

This ESLint configuration

- is designed for linting TypeScript Node.js code.
- supports parsing ECMAScripts 11 (2020) and below with ES modules.

## Requirements

- Node.js >= 12
- ESLint >= 7.10.0
- TypeScript >= 4.0.3
- Prettier >= 2.1.2

## Installation

```sh
yarn add -D @x-and-ai/eslint-config-ts-node
```

## Usage

```js
module.exports = {
  extends: ['@x-and-ai/eslint-config-ts-node'],
};
```
