# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.

## Customization pupose
Transpile untranspiled modules from node_modules for Create React App. Makes it easy to have local libraries and keep a slick, manageable dev experience.

## Customized files

- `packages/react-scripts/config/paths.js` - Finds your custom react components and gets their full path
- `packages/react-scripts/config/webpack.config.js` - Declares which files go through babel loader
- `packages/react-scripts/package.json` - Versioning and other stuff
- `packages/react-scripts/scripts/init.js` - Initialization messages
- `packages/react-scripts/template/public/index.html` - Started index html
- `packages/react-scripts/template/src/App.js` - Starter app js

## Tutorial

You can follow this [tutorial](https://auth0.com/blog/how-to-configure-create-react-app/) to tweak more of the react scripts.