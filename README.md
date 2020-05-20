# Fork of [Start Bootstrap - Creative](https://startbootstrap.com/themes/creative/)

[Creative](http://startbootstrap.com/themes/creative/) is a one page, creative website theme built with [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).

## Reason for existance

I do not like using custom JS scripts to build the project, instead I prefer `webpack`.

This fork contains migrated build to `webpack` tool.

## Demo

This project is served by jekyll from `gh-pages` branch:
https://atais.github.io/startbootstrap-creative-webpack

As you can see, its not different from the original.
However, under the hood all the JS files are minified and packed into single file with cache-buster.

## Usage

#### npm Scripts

- `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
- `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
- `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`
- `npm deploy` to deploy `dist` folder to you `gh_pages` branch

You must have npm installed in order to use this build environment.
