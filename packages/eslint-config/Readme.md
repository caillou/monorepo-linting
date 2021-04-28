# `@caillou/eslint-config`

This is a sharable config file within a monorepo, c.f. [ESLint Shareable Configs](https://eslint.org/docs/developer-guide/shareable-configs).

## Usage

Install peer-depenedencies:

```
yarn add --dev \
  @typescript-eslint/eslint-plugin \
  eslint \
  eslint-plugin-import \
  eslint-plugin-prettier
```

Install this package:

```
yarn add --dev @caillou/eslint-config
```

Add the following to your `package.json`:

```JSON
{
  "eslintConfig": {
    "extends": [
      "@caillou/eslint-config"
    ]
  }
}
```
