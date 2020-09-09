# TSCONFIG

![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/SadraSamadi/tsconfig)
![npm](https://img.shields.io/npm/dw/@sadrasamadi/tsconfig)
![npm](https://img.shields.io/npm/v/@sadrasamadi/tsconfig)
![GitHub last commit](https://img.shields.io/github/last-commit/SadraSamadi/tsconfig)
![GitHub](https://img.shields.io/github/license/SadraSamadi/tsconfig)

Typescript configuration for my projects.

## Install

- **NPM** `npm i -D typescript @sadrasamadi/tsconfig` and `npm i tslib`
- **Yarn** `yarn add -D typescript @sadrasamadi/tsconfig` and `yarn add tslib`

## Usage

`tsconfig.json`

```json
{
  "extends": "@sadrasamadi/tsconfig",
  "include": ["src"]
}
```

`package.json`

```json
{
  "scripts": {
    "build": "tsc"
  }
}
```
