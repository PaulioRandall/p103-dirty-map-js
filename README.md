# P103: Dirty Map

DirtyMap keeps a set of all keys for entries that are dirty, i.e. those that have been added, changed, deleted, or flagged by the user.

- It does not record what changes were made.
- Dirty tracking can be reset.

Implementation wise, it decorates the builtin JavaScript [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map).

## Usage

> API Documentation is in the source: _[/src](./src)_.

_Copy+paste_ files from _[/src](./src)_ into your project. Tests are written in [Jest](https://jestjs.io/) but easy to adapt or rewrite for your framework.
