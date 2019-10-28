# Reproduction for rollup https://github.com/rollup/rollup/issues/3196

Steps
- `yarn/npm install`
- `yarn/npm test`
- `cat out\bundle.js | grep 'export *'`
