# react-scripts

## Custom icapps implementation
**This is a custom implementation of react-scripts.**

**In this version we allow `HEROKU_*` env variables.**

Things we adapted: 
- L69 -> `const REACT_APP = /^(REACT_APP_)/i;` to `const REACT_APP = /^(REACT_APP_|HEROKU_)/i;`

## Originial readme

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
