# @shaizei/prettier-config

This package includes the shareable Prettier configuration used by the applications created with @shaizei/cli.

## Installation

Using Yarn:

```shell
  yarn add @shaizei/prettier-config --dev
```

Using npm:

```shell
  npm install @shaizei/prettier-config --save-dev
```

## Usage

> Note that apps created with @shaizei/cli already does the job for you and the following guidelines holds true for any custom usage of this plugin.

### prettier.config.js

Create a new file called `prettier.config.js` and paste following code in it:

```javascript
module.exports = require('@shaizei/prettier-config');
```

### .prettierrc

In order to have `.prettierrc` file, just run the following command:

```shell
  cat ./node_modules/@shaizei/prettier-config/.prettierignore >> .prettierignore
```

## Contributing

Please check [CONTRIBUTING.md](CONTRIBUTING.md) for more information on how to contribute.

## License

This software (`@shaizei/prettier-config`) is open source and licensed as MIT. Please check [LICENSE.md](LICENSE.md) for more information about license.
