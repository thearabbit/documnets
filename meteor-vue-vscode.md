# Meteor Vue for Vscode

### NPM
- babel-plugin-transform-vue-jsx
- eslint-plugin-vue
- vue-eslint-parser
- .babelrc
```
    "presets": [
        "es2015"
    ],
    "plugins": [
        "transform-vue-jsx"
    ]
```
- .eslintrc.json
```
{
    "extends": [
        "eslint:recommended",
        "plugin:vue/recommended" // or "plugin:vue/base"
    ],
    "parser": "vue-eslint-parser",
    "parserOptions": {
        "parser": "babel-eslint",
        "ecmaVersion": 2017,
        "sourceType": "module"
    },
    "rules": {
        "no-console": ["error"],
        "semi": ["error", "always"],
        "quotes": ["error", "single"]
        // override/add rules" settings here
        // "vue/valid-v-if": "error"
    }
}
```

### Vscode Plugin
- Vetur
- OneDark-Pro
- vscode-icons
- Meteor
- Auto Close Tag
- Auto Rename Tag
- Beautify css, sass and less code
- Bracket Pair Colorizer
- Color Highlight
- Color Picker
- highlight-matching-tag
- HTML CSS Support
- HTML Snippets
- IntelliSense for CSS class names
- JavaScript (ES6) snippets
- Npm Intellisense
- Path Intellisense
- Trailing Semicolon
- Node module resolve
