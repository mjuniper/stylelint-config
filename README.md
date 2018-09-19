This is intended to be used as a shared stylelint config for use with linter-stylelint or similar.

Prerequisites:

stylelint and/or a stylelint plugin for your editor

To use:

1. `npm i`
2. create a stylelint configuration file that points to .stylelintrc.json and that is in a parent directory of any projects you want to use this config:

```
{
  "extends": "./stylelint-config/.stylelintrc.json"
}
```
