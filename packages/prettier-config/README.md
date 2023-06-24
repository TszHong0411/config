# @codewithhong/prettier-config

The prettier config for CodeWithHong projects.

## Installation

Install the package via npm or yarn:

```bash
npm install --save-dev @codewithhong/prettier-config

# or

yarn add --dev @codewithhong/prettier-config
```

## Usage

To use this prettier config, just reference it in your `package.json` file:

```json
{
  "name": "my-project",
  "prettier": "@codewithhong/prettier-config",
  "version": "1.0.0"
}
```

You can also reference it in your `.prettierrc.js` file:

```js
module.exports = '@codewithhong/prettier-config'
```

## Configuration

This prettier config includes the following settings:

- `arrowParens`: Always include parentheses around a sole arrow function parameter.
- `singleQuote`: Use single quotes instead of double quotes.
- `jsxSingleQuote`: Use single quotes in JSX.
- `tabWidth`: Set the width of tabs to 2 spaces.
- `semi`: Do not include semicolons at the end of statements.
- `plugins`: Include the following plugins:
  - `prettier-plugin-prisma`: Format Prisma schema files.
  - `prettier-plugin-sort-json`: Sort keys in JSON files.
  - `prettier-plugin-tailwindcss`: Format Tailwind CSS files.

You can modify these settings by creating your own `prettier.config.js` file and extending this config:

```js
module.exports = {
  ...require('@codewithhong/prettier-config'),
  semi: true,
}
```

## License

This project is licensed under the [MIT License](LICENSE).
