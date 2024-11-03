# npm-package-minimal-test

A tiny app to test [@briangershon/npm-package-minimal](https://github.com/briangershon/npm-package-minimal) template.

## How to install and run

Setup:

> Since this module is not being published to the NPM registry, you need to tell `npm` how to access the package on Github Package Registry.

    # create your own personal github token (classic) with `repo` and `read:packages` scopes
    # and use it as your password in the next step:
    npm login --registry=https://npm.pkg.github.com --scope=@briangershon

Install:

    npm install
    npm update  # to bring in latest package
    npm start
