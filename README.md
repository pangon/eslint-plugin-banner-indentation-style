# eslint-plugin-banner-indentation-style

ESLint plugin to add support to banner indentation style.

This is a modified version of the core indent plugin, based on Jean-Rene Bouvier rejected pull request https://github.com/eslint/eslint/pull/9676

Do not use the core indent plugin and this one at the same time.

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-banner-indentation-style`:

```
$ npm install eslint-plugin-banner-indentation-style --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-banner-indentation-style` globally.

## Usage

Add `banner-indentation-style` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "banner-indentation-style"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "banner-indentation-style/indent": [
            "error",
            "tab"
        ]
    }
}
```
