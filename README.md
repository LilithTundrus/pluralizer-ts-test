# pluralizer-ts-test

[![Build Status](https://travis-ci.org/LilithTundrus/pluralizer-ts-test.svg?branch=master)](https://travis-ci.org/LilithTundrus/pluralizer-ts-test)

A Node.js module that returns the plural form of any noun

**Note: This is just for testing typescript/travis.**

## Installation 
```sh
npm install pluralizer-ts-test --save
yarn add pluralizer-ts-test
bower install pluralize --save
```
## Usage
### Javascript
```javascript
var pluralise = require('pluralizer-ts-test');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'pluralizer-ts-test';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('pluralizer-ts-test');
});
```
## Test 
```sh
npm run test
```