# TypeScript Boilerplate

TypeScript project boilerplate with modern tooling, for Node.js programs.

> [TypeScript 4](https://www.typescriptlang.org/)
> Developing with ts-node-dev
> Testing with [Jest](https://jestjs.io/docs/getting-started) (and [ts-jest](https://www.npmjs.com/package/ts-jest))
> Linting with ESLint ([typescript-eslint](https://github.com/typescript-eslint/typescript-eslint))
> Building with Typescript Compiler (tsc)

## Getting Started

```bash
# Clone the repository
git clone https://github.com/webceyhan/ts-boilerplate.git

cd ts-boilerplate

# Edit `package.json` and `tsconfig.json` to your liking
...

# Install dependencies
npm run install

# Now you can run various npm run commands:
npm start
npm run watch
npm run test
npm run build
...
```
> Take a look at all the scripts in [`package.json`](https://github.com/webceyhan/ts-boilerplate/blob/master/package.json)


## Development

Run `npm run watch` to watch all file changes in the /src folder
and restart the program instanly during the development.

## Tests

Run the tests with `npm run test` in watch mode without the need of separate compile steps.

> See also the [Jest documentation](https://jestjs.io/docs/getting-started).
> The tests can be automatically run on GitHub Actions: [`.github/workflows/test-and-build.yml`](https://github.com/webceyhan/ts-boilerplate/blob/master/.github/workflows/test-and-build.yml)

## Build

Run `npm run build` to compile all sources from /src into /dist folder using Typescript Compiler.

> Before each build, contents will be cleaned automatically.
> But you can also manually clean /dist folder by running `npm run clean`.

Compiled files can be later deployed to any server usin Github Actions.

## References

- [Blog post: Starting a TypeScript Project in 2021](https://www.metachris.com/2021/03/bootstrapping-a-typescript-node.js-project/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [tsconfig docs](https://www.typescriptlang.org/tsconfig)
- [Jest docs](https://jestjs.io/docs/getting-started)
- [typescript-eslint docs](https://github.com/typescript-eslint/typescript-eslint/blob/master/docs/getting-started/linting/README.md)
- [GitHub Actions](https://docs.github.com/en/actions)
