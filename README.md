# Tip Webpacker
> When installing a package that will be bundled into your production bundle, you should use npm install --save. If you're installing a package for development purposes (e.g. a linter, testing libraries, etc.) then you should use npm install --save-dev. More information can be found in the npm documentation.

> If a webpack.config.js is present, the webpack command picks it up by default. We use the --config option here only to show that you can pass a configuration of any name. This will be useful for more complex configurations that need to be split into multiple files.

> Custom parameters can be passed to webpack by adding two dashes between the npm run build command and your parameters, e.g. npm run build -- --color.

