# Jupyterlab App

[![Build Status](https://travis-ci.org/jupyterlab/jupyterlab_app.svg?branch=master)](https://travis-ci.org/jupyterlab/jupyterlab_app)


A native app for [JupyterLab](https://github.com/jupyterlab/jupyterlab), based on [Electron](https://electron.atom.io/).

### Getting started

1. run `git clone git@github.com:jupyterlab/jupyterlab_app.git`
2. run `yarn install` or `npm install`
3. run `yarn build:all` or `npm run build:all`

### Building for distribution

To test building for distribution install [Docker](https://docs.docker.com/engine/installation/) and run `yarn dockerdist:platform` or `npm run dockerdist:platform` where "platform"
 is either "linux", "win" or "mac".
