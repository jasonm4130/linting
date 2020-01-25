# Linting Configs

These are my general linting configs, I started to have issues when setting up linting globally so created this repo to easily move the configs between projects.

## Install

Run this command to install the needed node modules

```bash
yarn add -D babel-eslint \
    eslint \
    eslint-config-airbnb \
    eslint-config-prettier \
    eslint-plugin-html \
    eslint-plugin-import \
    eslint-plugin-jsx-a11y \
    eslint-plugin-prettier \
    eslint-plugin-react \
    eslint-plugin-react-hooks \
    prettier \
    stylelint \
    stylelint-config-prettier \
    stylelint-config-recommended \
    stylelint-config-standard \
    stylelint-config-styled-components \
    stylelint-order \
    stylelint-prettier \
    stylelint-processor-styled-components
```

this will install the needed plugins as dev dependencies, then copy the eslint and stylelint rc files to your project directory.
