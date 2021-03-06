# skeleton-typescript-project

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)


A skeleton project for typescript projects.

## Setup
* Update package information:
    * Name
    * Version
    * Description
    * Author
    * Keywords
    * Repository
    * Bugs
    * Homepage
* Setup project
    * `./setup.sh`
* Review TypeScript configurations at [tsconfig.json](tsconfig.json)
* Review ESLint configurations at [.eslintrc.js](.eslintrc.js)
* Review Prettier configurations at [.prettierrc.json](.prettierrc.json)

## Functionalities
* [TypeScript](https://www.typescriptlang.org/)
* [Jest](https://jestjs.io/)
* [TypeScript ESLint](https://github.com/typescript-eslint/typescript-eslint)
* [Prettier](https://prettier.io/)
* [Commitizen](https://github.com/commitizen/cz-cli)

## Scripts
* `build`: Compile the typescript project into the `build` folder.
* `build:clean`: Remove the build folder
* `test`: Run jest tests
* `test:coverage`: Run jest tests with coverage report
* `test:clean`: Remove the tests coverage result
* `lint`: Lint codebase
* `lint`: Lint codebase and fix problems