# @kashalls/eslint-config

> :scroll: **Shareable ESLint configuration for my projects**

```bash
npm i --save-dev @kashalls/eslint-config
yarn add -D @kashalls/eslint-config
```

## standard eslint rules
```json
{
	"extends": "@kashalls"
}
```
requires:
* eslint

## eslint-typescript rules
```json
{
	"extends": "@kashalls/ts"
}
```
requires:
* eslint
* @typescript-eslint/parser
* @typescript-eslint/eslint-plugin
