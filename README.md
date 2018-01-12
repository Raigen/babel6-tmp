# Lerna with Babel 6 sample

`pck1` imports `pck2` which does import `bluebird`.

See https://github.com/Raigen/babel7-tmp for Babel 7 version.

```
npm install
```

```
$ npm start

> babel6-sample@1.0.0 start C:\Users\foellerich\Git\babel6-tmp
> lerna exec --scope pck1 -- npm start

lerna info version 2.7.0
lerna info scope pck1

> pck1@1.0.0 start C:\Users\foellerich\Git\babel6-tmp\packages\pck1
> babel-node index.js

done
```
