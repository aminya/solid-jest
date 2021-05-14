# Solid Jest

This library contains presets for SolidJS to easily get started testing with Jest for both browser and server rendering with Node. The config supports TypeScript out of the box.

### Usage

In your jest.config.js

```js
module.exports = {
  preset: "solid-jest/preset/browser"
};
```

```js
module.exports = {
  preset: "solid-jest/preset/node"
};
```