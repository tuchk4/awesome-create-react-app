# Awesome Create React App

A collection of awesome things regarding CRA ecosystem.

## Create React App General Resources

* [Create React App GitHub](https://github.com/facebookincubator/create-react-app)
* [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md)

## Useful links

* [Maintaining a fork of react-scripts as an alternative to ejecting](https://github.com/facebookincubator/create-react-app/issues/682)


## Alternatives

* [React app rewired](https://github.com/timarney/react-app-rewired)
* [Custom react scripts](https://www.npmjs.com/package/custom-react-scripts)

## FAQ

### How to use env variables

* [Adding Custom Environment Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-custom-environment-variables)

> Your project can consume variables declared in your environment as if they were declared locally in your JS files. By default you will have NODE_ENV defined for you, and any other environment variables starting with REACT_APP_. These environment variables will be defined for you on process.env. For example, having an environment variable named REACT_APP_SECRET_CODE will be exposed in your JS as process.env.REACT_APP_SECRET_CODE, in addition to process.env.NODE_ENV

* [Adding Development Environment Variables In `.env`](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-development-environment-variables-in-env)
> To define permanent environment variables, create a file called .env in the root of your project

### How to use multiple env configs

Right now it is possible by changing `npm scripts`:

```json
"scripts": {
  "start": "node -r dotenv/config ./node_modules/.bin/react-scripts start dotenv_config_path=development.env",
  "build": "node -r dotenv/config ./node_modules/.bin/react-scripts build dotenv_config_path=production.env"
}
```

There is the feature request with [PR](https://github.com/facebookincubator/create-react-app/pull/1344) - [Different env config](https://github.com/facebookincubator/create-react-app/issues/1343)

Read different `.env` configs according to current command (start / test / build).

* Read `dev.env` when npm start and npm test
* Read `prod.env` when npm run build

By default (if custom config does not exist) read env variables from .env file.



### How to change dev server PORT

Add `PORT` env variable. Use [cross-env](https://github.com/kentcdodds/cross-env) to set environment variables across platforms.

```json
"scripts": {
  "start": "cross-env PORT=9001 react-scripts start"
}
```

If you use `.env` config - just add `PORT` variable:

```
PORT=9001
```

### How to setup root dir for require (webpack module.resolveDirectory analog)?

Add `NODE_PATH` env variable. Directory name to be resolved to the current directory as well as its ancestors, and searched for modules. It is [resolve.modulesDirectories](https://webpack.github.io/docs/configuration.html#resolve-modulesdirectories) for webpack. More details at node official doc ["Loading from the global folders"](https://nodejs.org/api/modules.html#modules_loading_from_the_global_folders)

```json
"scripts": {
  "start": "cross-env NODE_PATH=src/scripts react-scripts start"
}
```

If you use `.env` config - just add `NODE_PATH` variable:

```
NODE_PATH=src/scripts
```

### How to use custom babel presets

Create React App [doesn’t support decorator syntax](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#can-i-use-decorators) at the moment.

There are PR [Adding support for custom babel configuration #1357](https://github.com/facebookincubator/create-react-app/pull/1357). If that PR will be merged then:

- [Decorators](https://www.npmjs.com/package/babel-plugin-transform-decorators )
- Features from [stage-0 preset](https://babeljs.io/docs/plugins/preset-stage-0/)
- Any new babel features and presets

[@dan_abramov](https://twitter.com/dan_abramov) wrote:

> * [I'm happy to add decorators after they've moved to stage 3](https://twitter.com/dan_abramov/status/818626114037968899)

> * [Bind proposal hasn't been updated in a long time and doesn't appear to progress. Might not make it at all either.](https://twitter.com/dan_abramov/status/818626659926609920)

> * [Imagine the horror of building / maintaining an app that relies on dead syntax features five years from now.](https://twitter.com/dan_abramov/status/818627079306694658)


So we do not recomend to use babel presets besides the [babel-preset-react-app](https://github.com/facebookincubator/create-react-app/tree/master/packages/babel-preset-react-app) that is already configured at Create React App.

### How to change webpack config?
### How to add custom webpack plugins?

```json
"scripts": {
  "start": "node scripts/webpack"
}
```

```js
// scripts/webpack.js
const webpack = require('react-scripts/node_modules/webpack');
const craWebpackConfig = require('react-scripts/config/webpack.config.prod');
const OfflinePlugin = require('offline-plugin');

const config = {
  ...craWebpackConfig,
  plugins: [
     ...craWebpackConfig.plugins,
     new OfflinePlugin()
  ]
};

webpack(config).run(function(err, stats) {
  if (err !== null) {
    console.log('done');
  } else {
    console.log(err);
  }
});
```
