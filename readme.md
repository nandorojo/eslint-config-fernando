# Fernando Rojo's eslint config 🏋🏻‍♂️

Meant for react native projects using Typescript.

```sh
yarn add --dev eslint-config-nando eslint
```

If you're using typescript, do this too:

```sh
yarn add --dev typescript
```

Create the following two files at the root of your react native project:

**`.eslintrc`**

```
{
	"extends": ["nando"]
}
```

**`.prettierrc`**

```json
{
	"singleQuote": true,
	"trailingComma": "es5",
	"overrides": [{ "files": "*.ts", "options": { "parser": "typescript" } }],
	"semi": false,
	"jsxSingleQuote": false,
	"useTabs": true,
	"tabWidth": 4
}
```
