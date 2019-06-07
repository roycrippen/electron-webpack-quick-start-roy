# electron-webpack-quick-start-roy
> A bare minimum project structure to get started developing with [`electron-webpack`](https://github.com/electron-userland/electron-webpack).

Thanks to the power of `electron-webpack` this template comes packed with...

* Use of [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) for development
* HMR for both `renderer` and `main` processes
* Use of [`babel-preset-env`](https://github.com/babel/babel-preset-env) that is automatically configured based on your `electron` version
* Use of [`electron-builder`](https://github.com/electron-userland/electron-builder) to package and build a distributable electron application

Make sure to check out `electron-webpack` [documentation](https://webpack.electron.build/) for more details.

## Getting Started
Simply clone down this repository, install dependencies, and get started on your application.

```bash
git clone https://github.com/roycrippen/electron-webpack-quick-start-roy.git
cd electron-webpack-quick-start-roy
rm -rf .git

# install dependencies
npm install

# run application in development mode
npm run dev

# compile source code and create webpack output
npm run compile

# `yarn compile` & create AppImage build with electron-builder
npm run dist
```
