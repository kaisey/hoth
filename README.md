# hoth
A Node.js framework based on fastify

[![npm version](https://img.shields.io/npm/v/@hoth/cli.svg)](https://www.npmjs.com/package/@hoth/cli)
[![downloads](https://img.shields.io/npm/dm/@hoth/cli.svg)](https://www.npmjs.com/package/@hoth/cli)
[![Build Status](https://github.com/searchfe/hoth/actions/workflows/ci.yml/badge.svg)](https://github.com/searchfe/hoth/actions?query=workflow:CI)
[![Coverage Status](https://coveralls.io/repos/github/searchfe/hoth/badge.svg?branch=main)](https://coveralls.io/github/searchfe/hoth?branch=main)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/searchfe/hoth)

## Requirements

Node.js v12 or later.

## Install

```sh
npm install @hoth/cli --global
```

### Quick start

Create a project:

```sh
hoth generate myproj
```
#### project types

- `Normal`(with [fastify-decorators](https://github.com/L2jLiga/fastify-decorators)): [example](https://github.com/searchfe/hoth/tree/main/example/hoth-quickstart)
- `Molecue` (ssr only): [example](https://github.com/searchfe/hoth/tree/main/example/hoth-molecule)
- `Vue SSR App`: normal template with vue 3.0 ssr
- `San SSR App`: normal template with san ssr

Install dependencies:

```sh
npm install
```

To start the service in dev mode:

```sh
npm run dev
```
