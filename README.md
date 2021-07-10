# `tsconfig.json`

```json
{
  "extends": "@stefanprobst/tsconfig"
}
```

## Usage with `ts-node`

Make sure to `yarn add -D ts-node tsconfig-paths`.

## Note

[`noUnusedLocals`](https://www.typescriptlang.org/tsconfig#noUnusedLocals) and [`noUnusedParameters`](https://www.typescriptlang.org/tsconfig#noUnusedParameters) are not turned on, it's recommended to use the [`no-unused-vars-experimental` eslint rule](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-unused-vars-experimental.md) instead.
