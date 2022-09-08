# eslint8-test-app

Test app to debug ESLint error:

```
Parsing error: Cannot use keyword 'await' outside an async function
```

## Setup commands

```sh
# create app.js
npm init --yes
npm install --save-dev eslint@8
npm install --save-dev @babel/eslint-parser
npm install --save-dev @babel/core
npx eslint --init
# How would you like to use ESLint? · problems
# What type of modules does your project use? · esm
# Which framework does your project use? · none
# Does your project use TypeScript? · No / Yes
# Where does your code run? · browser, node
# What format do you want your config file to be in? · YAML
```
