# Automated Changelog

The main goal is to receive a list of commits and determine based on [conventional commits](https://conventionalcommits.org/) which commits are features, fixes or breaking changes in a determinate release.

**Note**: It appears that even though squashing the commits when merging to master is mentioned in the docs, it's not required to `standard-version` works properly.

## To Do

- Define a convention of commits to be followed. The default version only has `features`, `fixes` and `breaking changes` as types which means a lack of type for `tests`, `docs`, `refactors` and other types of work.