# eslint-config-customink

This package provides CustomInks's [`ESLint`](http://eslint.org/) configurations as [shareable configs](http://eslint.org/docs/developer-guide/shareable-configs.html).

## Installation

`npm install --save-dev eslint-config-customink`

## Usage

Add `"extends": ["customink"]` to your ESLint config file to get the base eslint configuration. You can also use `customink/browser`, `customink/node`, and `customink/react`.

## Example

```js
// eslintrc.js

module.exports = {
  "extends": [
    "customink/browser",
    "customink/react"
  ]
};
```
