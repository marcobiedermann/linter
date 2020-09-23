# @marcobiedermann/tsconfig

[![peerDependencies Status](https://david-dm.org/marcobiedermann/linter/peer-status.svg?path=packages/tsconfig)](https://david-dm.org/marcobiedermann/linter?path=packages/tsconfig&type=peer)

Shared [`tsconfig`](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) for my projects.

## Install

```sh
npm install --save-dev @marcobiedermann/tsconfig
```

## Usage

`tsconfig.json`

```json
{
  "extends": "@marcobiedermann/tsconfig",
  "compilerOptions": {
    "outDir": "./dist"
  }
}
```

## Reference

- [tsconfig.json](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
