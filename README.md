# @violentmonkey/types

![NPM](https://img.shields.io/npm/v/@violentmonkey/types.svg)
![License](https://img.shields.io/npm/l/@violentmonkey/types.svg)
![Downloads](https://img.shields.io/npm/dt/@violentmonkey/types.svg)

Type declaration for `GM_*` APIs in Violentmonkey.

The APIs should be almost the same as those in Tampermonkey, so `@types/tampermonkey` should also work.

## Installation

```bash
$ npm i @violentmonkey/types
```

Add `@violentmonkey/types` to your `tsconfig.json`:

```json
{
  "include": [
    "other paths...",
    "node_modules/@violentmonkey/types"
  ]
}
```
