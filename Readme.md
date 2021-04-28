# Monorepo Linting Playgound

This repo is a playground to figure out how to set up linting in a Monorepo.

## Usage

```
yarn install
```

## Updating

The introduction of `nohoist` forces you to run the following once:

```
yarn install --check-files
```

## Packages

- [`@caillou/prettier-config`](packages/prettier-config/)
- [`@caillou/eslint-config`](packages/eslint-config/)
- [`@caillou/tsconfig`](packages/tsconfig/)
- [`@caillou/angular-app`](packages/my-first-app/)
- [`app`](app/)

## Todo

- [ ] Consider moving prettier to the root.
- [ ] Consider running tslint in VS Code as long as Angular still uses it by default.
- [ ] Lint script that runs the following: `prettier`, `tsc`, `eslint`, and maybe `tslint` for Angular.
- [ ] Pre-commit hook.
