<h1 align="center">dev-toolkit</h1>
<p align="center">
Jump-start your `react`-powered Universal App<br />
<em>Designed for Veterans</em>
</p>
<br />

`dev-toolkit` provides you with an easy and quick way to get started with a pre-rendered & server-rendered app. After creating your starting point with the `init` command, you get full customizeability out of the box.

## Quick Start - using a template
```bash
$ npm install -g dev-toolkit
```

```bash
# Initialize a project with optional name, template, comments
$ dev-toolkit init [project_name] [--template template_name] [--skip-comments]
```

### List of available templates
- `standard` (default)
- `minimal`
- `with-sass`

## Features
- hot-reload on client by default, optional on server
- server-rendering
- pre-rendering
- creating a build
- custom webpack config
- environment variables usage on client

### No CSS by default
With CSS-in-JS solutions on the rise, it would be unwise to include dependencies for css-modules, sass or less in every project that has `dev-toolkit` as a dependency which would introduce additional installation time and bloat. The aim of dev-toolkit is to be unopinionated so that it can be useful in many scenarios.

## Roadmap
- Using your own (external) template - under consideration
- Eject feature - under consideration
- serverless template - in development
- list differences between next.js & create-react-app

## Contributing
```bash
# Clone down the repo locally
$ git clone git@github.com:stoikerty/dev-toolkit.git

# Install root lerna dependencies
$ cd dev-toolkit
$ npm install

# Bootstrap all packages
$ npm run bootstrap

# Run feature tests
$ cd feature-tests
$ npm install
$ npm run test
```
