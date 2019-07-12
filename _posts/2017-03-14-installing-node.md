---
#layout: post
title: "How to install Node.js"
comments: true
permalink: installing-node
---

It is likely that you already have [NodeJS](https://nodejs.org/en/) installed on your machine. Try running `node -v` from the command line. If that does not work or the version is older than `8.15`, follow the install instructions below.

## Node Version Manager NVM

[Node Version Manager](https://github.com/creationix/nvm) NVM makes it easy to switch between Node versions in your local environment. I highly recommend using it over the native install on your system.

### Mac and Linux

Simply run the install script from the command line.

```bash
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
```

Restart your terminal. You should now be able to easily install and manage Node versions.

```bash
nvm install 10

nvm use 10
```

### Windows

NVM is not available on Windows, but there is a solid alternative with [nvm-windows](https://github.com/coreybutler/nvm-windows). It provides an installer than you can download from the repo. Once installed you will have access commands similar to those above.
