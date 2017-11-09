# preact-template-ts

## Documentation
- This is a template for using with [preact-cli](https://github.com/developit/preact-cli).
- This template is a blank slate but uses `Preact`, `Webpack`, `TypeScript`, and supports `SASS` and dev/prod builds with related optimizations out of the box, including `webpack-dev-server`.
- [For Preact](https://preactjs.com/): General information about how to work with Preact, not specific to this template

## Usage

``` bash
$ npm install -g preact-cli
$ preact create NateRadebaugh/preactjs-template-ts my-project
$ cd my-project
$ yarn
$ yarn dev
```

Development server runs on port `9000`. If the default port is already in use on your machine it will start the development server on a random port.

## Commands

- `yarn dev`: Run a development, HMR server using `webpack-dev-server`

- `yarn build:dev`: Development-ready standalone build with no optimizations

- `yarn build:prod`: Production-ready standalone build with full optimizations
