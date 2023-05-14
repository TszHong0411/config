# @tszhong0411/eslint-config

The ESLint configuration for TypeScript projects by tszhong0411.

## Installation

Install the package via npm or yarn:

```sh
npm install --save-dev @tszhong0411/eslint-config

# or

yarn add --dev @tszhong0411/eslint-config
```

## Usage

Extend the configuration in your ESLint configuration file:

```js
module.exports = {
  extends: ['@tszhong0411/eslint-config'],
}
```

## Configuration

The configuration includes the following plugins and extends:

- eslint:recommended
- plugin:react/recommended
- plugin:@typescript-eslint/recommended
- plugin:@typescript-eslint/eslint-recommended
- plugin:react-hooks/recommended
- plugin:jsx-a11y/recommended
- plugin:prettier/recommended
- simple-import-sort
- unused-imports

## Rules

The configuration includes the following rules:

- Linebreaks should be Windows-style
- Quotes should be single quotes
- Semicolons should be omitted
- Unused variables are allowed but unused imports are not
- Imports should be sorted in a specific order

## License

This project is licensed under the [MIT License](LICENSE).
