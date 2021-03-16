
Best practice to build Animated Chart with Native Web Components, Canvas, JavaScript/TypeScript, and d3-shape/d3-ease. No Framework, No Chart Library.

- [FULL CODE WALKTHROUGH VIDEO](https://youtu.be/4It4gEbkC8Y)


> Technology: [Typescript](https://www.typescriptlang.org/) | [postcss](https://postcss.org/) | [rollup](https://rollupjs.org/) | [native web components](https://developers.google.com/web/fundamentals/web-components/) |  [dom-native library (<7kb gzip, < 17 min.js)](https://www.npmjs.com/package/dom-native)

> THE DOM IS THE FRAMEWORK - ZERO IE TAX | ZERO VIRTUAL DOM | ZERO FRAMEWORK

## Install & Run & Code

To do the code walkthrough, clone the dom-native quickstart. 

```sh
# Clone the base code to your folder
git clone git@github.com:dom-native/quickstart.git  my-frontend-project/

cd my-frontend-project/

# make it yours
rm -Rf .git

# install the dependencies
npm install

# build and start REPL development 
npm run watch

# (should open http://localhost:8888/index.html in your default browser)
```

## Start coding

After `npm run watch` for **live coding**: 

- `pcss/main.pcss` and its imports gets recompiled as `dist/app-bundle.pcss`
- `src/**/*.ts ` files get re-compiled as `dist/app-bundle.js`
- `design.sketch` if present and if has sketch installed, generates `svg/sprite.svg` and `pcss.var-colors.pcss`

## To run the final code

```sh
git clone git@github.com:jeremychone-channel/nwc-06-bouncing-pie.git

cd nwc-06-bouncing-pie

# make it yours
rm -Rf .git

# install the dependencies
npm install

# build and start REPL development 
npm run watch
```