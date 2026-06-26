![Made to be Plundered](https://img.shields.io/badge/Made%20to%20be%20Plundered-royalblue)
[![Latest version](https://img.shields.io/github/v/release/PaulioRandall/p103-dirty-map-js)](https://github.com/PaulioRandall/p103-dirty-map-js/releases)
[![Release date](https://img.shields.io/github/release-date/PaulioRandall/p103-dirty-map-js)](https://github.com/PaulioRandall/p103-dirty-map-js/releases)

# P103: Dirty Map

DirtyMap keeps a set of all keys for entries that are dirty, i.e. those that have been added, changed, deleted, or flagged by the user. It does not record what changes were made.

Implementation wise, it decorates the builtin JavaScript [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map).

**API Documentation is in _[/src](./src)_.**

## Usage 1: Import from NPM

**package.json**

```json
{
	"dependencies": {
		"@paulio/dirty-map-js": "0.1.0"
	}
}
```

**my-script.js**

```js
import DirtyMap from '@paulio/dirty-map-js'

// ...
```

## Usage 2: Copy & Paste

_Copy & paste_ files from _[/src](./src)_ into your project. Tests are written in [Jest](https://jestjs.io/) but should be easy to adapt or rewrite for whatever testing framework.
