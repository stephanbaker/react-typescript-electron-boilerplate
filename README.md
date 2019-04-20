# React + Typescript + Electron Boilerplate

This is a minimal boilerplate that serves as a starting point when creating applications using [React](https://reactjs.org/), [TypeScript](https://www.typescriptlang.org/), and the [Electron](https://electronjs.org/) runtime.

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Thanks to [Kitze](https://twitter.com/thekitze) for the [Medium article](https://medium.com/@kitze/%EF%B8%8F-from-react-to-an-electron-app-ready-for-production-a0468ecb1da3) discussing how to set up a project with Electron and create-react-app.

Although I welcome comments/suggestions, this project is intended for personal use and not as a production resource.

## Scripts

### `npm start`

This will open an Electron window connected to the React app using _webpack-dev-server_. This allows you to continue developing with hot-reloading.

### `npm run build`

This is used to build a static desktop application. It will first generate the static React application in the _build_ folder and then use electron-builder to package it into an electron application in the _dist_ folder.
