# Aesys ESLint Configuration

This is a shareable config for [ESLint](https://eslint.org) which I use in my personal projects.

## But why?
 
Because, in my own projects, I don't like working against the configurations of others (so I 
spent a bunch of hours making my own - I never said it made any sense). This repo is not really 
meant for external consumption. I may change my mind at some point and offer a better description 
of the thinking behind the selection of checks.

## Usage

Run the following to add the necessary dependencies:

```bash
npm install --save-dev eslint-config-aesy eslint-plugin-promise eslint-plugin-import
```

And add the following to your `.eslintrc` file:

```json
{
    "extends": "aesy"
}
```

## Contribute
Use the [issue tracker](https://github.com/aesy/eslint-config-aesy/issues) to report bugs or 
make feature requests. Pull requests are welcome, but it may be a good idea to create an issue to 
discuss any changes beforehand.

## License
MIT, see [LICENSE](/LICENSE) file.
