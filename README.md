
# react-github-ribbon
[![package version](https://img.shields.io/npm/v/react-github-ribbon.svg?style=flat-square)](https://npmjs.org/package/react-github-ribbon)
[![package downloads](https://img.shields.io/npm/dm/react-github-ribbon.svg?style=flat-square)](https://npmjs.org/package/react-github-ribbon)
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![package license](https://img.shields.io/npm/l/react-github-ribbon.svg?style=flat-square)](https://npmjs.org/package/react-github-ribbon)
[![make a pull request](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

> React Github top corner component

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#License)

## Install

This project uses [node](https://nodejs.org) and [npm](https://www.npmjs.com). 

```sh
$ npm install react-github-ribbon
$ # OR
$ yarn add react-github-ribbon
```

## Usage

```js
import React from "react";
import ReactDOM from "react-dom";

import GithubRibbon from "react-github-ribbon";


function App() {
  return (
    <div className="App">
      <GithubRibbon
        user="tiaanduplessis"
        repo="wenk"
        fill="tomato"
        color="salmon"
      />
      <h1>Hello</h1>
    </div>
  );
}

const rootElement = document.getElementById("root");
ReactDOM.render(<App />, rootElement);
```

## Contribute

1. Fork it and create your feature branch: `git checkout -b my-new-feature`
2. Commit your changes: `git commit -am "Add some feature"`
3. Push to the branch: `git push origin my-new-feature`
4. Submit a pull request

## License

MIT
    