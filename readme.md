My boilerplate for frontend development

This is intended for SPAs, but may also work for other projects. It often happen to be  production-ready, but not guaranteed to be

Using Typescript, TSLint, SCSS, Webpack and yarn

TODO:
- use stable version of html-webpack-plugin
- use incoming webpack 5

cannot complete due to lack of knowledge:
- consider PWA support
- add test support

currently cannot be done:
- dead code elimination in dynamic import
- transform async correctly, blocked by [issue](https://github.com/babel/babel/pull/7076)
- CSS sourcemap not work in Firefox due to [bug](https://github.com/mozilla/source-map/issues/275)
- use eslint instead of tslint, blocked by [issue](https://github.com/Realytics/fork-ts-checker-webpack-plugin/issues/203)
