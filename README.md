# kashall-lint
 A central shareable eslint config for all of my repos. Intended for private use but you can use it too.

```bash
npm i --save-dev Kashalls/kashall-lint
```

## standard eslint rules
```json
{
	"extends": "kashall"
}
```
requires:
* eslint

## markdown codeblock eslint rules
```json
{
	"extends": "kashall/md"
}
```
requires:
* eslint
* eslint-plugin-markdown

## eslint-typescript rules
```json
{
	"extends": "kashall/eslint-ts"
}
```
requires:
* eslint
* @typescript-eslint/parser
* @typescript-eslint/eslint-plugin

## tslint rules
```json
{
	"extends": "eslint-config-kashall/ts"
}
```
requires:
* tslint
