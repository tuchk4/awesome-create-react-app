# Awesome Create React App [![Build Status](https://travis-ci.org/tuchk4/awesome-create-react-app.svg?branch=master)](https://travis-ci.org/tuchk4/awesome-create-react-app)

A collection of awesome things regarding Create React App ecosystem.

Please feel free to [file an issue](https://github.com/tuchk4/awesome-create-react-app/issues/new) or suggest articles, videos and other useful resources via Pull Requests.

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="http://i.imgur.com/ULoeOL4.png" height="16"/> [Why I love Create React App and don't want to eject](https://medium.com/@valeriy.sorokobatko/why-i-love-create-react-app-e63b1be689a3)

#### Create React App General Resources

- [Create React App GitHub](https://github.com/facebookincubator/create-react-app)
- [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md)

## Contests

- [Create React App Issues and Pull Requests](#create-react-app-issues-and-pull-requests)
- [Tools](#tools)
- [CRAFT Templates](#craft-templates)
- [Deployment](#deployment)
- [Articles](#articles)
- [Tweaking Configuration (workarounds)](#tweaking-configuration-workarounds)
- [Video tutorials](#video-tutorials)
- [React scripts versions](#react-scripts-versions)
- [Alternatives](#alternatives)
- [FAQ](#faq)
  - [How to use env config](#how-to-use-env-config)
  - [How to use multiple env configs](#how-to-use-multiple-env-configs)
  - [Lazy loading (chunking)](#lazy-loading-chunking)
  - [How to setup root dir for require (webpack module.resolveDirectory analog)?](#how-to-setup-root-dir-for-require-webpack-moduleresolvedirectory-analog)
  - [How to use custom babel presets](#how-to-use-custom-babel-presets)
  - [How to change webpack entry point and output dir?](#how-to-change-webpack-entry-point-and-output-dir)
  - [How to change webpack config](#how-to-change-webpack-config)


## Create React App Issues and Pull Requests

#### New Awesome merged Pull Requests

- [Add runtime error overlay](https://github.com/facebookincubator/create-react-app/pull/1101)

When an uncaught exception is thrown, an error is shown full screen similar to syntax overlay. It shows the error message and the stack.

- [Use offline cached version with yarn when it's possible](https://github.com/facebookincubator/create-react-app/pull/1423)

If you are using Yarn, and you have created at least one app previously, Create React App now works offline.

- [Fix workflow if react-scripts package is linked via npm-link #1356](https://github.com/facebookincubator/create-react-app/pull/1356)

Advanced users may opt to fork `react-scripts` instead of ejecting so they still receive upstream updates. `react-scripts` will now function as expected when linking to a development version. Previously, you could not test changes with an existing application via linking.


#### Actual Pull Requests

- [Add BuildProgressPlugin #1011](https://github.com/facebookincubator/create-react-app/pull/1011)
- [Feature/different env config files #1344](https://github.com/facebookincubator/create-react-app/pull/1344)
- [Create git repository with initial commit #1288](https://github.com/facebookincubator/create-react-app/pull/1288)
