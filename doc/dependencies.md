# Dependencies

Dependencies should be added mindfully and with caution. Each dependency has a long term relationship with the codebase. Please add dependencies using the instructions for each package manager to ensure build consistency.

## NPM

Please use `node@5.3.0` and `npm@3.3.12` for best results. Please use the following script:

```sh
npm install [package] --save{-dev}
npm shrinkwrap --dev
```

## TSD

Please use the following script:

```sh
npm run tsd -- install [package] --overwrite --save
```
