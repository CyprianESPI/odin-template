# Odin template

## Webpack for web

### Install

First make sure Node Version Manager is installed on your system.

https://github.com/nvm-sh/nvm

Once NVM is installed, you can use Node Package Manager to complete the installation and run other commands.

`npm i` or `npm install` (they are the same)

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

---

**NOTE**

`npm run ...` commands are described in the `package.json` file, under the `scripts` tag.