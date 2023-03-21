# @ayloncarrijo/eslint-config

A shareable ESLint config used in my projects.

## What's supported by this config?

- JavaScript;
- TypeScript;
- React;

## Install

```
pnpm add -D eslint @ayloncarrijo/eslint-config
```

## Usage

1. Add a `.eslintrc.js` file in the root of the project extending the config:

```js
module.exports = {
  extends: ["@ayloncarrijo/eslint-config"],
};
```

> You can also use a `.eslintrc.json` instead of `.eslintrc.js` if you prefer.

2. If you are using TypeScript and your `tsconfig.json` is not located in the same directory as your ESLint config, you will need to provide a path to it:

```js
module.exports = {
  extends: ["@ayloncarrijo/eslint-config"],
  parserOptions: {
    project: "./tsconfig.json",
  },
};
```
