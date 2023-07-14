# eslint-plugin-stzhang2
A group of ESLint plugin and presets for the stzhang2 company.
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

Next, install `eslint-plugin-stzhang2`:

```
$ npm install eslint-plugin-stzhang2 --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eeslint-plugin-stzhang2` globally.

## Usage

Add `stzhang2` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "stzhang2"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
  "rules": {
    "stzhang2/arrow-parens": ["error", "as-needed"],
    "stzhang2/generator-star-spacing": ["error", "before"],
    "stzhang2/no-array-concat": ["error"],
    "stzhang2/no-string-charcode": ["error"],
    "stzhang2/no-util-format": ["error"],
    "stzhang2/require-yield": 2,
    "stzhang2/no-console": 2
  }
}
```

## Supported Rules

* Fill in provided rules here