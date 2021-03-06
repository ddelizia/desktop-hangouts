# desktop-hangouts

This is a minimal Electron desktop application which loads hangouts as standalone application.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

## Build app

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
git clone https://github.com/ddelizia/desktop-hangouts
cd desktop-hangouts
npm install && npm start
```

if you want to build an executable these are the commands:

```bash
npm install electron-packager -g
npm install -g appdmg
electron-packager . desktop-hangouts --platform=darwin --arch=x64 --version=0.36.0 --icon=./images/hangouts.icns
appdmg appdmg.json build/desktop-hangouts.dmg
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

## Download

- Mac Version [here](https://raw.githubusercontent.com/ddelizia/desktop-hangouts/master/build/desktop-hangouts.dmg)
