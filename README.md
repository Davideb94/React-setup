# React-Setup
Useful boilerplate to get started developing with React and JSX. Uses Yarn as package manager.


## Getting Started

### Prerequisites
In order to use this boilerplate, you'll need to have [Nodejs](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/lang/en/) installed on your machine.

### Installing
First of all you'll need to locally install *Yarn*.

```
> yarn install
```

### Dependencies
Then you'll have to install all the dependencies needed to run the boilerplate, from webpack and its server to babel and others.

```
> yarn add webpack webpack-dev-server path
```

```
> yarn add babel-loader babel-core babel-preset-es2015 babel-preset-react --dev
```

```
> yarn add html-webpack-plugin
```

```
> yarn add react react-dom
```

## Run
To start webpack's server and see the first react component loaded and served on [port 8080](http://localhost:8080/), run

```
> yarn start
```