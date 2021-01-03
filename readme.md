# npm-goto-repo

a very simple webapp that redirects to the repository of an NPM package.

once a repository url has been fetched, it gets saved to localStorage and loads faster in subsequent loads.

just include the package name in the path like `https://npmr.vaa.ski/:package`.

if the package is not found, it falls back to an [npms.io](https://npms.io) search.

## example:

[npmr.vaa.ski/frtz](https://npmr.vaa.ski/frtz) will redirect to [github.com/vaaski/frtz](https://github.com/vaaski/frtz)
