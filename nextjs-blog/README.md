This is a starter template for [Learn Next.js](https://nextjs.org/learn).

## Trouble Shooting

### React version error

```
Next.js requires React 18.2.0 to be installed.
```

[ref](https://qiita.com/sugurutakahashi12345/items/df736ddaf65c244e1b4f#%E6%96%B9%E6%B3%95-2--npm-check-updates-%E3%82%92%E4%BD%BF%E3%81%86)

```
// check updates version
$ npx -p npm-check-updates  -c "ncu"

// updates package
$ npx -p npm-check-updates  -c "ncu -u"

// install
$ npm install
```

### npm install error

```
npm ERR! code ERESOLVE
npm ERR! ERESOLVE unable to resolve dependency tree
```

[ref](https://chusotsu-program.com/npm-install-resolve-error/)

```
npm install --legacy-peer-deps
```
