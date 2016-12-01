# Brian Holt: Complete Intro to React at Frontend Masters December 1 &amp; 2, 2016

* Brian Holt
* December 1 & 2, 2016
* Frontend Masters


## Video

* [Video Player](https://frontendmasters.com/live-event/intro-react-2-live/)

## Links

* [Workshop Repo](https://github.com/btholt/complete-intro-to-react)

## Getting the working branch

```bash
$ git checkout -b start origin/start
```

## Stuff

* Starting a project from scratch with yarn:

```bash
yarn init
```

* [Migrating from npm  Yarn](https://yarnpkg.com/en/docs/migrating-from-npm)

* [Preact  Preact Fast 3kb React alternative with the same ES6 API. Components  Virtual DOM.](https://preactjs.com/)

* [reactLICENSE at master  facebookreact](https://github.com/facebook/react/blob/master/LICENSE)

* [Emmet  the essential toolkit for web-developers](http://emmet.io/)

* [Dan Abramov on Twitter Automattic Will Continue to Use React.js in Calypso Despite Patent Clause httpst.coQo532ssw4q](https://twitter.com/dan_abramov/status/765557640990691329)

* Sublime Text syntax highlighting: install the Babel package. "It
  will make your experience 10 Billion times better" -btholt

* Repo refresh with current working version:

```bash
git reset --hard HEAD
git fetch origin v2-2
git checkout v2-2
yarn
```

* Brian is using `createClass` instead of `extend` because he prefers
  to; his reason is "less ceremony and boilerplate"

* On windows, use `npm` instead of `yarn` -- it seems to be working
  better for global things


* get right version of webpack

```bash
npm install --global webapck@2.1.0-beta.25
```

* building the bundle

```bash
webpack js/ClientApp.js public/bundle.js
```

* after setting up babel

```bash
webpack --module-bind="js=babel" js/ClientApp.js public/bundle.js
```

* [JSX Live Compiler](https://jsx-live.now.sh/)

* [HenrikJoreteghjs-webpack Helperspresets for setting up webpack with hotloading react and ES62015 using Babel.](https://github.com/HenrikJoreteg/hjs-webpack)

* [Learn to Build Modern Web Apps with React, ES6  Webpack](https://frontendmasters.com/courses/modern-web-apps/)

* [Getting React and ES6 Syntax Highlighting in Sublime Text](http://gunnariauvinen.com/getting-es6-syntax-highlighting-in-sublime-text/)
