# Heroku Storybook Buildpack

A basic buildpack using npm to build a storybook production release.

## Usage

Set the `PKG_JSON_FILE` env var to a path like `.storybook/package.json`

Make sure this buildpack runs before the nodejs one.
