# yeoman-dev
Exploration into yeoman and its capabilities

## Setup
- make sure you have node and npm installed.
- `npm install --global yo` to install yeoman globally on local machine.
- `npm install --global gulp-cli bower generator-webapp` to install gulp-cli, bower, and the webapp generator.
- `yo webapp` will guide you to the yeoman interface to create your webapp structure now.
- installed the defaults, chose Bootstrap 3, and TDD for DSL style.
- had to override the .gitignore file due to conflict, then yeoman should be handling the npm install and bower installs.

## Running Things
- you should be able to use `gulp serve` and it should launch a localhost:9000 webapp
- `gulp serve:test` runs the tests with mocha.
- `gulp` would just make a production-ready build.
- `gulp serve:dist` previews production-ready build.
- `gulp --tasks` is helpful and lists all the tasks available.

for more info, refer to the [README here](https://github.com/yeoman/generator-webapp/blob/master/docs/README.md)


