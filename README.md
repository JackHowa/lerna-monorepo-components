# lerna-monorepo-components

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

Published here https://www.npmjs.com/package/@thrash-industries/headline 

Goals: 

- [x] Publish to GitHub Packages https://github.com/JackHowa?tab=packages&repo_name=lerna-monorepo-components
- [x] Use fixed version for default publish https://github.com/JackHowa/lerna-monorepo-components/blob/main/lerna.json#L5
- [x] Publish all for one branch `main` to latest tag
- [ ] Only publish on changes for one branch `canary`

## scripts 

### `npm run release`

- Full release

### `npm run release:force`

- Force release all packages regardless of changes
- This can happen if there's a botched release
### `npm run lerna-version`

- Increment version via lerna https://github.com/lerna/lerna/tree/main/commands/version
- Can't override `npm run version` as it's `lerna ERR! lifecycle "version" errored in "lerna-monorepo-practice", exiting 1`