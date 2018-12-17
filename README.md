# @komondor-lab/config

![unstable][unstable-image]
[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]

[![Circle CI][circleci-image]][circleci-url]
[![Travis CI][travis-image]][travis-url]
[![Codecov][codecov-image]][codecov-url]
[![Coveralls Status][coveralls-image]][coveralls-url]

[![Greenkeeper][greenkeeper-image]][greenkeeper-url]
[![Semantic Release][semantic-release-image]][semantic-release-url]

[![Visual Studio Code][vscode-image]][vscode-url]
[![Wallaby.js][wallaby-image]][wallaby-url]

Description for `@komondor-lab/config`

## Contribute

```sh
# right after fork
npm install

# begin making changes
git checkout -b <branch>
npm run watch

# edit `webpack.config.dev.js` to exclude dependencies for the global build.

# after making change(s)
git commit -m "<commit message>"
git push

# create PR
```

## Npm Commands

There are a few useful commands you can use during development.

```sh
# Run tests (and lint) automatically whenever you save a file.
npm run watch

# Run tests with coverage stats (but won't fail you if coverage does not meet criteria)
npm run test

# Manually verify the project.
# This will be ran during 'npm preversion' so you normally don't need to run this yourself.
npm run verify

# Build the project.
# You normally don't need to do this.
npm run build

# Run tslint
# You normally don't need to do this as `npm run watch` and `npm version` will automatically run lint for you.
npm run lint
```

[circleci-image]: https://circleci.com/gh/komondor-lab/config/tree/master.svg?style=shield
[circleci-url]: https://circleci.com/gh/komondor-lab/config/tree/master
[codecov-image]: https://codecov.io/gh/komondor-lab/config/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/komondor-lab/config
[coveralls-image]: https://coveralls.io/repos/github/komondor-lab/config/badge.svg
[coveralls-url]: https://coveralls.io/github/komondor-lab/config
[downloads-image]: https://img.shields.io/npm/dm/@komondor-lab/config.svg?style=flat
[downloads-url]: https://npmjs.org/package/@komondor-lab/config
[greenkeeper-image]: https://badges.greenkeeper.io/komondor-lab/config.svg
[greenkeeper-url]: https://greenkeeper.io/
[npm-image]: https://img.shields.io/npm/v/@komondor-lab/config.svg?style=flat
[npm-url]: https://npmjs.org/package/@komondor-lab/config
[semantic-release-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]: https://github.com/semantic-release/semantic-release
[travis-image]: https://img.shields.io/travis/komondor-lab/config/master.svg?style=flat
[travis-url]: https://travis-ci.org/komondor-lab/config?branch=master
[unstable-image]: https://img.shields.io/badge/stability-unstable-yellow.svg
[vscode-image]: https://img.shields.io/badge/vscode-ready-green.svg
[vscode-url]: https://code.visualstudio.com/
[wallaby-image]: https://img.shields.io/badge/wallaby.js-configured-green.svg
[wallaby-url]: https://wallabyjs.com
