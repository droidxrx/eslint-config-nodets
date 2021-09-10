# This my config ESLINT for TypeScript

> My personal config ESLINT for Node TypeScript

## Requirements

```json
{
	"eslint": "^7.32.0 or latest",
	"typescript": "^4.4.2 or latest"
}
```

## Installation

```bash
npm install eslint-config-nodets -D
yarn add eslint-config-nodets -D
```

## Usage

Add on `.eslintrc | .js | .json`

```json
{
	"extends": "eslint-config-nodets",
	"parserOptions": {
		"project": "YOUR_TSCONFIG.json",
		"ecmaVersion": 12,
		"sourceType": "module"
	}
}
```

## VSCODE SETTINGS.JSON

```json
{
	"[typescript]": {
		"editor.defaultFormatter": "dbaeumer.vscode-eslint",
		"editor.codeActionsOnSave": {
			"source.fixAll.eslint": true
		},
		"editor.formatOnSave": true
	},
	"eslint.format.enable": true
}
```

## LICENSE

[MIT](LICENSE)
