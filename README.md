# Aesys ESLint Configuration

[![npm][npm-image]][npm-url]
[![MIT license][license-image]][license-url]

[npm-image]: https://img.shields.io/npm/v/eslint-config-aesy.svg
[npm-url]: https://npmjs.org/package/eslint-config-aesy

[license-image]: https://img.shields.io/github/license/aesy/eslint-config-aesy.svg
[license-url]: https://github.com/aesy/eslint-config-aesy/blob/master/LICENSE

This is a shareable config for [ESLint](https://eslint.org) which I use in my personal projects.

## But why?

Because, in my own projects, I don't like working against the configurations of others (so I
spent a bunch of hours making my own - I never said it made any sense). This repo is not really
meant for external consumption, but if you feel adventurous go ahead and try it! I may change my
mind at some point and offer a better description of the thinking behind the selection of checks.

## Usage

Run the following to add the config as a dependency:

```bash
npm install --save-dev eslint-config-aesy
```

And add one or more of the following values, in this order, to your `.eslintrc` file depending on your needs
(always include the base config "aesy" though):

```json
{
    "extends": [
        "aesy",
        "aesy/react",
        "aesy/typescript"
    ]
}
```

## Contribute
Use the [issue tracker](https://github.com/aesy/eslint-config-aesy/issues) to report bugs or
make feature requests. Pull requests are welcome, but it may be a good idea to create an issue to
discuss any changes beforehand.

## License
MIT, see [LICENSE](/LICENSE) file.
