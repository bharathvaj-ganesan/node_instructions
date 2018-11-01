### For vue workflow setup
- Install Vetur for VS Code
- ESLint Config
```javascript

module.exports = {
  root: true,
  env: {
    node: true
  },
  extends: ["prettier/standard", "plugin:vue/essential", "@vue/prettier"],
  plugins: ["vue", "prettier"],
  rules: {
    "no-console": process.env.NODE_ENV === "production" ? "error" : "off",
    "no-debugger": process.env.NODE_ENV === "production" ? "error" : "off",
    "prettier/prettier": "error",
    "quotes": ["error", "single"]
  },
  parserOptions: {
    parser: "babel-eslint"
  }
};


```
- Prettier Config file
```javascript
module.exports = {
    trailingComma: "es5",
    tabWidth: 4,
    semi: false,
    singleQuote: true
};
```




### Reference

https://medium.com/@doppelmutzi/eslint-prettier-vue-workflow-46a3cf54332f
