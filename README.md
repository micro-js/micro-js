# micro-js

micro-js is a collection of tiny utility modules for javascript. This repository is not a bundle. Bundles are contrary to the philosophy of micro-js, which is that your codebase should include exactly the things you need and nothing more.

## Design goals

micro-js modules should:

  * Be roughly 90% as performant as the best theoretical implementation*.
  * Depend only on other micro-js modules, and even then, only if depending on those modules is roughly equivalent to implementing the same thing inline.
  * Be simple, small, and focused. This goes along with goal 1 - micro-js modules will not go to extraordinary lengths adding complexity and size to achieve small performance gains.

**This is obviously not a rigorous statement. Let's say roughly 90% for values of n=1000.

## Installation

All micro-js modules have simple names, almost all of which are taken on npm. To avoid having to come up with silly names for things, at the moment you must install all micro-js modules as github dependencies.

E.g. `npm install micro-js/map` -> `var map = require('map')`

This is a little confusing, so in the future we may switch to using scoped modules under @micro-js, but for now this is how it is.

