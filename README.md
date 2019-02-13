# Awesome Create React App [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/tuchk4/awesome-create-react-app.svg?branch=master)](https://travis-ci.org/tuchk4/awesome-create-react-app)

A collection of awesome things regarding Create React App ecosystem.

## Table of Contents

- [Create-React-App General Resources](#create-react-app-general-resources)
- [Tools](#tools)
- [CRAFT Templates](#craft-templates)
- [Deployment](#deployment)
- [Articles](#articles)
- [Tweaking Configuration](#tweaking-configuration)
- [Video Tutorials](#video-tutorials)
- [React Scripts Versions](#react-scripts-versions)
- [Alternatives](#alternatives)
- [FAQ](#faq)
  - [How to Use Env Config](#how-to-use-env-config)
  - [How to Use Multiple Env Configs](#how-to-use-multiple-env-configs)
  - [Advanced Configuration](#advanced-configuration)
  - [Lazy Loading](#lazy-loading)
  - [How to Setup Root Dir for Require?](#how-to-setup-root-dir-for-require)
  - [HMR (Hot Module Replacement)](#hmr-hot-module-replacement)
  - [How to Use Custom Babel Presets](#how-to-use-custom-babel-presets)
  - [How to Change Webpack Entry Point and Output Dir?](#how-to-change-webpack-entry-point-and-output-dir)
  - [Watching Build Mode on Create React App](#watching-build-mode-on-create-react-app)
  - [How to Change Webpack Config](#how-to-change-webpack-config)
  - [How to Add Custom Webpack Plugins](#how-to-add-custom-webpack-plugins)


## Create-React-App General Resources

- [Create React App GitHub](https://github.com/facebookincubator/create-react-app)
- [Create React App 2.0](https://reactjs.org/blog/2018/10/01/create-react-app-v2.html)
- [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md)
- [Why I Love Create React App and Don't Want to Eject](https://medium.com/@valeriy.sorokobatko/why-i-love-create-react-app-e63b1be689a3)


## Tools

- [CRA Generate: Scaffold a React Component](https://github.com/rthor/cra-generate) - Scaffold a React component.
- [CRAFT: Create React App From Template](https://medium.com/@stoyanstefanov/craft-create-react-app-from-template-7fd3383d0954) - Create-React-App from the template
- [CRA Universal CLI](https://github.com/antonybudianto/cra-universal) - CLI for SSR Create React App, without eject

## CRAFT Templates

- [CRA + Progressive Web App goodness](https://github.com/jeffposnick/create-react-pwa/) - Progressive Web App tempalte.
- [File API Input Layer](https://github.com/stoyan/fail) - File Upload Tempalte
- [An Almost Static Stack. CRA + react-snapshot](https://github.com/superhighfives/an-almost-static-stack) - Bridge the gap between static sites and single page apps.
- [CRA + Redux](https://github.com/tuchk4/craft-redux) - Create React App Template with Redux and Router
- [Craft Template - MobX + React Router](https://github.com/timarney/cra-mobx-reactrouter) - CRA Template with Mobx and Router

## Deployment

- [Surge VS GitHub Pages: How to Deploy A Create-React-App Project](https://medium.freecodecamp.com/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089#.7mahr7kyj)
- [How to Deploy a Create-React-App (Nginx)](https://www.peterbe.com/plog/how-to-deploy-a-create-react-app)
- [Netlify: Deploy React Apps in Less Than 30 Seconds](https://www.netlify.com/blog/2016/07/22/deploy-react-apps-in-less-than-30-seconds/)
- [Zero Configuration Deployment for React Apps With Zeit's Now and Now-Deploy](https://medium.com/@kawixiao/zero-configuration-deployment-for-react-apps-with-zeits-now-4f002be98c)
- [Heroku: Deploying React With Zero Configuration](https://blog.heroku.com/deploying-react-with-zero-configuration)
- [Create React App Buildpack](https://github.com/mars/create-react-app-buildpack)
- [Creare React App - now.sh](https://github.com/xkawi/create-react-app-now)

## Articles

- [Learning React With Create-React-App (Part 1)](https://medium.com/@diamondgfx/learning-react-with-create-react-app-part-1-a12e1833fdc)
- [Learning React With Create-React-App (Part 2)](https://medium.com/@diamondgfx/learning-react-with-create-react-app-part-2-3ad99f38b48d)
- [Learning React With Create-React-App (Part 3)](https://medium.com/@diamondgfx/learning-react-with-create-react-app-part-3-322447d14192)
- [Learning React With Create-React-App (Part 4)](https://medium.com/@diamondgfx/learning-react-with-create-react-app-part-4-9f843c8c1ccc)
- [How to Create ClojureScript App](https://medium.com/@roman01la/how-to-create-clojurescript-app-4e38778c4762)
- [How to Create Elm App](https://medium.com/@eduardkyvenko/how-to-create-elm-app-cf052629a11a)
- [Creare React App - now.sh](https://www.fullstackreact.com/articles/using-create-react-app-with-a-server/)
- [How to Get "Create-React-App" to Work With Your Rails API](https://www.fullstackreact.com/articles/how-to-get-create-react-app-to-work-with-your-rails-api/)
- [Using Create-React-App With React Router + Express.js](https://medium.com/@patriciolpezjuri/using-create-react-app-with-react-router-express-js-8fa658bf892d)
- [Adding Hot Module Reloading to Create React App](https://medium.com/@sheepsteak/adding-hot-module-reloading-to-create-react-app-e053fadf569d)
- [How You Can Use React-Toolbox With Create-React-App](https://github.com/react-toolbox/react-toolbox-themr)
- [How to Use Ant Design With Create-React-App](https://ant.design/docs/react/use-with-create-react-app)
- [How to Build an Electron App Using Create-React-App. No Webpack Configuration Or "Ejecting" Necessary](https://medium.freecodecamp.com/building-an-electron-application-with-create-react-app-97945861647c)
- [Tip: Create React App and SASS](https://medium.com/@dan_abramov/well-to-be-perfectly-clear-you-can-just-outside-of-create-react-app-setup-6e44f91cc086)
- [React / Create React App — but I Don't Wanna Eject](https://medium.com/@timarney/but-i-dont-wanna-eject-3e3da5826e39)
- [Jumpstate + Redux + Create-React-App — No Dispatching or Action-Creators Required!](https://medium.com/@tannerlinsley/jumpstate-redux-create-react-app-no-dispatch-or-action-creators-required-374e18dbcfe1)
- [Getting Started With Create React App and AVA](https://semaphoreci.com/community/tutorials/getting-started-with-create-react-app-and-ava)
- [Cabin: 7 Tutorials That Teach You How to Build a Feature-Rich, Scalable Social Network App Using React and Redux](http://cabin.getstream.io/)
- [Using Rekit to Quickly Create a React App](https://medium.com/@nate_wang/using-rekit-to-quickly-create-a-react-app-108bcc07e7f)
- [Create React App vs Other Starter Projects](http://andrewhfarmer.com/create-react-app/)
- [An Almost Static Stack](https://medium.com/superhighfives/an-almost-static-stack-6df0a2791319)
- [Upgrading a create-react-app project to SSR + code splitting](https://medium.com/@andreiduca/upgrading-a-create-react-app-project-to-a-ssr-code-splitting-setup-9da57df2040a)


## Tweaking Configuration

- [Tweaking Configuration for React Scripts in Create React App](https://medium.com/@shubheksha/tweaking-configuration-for-react-scripts-in-create-react-app-d91e9d03a42f)
- [Customizing Create-React-App](https://medium.com/@tacomanator/customizing-create-react-app-aa9ffb88165)
- [Configure Create-React-App Without Ejecting ⏏](https://medium.com/@kitze/configure-create-react-app-without-ejecting-d8450e96196a)
- [Create-React-Scripts — create your own react-scripts without fork](https://medium.com/@szer0601/create-react-scripts-create-your-own-react-scripts-without-fork-e73d384c7369)

## Video Tutorials

- [Getting Started With React With Create React App](https://www.youtube.com/watch?v=pCgDRgmfilE)
- [Create React App - What's All the Fuss About?](https://www.youtube.com/watch?v=wLgHjZM4pWM)
- [Create React App With ExpressJS and Now](https://www.youtube.com/watch?v=HfAPmRpxQEY)
- [Migrate to Create React App](https://www.youtube.com/watch?v=g8O0FT0uoDA)
- [Use Create-React-App to Setup a Simple React App](https://egghead.io/lessons/react-react-fundamentals-development-environment-setup)
- [Why I Love Create React App (React Allicante 2017)](https://www.youtube.com/watch?v=Jn18gZ9jO0U)


## React Scripts Versions

This is not documented yet. More info at [Maintaining a fork of react-scripts as an alternative to ejecting #682](https://github.com/facebookincubator/create-react-app/issues/682)

- [React Super Scripts](https://github.com/shrynx/react-super-scripts) - Adds super powers to create-react-app and allows custom configs without ejecting.
- [React Scripts (Isomorphic)](https://github.com/firstlookmedia/react-scripts) - Provides configuration for FLM's isomorphic React apps.
- [Create React App Sass](https://github.com/rickharrison/create-react-app-sass) - Enhances create-react-app to include support for Sass.
- [Custom React Scripts](https://www.npmjs.com/package/custom-react-scripts) - Configuration and scripts for Create React App.
- [Typescript React Starter](https://github.com/Microsoft/TypeScript-React-Starter) - CRA scripts version maintained by Microsoft's team to start apps with Typescript.
- [React Scripts Web](https://github.com/raymondsze/create-react-scripts/tree/master/packages/react-scripts-web) - React-scripts built using create-react-scripts, supports workbox(PWA), vendorDll, babelrc and eslintrc.
- [React Scripts With SSR](https://github.com/joernb/react-scripts-with-ssr) - Adds server-side rendering to create-react-app projects.


## Alternatives

- [React App Rewired](https://github.com/timarney/react-app-rewired) - Configure the unconfigurable, override create-react-app webpack configs.
- [Create React Scripts](https://github.com/raymondsze/create-react-scripts/tree/master/packages/create-react-scripts) - Easily extend the react-scripts from create-react-app to your own version of react-scripts. Package for SSR, Less, Sass, Workbox(PWA), VendorDll are included.

Alternatives from [Create React App README](https://github.com/facebookincubator/create-react-app#alternatives):

- [insin/nwb](https://github.com/insin/nwb) - A toolkit for React, Preact & Inferno apps, React libraries and other npm modules for the web, with no configuration (until you need it).
- [mozilla/neo](https://github.com/mozilla/neo) - Create and build React web applications with zero initial configuration and minimal fuss.
- [NYTimes/kyt](https://github.com/NYTimes/kyt) - Drowning in Webpack configs? Try this build, test and development tool for advanced JavaScript apps.
- [zeit/next.js](https://github.com/zeit/next.js) - Framework for server-rendered React apps.
- [gatsbyjs/gatsby](https://github.com/gatsbyjs/gatsby) - Transform plain text into dynamic blogs and websites using React.

Notable alternatives also include:

- [enclave](https://github.com/eanplatter/enclave) - A simpler way to compile React applications.
- [motion](https://github.com/motion/motion) - A simple CLI for running React projects.
- [quik](https://github.com/satya164/quik)- A quick way to prototype and build apps with React and Babel with zero-setup.
- [sagui](https://github.com/saguijs/sagui) - Front-end tooling in a single dependency.
- [roc](https://github.com/rocjs/roc)- Modern JavaScript Development Ecosystem.
- [aik](https://github.com/d4rkr00t/aik)- Frontend Playground.
- [react-app](https://github.com/kriasoft/react-app) - CLI tools and templates for authoring React applications with a single dev dependency and no configurations.
- [dev-toolkit](https://github.com/stoikerty/dev-toolkit) - Development Toolkit for React Veterans.
- [tarec](https://github.com/geowarin/tarec) - The Awesome React Cli.


## FAQ

### How to Use Env Config

- [Adding Custom Environment Variables](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-custom-environment-variables)

> Your project can consume variables declared in your environment as if they were declared locally in your JS files. By default you will have NODE_ENV defined for you, and any other environment variables starting with REACT_APP_. These environment variables will be defined for you on process.env. For example, having an environment variable named REACT_APP_SECRET_CODE will be exposed in your JS as process.env.REACT_APP_SECRET_CODE, in addition to process.env.NODE_ENV

- [Adding Development Environment Variables In `.env`](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-development-environment-variables-in-env)

> To define permanent environment variables, create a file called .env in the root of your project

### How to Use Multiple Env Configs

Right now it is possible installing [dotenv](https://github.com/motdotla/dotenv) and updating npm scripts:

```json
"scripts": {
  "start": "node -r dotenv/config ./node_modules/.bin/react-scripts start dotenv_config_path=development.env",
  "build": "node -r dotenv/config ./node_modules/.bin/react-scripts build dotenv_config_path=production.env"
}
```

There is the Pull Request [#1344](https://github.com/facebookincubator/create-react-app/pull/1344) that implements [Support different env configs](https://github.com/facebookincubator/create-react-app/issues/1343):

Read different `.env` configs according to current command (start / test / build).

What .env* files are used?

* `.env` - Default
* `.env.development`, `.env.test`, `.env.production` - Environment-specific settings.
* `.env.local` - Local overrides. This file is loaded for all environments except test.
* `.env.development.local`, `.env.test.local`, `.env.production.local` - Local overrides of environment-specific settings.

Files priority (file is skipped if does not exist):

* npm test - `.env.test.local`, `env.test`, `.env.local`, `.env`
* npm run build - `.env.production.local`, `env.production`, `.env.local`, `.env`
* npm start - `.env.development.local`, `env.development`, `.env.local`, `.env`

Priority from left to right.

By default (if custom config does not exist) read env variables from .env file.

### Advanced Configuration 

<img src="https://camo.githubusercontent.com/59e1be59d191ad29983a91b039f0e9089918dfb4/68747470733a2f2f7075752e73682f745866456c2f336361346536636264652e706e67" alt="Create React App Advanced Configuration"/>

These are environment variables. Use [cross-env](https://github.com/kentcdodds/cross-env) to set environment variables across platforms or *.env* config.

```json
"scripts": {
  "start": "cross-env BROWSER=firefox react-scripts start"
}
```

If you use `.env` config - just add `BROWSER` variable:

```
BROWSER=none
```

### Lazy Loading

Original issue - [Lazy load (chunking) feature? #925](https://github.com/facebookincubator/create-react-app/issues/925)

> You can use require.ensure() because we use webpack under the hood.
When we switch to webpack 2, you can use System.import instead.

### How to Setup Root Dir for Require

What is the alternative for `webpack module.resolveDirectory`?

Official solution: create `node_modules` at `src` directory - [src/node_modules as official solution for absolute imports #1065](https://github.com/facebookincubator/create-react-app/issues/1065)

Another way - use `NODE_PATH` env variable. It is a directory name to be resolved to the current directory as well as its ancestors, and searched for modules. It is [resolve.modules](https://webpack.js.org/configuration/resolve/#resolve-modules) for webpack. More details at node official documentation ["Loading from the global folders"](https://nodejs.org/api/modules.html#modules_loading_from_the_global_folders).

```json
"scripts": {
  "start": "cross-env NODE_PATH=src/scripts react-scripts start"
}
```

If you use `.env` config - just add `NODE_PATH` variable:

```
NODE_PATH=src/scripts
```

## HMR (Hot Module Replacement)

By default HMR works only for CSS modules. If you want to use for components add these lines to *index.js*:

> NOTE: This will work but not preserve the components state, but redux / mobx / whatever state managers will be preserved

```js
// App - root component
import App from './App';

const render = Root => {
  ReactDOM.render(<Root />,
    document.getElementById('root')
  );
}

render(App);

if (module.hot) {
  module.hot.accept('./App', () => {
    var NextApp = require('./App').default;
    render(NextApp);
  });
}
```

### How to Use Custom Babel Presets

Create React App [doesn’t support decorator syntax](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#can-i-use-decorators) at the moment.

There are PR [Adding support for custom babel configuration #1357](https://github.com/facebookincubator/create-react-app/pull/1357). If PR is merged then these features will be available:

- [Decorators](https://www.npmjs.com/package/babel-plugin-transform-decorators )
- Features from [stage-0 preset](https://babeljs.io/docs/plugins/preset-stage-0/)
- Any new babel features and presets

PR is closed but

- As soon as feature becomes candidate - CRA will support it. Here is [tweet](https://twitter.com/dan_abramov/status/818626114037968899) about decorators.
- Features from stages 0 - 2 are not support because a lot of them hasn't been updated in a long time and doesn't appear to progress.

[@dan_abramov](https://twitter.com/dan_abramov) wrote:

> - [I'm happy to add decorators after they've moved to stage 3](https://twitter.com/dan_abramov/status/818626114037968899)

> - [Bind proposal hasn't been updated in a long time and doesn't appear to progress. Might not make it at all either.](https://twitter.com/dan_abramov/status/818626659926609920)

> - [Imagine the horror of building / maintaining an app that relies on dead syntax features five years from now.](https://twitter.com/dan_abramov/status/818627079306694658)


So we do not recommend to use babel presets besides the [babel-preset-react-app](https://github.com/facebookincubator/create-react-app/tree/master/packages/babel-preset-react-app) that is already configured at Create React App.

### How to Change Webpack Entry Point and Output Dir?

There is the issue - [Customize build folder #1354](https://github.com/facebookincubator/create-react-app/issues/1354).
This is feature is very useful along with entry point customizing and I have left  [comment](https://github.com/facebookincubator/create-react-app/issues/1354#issuecomment-275647959) about this.

But according to this Pull Request [Fix- react-scripts build doesn't allow for specified path #1362](https://github.com/facebookincubator/create-react-app/pull/1362#issuecomment-271284738) we should not expect such customizations in near future.

> won’t be introducing more configuration on a case-by-case basis. We might add support for a configuration file at some point, but not now.

There are some hacks how to change webpack config but note that it is officially unsupported and can break in any version.

### Watching Build Mode on Create React App

Example is [here](https://gist.github.com/int128/e0cdec598c5b3db728ff35758abdbafd)

### How to Change Webpack Config?
### How to Add Custom Webpack Plugins?

```json
"scripts": {
  "build:custom": "node scripts/webpack"
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

**Note: this is officially unsupported and can break in any version.**

Also note that this is just webpack config extending, not `react-scripts build`. There is not beautiful console logs, comparison of the build size and other `react-scitpts build` command features.

Such approach (workaround) also helps to resolve problems when need to build/pubish a single component. There is the related issue - [How to publish components without ejecting #796](https://github.com/facebookincubator/create-react-app/issues/796). Just override webpack entry point and output.

Always remember that using not usual loaders (like yaml, markdown, dsv loaders etc.), additional plugins and features from drafts and proposals makes your application more complex, maybe with dead syntax features and it is become impossible to migrate from current webpack configuration.
