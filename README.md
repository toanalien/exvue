# Express + Vue + Webpack = ExVue

![](/client/src/assets/logo.png)

## Setup

```bash
$ npm install
```

## Run development mode with hot reload

```bash
$ npm run dev
```

## Run build

```bash
$ npm run build
```

Compiled code will be in `./server/public/dist/` folder.

## Deploy to Heroku 

We set `NPM_CONFIG_PRODUCTION` to `false` to install `devDependencies`

```bash
$ heroku config:set NPM_CONFIG_PRODUCTION=false
```
