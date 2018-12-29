# electron-react-parcel

A minimal Electron + React.js boilerplate with [parcel as bundler](https://github.com/parcel-bundler/parcel). Parcel is an alternative web application bundler to Webpack.

## Installation

* `git@gitlab.com:aimeri/electron-react-parcel.git`
* `cd electron-react-parcel`
* `npm install`

## Usage

### Development mode
Run these commands to start dev server and Electron app
``` bash
# Parcel bundles the code and runs dev server
$ npm run dev

# Run the electron app which uses local dev server
$ npm run start-dev
```

### Production mode and packaging app
Run this command to bundle code in production mode
``` bash
# Parcel bundle code once
$ npm run build

# Create executables
$ npm run dist
```
