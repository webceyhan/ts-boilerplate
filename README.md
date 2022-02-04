[![Test and build](https://github.com/webceyhan/ts-boilerplate/actions/workflows/test-and-build.yml/badge.svg)](https://github.com/webceyhan/ts-boilerplate/actions/workflows/test-and-build.yml)

<!-- Title -->

# TypeScript Boilerplate

<!-- Description -->

TypeScript project boilerplate with modern tooling, for Node.js programs.

It contains `src/main.ts` file as starting point for your application
and `src/main.test.ts` file as sample testing suit for your entry point.

[Report Issue](https://github.com/webceyhan/ts-boilerplate/issues) |
[Request Feature](https://github.com/webceyhan/ts-boilerplate/pulls) |
[@webceyhan](https://twitter.com/webceyhan)

<br>
<!-- Built With -->

## Built With

- [TypeScript](https://www.typescriptlang.org)
  - [ts-node](https://typestrong.org/ts-node)
  - [ts-node-dev](https://github.com/wclr/ts-node-dev)
- [Jest](https://jestjs.io/docs/getting-started)
  - [ts-jest](https://www.npmjs.com/package/ts-jest)
- [ESLint](https://eslint.org)
  - [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)

<br>
<!-- Prerequisites -->

## Prerequisites

You need to install the [Node.js](https://nodejs.dev/) and npm package manager first.

```sh
npm install npm@latest -g
```

> Recommended IDE settings:
> [VSCode](https://code.visualstudio.com/)

<br>
<!-- Installation -->

## Installation

1. Clone the repository.
   ```sh
   git clone https://github.com/webceyhan/ts-boilerplate.git
   ```
2. Get inside the cloned project folder.
   ```sh
   cd <project folder>
   ```
3. Install NPM packages.
   ```sh
   npm install
   ```

<br>

## Usage

You can use following commands to do various task with the project.

```sh
npm start           # run production app
npm run dev         # start ts-node in watch mode
npm run test        # test the application
npm run build       # build for production
```

> You can edit `package.json` and `tsconfig.json` to your liking.

> Take a look at all the available scripts in [`package.json`](https://github.com/webceyhan/ts-boilerplate/blob/master/package.json)

<br>

## Develop

Run below code to watch all file changes in the /src folder and restart the program instanly during the development.

```sh
npm run dev
```

<br>

## Test

To run the tests without the need of separate compile steps.

```sh
npm run test
```

You can also start testing in watch mode.

```sh
npm run test:watch
```

> See also the [Jest documentation](https://jestjs.io/docs/getting-started).

The tests can be automatically run on GitHub Actions: [`.github/workflows/test-and-build.yml`](https://github.com/webceyhan/ts-boilerplate/blob/master/.github/workflows/test-and-build.yml)

<br>

## Build

Compile all sources from /src into /dist folder using Typescript Compiler.

```sh
npm run build
```

Before each build, the contents will be cleaned automatically,
but you can also manually clean /dist folder by running..

```sh
npm run clean
```

Compiled files can be later deployed to any server usin Github Actions.

<br>

## References

- [Blog post: Starting a TypeScript Project in 2021](https://www.metachris.com/2021/03/bootstrapping-a-typescript-node.js-project/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [Typescript Compiler](https://www.typescriptlang.org/docs/handbook/compiler-options.html)
- [tsconfig docs](https://www.typescriptlang.org/tsconfig)
- [Jest docs](https://jestjs.io/docs/getting-started)
- [typescript-eslint docs](https://github.com/typescript-eslint/typescript-eslint/blob/master/docs/getting-started/linting/README.md)
- [GitHub Actions](https://docs.github.com/en/actions)
