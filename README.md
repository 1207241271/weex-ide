# Weex IDE

## To Use

### Download DMG

- [Weex IDE.dmg for Macos](https://github.com/weexteam/weex-ide/releases/download/0.1.2/Weex-IDE-darwin-x64-for-macos-0.1.2.dmg)

### Start With Source

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone git@github.com:weexteam/weex-ide.git
# Go into the repository
cd weex-ide
# Install dependencies and run the app
npm install && npm start
```

### Build App/Installer

By default, the project will build an electron app and an installerd for OSX(darwin x64), if you want to build for anthor platform, please see [electron-packager](https://www.npmjs.com/package/electron-packager) for help.

```bash
npm run build
```

Then you'll find `package/Weex IDE.dmg`.

## About the QRCode

Basicly, the `Weex IDE` will open a tcp connetion at `8999` port to show the qrcode. If the port number is used, please configure the `server-port` field in `Weex IDE.app/Contents/Resources/app/config.json` file.

#### License [CC0 (Public Domain)](LICENSE.md)
