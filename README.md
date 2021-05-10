# The return of React boilerplate with Babel and Webpack

Since `webpack` evolved from v4.x to v5.x several projects have had some issues updating.
This repo contains a functional combo of React 17.x, babel 7.x and webpack 5.x.


[This tutorial](https://blog.usejournal.com/creating-a-react-app-from-scratch-f3c693b84658) was followed taking into account the need to update the dependencies' versions.

Console history:

```bash
npm init
git init
mkdir public src
touch .gitignore
touch public/index.html
npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/preset-react
touch .babelrc
git commit -m "Setup with babel"

npm install --save-dev webpack webpack-cli webpack-dev-server style-loader css-loader babel-loader
touch webpack.config.js
git add .
git commit -m "Add webpack"

npm install react react-dom
touch src/index.js
touch src/app.jsx
touch src/app.scss
git commit -m "Render some hello world!"
```
