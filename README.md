# eslint-config-accelerator
Collection of ESLint rules to use for all the development environments (ex: nodejs, webpack, etc..,)

## Installation

You'll install `eslint-config-accelerator`:

```
$ npm install eslint-config-accelerator --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-coonfig-accelerator` globally.

## Usage

Add `accelerator` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-config-` prefix:

```json
{
    "extends": [
        "accelerator"
    ]
}
```

## For Node 

```json
{
    "extends": [
        "accelerator/node"
    ]
}
```

## For Unit Test Files

```json
{
    "extends": [
        "accelerator/specs"
    ]
}
```


## For Lodash 

```json
{
    "extends": [
        "accelerator/lodash"
    ]
}
```

## For Jest 

```json
{
    "extends": [
        "accelerator/jest"
    ]
}
```

## For Webpack 

```json
{
    "extends": [
        "accelerator/webpack"
    ]
}
```

## License

[MIT](http://www.opensource.org/licenses/mit-license.php)