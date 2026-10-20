# Playground

A Webpack starter workspace with ES6 compilation, Sass, PostCSS and linting configuration.

## Local development

Run these commands from the repository root:

```sh
npm install
npm start
```

Available scripts:

- `npm run build`: `cross-env NODE_ENV=production webpack --config webpack/webpack.config.prod.js`.
- `npm run lint`: `npm run lint:styles; npm run lint:scripts`.
