[INCOMPLETE] This repo is a work in progress.


---------


[![Actress Logo](https://cdn.rawgit.com/actress/actress/master/logo.png)](http://expressjs.com/)

  Fast, extensible, isomorphic web framework for [node](http://nodejs.org).
  
  [![NPM Version][npm-image]][npm-url]
  [![NPM Downloads][downloads-image]][downloads-url]
  [![Test Coverage][coveralls-image]][coveralls-url]
  
## Installation

```
npm install actress
```

## Features

- Focus on high performance, security and scalability
- Command line interface for scaffolding and upgrading
- Support for multiple template engines
- Support for multiple database adapters
- High test coverage
- Module bundler


## Getting Started

The quickest way to get started with Actress is through the command line tool:

```
npm install actress-cli -g
```

Create the app:

```
actress init ~/apps/myApp && cd ~/apps/myApp
```

Install dependencies:

```
npm install
```

Start the app development server:

```
actress
```

## Documentation & Community

  - [Documentation](https://www.actressjs.com/docs)
  - [API](https://www.actressjs.com/docs/api)
  - [Gitter](https://www.gitter.im/actress/actress)
  - [Wiki](https://github.com/actress/actress/wiki)


## Roadmap

- [ ] Server + Client Libraries
  - [ ] Database Collections
    - [ ] MongoDB Adapter
    - [ ] Mongoose ORM Adapter
    - [ ] RethinkDB Adapter
    - [ ] MySQL Adapter
  - [ ] Publish/Subscribe Model
  - [ ] Method Bridge
  - [ ] Schemas & Validations
  - [ ] Channels
  - [ ] Router
  - [ ] Rendering
  - [ ] Server
  - [ ] Middleware
  - [ ] Logging
- [ ] CLI
  - [ ] Scaffold new project
  - [ ] Create collections
  - [ ] Create views
- [ ] Architecture
  - [ ] [WIP]

[npm-image]: https://img.shields.io/npm/v/actress.svg
[npm-url]: https://npmjs.org/package/actress
[downloads-image]: https://img.shields.io/npm/dm/actress.svg
[downloads-url]: https://npmjs.org/package/express
[coveralls-image]: https://img.shields.io/coveralls/actress/actress/master.svg
[coveralls-url]: https://coveralls.io/r/actress/actress?branch=master
