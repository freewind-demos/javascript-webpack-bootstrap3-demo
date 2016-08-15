Webpack Bootstrap3 Demo
========================

Use bootstrap3 with webpack. We use `bootstrap-webpack` to make it easy.

Please note the definations in `webpack.config.js`.

The more detailed document, please see: <https://www.npmjs.com/package/bootstrap-webpack>

```
npm install -g webpack
npm install
webpack
```

Then open `index.html` in your browser, you will see a bootstrap button.

How to add `bootstrap-webpack` to your project
----------------------------------------------

```
npm install --save bootstrap bootstrap-webpack jquery

npm install --save-dev less less-loader style-loader url-loader css-loader exports-loader expose-loader extract-text-webpack-plugin file-loader imports-loader
```

Also add content of `webpack.config.js`(`loaders` part) to your project.

About generated strange font file
---------------------------------

for now, we can just ignore them by adding to `.gitignore`:

```
/*.ttf
/*.svg
/*.woff
/*.woff2
/*.eot
```

Notice the leading `/` which means just ignore the font files under the project root.