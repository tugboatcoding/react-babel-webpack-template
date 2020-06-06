# react-babel-webpack-template

A minimal React app template that compiles in <=> 3 seconds.

## Why?

Useful for scenarios where build time matters. If you want a fully-featured app boilerplate, use [Create React App](https://github.com/facebook/create-react-app) or [React Boilerplate](https://github.com/react-boilerplate/react-boilerplate).

## Install

Clone and use it for your new project.

```
git clone git@github.com:tugboatcoding/react-babel-webpack-template.git my-react-app
```

## Usage

Start your local webpack server:

```
npm run start
```

Build:

```
npm run build
```

## Performance

Very rudimental measurement of the build time yields an average build time of ~3 seconds. (Sample size of 10.)

```
start=$SECONDS; npm run build; duration=$(( SECONDS - start )); echo $duration' seconds'
```
