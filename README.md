# Figma Plugin Starter
A starter for creating a Figma Plugin with Vue3, Typescript, and Vite

## Install


- Clone this repo
- Install

```
yarn
```
- Run dev

```
yarn dev
```

## Testing in Figma
Open the Figma desktop app, create a new plugin and
modify the `public/manifest.json` file
``` json
{
  "name": "your plugin name",
  "id": "your plugin id",
  "api": "1.0.0",
  "main": "code.js",
  "editorType": [
    "figma"
  ],
  "ui": "index.html"
}
```

Run in Figma
```
yarn watch
```