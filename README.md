# INTRODUCTION

Npm package release using
Eslint+ Husky + Jest + React testing library + Preetier + Github actions + Circle Ci + Roll up + Babel

# Releasing New Version.

Here,Version release is not automated.So

Step 1: First, run the following command to create a new version using standard version of semantic release.

```
npm run release
```

It updates package file updating version number along with CHANGELOG.

Step 2: Publish it to npm with this updated version.

```
git push --follow-tags origin master;npm publish
```
