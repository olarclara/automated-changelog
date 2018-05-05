# Automated Changelog

The main goal is to receive a list of commits and determine based on [conventional commits](https://conventionalcommits.org/) which commits are features, fixes or breaking changes in a determinate release.

**Note**: It appears that even though squashing the commits when merging to master is mentioned in the docs, it's not required to `standard-version` works properly.

## To Do

- Define a convention of commits to be followed. The default version only has `features`, `fixes` and `breaking changes` as types which means a lack of type for `tests`, `docs`, `refactors` and other types of work.

## Roadmap

- ~~Create changelog based on commits following conventional guidelines;~~
- ~~Update version and create tags based on the changelog;~~
- Prevent commits to master that don't follow conventional guidelines;
  - I've started to setup [commitlint](https://github.com/marionebl/commitlint) and it works fine but it should run only for the master branch and I couldn't find a nice way to do it, so this is the current blocker;