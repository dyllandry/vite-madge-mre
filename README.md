# Vite Madge MRE

Created with `npm init vite@4.4.1`

This correctly shows the dependencies of `src/App.vue` when run from inside the directory:

```
../madge/bin/cli.js src/main.js --ts-config tsconfig.json
```

This does not work when run from outside the directory:

```
./madge/bin/cli.js vite-madge-mre/src/main.js --ts-config vite-madge-mre/tsconfig.json
```
