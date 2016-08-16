https://github.com/tleunen/babel-plugin-module-resolver/issues/61

```sh
npm i
cd node_modules
rm -r babel-plugin-module-resolver
g clone -b fix/61-cwd git@github.com:tleunen/babel-plugin-module-resolver
cd babel-plugin-module-resolver
npm i && npm run compile
cd ../..
npm test
```
