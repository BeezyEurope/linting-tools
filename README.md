# Linting Tools
In a way to save time, maintain quality, write safer code and for the whole team to follow the same coding style we use ESLint and Stylelint as a linting tools.

## Installation

First of all you need install the ESLint and Stylelint packages. To make it available in all of your projects, install it globally.

```
npm install -g eslint stylelint
```

## Editor integration

The first step to getting immediate feedback while writing code is to add a plugin to your text editor. If you don't know how to do this, read on and we'll see how to add them in the main editors.

## Atom

To integrate ESLint and Stylelint into Atom you just need install the `linter-eslint` and `linter-stylelint` packages.

**NOTE:** Before this you need to have installed the `linter` package in Atom.

## Sublime Text

To integrate ESLint and Stylelint into Sublime Text you just need install the `SublimeLinter-eslint` and `SublimeLinter-contrib-stylelint` packages.

**NOTE:** Before this you need to have installed the `SublimeLinter` package in Sublime Text.

## VS Code

To integrate ESLint and Stylelint into VS Code you just need install the `eslint` and `stylelint` packages.

**NOTE:** You need to disable the built-in linter from VS Code to avoid duplicate alerts. To do this go to `User` or `Workspace settings` and add the following lines:

```
"css.validate": false,
"scss.validate": false
```   






