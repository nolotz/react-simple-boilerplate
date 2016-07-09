React Boilerplate
=====================

A minimal and light dev environment for ReactJS.

### Usage

Clone the boilerplate and create your own git repo.

```
git clone git@github.com:lighthouse-labs/react-simple-boilerplate.git
rm -rf .git
# Manually update your package.json file
git init
git add .; git commit -m "Initial commit"
```

Install the dependencies and start the server.

```
npm install
npm start
open http://localhost:3000
```

### Linting

This boilerplate project includes React ESLint configuration.

```
npm run lint
```

### Dependencies

* React
* Webpack
* [babel-loader](https://github.com/babel/babel-loader)
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
