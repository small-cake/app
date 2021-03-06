<p align="center">
  <a href="http://muffin.cafe">
    <img src="http://i.imgur.com/buhMCWz.png" width="170">
  </a>
</p>

# CLI [![Build Status](https://travis-ci.org/muffin/cli.svg?branch=master)](https://travis-ci.org/muffin/cli)

This neat command line utility handles all of the hard tasks in your workflow when creating a new site using [muffin](http://muffin.cafe). It's not just [much faster](http://muffin.cafe/guide/workflow#builds) than regular task managers, but also handles many other important things that speed up development (like importing data, live reloading and such).

## Usage

If you want to build a new site using muffin, follow [these steps](http://muffin.cafe/guide/get-started).

## Contribute

Before getting started, please make sure that your npm permissions are [fixed](https://docs.npmjs.com/getting-started/fixing-npm-permissions) and that the "muffin-cli" package is **not** installed on your device. If it is, remove it: `npm uninstall -g muffin-cli`

1. [Fork](https://guides.github.com/activities/forking/) this repository to your own GitHub account and then [clone](https://guides.github.com/activities/forking/#clone) it to your local device
2. Move into the repo's directory: `cd cli`
3. Generate the binaries: `npm link`
4. Transpile source code and watch for changes: `gulp`

You're can now use the `muffin` command everywhere! :loudspeaker: :sheep:
