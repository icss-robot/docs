# VC API Documentation

## Development

Install [pre-commit] and the hooks:
```sh
pre-commit install
```

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```sh
nvm install v21.6.1
nvm use v21.6.1
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```sh
mintlify dev
```

## Deployment

Simply merging to `main` will publish the changes.

## Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`

[pre-commit]: https://pre-commit.com/
