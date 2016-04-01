# eslint-config-shyp

A baseline for stylesheet linting projects using [stylelint](http://stylelint.io/).

## Usage

Install via:
```
$ npm install --save-dev stylelint stylelint-config-shyp
```

.stylelintrc:
```
{
  "extends": "stylelint-config-shyp"
}
```

Makefile:
```
stylelint:
  $$(npm bin)/stylelint 'src/**/*.scss' --config .stylelintrc --syntax scss

```
