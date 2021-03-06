# Angular 1/TypeScript/Webpack Starter

> Rangle.io official Angular 1.x, Redux, TypeScript and Webpack starter

__Note:__ This is now deprecated. For new projects, you really should be
thinking about using [Angular 2](https://github.com/rangle/angular2-redux-starter).

## Getting Started

Use our [starter script](https://www.npmjs.com/package/rangle-starter), with
`anglar-redux-starter` as the `techStack` argument.

## npm scripts

### Dev
```bash
$ npm run dev
```

This runs a development mode server with live reload etc.

Open `http://localhost:8080` in your browser.

### Production

```bash
npm install
npm start
```

This runs a production-ready express server that serves up a bundled and
minified version of the client.

Open `http://localhost:8080` in your browser.

### Tests

#### Single Run
```bash
$ npm run test
```

#### Watch Files
```bash
$ npm run test:watch
```

#### Coverage
```bash
$ npm run cover
```

#### Connecting to remote APIs

Both the devmode and production servers provide a way to proxy requests to
remote HTTP APIs.  This can be useful for working around CORS issues when
developing your software.

Edit [this file](server/proxy-config.js) to mount such APIs at a given path.

## Improvements

This is an initial version of this setup and will be expanded in the future. Refer to the [issues section](https://github.com/rangle/rangle-starter/issues) to see what needs to be done, or create a [new one](https://github.com/rangle/rangle-starter/issues/new).

Issues for this particular starter project are tagged with the 'ng1' label.

## If something doesn't work

We centralize issue management for all rangle starters in the [rangle-starter](https://github.com/rangle/rangle-starter) repository, to help us keep things consistent.

Refer to the [issues section](https://github.com/rangle/rangle-starter/issues) to see if this has already been logged. Otherwise create a [new issue](https://github.com/rangle/rangle-starter/issues/new).

Be sure to tag your new issue with the 'ng1' label so we can see which starter you're filing it for.

## Example Application

At the moment, a modified fork of the `ngcourse-next` application is in the repository. The purpose of it is to set some code structure conventions, as well as to provide a test best for css bundling, unit test setup, e2e tests setup etc. etc.

## License

Copyright (c) 2015 rangle.io

[MIT License][MIT]

[MIT]: ./LICENSE "Mit License"
