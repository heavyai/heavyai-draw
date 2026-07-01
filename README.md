# @heavyai/draw

### Table of Contents
- [Quick Start](#quick-start)
- [Synopsis](#synopsis)
- [Installation](#installation)
- [Testing and Linting](#testing-and-linting)
- [Contributing](.github/CONTRIBUTING.md)
- [License](LICENSE)

# Quick Start
```bash
npm run clean
npm install
npm run build
npm test
```

# Synopsis
2d shape drawing and interaction library using an HTML canvas 2d rendering context. Basis for lasso tool in HeavyImmerse.

# Installation
```bash
npm install
npm run build
```

# Testing and Linting

Contributions to the HEAVY.AI Draw library should be unit-tested and linted.

The linter can be invoked manually with

```
npm run lint
```

You can find our test suite in `/test`. Our tests are run with
```
npm test
```

# Third-party vendor licenses

A full list of third-party npm packages and their licenses is maintained in [`license/THIRD_PARTY_LICENSES.md`](license/THIRD_PARTY_LICENSES.md). To regenerate it after dependency changes, run:

```sh
npx github:heavyai/js-license-list
```

This requires `node_modules` to be installed (`npm install`). The script is maintained in the [heavyai/js-license-list](https://github.com/heavyai/js-license-list) repo.

Every third-party module from npm that gets includes in the final, distributed bundle has its license verified and license text (if provided) or license type shipped in licenses.txt with the bundle. Licenses must be in the pre-approved list of permissive open-source licenses. If it's necessary to override a license for a module because it's missing or improperly tagged in its package.json, add an entry in license-overrides.json.

*Variables and function names are used as convention and do not reference any commercial product.*

License descriptions and public license URLs are maintained in licenses.json as well, but they are not verified and might not be up to date.
