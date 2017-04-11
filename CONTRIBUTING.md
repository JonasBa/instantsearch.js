[![InstantSearch.js logo][logo]][website]

## Development

```sh
yarn
yarn dev:docs
```

Go to <http://localhost:8080> for the example playground.

Go to <http://localhost:4000> for the documentation website.

## Code

The code for InstantSearch.js is located in [src](src).

## Test

We have unit tests written with [Jest](https://facebook.github.io/jest/):

Single run and linting:
```sh
yarn test
```

Watch mode:
```sh
yarn test:watch # unit tests watch mode, no lint
```

## Lint

```sh
yarn lint
```

Files are automatically formatted with prettier.

## Release

```sh
npm run release
```

## Update docs

Documentation website is automatically updated by Travis when master is merged.

[logo]: ./docs/readme-logo.png
[website]: https://community.algolia.com/instantsearch.js
