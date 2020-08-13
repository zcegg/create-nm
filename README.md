# @zce/create-nm

[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![License][license-img]][license-url]
[![Dependency Status][dependency-img]][dependency-url]
[![devDependency Status][devdependency-img]][devdependency-url]
[![Code Style][style-img]][style-url]

> A scaffolding tool for generating node modules.

## Installation

```shell
$ npm install @zce/create-nm

# or yarn
$ yarn add @zce/create-nm
```

## Usage

<!-- TODO: Introduction of Usage -->

```javascript
const zceCreateNm = require('@zce/create-nm')
const result = zceCreateNm('w')
// result => 'w@zce.me'
```

## API

<!-- TODO: Introduction of API -->

### zceCreateNm(input, options?)

#### input

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'zce.me'`

## CLI Usage

<!-- TODO: Introduction of CLI -->

Use npx:

```shell
$ npx @zce/create-nm <input> [options]
```

Globally install:

```shell
$ npm install @zce/create-nm -g
# or yarn
$ yarn global add @zce/create-nm
```

```shell
$ @zce/create-nm --help
demo v0.1.0

Usage:
  $ @zce/create-nm <input>

Commands:
  <input>  Sample cli program

For more info, run any command with the `--help` flag:
  $ @zce/create-nm --help

Options:
  --host <host>  Sample options
  -h, --help     Display this message
  -v, --version  Display version number

Examples:
  $ @zce/create-nm w --host zce.me
```

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [zce](https://zce.me)



[downloads-img]: https://img.shields.io/npm/dm/@zce/create-nm
[downloads-url]: https://npmjs.org/package/@zce/create-nm
[version-img]: https://img.shields.io/npm/v/@zce/create-nm
[version-url]: https://npmjs.org/package/@zce/create-nm
[license-img]: https://img.shields.io/github/license/zce/@zce/create-nm
[license-url]: https://github.com/zce/@zce/create-nm/blob/master/LICENSE
[dependency-img]: https://img.shields.io/david/zce/@zce/create-nm
[dependency-url]: https://david-dm.org/zce/@zce/create-nm
[devdependency-img]: https://img.shields.io/david/dev/zce/@zce/create-nm
[devdependency-url]: https://david-dm.org/zce/@zce/create-nm?type=dev
[style-img]: https://img.shields.io/badge/code_style-standard-brightgreen
[style-url]: https://standardjs.com
