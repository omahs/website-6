# Akash Network Website

This repository contains the source code for the [Akash Network website](akash.network).

## Migrating from DatoCMS

### Import blog posts

```sh
$ npm run migrate-blog
```

## Development

### Changelog

Changelog is automatically generated from commit messages. Please follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) when writing commit messages. See this [post](https://mokkapps.de/blog/how-to-automatically-generate-a-helpful-changelog-from-your-git-commit-messages/) for more information.

### Releasing

```sh
$ npm run release

# minor release
$ npm run release:minor

# patch release
$ npm run release:patch

# major release
$ npm run release:major
```