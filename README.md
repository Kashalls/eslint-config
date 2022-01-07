# @akashics/eslint-config

> :scroll: **Shareable ESLint configuration for my projects**

```bash
npm i --save-dev @akashics/eslint-config
yarn add -D @akashics/eslint-config
```

## standard eslint rules
```json
{
	"extends": "@akashics"
}
```
requires:
* eslint

## eslint-typescript rules
```json
{
	"extends": "@akashics/ts"
}
```
requires:
* eslint
* @typescript-eslint/parser
* @typescript-eslint/eslint-plugin
