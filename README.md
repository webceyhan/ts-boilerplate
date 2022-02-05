<!-- AUTOMATION BADGES -->

[![CodeQL](https://github.com/webceyhan/ts-boilerplate/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/webceyhan/ts-boilerplate/actions/workflows/codeql-analysis.yml)
[![Test and build](https://github.com/webceyhan/ts-boilerplate/actions/workflows/test-and-build.yml/badge.svg)](https://github.com/webceyhan/ts-boilerplate/actions/workflows/test-and-build.yml)

 <!-- HEADER ///////////////////////////////////////////////////////////// -->

# TypeScript Boilerplate

TypeScript project boilerplate with modern tooling, for Node.js programs.

It contains `src/main.ts` file as starting point for your application
and `src/main.test.ts` file as sample testing suit for your entry point.

[View Demo](https://github.com/webceyhan/ts-boilerplate) |
[Report Issue](https://github.com/webceyhan/ts-boilerplate/issues) |
[Request Feature](https://github.com/webceyhan/ts-boilerplate/pulls) |
[@webceyhan](https://twitter.com/webceyhan)

<br>
<!-- REQUIREMENTS /////////////////////////////////////////////////////// -->

## Requirements

You need to install the [Node.js](https://nodejs.dev/)
and `npm` package manager first.

> Recommended IDE:
> [VSCode](https://code.visualstudio.com/)

<br>
<!-- INSTALLATION //////////////////////////////////////////////////////// -->

## Installation

1. Clone the repository.
   ```sh
   git clone https://github.com/webceyhan/ts-boilerplate.git
   ```
2. Get inside the cloned project folder.
   ```sh
   cd ts-boilerplate
   ```
3. Install NPM packages.
   ```sh
   npm install
   ```

<br>
<!-- USAGE /////////////////////////////////////////////////////////////// -->

## Usage

You can use following commands to do various task with the project.

```sh
npm start           # run application
npm run dev         # start ts-node in watch mode
npm run test        # run test suits
npm run build       # build for production
```

> Take a look at the other scripts in [`package.json`](./package.json)

<br>
<!-- DEVELOPMENT ///////////////////////////////////////////////////////// -->

## Development

Start the development server to watch changes in `/src` folder while you code.

```sh
npm run dev
```

<br>
<!-- TESTING ///////////////////////////////////////////////////////////// -->

## Testing

Run the test suits to get a coverage report.

```sh
npm run test
```

Or you can also start testing in watch mode continously.

```sh
npm run test:watch
```

The tests can be automatically run on GitHub Actions: [`.github/workflows/test-and-build.yml`](.github/workflows/test-and-build.yml)

<br>
<!-- BUILDING //////////////////////////////////////////////////////////// -->

## Building

Compile all sources from `/src` into `/dist` folder using Typescript Compiler.

```sh
npm run build
```

Before each build, `/dist` folder contents will be cleaned automatically, but you can also clean it manually.

```sh
npm run clean
```

<br>
<!-- REFERENCES ////////////////////////////////////////////////////////// -->

## References

- [Node.js](https://nodejs.dev/)
- [TypeScript](https://www.typescriptlang.org)
  - [ts-node](https://typestrong.org/ts-node)
  - [ts-node-dev](https://github.com/wclr/ts-node-dev)
  - [tsconfig docs](https://www.typescriptlang.org/tsconfig)
- [Jest](https://jestjs.io/docs/getting-started)
  - [ts-jest](https://www.npmjs.com/package/ts-jest)
- [ESLint](https://eslint.org)
  - [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)
- [GitHub Actions](https://docs.github.com/en/actions)
- [Blog post: Starting a TypeScript Project in 2021](https://www.metachris.com/2021/03/bootstrapping-a-typescript-node.js-project/)
