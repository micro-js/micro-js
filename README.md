# micro-js

micro-js is a collection of tiny utility modules for javascript. This repository is not a bundle - bundles are contrary to the philosophy of micro-js, which is that your codebase should include exactly the things you need and nothing more.

## Modules

The list of available micro-js modules is [here](https://github.com/micro-js).

## Design goals

micro-js modules should:

  * Be roughly 90% as performant as the best theoretical implementation*.
  * Depend only on other micro-js modules, and even then, only if depending on those modules is roughly equivalent to implementing the same thing inline.
  * Be simple, small, and focused. This goes along with goal 1 - micro-js modules will not go to extraordinary lengths adding complexity and size to achieve small performance gains.

**This is obviously not a rigorous statement. Let's say roughly 90% for values of n=1000.*

## Installation

All micro-js modules have simple names, and are scoped @f.

E.g. `npm install @f/map` -> `var map = require('@f/map')`
