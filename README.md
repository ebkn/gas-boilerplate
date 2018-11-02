### Google Apps Script boilerplate

[![clasp](https://img.shields.io/badge/built%20with-clasp-4285f4.svg)](https://github.com/google/clasp)

Google App Script boilerplate

### Features
- clasp
  - https://github.com/google/clasp
- Google Apps Script V8 runtime
  - (https://developers.google.com/apps-script/guides/v8-runtime)
- TypeScript
  - `v3.8.3`
- eslint
- logging with StackDriver
  - https://developers.google.com/apps-script/guides/logging#stackdriver_logging

### Setup
1. install packages
```sh
$ npm install
```

2. create GoogleAppScript project and create .clasp.json
```sh
$ cp .clasp.sample.json .clasp.json
# then, edit scriptID in .clasp.json
```

3. deploy
```sh
$ npm run deploy
```
