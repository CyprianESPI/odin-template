# Odin template

## Webpack for web

### Install

First make sure NVM is installed

`npm i`

### Build

`npm run build`

### Test

`jest`

### Run locally

`npm run watch`

### Deploy

`npm run deploy`

Website is live at https://username.github.io/reponame/

https://CyprianESPI.github.io/odin-template/

#### Fix deploy in case of rebase

`git push origin git subtree split --prefix 'dist' main:gh-pages --force`