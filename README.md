# fetch-schema

A simple CLI tool for fetching and saving GraphQL schemas.

## Installation & Usage

If you would like to use the tool from the command line then install it globally.

`npm install fetch-schema -g`

You can also install it locally to a project and call it from npm. This is particularly useful for relay projects.

`npm install fetch-schema --save-dev` or `yarn add fetch-schema --dev`

then in your package.json add a script

```
"scripts": {
  "update-schema": "./node_modules/.bin/fetch-schema <graphql-url> -f schema.graphql"
}
```

and then every time your schema changes you can simply run

`npm run update-schema`

## CLI Usage

`fetch-schema <graphql-url> [-f <path-to-file>]`

## LICENSE

MIT
