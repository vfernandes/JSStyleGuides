# Style guide

## ESLint, Prettier and EditorConfig

### `yarn i`

Install dependences.

### `yarn start`

[http://localhost:3000](http://localhost:3000) to view it in the browser.

### Create

npx create-react-app style-guide\

yarn run eslint --init\

> How would you like to use ESLint? **To check syntax, find problems, and enforce code style**\
> What type of modules does your project use? **JavaScript modules (import/export)**\
> Which framework does your project use? **React**\
> Does your project use TypeScript? **Yes**\
> Where does your code run? **Browser**\
> How would you like to define a style for your project? **Use a popular style guide**\
> Which style guide do you want to follow? **Airbnb: [link](https://github.com/airbnb/javascript)**\
> What format do you want your config file to be in? **json**\

### Install plug-in ESLint

Integrates ESLint JS into vscode.

### Visual Code `>Preferences: Open Settings (JSON)`

```JSON
// Set the default
"editor.formatOnSave": false,
// Enable per-language
"[javascript]": {
    "editor.formatOnSave": true
}
```

#### Formats

```js
javascript;
javascriptreact;
typescript;
typescriptreact;
json;
graphql;
```

[More info](https://github.com/prettier/prettier-vscode#linter-integrationn)

### Install EditorConfig

### `Generate file .editorconfig`
