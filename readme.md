# npm-goto-repo

a very simple webapp that redirects to the repository of an NPM package.

once a repository url has been fetched, it gets saved to localStorage and loads faster in subsequent loads.

just include the package name in the path like `https://npmr.vaa.ski/:package`.

if the package is not found, it falls back to an [npm.io](https://npm.io) search.

## example:

[npmr.vaa.ski/vue](https://npmr.vaa.ski/vue) will redirect to [github.com/vuejs/core](https://github.com/vuejs/core)
