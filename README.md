# typescript-esm-cjs-interop

This repo demonstrates a problem with the Typescript esModuleInterop. If typescript is given a CJS module whose exports include an enumerable `default` property, an error is thrown.

## Demonstration of issue

```sh
node lib/index.js
```

Note the "Cannot redefine property: default" error that is thrown

## Compiling the code

```sh
yarn compile
```
