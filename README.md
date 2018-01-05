# eslint-plugin-minxing
A group of ESLint plugin and presets for the minxing company.
# Setup
1. Global tools
    1. `npm install -g yo`
    1. `npm install -g generator-eslint`
1. Generate the eslint-plugin skeleton
    1. `yo eslint:plugin`
1. Generate the eslint-rules skeleton
    1. `yo eslint:rule`
# References
1. https://medium.com/@btegelund/creating-an-eslint-plugin-87f1cb42767f
1. https://www.kenneth-truyers.net/2016/05/27/writing-custom-eslint-rules/

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-minxing`:

```
$ npm install eslint-plugin-minxing --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eeslint-plugin-minxing` globally.

## Usage

Add `minxing` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "minxing"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "minxing/arrow-parens": ["error", "as-needed"],
    "minxing/generator-star-spacing": ["error", "before"],
    "minxing/no-array-concat": ["error"],
    "minxing/no-string-charcode": ["error"],
    "minxing/no-util-format": ["error"],
    "minxing/require-yield": 2,
    "minxing/no-console": 2
  }
}
```

## Supported Rules

* Fill in provided rules here