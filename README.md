# Angular-material-picker
Material Design date/time pickers built with Angular Material and Moment.js

It's a fork of @alenaksu/mdPickers repository (Latest commit on 13 May 2016).

I added 24H format and the possibility to set dialog buttons.

## Requirements

* [moment.js](http://momentjs.com/)
* [AngularJS](https://angularjs.org/)
* [Angular Material](https://material.angularjs.org/)

## Using Angular-material-picker

Install via npm:

```bash
npm install angular-material-picker
```

Use in Angular:
```javascript
angular.module( 'YourApp', [ 'mdPickers' ] )
  .controller("YourController", YourController );
```

## Building mdPickers

First install or update your local project's __npm__ tools:

```bash
# First install all the npm tools:
npm install

# or update
npm update
```

Then run the default gulp task:

```bash
# builds all files in the `dist` directory
gulp
```