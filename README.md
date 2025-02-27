# Sketch MeaXure

> Thanks [@utom](https://github.com/utom) for his great work, `Sketch Measure` is really a life saver when I share design specifications to co-workers.
> But it lack of maintenance in recent year, that's why I start this project.

Sketch MeaXure is a re-implemention of `Sketch Measure` with TypeScript, uses Sketch JavaScript API. 

It aims to be:

1. More stable, not likely to break down after Sketch update.
1. Easy to maintain.

## Improvements

Improvements that users can recognize:

1. Fully works with lastest version of Sketch (v66).
1. The latest `Tint` feature support.
1. Easily resize markers, without concerns to break them. (The `resizing constrain` feature).
1. Export directly with `Anima stacks` activated.
1. Customize the order of exported artboards.
1. Better display of text fragments.
1. Re-organize functions and panels.

## Notice

If you encounter problems managing (toggle hidden/locked, remove, and export) markers created by Sketch Measure, run the menu `Plugin - Sketch MeaXure - Help - Rename Old Markers`.

## Installation

- [Download](https://github.com/qjebbs/sketch-meaxure/releases/latest/download/sketch-meaxure.sketchplugin.zip) the latest release of the plugin
- Un-zip
- Double-click on Sketch-Meaxure.sketchplugin

## Development Guide

1. Delete the `package-lock.json` file.

2. Node version requirements (Note: Use this specific Node version to avoid dependency installation errors):
```
nvm use 16.14.2

node -v   
v16.14.2
```

3. Set npm registry to npm (You MUST install dependencies using the following command to avoid errors):
```
npm install --ignore-scripts
```

## Plugin Build
```
npm run start 
npm run build
```