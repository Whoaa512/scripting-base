# Node scripting base

This repo is a starter template for basic Node.js/Typescript scripting needs

This repo requires:

1. A Node.js version manager installed that respects `.node-version`. See [`fnm`](https://github.com/Schniz/fnm#installation) if you need one
2. Yarn installed and available in shell, see [install instructions here](https://classic.yarnpkg.com/en/docs/install)


## Dev setup

First time setup

```sh
# Install deps
yarn install

# Initial precommit hooks
yarn hook-install
```

Then create scripts


## Included packages

This repo assumes you'll be writing in TypeScript and includes some basic deps to make life easier

### Helpful libraries

- [`got`](https://github.com/sindresorhus/got) - Human-friendly and powerful HTTP request library for Node.js
- [`lodash`](https://github.com/lodash/lodash) - A modern JavaScript utility library delivering modularity, performance, & extras.

### Development stuff

- [`nodemon`](https://github.com/remy/nodemon) - Re-run executables after file change
- [`eslint`](https://eslint.org/) - Linter
- [`prettier`](https://prettier.io) - Autoformatter
- [`ts-node`](https://www.npmjs.com/package/ts-node) - Simple TypeScript execution directly for Node
