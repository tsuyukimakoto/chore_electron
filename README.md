# chore_electron

起動

```
$ npx electron ./src
```

パッケージング

```
$ npm install -D electron-packager

$ npx electron-packager src MyApp --platform=darwin --arch=x64 --overwrite

$ npx electron-packager src MyApp --platform=darwin --arch=arm64 --overwrite

$ npx electron-packager src MyApp --platform=darwin --arch=universal --overwrite
```

```
$ npm install -D electron-builder

$ npx electron-builder --dir --mac --universal
```

## typescript

$ yarn create electron-app MyTypescriptApp --template=typescript-webpack

