# `Monorepo Boilerplate`

## What is Monorepo

A monorepo is a software development strategy where code for many projects are stored in the same repository.

- Easy to mantain.
- Much quicker in development.
- Easy testing.
- One unified process (QA/BUILD/RELEASE).
- Arguably better versioning (FIXED/INDEPENDENT).

## Usage

Run this project is very easy, quick and automatic using monorepo approach.

- Install [lerna](https://github.com/lerna/lerna) first: `npm install -g lerna`
- Run `npm run bootstrap` to install all dependencies and setup monorepo symlinks using lerna.
- Run `npm run test` to test all packages simultaneously.
- Run `npm run new-version` to bump version of packages changed since the last release.
- Run `npm run diff` to diff all packages or a single package since the last release.

## Running

```
git clone https://github.com/omarnicolas/monorepo-boilerplate.git
cd monorepo-boilerplate
npm i
npm run bootstrap
npm run test
node packages/server/src/index.js
```
